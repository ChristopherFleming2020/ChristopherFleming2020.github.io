# Places API
This document is the link I created for a Places API for Fleming College Frost Campus

## Information to learn about this was sourced from 
https://developers.google.com/places/web-service/details#PlaceDetailsResults

## Place Details Obtained
While messing around with the Places API, I discovered that we can use the URL to give us more information about the selected location. For example I wanted the Name, rating, type of store,
hours of operation, the phone number, and a URL link to google maps. 

## Here is a URL:

https://maps.googleapis.com/maps/api/place/details/json?place_id=ChIJq6p6ZumM1YkRwlenRs5y5SY&fields=name,rating,type,geometry,opening_hours,url,formatted_phone_number&key=AIzaSyDWPklzn-CLNUL_DtbOt4j2cEZ0vnk085k

```json
{
   "html_attributions" : [],
   "result" : {
      "formatted_phone_number" : "(705) 324-9144",
      "geometry" : {
         "location" : {
            "lat" : 44.34101889999999,
            "lng" : -78.7412238
         },
         "viewport" : {
            "northeast" : {
               "lat" : 44.34240168029149,
               "lng" : -78.74009216970849
            },
            "southwest" : {
               "lat" : 44.3397037197085,
               "lng" : -78.7427901302915
            }
         }
      },
      "name" : "Fleming College - Frost Campus",
      "opening_hours" : {
         "open_now" : false,
         "periods" : [
            {
               "close" : {
                  "day" : 1,
                  "time" : "1600"
               },
               "open" : {
                  "day" : 1,
                  "time" : "0830"
               }
            },
            {
               "close" : {
                  "day" : 2,
                  "time" : "1600"
               },
               "open" : {
                  "day" : 2,
                  "time" : "0830"
               }
            },
            {
               "close" : {
                  "day" : 3,
                  "time" : "1600"
               },
               "open" : {
                  "day" : 3,
                  "time" : "0830"
               }
            },
            {
               "close" : {
                  "day" : 4,
                  "time" : "1600"
               },
               "open" : {
                  "day" : 4,
                  "time" : "0830"
               }
            },
            {
               "close" : {
                  "day" : 5,
                  "time" : "1600"
               },
               "open" : {
                  "day" : 5,
                  "time" : "0830"
               }
            }
         ],
         "weekday_text" : [
            "Monday: 8:30 AM – 4:00 PM",
            "Tuesday: 8:30 AM – 4:00 PM",
            "Wednesday: 8:30 AM – 4:00 PM",
            "Thursday: 8:30 AM – 4:00 PM",
            "Friday: 8:30 AM – 4:00 PM",
            "Saturday: Closed",
            "Sunday: Closed"
         ]
      },
      "rating" : 4.4,
      "types" : [
         "book_store",
         "university",
         "point_of_interest",
         "store",
         "establishment"
      ],
      "url" : "https://maps.google.com/?cid=2802772573382203330"
   },
   "status" : "OK"
}
```
