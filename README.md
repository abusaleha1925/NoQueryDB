# NoQueryDB
The provided code snippet defines a graphical user interface (GUI) application called "NoQueryDB," which facilitates interactions with an Oracle database using Java's JDBC API. The application allows users to perform basic database operations such as creating tables, reading table contents, inserting values, and dropping tables. Here's a brief summary of the code:

UI Initialization: The code initializes the graphical user interface components, including text fields, text areas, buttons, and layout configurations. The UI elements are organized using the GridBagLayout manager to create a structured layout for input fields, buttons, and result display areas.

Database Connection Setup: The setupDatabaseConnection method establishes a connection to the Oracle database using the JDBC API. It provides the necessary database URL, username, and password for connection.

Database Operations:

Create Table: The createTable method is responsible for creating a new table in the database. It reads the table name and attributes from the UI, constructs the SQL statement, and executes it using the Statement object.
Read Table Contents: The readTableContents method retrieves and displays the contents of a selected table. It fetches data from the result set and constructs a formatted display to show the data in the result area.
Insert Values: The insertValues method inserts user-provided values into the selected table. It validates the input values and ensures that the number of values matches the number of columns in the table.
Drop Table: The dropTable method removes a selected table from the database.
Main Method: The main method is the entry point of the application. It invokes the GUI construction and rendering using the SwingUtilities.invokeLater method, which ensures proper thread management for GUI operations.

In summary, the code creates a GUI-based application for interacting with an Oracle database. Users can perform operations like creating, reading, inserting, and dropping tables through the graphical interface. The application's functionality relies on Java's JDBC API to establish connections and execute SQL queries.
