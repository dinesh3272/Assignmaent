# Summary
A client has requested a web application that calls an API-enabled backend utilizing an algorithm.  The backend algorithm takes in 2 integers representing a range, and converts each number in the range. Multiples of 7 convert to “MS3”, multiples of 3 convert to “ME”, and multiples of both 7 and 3 convert to “MS3 and ME”.  The algorithm should be created in the most optimized way possible. The input range has a limit from a minimum of 1 to a maximum of 200. Ideally, users should be able to query inputs HTTP API calls.  Responses should be in the form of JSON, bonus points for use of a UI.

# Requirements
1) Anypoint studio 6.* version
2) jdk 1.8
3) maven 3.0.3

# Steps to run the project
1) clone or download the git project to local.
2) open the anypoint studio set jdk and maven envernonment properties.
3) right click on the package explorer and import the anypoint studio project from external location.
4) right click on thje project name and click run as mule application.
5) now after deployed go to url: http://localhost:8081/test
6) now feed the text boxes and click submit.
