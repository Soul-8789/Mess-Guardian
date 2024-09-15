# Mess-Guardian

The **"Mess Guardian"** project focuses on creating a dedicated hostel 
mess management app, streamlining meal distribution through daily QR 
code-based meal coupons for students. The application offers an interface 
enabling students to rate, review meals, and includes a complaints section 
for reporting hostel mess food concerns.

**Efficient Meal Planning** : Ensure efficient planning of meals based on the number of coupons redeemed.

**Fair Distribution** : Ensure fair distribution of meals among all participants, preventing misuse or hoarding of coupons.

**Feedback and Improvement** : Collect feedback from participants to continuously improve the quality and variety of meals offered through the mess management system.




---

## Technologies Used
- **Backend**: Node.js, Express.js
- **Frontend**: React.js
- **Database**: MongoDB
- **Authentication**: JWT

---

## Features

### 1. **Admin Dashboard**
The admin dashboard is the control center for managing mess operations. It provides the admin with tools to handle student check-ins, manage meals, and view feedback and complaints.

#### **Sections:**

- **QR Code Scanning**: 
  Admins can scan or verify the QR codes generated for students. This ensures that only authorized students access the meals. The system checks if the student has already used their QR for the day.
  
  ![Screenshot from 2024-09-15 11-23-11](https://github.com/user-attachments/assets/364719ae-9c62-45b7-954e-b9625a74839b)
  ![Screenshot from 2024-09-15 11-38-00](https://github.com/user-attachments/assets/fbcae25a-488b-4a06-923e-242560264d8d) 

- **Profile**: 
  This section contains the admin’s details, including their name, email, contact number, and role. It allows the admin to update their information if needed.
  
  ![Screenshot from 2024-09-15 11-23-18](https://github.com/user-attachments/assets/598ccff1-4102-4914-9309-9b43656cf07c)

- **Coupan Generation**: 
  Admins can generate meal coupons for students. These coupons are redeemable and allow students to get meals at specific times. The admin can set expiration dates for the coupons.
  
  ![Screenshot from 2024-09-15 11-23-24](https://github.com/user-attachments/assets/cc367f85-ee4a-4df7-9dca-b24e82d3dae5)
 

- **Meal Chart**: 
  The meal chart displays the current menu for the week. The admin can update it according to availability and preferences. Students can view the updated menu in real-time.
  
  ![Screenshot from 2024-09-15 11-23-29](https://github.com/user-attachments/assets/ed2e0711-18a7-41f8-9b24-7e4cde8e5515)
 

- **Reviews**: 
  This section lists all the reviews provided by students about the meals and services. Admins can read the reviews, analyze feedback, and use it to improve mess operations.
  
  ![Screenshot from 2024-09-15 11-14-39](https://github.com/user-attachments/assets/e4482ad6-f503-4eb0-8325-17cfc569f886)


- **Complaints**: 
  A detailed list of complaints submitted by students, categorized by hostel. Admins can view, sort, and respond to each complaint to ensure timely resolutions. This helps in maintaining transparency and improving services.
  
  ![Screenshot from 2024-09-15 11-14-44](https://github.com/user-attachments/assets/4d5b73db-f7bd-4731-aa1f-123c75c961eb)
  

- **Contact**: 
  The contact section lists important personnel contacts such as the hostel warden, mess secretary, clerk, and other relevant staff. Admins can update or modify these details.
  
  ![Screenshot from 2024-09-15 11-14-48](https://github.com/user-attachments/assets/1a64537c-80df-48f2-8b89-fff5b6276fd2)
 

---

### 2. **Student Profile**
The student profile section is where students can manage their interactions with the mess, access their meal coupons, and provide feedback.

#### **Sections:**
- **Register**: 
    New students can create an account by providing their details like name, email, roll number, branch, hostel number, and password. Upon registration, they will receive their credentials to access the system.
  
    ![Screenshot from 2024-09-13 09-31-11](https://github.com/user-attachments/assets/1597a4fa-b862-467f-ab03-47ca8a44646b)
  
- **Login**: 
  Students must first log in using their email and password to access their profile and other services. The login form includes fields for entering credentials, and upon successful login, students are redirected to their dashboard.
    
  ![Screenshot from 2024-09-15 11-12-39](https://github.com/user-attachments/assets/e8c47fa2-f643-4a3e-9947-1c126cf9f61d)

- **Profile**: 
  This section displays the student's basic details like name, email, roll number, branch, and hostel number. Students can update their profile if necessary.
  
  ![Screenshot from 2024-09-15 11-14-24](https://github.com/user-attachments/assets/56184a08-7897-4877-a02f-169c15230130)
  
 

- **Coupons**: 
  Students can view and redeem available meal coupons. These coupons are time-sensitive and can be used to get food during specified meal times.
  
  ![Screenshot from 2024-09-15 11-27-01](https://github.com/user-attachments/assets/d55e53ff-9425-4f64-bcb0-bfc9edbdecf9)


- **Meal Chart**: 
  Students can check the current meal schedule and see what's being served for breakfast, lunch, and dinner. The chart is updated by the admin and reflects real-time changes.
  
  ![Screenshot from 2024-09-15 11-14-35](https://github.com/user-attachments/assets/23bd087b-cc79-4f0a-b13e-319f4f2dbb20)

 

- **Reviews**: 
  Students have the option to leave reviews for the food. They can rate the meals and provide feedback, which helps improve the quality of service.
  
  ![Screenshot from 2024-09-15 11-51-17](https://github.com/user-attachments/assets/8e30dc04-a5f2-4991-92a8-d2656d6e6a61)
  ![Screenshot from 2024-09-15 11-14-39](https://github.com/user-attachments/assets/e4482ad6-f503-4eb0-8325-17cfc569f886)



- **Complaints**: 
  Students can submit complaints about the mess or hostel services. All submitted complaints are forwarded to the admin for resolution. Students can track the status of their complaints.
  
  ![Screenshot from 2024-09-15 11-51-39](https://github.com/user-attachments/assets/b3e4e5b0-1a30-4464-8f17-84daaacc65cc)

  ![Screenshot from 2024-09-15 11-14-44](https://github.com/user-attachments/assets/4d5b73db-f7bd-4731-aa1f-123c75c961eb)
 

- **Contact**: 
  This section provides the students with essential contact details of staff members such as the hostel warden, mess secretary, laundry staff, and others. It helps students easily reach out for assistance.
  
  ![Screenshot from 2024-09-15 11-14-48](https://github.com/user-attachments/assets/1a64537c-80df-48f2-8b89-fff5b6276fd2)


---

## How to Use

### 1. Admin
1. Log in to the admin dashboard.
2. Use the QR scanning system to verify student entries.
3. Generate meal coupons and update the meal chart.
4. View and respond to reviews and complaints submitted by students.
5. Keep the contact information of important staff members updated.

### 2. Student
1. Log in to your student profile.
2. View your available meal coupons and redeem them.
3. Check the meal chart to see the daily menu.
4. Leave reviews for the meals and services.
5. Submit complaints about the mess or hostel and track their resolution.
6. Access contact information for important personnel.


