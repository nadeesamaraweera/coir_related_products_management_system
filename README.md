# **🧵 Coir Management System**

## **📌 Project Overview**
The **Coir Management System** is a Java-based application designed to streamline the management of customer orders, suppliers, employees, raw materials, and deliveries within a coir-related business. It provides a structured and efficient approach to handling business operations.

## **🛠️ Tech Stack**
- **☕ Java (JavaFX)** – Frontend user interface
- **🐬 MySQL** – Database management
- **🖼️ FXML** – UI design with JavaFX
- **🔗 JDBC** – Database connectivity
- **📦 Maven** – Dependency management

## **📂 Project Structure**
### **🔙 Backend (Java)**
The project follows an **MVC (Model-View-Controller)** architecture:

- **🎮 Controller Layer (`controller`)**  
  Handles business logic and user interactions.

- **📤 Data Transfer Objects (`dto.tm`)**  
  DTOs are used to transfer data between layers without exposing database structures.

- **🗂️ Model Layer (`model`)**  
  Represents entities such as Customers, Orders, Employees, and Suppliers.

- **🔌 Database Connection (`db.DbConnection`)**  
  Manages database connections.

- **🛠️ Utility Classes (`util`)**
    - `AppInitializer` – Initializes the application
    - `AppInitializerWrapper` – Additional setup configurations

### **🖥️ Frontend (FXML)**
The `resources/view/` directory contains the FXML files defining UI components:
- **🏠 dashboardForm.fxml** – Main dashboard
- **👤 customerForm.fxml** – Customer management
- **🚚 deliveryForm.fxml** – Delivery tracking
- **📧 emailForm.fxml** – Email notifications
- **🧑‍💼 employeeForm.fxml** – Employee management
- **🔑 forgotPasswordForm.fxml** – Password recovery
- **📦 itemForm.fxml** – Item management
- **🔐 loginPageForm.fxml** – User authentication
- **📊 materialStockForm.fxml** – Raw material inventory
- **🔢 otpForm.fxml** – OTP verification
- **🛒 placeOrderForm.fxml** – Order placement
- **🌾 rawMaterialForm.fxml** – Raw material management
- **🔄 resetPasswordForm.fxml** – Password reset
- **🏭 supplierForm.fxml** – Supplier management

## **🚀 How to Run the Project**
1. **📥 Clone the repository**
   ```sh
   git clone <https://github.com/nadeesamaraweera/coir_related_products_management_system.git>
   ```
2. **🛠️ Setup MySQL Database**
    - Import the SQL script from the `sql/` directory.
    - Update the database connection details in `DbConnection.java`.

3. **▶️ Run the Application**
    - Open the project in an IDE (**IntelliJ IDEA** or **Eclipse**).
    - Run `AppInitializer.main()`.

## **✨ Features**
- **👥 Customer & Employee Management** – Add, update, delete, and view records.
- **📦 Order & Supplier Tracking** – Maintain order history and supplier details.
- **🚛 Delivery Monitoring** – Track deliveries efficiently.
- **📊 Material Stock Management** – Maintain inventory of raw materials.
- **🔐 User Authentication** – Login, password reset, OTP verification.
- **📑 Report Generation** – Generate reports using JasperReports.

## **📜 License**
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.


