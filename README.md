# cloud-gateway
All the requests traverse through the API gateway. 
It is just a gateway for all the APIs we have in our microservices. 
All the requests should not directly go to the microservices. 
This should be gone from an API gateway and from there it should traverse according to the microservices url patterns or other information.
