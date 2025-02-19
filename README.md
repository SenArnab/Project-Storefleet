# StoreFleet - Instant Product Delivery

## 🚀 Project Overview
Welcome to **StoreFleet**, a next-gen instant product delivery service aiming to compete with Blinkit, Zepto, and Swiggy. Unlike traditional platforms, StoreFleet delivers not only food and groceries but also a wide range of products like smartphones and other essentials—ensuring seamless, fast, and reliable service.

As a part of this exciting venture, your role includes:
- Implementing new features
- Debugging existing issues
- Enhancing the overall functionality of the platform

## 📂 Getting Started
Clone the GitHub repository to access the scaffold code and begin development.

🔗 **GitHub Repository:** [https://github.com/SenArnab/Project-Storefleet]

---
## 🔍 Key Objectives & Features
### 1️⃣ Code Analysis & Debugging
- Gain an in-depth understanding of the codebase
- Analyze the flow of each route
- Identify and fix bugs to enhance stability and performance

### 2️⃣ Welcome Email Feature (Nodemailer Integration)
- Automatically send a welcome email upon successful registration
- Include the company’s brand logo and a warm greeting


📌 **Related Route:** User Signup Route

### 3️⃣ Handling Duplicate Key Errors in MongoDB
- Ensure unique email registration
- Implement clear, user-friendly error messages


### 4️⃣ Secure Password Storage (Mongoose Middleware + Bcrypt)
- Automatically hash user passwords before saving them to the database

### 5️⃣ Forgot & Reset Password Feature
- Implement a secure, token-based password reset system
- Set token expiry (10 minutes) to enhance security
- Utilize Nodemailer to send reset tokens to users

📌 **Related Routes:**
- Forget Password Route
- Reset Password Route


### 6️⃣ Secure Admin Routes
- Fix existing security loopholes in `authByUserRole("admin")`
- Ensure only **admin users** can access restricted routes

### 7️⃣ Admin-Controlled User Role Management
- Implement a route allowing admins to update user roles

📌 **Route:** `/api/storefleet/user/admin/update/:id`

### 8️⃣ Product Search, Filtering, & Pagination
- Implement MongoDB **regex search** for keyword-based queries
- Use MongoDB **limit method** for efficient pagination
- Design custom filtering logic

📌 **Refer to the Postman link for route URLs.**

### 9️⃣ Fix Review Delete & Rating Update Feature
- Restrict users to deleting only **their own reviews**
- Ensure **product ratings update dynamically** after a review is deleted

### 🔟 Order Placement System
- Implement controllers & repository functions to manage order processing
- Analyze the existing `order` schema

📌 **Key Components:**
- `createNewOrder` Controller
- `createNewOrderRepo`

---
## 🛠 API Testing & Postman Collection
📌 **Test your API endpoints with the Postman collection:**

🔗 [StoreFleet Postman Collection](https://www.postman.com/prayrit/workspace/storefleet/collection/26789165-4d015bc6-c27e-4696-950c-6bd0e7cb0426?action=share&creator=26789165)

### How to Use:
1. Click the link above
2. Fork the collection to your Postman workspace
3. Adjust parameters (ObjectId, postId, commentId, etc.) as needed
4. Start testing the API!

---
## 🚀 Get Involved & Contribute
Whether you're fixing bugs, implementing features, or optimizing performance, your contributions are invaluable to **StoreFleet’s success**. Let's build an **efficient, fast, and scalable** delivery platform together!

🎯 **Happy Coding!** 🚀

