# VoltWave Application

**VoltWave Application** is a Java-based electricity billing system designed to manage and streamline various aspects of electricity billing operations. This application provides a user-friendly interface using Java Swing and is backed by a MySQL database for efficient data management.

## Features

- **Customer Management**: Add and manage new customers, update their information, and view details.
- **Billing Operations**: Calculate and generate electricity bills based on meter readings, view bill details, and handle bill payments.
- **Utility Integration**: Includes access to Notepad and Calculator utilities directly from the application.
- **Admin and User Interfaces**: Differentiated functionalities for Admin and regular users to handle different aspects of the billing system.

## Project Structure

- **`main_class.java`**: The main class for the application that initializes the GUI, sets up the menu bar, and handles user interactions.
- **`newCustomer.java`**: Handles new customer registration.
- **`customer_details.java`**: Displays customer details.
- **`deposit_details.java`**: Manages deposit details.
- **`calculate_bill.java`**: Calculates electricity bills.
- **`view_information.java`**: Allows viewing of customer information.
- **`update_information.java`**: Handles updating of customer information.
- **`bill_details.java`**: Shows bill details.
- **`pay_bill.java`**: Manages bill payments.
- **`generate_bill.java`**: Generates electricity bills.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/PhoenixA380/VoltWave.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd VoltWave
   ```

3. **Compile and Run the Application:**
   Make sure you have installed the Java Development Kit (JDK). Compile the project with:
   ```bash
   javac -d bin src/electricity/billing/system/*.java
   ```
   Run the application using:
   ```bash
   java -cp bin electricity.billing.system.main_class
   ```

## Dependencies

- **Java SE Development Kit (JDK)**: Required for compiling and running the Java application.
- **MySQL**: Used to manage the database.

## Contributing

If you want to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure that your contributions adhere to the coding standards used in this project.

## Contact

For any questions or suggestions, feel free to contact me via GitHub.

---

Feel free to adjust any sections based on additional specifics or details of your project!
