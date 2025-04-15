# hotels
Repository for hotel demo project

Created a spring boot application exposing two REST end points for the given commands. Parameters are passed in URL as path variable.

Command 1-

Case:1-> Availability(H1, 20240901, SGL)

Input URL: http://localhost:8080/Availability/H1/20240901/SGL
Output: {"availableRoomCount":2}

Case:2-> Availability(H1, 20240901-20240903, DBL)

Input URL: http://localhost:8080/Availability/H1/20240901-20240903/SGL
Output: {"availableRoomCount":1}

Command 2-

Case:1-> Search(H1, 365, SGL)
Input URL: http://localhost:8080/Search/H1/365/SGL
Output: {"20250415-20260414":2}

Case:2-> Search(H1, 35, SGL)
Input URL: http://localhost:8080/Search/H1/365/SGL
Output: {"20250415-20250519":2}




