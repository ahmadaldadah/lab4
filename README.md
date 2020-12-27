** How to use  
 npm install express
 npm start

** For the testing

 For POST using this command
----
curl -X POST -H "Content-Type: application/json" \
    -d '{"name": "Ahmad"}' \
    https://127.0.0.1:3000/data
----
-For get use the following command 
----
curl -X GET \
  -H "Content-type: application/json" \
  -H "Accept: application/json" \
 
  "https://127.0.0.1:3006/greeting/ahmad"
----
