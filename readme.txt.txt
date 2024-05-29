
Project Overview
The project is part of an advanced programming course focused on developing a vehicle management system using Java, Streams, Regex, GUI, and SQL.

Project Structure
1. Core Package: Contains base classes such as:
   - Car: Represents a vehicle in the system, inherits from Vehicle.
   - Customer: Represents a customer.
   - Delivery: Represents the delivery of a vehicle to a customer.
   - ICalc: Interface for calculating the cost of an order and transportation.
   - MotorCycle: Represents a motorcycle, inherits from Vehicle.
   - Order: Represents an order with various vehicles and quantities.
   - TransportCompany: Represents a company that handles vehicle transportation.
   - Vehicle: Abstract class representing a vehicle.
   - Worker: Represents an employee in the system.

2. Init Package: Contains initialization classes:
   - Main: Runs the program.
   - Store: Manages the store operations.

3. SQL Package: Handles database interactions.

4. Utilities Package: Contains utility classes and enums.

5. Application Package: Includes application logic and GUI components.

Tasks
Part A: Streams, Lambda Expressions, String Builder, and Regex
1. Store Class Methods:
   - checkIfVehicleExistInSystem(Vehicle v): Verify if a vehicle exists.
   - PrintMostLowPriceVehicle(): Print the cheapest vehicle.
   - sortCarsByPrice(): Sort vehicles by price (descending).
   - qryCustomersWithNumberOfOrdersOrderedByNumberOfOrdersAsc(): Sort customers by number of orders (ascending).
   - QryNumOfXMotorCycleColor(E_Color color): Print the number of motorcycles of a specific color.
   - getVehicleSummaryOfSelectedModel(E_Model e): Print a summary of selected model vehicles.
   - validatePhoneNumber(String phone): Validate phone number format.
   - validateCarNumberPlate(String s): Validate car number plate format.
   - checkModelInput(String s): Validate vehicle model format.
   - allUniqueWords(String s): Return unique words separated by hyphens.
   - StringList(ArrayList<String> list): Concatenate strings from a list with specific delimiters.

Part B: SQL and GUI
1. SQL Class Methods:
   - getCustomerFromSQLDB(String idNumber): Retrieve customer by ID.
   - sqlAddWorker(Worker w): Add new worker to the database.
   - connectTo(): Establish database connection.

2. GUI Components:
   - Add a form for adding new workers (AddWorker class).
   - Implement a table display for TblQryBoats with sorting capabilities.

Submission Requirements
- Complete project directory executable through ECLIPSE.
- Implement all specified methods and classes.
- Ensure the output matches provided examples.
- Perform input validation.
- Use Streams and Lambda Expressions where applicable.
- Avoid using loops unless specified.
- Do not modify fully implemented classes and methods.
- Avoid using Comparator/Comparable for sorting tasks.

Important Notes
- Follow submission guidelines provided by the instructor.
- Ensure output matches the expected format for full credit.
- Thoroughly test your code to avoid penalties.

Additional Details from Instructor Guidelines
- Vehicles have various parts like engine, gearbox, wheels, and steering.
- Specific vehicle types: SportCar, MiniCar, RegularCar with unique properties.
- Vehicle classes must implement constructors, getters, setters, and standard methods (equals, hashCode, toString).
- Implement custom exceptions for incomplete vehicles.
- Additional methods for handling vehicles in the Store class.
- File operations for reading customer data and saving vehicle data.
