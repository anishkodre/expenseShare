# Expense Sharing Application

This is an expense-sharing application designed to help users track and manage group expenses. It allows users to easily split expenses among friends, family, or groups and provides tools to simplify debts and minimize the number of transactions required for settling up. The app also offers user and group management features for seamless and efficient collaboration.

## Main Features

- **User Management**
  - Register new users
  - User authentication (Login/Logout)
  
- **Group Management**
  - Add new groups
  - Add and remove members from groups
  
- **Expense Management**
  - Split expenses among group members
  - Simplify debts to minimize the number of transactions for settlement
  
## Setup Instructions

### 1. Clone the Repository

First, clone the repository to your local machine by running the following command:

    git clone https://github.com/anishkodre/expenseShare

### 2. Update Database Configuration

Navigate to the `DatabaseConfig.java` file in the project. Update the database connection credentials with your own by modifying the following lines:

    private  static  final  String  DB_URL  =  "YOUR URL"; 
    private  static  final  String  DB_USER  =  "YOUR USERNAME"; 
    private  static  final  String  DB_PASSWORD  =  "YOUR PASSWORD";
    
### 3. Run the Application

Once you have updated the database credentials, run the following command to clean and launch the application:

    mvn clean javafx:run
