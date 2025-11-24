# VeloMax – Bike Shop Management System (C# WPF)

VeloMax is a desktop management application built with **C# and WPF**.  
It allows a bike shop to manage its workflow end-to-end: customers, orders, bikes, parts, suppliers, and inventory.  
All data is stored locally using **XML files**.

This project was created as part of an academic assignment and follows clean object-oriented programming principles.

---

## Project Overview

VeloMax centralizes all the operations of a bike shop into a single application.  
It supports customer tracking, product catalog management, supplier handling, order creation, and inventory management.

The system uses XML-based storage to keep the application lightweight and easy to deploy.  
The main goal is to offer a clean, modular, and extensible management tool.

---

## Main Features

### Customer Management
- Create, update, and delete customers  
- Support for regular and loyalty-member customers  
- Track customer order history  
- Persist customer data in XML  

### Bike & Part Management
- Manage bike models  
- Manage parts and associate them with suppliers  
- Track and update stock levels  
- Search and display product information  

### Order Management
- Create and modify orders  
- Automatic price calculation  
- Associate orders with customers  
- Manage orders for both bikes and parts  
- Save orders in XML format  

### Supplier Management
- Store supplier details and contacts  
- Associate suppliers with parts  
- Track delivery delays  

### WPF Interface
- Multiple screens for each module  
- Simple and intuitive navigation  
- XAML-based user interface  

---

## How It Works

1. The application loads existing data from XML files at startup.  
2. The user navigates through the different screens to manage entities.  
3. All changes (create, update, delete) are instantly saved.  
4. On closing the app, all data is written back to XML.

---

## Technologies Used

| Purpose | Technology |
|---------|------------|
| Front-End | WPF (XAML) |
| Programming Language | C# (.NET Framework) |
| Data Storage | XML Files |
| Architecture | Object-Oriented Programming |
| IDE | Visual Studio |

---

## Installation and Execution

### Clone the repository

```bash
git clone https://github.com/laulbrt/VeloMax.git
cd VeloMax

Open the project

Open the solution using Visual Studio.

Restore dependencies

Restore NuGet packages if prompted.

Run the application

Build and run with:

Ctrl + F5


The application will automatically load data from the XML files.

License

This project was created for academic purposes.
