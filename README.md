# Student-Sample

Sample Application to learn Eureka discovery, Zuul Routing and zipkin traces

==========================================================================

Start Eureka server in 8761 and zipkin server in 9411 before this application

==========================================================================

build and run the student sample which runs in localhost:8090

appication will be connected with eureka which is running in localhost:8761, and this application name will be shown in eureka dashboard.

check if the student application is working fine, try to hit

localhost:8090/echoStudentName/sumanth
Expected response: Hello sumanth Responsed on : Tue Oct 02 15:35:22 IST 2018

localhost:8090/getStudentDetails/sumanth
Expected Response: {"name":"sumanth","address":"Pune","cls":"MCA"}

==========================================================================

If you want to find the details for each request, open zipkin dashboard and find the trace details

