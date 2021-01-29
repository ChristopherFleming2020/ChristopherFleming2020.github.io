# Directions API Tutorial
   This example uses the Google Maps Directions API to show directions of a certain student if the ski hills were open on a friday night
   The information was gathered from https://developers.google.com/maps/documentation/directions/overview

# URL Parameters
   * Origin: The Blue Mountains
   * Waypoint: LCBO
   * Destination: Flesherton
   * Mode: Driving
   * Language: English

# Vaid URL
https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJ8Zg9vTE0K00RWQglliSdZzs&destination=place_id:ChIJJSPdLxk8KogRDLUASga0neY&waypoints=place_id:ChIJ92ziadt7KogRCIEuU5Zpj8o&mode=driving&language=en&key=AIzaSyDWPklzn-CLNUL_DtbOt4j2cEZ0vnk085k

```json

   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ8Zg9vTE0K00RWQglliSdZzs",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ92ziadt7KogRCIEuU5Zpj8o",
         "types" : [ "establishment", "liquor_store", "point_of_interest", "store" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJJSPdLxk8KogRDLUASga0neY",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.5404607,
               "lng" : -80.2180544
            },
            "southwest" : {
               "lat" : 44.2618613,
               "lng" : -80.5504299
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "16.8 km",
                  "value" : 16788
               },
               "duration" : {
                  "text" : "18 mins",
                  "value" : 1064
               },
               "end_address" : "1 First St, Collingwood, ON L9Y 1A1, Canada",
               "end_location" : {
                  "lat" : 44.50279829999999,
                  "lng" : -80.2180544
               },
               "start_address" : "The Blue Mountains, ON, Canada",
               "start_location" : {
                  "lat" : 44.5404607,
                  "lng" : -80.408123
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "15.5 km",
                        "value" : 15470
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 904
                     },
                     "end_location" : {
                        "lat" : 44.5011427,
                        "lng" : -80.2345105
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eON-26 E\u003c/b\u003e toward \u003cb\u003eGrey County Rd 40\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{hznGvuwiNHS\\eA|AsEbAuCd@wAlBwF`@cBT_ARiALo@X}AtAsHv@oEb@mCReATaBb@sBLo@^yB^uB`@cC?Cd@yCFe@Js@N}AFq@@OTuD?I@O@KBmC?U@q@@e@?e@?WAs@C}BMkGGyCI{DGuBUuMAs@MeHOaGEqBGsCE}BMgFQyGM_JQeKOoGKeEQmHIuCEcBEeBCq@EcBAu@MqCQ}EQ_DSaDW}EIcBEq@Eq@IcBEq@YwFEq@Eq@Cm@?CCm@?c@@qD?]@Y@UB_@LoAFq@PaBFc@d@aD`@kCjAaJFa@z@kFF_@t@iFl@}ERyARmA^{B^eCb@cCh@oCLi@^}ALm@Ps@r@sCtAmFDMp@sB~@mC?AvByFNa@BEx@oB~CkGFKVe@P[dB_D~@aB`DkGnAwBjEmIjAcC`@y@JWd@eAh@wAbAmC~BaHd@wANa@fAiDfEqL|AkERs@X_ADQBK@IX_BlA_HJo@bByJvAkIpBiLTwANeAFa@HgAN}BBgD?g@Cs@OoCa@_FGsAMqBqAwRM_Cq@aLoAkSE}@EcCEmD?oA?q@?Q@cB@sADoA@a@B_ADw@RsC\\mEV_CXiCvA_LrE{^tCmUZeCh@wENuA~@qKZsDP_D?GJoBd@aLHqBLgDDy@DeBB_@\\qIp@{OJgCJqCZqHXoHTuFH}BNiEDiAN{D@UPyDB}@ZgHD{ANkCF}@Fu@LmAXiBVuAPk@Pi@Xm@Xc@Xe@NSR]vCgExEiI~A}BvAcCvFuIr@eAlEaHfAaBbAcB~E}Hr@eAfBoCLQp@y@xAyAfByAhAu@t@]LE\\ONGVIbAWxCc@TEpEo@PEPCj@Cn@Gz@M\\EnAS~Di@"
                     },
                     "start_location" : {
                        "lat" : 44.5404607,
                        "lng" : -80.408123
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1318
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 160
                     },
                     "end_location" : {
                        "lat" : 44.50279829999999,
                        "lng" : -80.2180544
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFirst St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-26 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "csrnGtxuhNU}DGsAImBAESiEGcBG{@WmF_@{HQyDGkBIuBQqDOeCOgDKoBS{DI}ASgESkDMoCKkCCk@"
                     },
                     "start_location" : {
                        "lat" : 44.5011427,
                        "lng" : -80.2345105
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "49.1 km",
                  "value" : 49061
               },
               "duration" : {
                  "text" : "41 mins",
                  "value" : 2469
               },
               "end_address" : "Flesherton, ON N0C 1E0, Canada",
               "end_location" : {
                  "lat" : 44.2618613,
                  "lng" : -80.5504299
               },
               "start_address" : "1 First St, Collingwood, ON L9Y 1A1, Canada",
               "start_location" : {
                  "lat" : 44.50279829999999,
                  "lng" : -80.2180544
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1318
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 158
                     },
                     "end_location" : {
                        "lat" : 44.5011427,
                        "lng" : -80.2345105
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eFirst St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-26 W\u003c/b\u003e toward \u003cb\u003eN Pine St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "o}rnGxqrhNBj@JjCLnCRjDRfEH|ARzDJnBNfDNdCPpDHtBFjBPxD^zHVlFFz@FbBRhE@DHlBFrAT|D"
                     },
                     "start_location" : {
                        "lat" : 44.50279829999999,
                        "lng" : -80.2180544
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 121
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 44.5000695,
                        "lng" : -80.2342369
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHigh St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "csrnGtxuhNnB[XGjAQ"
                     },
                     "start_location" : {
                        "lat" : 44.5011427,
                        "lng" : -80.2345105
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 895
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 81
                     },
                     "end_location" : {
                        "lat" : 44.4921221,
                        "lng" : -80.2324624
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eHigh St\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "mlrnG~vuhN|Do@dC]dG{@dBYhAOv@MfFs@hDc@bDa@dBUfBQ"
                     },
                     "start_location" : {
                        "lat" : 44.5000695,
                        "lng" : -80.2342369
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.1 km",
                        "value" : 4076
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 246
                     },
                     "end_location" : {
                        "lat" : 44.4815689,
                        "lng" : -80.281667
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSixth St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wzpnGzkuhNf@~Df@`Ef@`ER`Bz@`H^vCX`C\\|CpBdOv@|Fd@`EZbCjCzSfApIrCzTb@dDt@dGZ`C|@~G|@`Hh@`E|ApLlAhJbCxQZ~BxApKrDrX`AnHpAbK~AhL~ApL"
                     },
                     "start_location" : {
                        "lat" : 44.4921221,
                        "lng" : -80.2324624
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1263
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : 44.4703598,
                        "lng" : -80.27907220000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCollingwood Clearview Townline\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGrey County Rd 19\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSimcoe County Rd 34\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yxnnGl__iNrMcBx@K`Fw@XEpAOhAMhC_@fAQdAQlCa@zGcArEs@hBWhBYpDk@"
                     },
                     "start_location" : {
                        "lat" : 44.4815689,
                        "lng" : -80.281667
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.2 km",
                        "value" : 11226
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 496
                     },
                     "end_location" : {
                        "lat" : 44.43659299999999,
                        "lng" : -80.40980290000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGrey County Rd 19\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wrlnGdo~hNR~ArA`KfApI`@~Cv@zGRxA^nCr@~Ed@jDVxAFVTz@^dAZ`Al@pBJf@Nh@R`Bt@zIDp@N`B?@Bn@DhAFjABp@?BTnCT~ABRRhAJn@BLH`@Jl@Ln@Jl@n@hDR~@Lj@b@xABFr@dBZt@~ClI|@xB@BzChEr@bAtF~H`ArAb@`@@@ZTZPnDtAhBp@|A|@HDj@l@dAfBf@fBH^ZtBFf@T`BT~A~@~GHn@j@~DtA`K^tCHp@Hn@rA`KR~AHn@\\pCT~Ar@nFDVNfABTpAjJ~B|P|@jFb@nC@Bb@fCV~Ad@lCtAhIX~Ab@lC\\nBPjA?@Fb@Hz@@@Dt@@V@R?B@X?P@|D?L@v@?l@Dh@?DBVD`@Ff@@LPnARbB`BbNf@`EL~@^lCp@fFHn@Jn@Hn@Hn@Hp@Jn@R~AHn@Hn@Jn@R`BHn@Hn@Jn@Hn@Hn@Hn@T~AHp@Hn@Hn@Jn@Hn@R~AJn@Hn@fApIHn@Jn@J|@Fb@R~AHp@LjAp@rE`@nC`A|G|@lGh@tEl@vFr@jFJn@Hn@Hn@\\nC\\pCT~A@LF`@Hn@T~AJn@T~AHn@Jn@Hn@Jn@Fd@@HJn@Hn@Hp@rBpO^nCHn@@LpAzJf@bCZzA\\xA?@r@`FBLHn@R~A`@`DD^jB~MT`BFh@h@dEJn@DZXrBHn@T`BHn@Hn@d@pD`@~CR~AHn@BLDb@Hn@Hn@Hn@Hn@Hn@Jp@\\nCHn@Hp@Dn@Fp@JzA@DBp@FxAHz@Fn@NtBPlA`@nCJn@Hn@R~AHn@h@`ETnBf@pDHn@Jn@Hn@Hn@Jn@Hn@Hn@T~AHn@T~AHn@NhADVHn@p@fFJv@~@`Hh@~DHn@Hp@Hn@DXLdAHn@Hp@Hn@Hn@VvB"
                     },
                     "start_location" : {
                        "lat" : 44.4703598,
                        "lng" : -80.27907220000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "14.4 km",
                        "value" : 14419
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 641
                     },
                     "end_location" : {
                        "lat" : 44.31456350000001,
                        "lng" : -80.37244699999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGrey County Rd 2\u003c/b\u003e (signs for \u003cb\u003eFevershaw\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "u_fnGf`xiNlC_@`@GfAOdAQb@Gb@GpDg@`@IjBWdAOb@Gb@G`@Gb@IfAO`@Gb@Gb@Gb@GdAOb@G~HiA`@IfAO`@GfAOb@G`@Gl@I|@Ob@GdAQVGHCNGPINIf@[FE^Yd@]dByALI~@k@VOHCTKb@KH?\\En@@p@Lj@Pp@Xr@\\p@R\\F\\@`@Aj@GB?pDi@nDk@hBYb@Gb@Gb@G`@Ib@Gj@I|@KnC[dAOTCp@GhBSLATEb@IdAShB[b@I`@Ib@Ib@Gj@MbC_@@AfL_Bt@K|MoBvFy@fAQrEo@tEq@b@GdAQrAQdAQb@GlCa@hBWhBWpDi@fAQdAOhBWjBY~B]rAQhBUfBUpCa@fDe@j@Ib@Gb@GdK{AFA`Fq@zCc@b@Ib@GFAXIb@KFAt@]|@k@DE\\[RUZi@b@q@LW@CRc@N]BINm@FQFYLo@?AHm@@OD_@Do@@s@@UA[As@Aq@o@qFKy@OyAIu@?k@CaALiB@UBYNkADSJk@Pm@HYFQb@aAj@aA~@cAt@i@fAk@p@QLCzA]jC_@jBYdAOb@IhBUfAO`@Gb@GjBW`@Gb@Gb@GhBWb@Gb@GdAOb@Eb@G`@Gb@GfAOb@G`@GfKwA`@Eb@GzG_Ab@GpBYbBUdAQb@GhBWb@G|RuCfG}@|Cc@lC_@b@G\\GlAO`@Gh`@kFfKuAb@G`@ExP}B`@GpDg@lMcBlC_@zDi@dDe@fAO`@Gb@Gb@Gb@G`@Gb@Gb@Gb@GdAOhBW~HgAb@GdAOtEo@b@G`JoAfAOjDe@DAhBSb@GdAMb@Gb@EfAM`Ek@hBW~@Ob@GhBYnDk@xFs@dEg@rBY`@GtEq@b@G`@Gb@Gb@Gb@GlC_@`@GjBW`@Gb@GvFw@zGaAfAOdAO|G_A`@Gb@GfAOhBYb@G`@Gb@GhBWb@GhBWb@GpDg@vFw@b@G`JqAb@Gb@G~HgA"
                     },
                     "start_location" : {
                        "lat" : 44.43659299999999,
                        "lng" : -80.40980290000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "15.7 km",
                        "value" : 15743
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 736
                     },
                     "end_location" : {
                        "lat" : 44.2618613,
                        "lng" : -80.5504299
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGrey County Rd 4\u003c/b\u003e (signs for \u003cb\u003eCounty Road 4\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_enmGxvpiNv@pGHn@Hn@@Fz@xGh@fEFf@@FPxAR~A@DPxAfAxIHf@?F\\hC@DHn@Fh@R~A@FPvAHp@@DFh@Hn@@Dp@hFHv@NhAHn@NhABT\\nCHp@DXXtBBXNdAR~AR`BDXJ|@fApIHn@R`BR~AHn@xApLzApL~@rHfApIHn@\\nCdApIT~Af@`E`BtMLz@b@lDJv@j@nE\\nCp@pF\\nC|@`HHn@Hn@dApIr@pF\\nCf@`EHn@Hn@R~Ah@~DHp@f@~DnAvJHn@pA`KHn@z@`HJn@f@~Df@`EHn@^nCR~AHp@Hn@Hn@Hn@Jn@f@~DHn@Hp@Hn@Hn@@BFj@Jn@R~A|@`H\\nCHn@Hn@T~Az@`HJn@Hn@R~AHn@R~AHn@|@`HHn@dCpR`BrMHn@xB`Q\\pCp@nFHn@Hn@T`BlBpOHn@r@pFz@~GHn@p@pFHh@?DT~AHn@Hp@Hn@Hn@Hn@p@nFT`BHn@R~AHn@Hn@R~AR`BHn@DZLbAHn@dB`NR~AR`BdApIHn@L`ALnAVnCXrCH|@RrAJn@lAlINbAvEn_@Hn@f@`EtDbZHn@\\pCf@~DR~A\\pCR~AHn@R~AHn@l@tEvB`Q\\pCJn@Hn@Hn@PtAr@zGVpBHp@jDpXHn@dB`NJt@PzAp@pFHn@\\nC~BrR`CrRn@jFR|AR`Bn@pF\\pCRbB`@dDb@|Ct@fGH`@Jl@@HZxALd@FRHV`@bAFLRh@HTb@v@Zj@fAbB?@nBzBrA~AZ\\d@l@zCnDrA~AVZBBrA|AhC~CdKzL\\`@rA~AZ^`E|ErA~AzAhBPTnB|Bv@~@FHfBtBFHv@~@Z\\PTv@~@rChDZ^z@`AVZv@~@PRHJZ^X\\x@~@t@~@Z^`@f@\\\\v@|@Z^fBrBzAfBrA|AjD~DpA~AvAbBz@|@t@~@v@`AvAdBLNTXb@h@Z^v@~@"
                     },
                     "start_location" : {
                        "lat" : 44.31456350000001,
                        "lng" : -80.37244699999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "{hznGvuwiNhEcMrCoIv@cDpCkOdCeOp@cD~@oFnAgId@sEX{EF{FEoFg@wUu@q`@a@kRaAog@_A_`@_@oJe@aIm@eL}@qQBmGZwDXeCfAmHrAcKbAkGbBgMf@gD~@aGlAsGlAiFhCaKv@aCfEkL|@uBfDwGnEcI`DkGnAwBvGqM|BoFxFiPnG{QpB_Gd@gBvEiXnFs[PiBN}BBgDC{Aq@oJuB}\\aCm`@KaEEaIJiHHwBp@aJp@iGjH{k@pDsYx@mHzAeQPgDhAkXl@qOdBgb@hAmZh@uMt@mQNsBf@wDh@aCj@wAvA{BvCgExEiI~A}BvAcCjH{KtGcKbHaLzCuE~@kAxAyAfByAhAu@t@]j@Uf@QbAWxCc@fFu@b@IzAKxASnG}@]qGg@aLqA_Xs@yOy@qPaAoSCk@Bj@XzGdAlS|@nQ~Bnh@h@dKrKeBzPcClRgClEg@nA`KvC|Uv@~GhDbWtGrh@lO~kAnVfjB~ApLrMcBzGcAjBUrEm@vPiCxQqCpEr]jAtJrAnJ|@dG\\rAz@fCx@xCb@jCz@lKX|E`@pGx@lFf@lC|AbIf@`BnAzC|EfM|ClEhHbK`ArAb@`@\\VjEfBhBp@|A|@t@r@dAfBf@fBd@tCrBhOjDfWlFta@jB`N~B|P|@jFd@rCvD~TlBhLRbBHdBBvF@dBDn@RnBnDxYrCfTdEr[|CpUp@rFbDlU|@lGh@tEl@vFr@jFT~Af@~D|@`H`A~GjAnIfDbWrAhKbA~E\\zAv@nFdApIhF``@tFfc@`@bEXlFPjB`@bEjAnIzCrUnBxNjEj\\|AhMb_@mFd_@oFp@SpAu@xD{CvA{@^Ol@KlAC|A^dBv@nAZ~@?pK}AdKyA|Gw@pDe@lNcCft@kKhSwChLcBhL_Bb\\uEdMgBlAYt@]|@k@b@a@n@_Ap@iAh@oAl@iCP_BFcB?q@CeB{@kHYoCCmBN_CReBl@gCj@sAj@aA~@cAt@i@fAk@~@UzA]vFy@zG_AhL_Bhj@sHhl@qIht@wJn`AqMtd@oGtOoBrLaBlCa@nDk@xFs@xHaAvFy@lC_@x[qEfUaDjWoDlMiB~HgAv@pGR~AnBpOh@fEtClUxEt_@fNtgAtd@drDzQxwAp`@f~ChEd]jBrOp@bH\\pCxA|JfFra@pFdc@hDrX~F~d@jAlKtDbZlCbTrLdaAbClSxAdLTnAr@|CfArCl@lAbBnC~EzFt[v_@`S|U`UdXxH`JbMxNhDbEpB|BrDpEvBhC"
         },
         "summary" : "ON-26 E",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}