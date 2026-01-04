# FAST Equipment Borrowing Tool

## Course
PROG30000 – Enterprise Software Development  
Fall 2024

## Description
The FAST Equipment Borrowing Tool is an ASP.NET Core MVC web application that allows FAST students and professors to submit requests to borrow IT equipment.  
The application follows the MVC architecture and demonstrates server-side validation, Razor views, and professional development practices using Git and GitHub.

---

## Features
- Home page with navigation menu
- Equipment request form
- Server-side validation for all inputs
- Equipment type selection using enum
- Confirmation page after submitting a request
- Equipment listing pages
- Admin requests page (URL access only)
- Bootstrap styling
- MVC separation of concerns

---

## User Roles
### Students / Professors
- Submit equipment borrowing requests
- View equipment listings

### Admin (IT Department)
- View all submitted requests

---

## Technologies Used
- ASP.NET Core MVC (.NET 8)
- C#
- Razor Views
- Bootstrap
- Git & GitHub
- Visual Studio Code

---

## Equipment Request Form Fields
- Name
- Email (validated format)
- Phone Number (xxx-xxx-xxxx)
- Role (Student / Professor)
- Equipment Type (Laptop, Phone, Tablet, Other)
- Request Details
- Duration (number of days, must be greater than zero)

---

## Project Structure
EquipmentBorrowingApp/
├── Controllers/
├── Models/
├── Views/
│ ├── Home/
│ ├── Requests/
│ └── Shared/
├── Data/
├── Program.cs
├── EquipmentBorrowingApp.csproj
└── README.md


---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-url>
   
2. Navigate to the project folder:
   ```bash
   cd EquipmentBorrowingApp>

4. Run the application:
   ```bash
   dotnet run

5. Open a browser and go to:
  ```bash
  http://localhost:5000
