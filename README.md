🚲 VeloMax – Bike Shop Management System (C# WPF)

VeloMax is a desktop management application built with C# and WPF.
It allows a bike shop to manage its entire workflow: customers, orders, bikes, parts, suppliers, and inventory, with all data stored using XML files.

This project was created for an academic assignment and follows clean object-oriented programming principles.

⭐ Features
🧑‍🤝‍🧑 Customer Management

Add, update and delete customers

Regular customers and loyalty-members

Track customer order history

Automatic XML data persistence

🚲 Bike & Part Management

Manage bike models

Manage parts and their suppliers

Update stock levels

Association between parts and bikes

Display and search features

🛒 Order Management

Create, edit, and track orders

Automatic total price calculation

Link customers to orders

Manage orders for bikes and parts

Store all transactions in XML

🏭 Supplier Management

Manage supplier profiles and contacts

Associate suppliers with parts

Track delivery delays

💾 Data Persistence

All data (customers, bikes, parts, suppliers, orders) is stored in XML files

Automatic load/save on application start/close

🖥️ WPF User Interface

Multiple screens/windows for each module

XAML-based UI

Clear and intuitive navigation

Functional and simple layout

🛠️ Tech Stack

C# (.NET Framework)

WPF / XAML

Object-Oriented Programming

XML Data Storage

Visual Studio

📁 Project Structure Overview
VeloMax/
 ├── Models/
 ├── Customers/
 ├── Orders/
 ├── Bikes/
 ├── Parts/
 ├── Suppliers/
 ├── XML_Database/
 ├── *.cs        (business logic)
 ├── *.xaml      (UI)
 ├── *.xml       (data)
 └── VeloMax.csproj

▶️ How to Run

Clone the repository

git clone https://github.com/laulbrt/VeloMax.git

Open the project in Visual Studio

Restore NuGet packages if required

Build and run the project
(Ctrl + F5)

The application will automatically load data from XML files when it starts.

📜 License

This project was created for educational purposes.
