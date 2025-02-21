🛒 E-Commerce Webpage (React & Spring Boot)
This is a simple E-Commerce webpage where users can view products and filter them by category.  

The project is built using:  
- Frontend: React.js (Vite)  
- Backend: Spring Boot  
- Database: MySQL (to store and fetch product data)  

I will be adding more features soon! 🚀  

---

⚙️ Tech Stack
Frontend (React with Vite)
- React.js (useState, useEffect, React Router)
- Axios (for API calls)
- TailwindCSS / Bootstrap (for styling)
- Vite (for fast development and better performance)

Backend (Spring Boot)
- Spring Boot (Spring MVC, Spring Data JPA)
- MySQL (to store product details)
- REST API (built using Spring Boot)
- Spring Boot DevTools (for hot reloading)
- CORS Configured for frontend-backend communication

---

🚀 How to Run the Project
1⃣ Backend (Spring Boot) Setup
1. Clone the project and navigate to the backend folder:
    git clone <repo-url>
    cd backend
2. Configure MySQL Database:  
    Open `application.properties` (or `application.yml`) and set up your MySQL credentials:
     spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
     spring.datasource.username=root
     spring.datasource.password=your_password
     spring.jpa.hibernate.ddl-auto=update
3. Run the backend:
    mvn spring-boot:run
    The API will be available at: `http://localhost:8080`

---

2⃣ Frontend (React with Vite) Setup
1. Navigate to the frontend folder:
   cd ../frontend
2. Install dependencies:
   npm install
3. Start the frontend:
   npm run dev
   - React app will run at: `http://localhost:5173/`

---

📀 Upcoming Features
🛠 User authentication (Login/Register)  
🛠 Add to Cart & Checkout functionality  
🛠 Payment Integration  
🛠 Admin Dashboard (Add/Edit/Delete products)  

---

🛠️ Contributions & Feedback
- Feel free to fork this repo and add new features!  
- If you find bugs or want new features, open an issue.  

📧 Contact: namanswami3696@gmail.com  



