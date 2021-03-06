# 307FlightSim
Programming Assignment 1

Due Dates:
1. Preliminary Class Diagram: February 14
2. Class Outline: February 21
3. Functionality Outline: February 28
4. Final Project Due: March 14

Assignment: You are to create a program that simulates the flights of a number of airplanes. The basic requirements for this assignment are listed below.	
1. The simulation scenario shall consist of a set of cities joined by flight paths and a set of defined airline flights between those cities.
	
2. When the simulation is running each one second of real time shall be one minute of simulation time. The simulation shall be capable of being run in 1X, 2X, or 3X time. This shall be user selectable at the start of the simulation.
	
3. Data on cities shall consist of the city name, state, latitude, longitude, and the distance in miles from each city to every other city in the scenario. The data shall be provided in a special data file. Source code for a data parser to read, parse, and provide the data for use in the scenario shall be provided by the instructor.
	
4. Data on all aircraft which could appear in the scenario shall consist of the aircraft make and model, cruise speed, cruise altitude, rate of climb, and size consisting of the wingspan and the fuselage length. The data shall be provided in a special data file. Source code for a data parser to read, parse, and provide the data for use in the scenario shall be provided by the instructor.
	
5. Data on all flights shall consist of the airline, aircraft type, flight number, departure city, destination city, and departure time. The data shall be provided in a special data file. Source code for a data parser to read, parse, and provide the data for use in the scenario shall be provided by the instructor.
	
6. When started the application shall ask the user to input the name of a text file giving the names of the two data files (City and Aircraft/Flight).
	
7. Whenever the clock time of the scenario indicates time for a flight to be departing or arriving a message shall be printed on the screen giving the current scenario clock time, the airline, flight number, type of aircraft, the departure city and state, the arrival city and state, and the estimated time of arrival.
	
8. At 5 second intervals a report shall be printed on the screen giving the current scenario clock time and information on all flights currently in route. Flight information shall include the airline, flight number, type of aircraft, the departure city symbol, latitude and longitude, the time of departure, the arrival city symbol, latitude and longitude, the estimated time of arrival, the current location of the aircraft in latitude and longitude, the number of miles from the departure city, the number of miles to the destination city, the  speed of the aircraft, and the current altitude.
	
9. An example implementation, including example simulation data files, city data files, and flight data files, is available here. This zip file also includes the source code to parse the simulation data files, city data files, and flight data files. You should use those parsers in your program. You do not need to write your own parsers. 

