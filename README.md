# Marjane Doc - Doctor Patient Management System

This project is a **simple PHP-based patient management system** for doctors in Morocco. It allows doctors to manage **appointments and walk-in patients**, and lets patients **view their appointment status online**.  

You can access the live project here: [Marjane Doc](https://marjanedoc.wuaze.com/)

---

## Features

### Doctor
- Login to the dashboard
- View today’s patients
- Add patients (appointments or walk-ins)
- Update patient status: waiting → in consultation → finished
- Copy patient link to share with patients

### Patient
- Login using phone number
- View appointment type, time, status, and clinic location
- Walk-ins see estimated waiting time in minutes

---

## How to Use

### Landing Page
Visit the project link and choose:
- **Doctor Login** → access the dashboard  
- **Patient View** → login with phone number  

### Doctor Login
- Default credentials:  
  - Username: `doctor`  
  - Password: `1234`  
- After login, you can:
  - View today’s patients  
  - Add new patients  
  - Update patient status  
  

### Patient View
- Go to **Patient View**  
- Enter your phone number  
- See your appointment details, status, clinic location, and estimated wait (for walk-ins)

---

## Notes
- All data is stored in a MySQL database
- Default timezone: Africa/Casablanca
- Clinic location can be customized in `patient_view.php`
- Login is currently hardcoded; database-based login can be implemented for multiple doctors

---

This project is fully hosted on InfinityFree and ready to use.
