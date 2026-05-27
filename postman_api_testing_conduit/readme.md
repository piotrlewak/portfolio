# Conduit API – Automated Postman Testing (Case Study)

**Role:** QA Engineer 

## 🎯 Project Overview
This project demonstrates a complete API testing workflow using **Postman**.  
The goal was to validate the Conduit API by covering authentication, user management, articles, profiles, comments, and tags.

All tests in this collection are:
- fully automated  
- independent  
- data‑driven  
- designed to validate both positive and negative scenarios  

---

## 🧪 Scope of Testing

### **User**
- Successful login  
- Login with invalid credentials  
- Successful registration  
- Registration with invalid data (username, email, password)  
- Get user info  
- Update user info  
- Unauthorized update  

### **Articles**
- Create, update, delete article  
- Get single article  
- Get global feed  
- Get personalized feed  
- Get articles by tag  
- Negative scenarios (unauthorized create/delete, delete non-existing article)

### **Profiles**
- Get profile  
- Follow user  
- Unfollow user  

### **Comments**
- Get comments  
- Add comment  
- Delete comment  
- Negative scenarios (unauthorized delete, delete another user’s comment)

### **Tags**
- Get tags  

---

## 🧩 Pre-request Scripts
- Generate unique users  
- Prepare invalid payloads  
- Set environment variables dynamically  

---

## 🧪 Test Scripts
- Validate status codes  
- Validate error messages  
- Validate response schema  
- Validate business logic  

---

## 📊 Execution Summary
- **Total requests:** 50+  
- **Automated:** 100%  
- **Independent tests:** Yes  
- **Negative tests:** 20+  
- **Authorization tests:** Yes  
- **Data-driven tests:** Yes  

---

## 📸 Screenshots
Included screenshots show:
- Postman collection structure  
- Example request with tests  

Screenshots are located in:

**[screenshots](./screenshots/)**

---


## 📚 What I Learned
- Designing a complete API test suite  
- Using Postman as an automation framework  
- Creating reusable test logic  
- Generating dynamic test data  
- Structuring API testing projects for real teams  

---

## ✔ Summary
This project demonstrates practical, real-world API testing skills:
- full CRUD coverage  
- negative testing  
- authorization testing  
- dynamic data generation  
- automated execution  

