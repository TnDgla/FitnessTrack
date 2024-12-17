---

## Project Name: FitnessTrack

FitnessTrack is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to help users track their fitness activities, manage workouts, and monitor calories burned. The app features user authentication, charts for progress visualization, responsive design, and data management.

---

### **Mission and Objectives for FitnessTrack**

---

### **Mission:**
To create a feature-rich, responsive fitness tracking platform that enables users to monitor their progress, manage workouts, and achieve fitness goals, while ensuring secure and scalable performance.

---

### **Objectives:**
1. **User Authentication:**
   - Implement secure user authentication using JWT.
   - Enable profile management with picture uploads.

2. **Dashboard and Tracking:**
   - Build an interactive dashboard for tracking workouts and calories burned.
   - Visualize weekly and monthly progress with interactive charts.

3. **Workout Management:**
   - Allow users to log, edit, and delete workouts.
   - Store and retrieve workout data securely.

4. **Responsive Design:**
   - Ensure a mobile-first design for seamless use across devices.

5. **Deployment:**
   - Deploy the application for global accessibility with robust backend services.

---

## **Technology Stack**

### **Frontend**
1. **React.js**
   - **Why:** Simplifies building dynamic UIs.
   - **Use Case:** Creates forms, handles authentication, and renders charts.

2. **Styled Components**
   - **Why:** Enhances CSS management within React components.
   - **Use Case:** Styles pages like the dashboard and workout tracker.

3. **MUI (Material-UI)**
   - **Why:** Provides pre-designed components for consistent UI.
   - **Use Case:** Builds components like buttons, inputs, and charts.

---

### **Backend**
1. **Node.js**
   - **Why:** Provides scalability for backend development.
   - **Use Case:** API development and server-side logic.

2. **Express.js**
   - **Why:** Lightweight framework for RESTful APIs.
   - **Use Case:** Defines routes for authentication, user management, and workout data.

3. **JWT (JSON Web Tokens)**
   - **Why:** Ensures secure user sessions.
   - **Use Case:** Manages authentication and session validity.

4. **Bcrypt.js**
   - **Why:** Hashes passwords for secure storage.
   - **Use Case:** Encrypts user passwords during registration.

---

### **Database**
1. **MongoDB**
   - **Why:** Provides a flexible schema for managing user and workout data.
   - **Use Case:** Stores user accounts, workout details, and statistics.

2. **Mongoose**
   - **Why:** Simplifies database interactions through schemas.
   - **Use Case:** Handles CRUD operations for users and workouts.

---

### **Deployment**
1. **Frontend Hosting:** Netlify or Vercel
   - **Why:** Optimized platforms for React app hosting.
   - **Use Case:** Deploys the client-side application.

2. **Backend Hosting:** Render or AWS
   - **Why:** Reliable platforms for backend services.
   - **Use Case:** Hosts APIs and handles database connections.

---

## **Workflow Overview**
This section illustrates the interaction between users and the application:
1. **User Registration/Login**: Secure authentication with JWT.
2. **Workout Tracking**: Logging, updating, and managing fitness activities.
3. **Data Visualization**: Displaying progress using **Chart.js**.
4. **Profile Management**: Updating user details and uploading profile pictures.
5. **API Communication**: Seamless data exchange between the frontend and backend.

---

### **System Architecture**
The FitnessTrack Web App architecture demonstrates the interaction between the frontend, backend, database, and external services like Cloudinary for media storage.
![image](https://github.com/user-attachments/assets/d6d9ec9c-b02b-434c-af1e-69141c805296)

---

## **Week-by-Week Plan**

### **Week 1: Project Setup and Basic Structure**
- **Goal:** Set up the foundational structure for FitnessTrack.

- **Tasks:**
  1. Install Node.js, React.js, and MongoDB.
     - **Reading:** [Setting Up MERN Stack](https://www.mongodb.com/mern-stack)  
     - **Video:** [MERN Stack Crash Course](https://www.youtube.com/watch?v=fnpmR6Q5lEc)
  2. Initialize React and Express apps.
     - **Reading:** [React App Basics](https://reactjs.org/docs/getting-started.html)  
     - **Video:** [Express Server Setup](https://www.youtube.com/watch?v=L72fhGm1tfE)
  3. Install Styled Components for CSS styling.
     - **Reading:** [Styled Components Docs](https://styled-components.com/)  
     - **Video:** [Styled Components Tutorial](https://www.youtube.com/watch?v=O7xE4MRV4bY)

- **Deliverables:**
  - Basic project setup with backend and frontend initialized.

---

### **Week 2: User Authentication**
- **Goal:** Implement secure user authentication using JWT.

- **Tasks:**
  1. Create a User schema in MongoDB.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)  
     - **Video:** [MongoDB Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build authentication APIs for login and signup.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)  
     - **Video:** [JWT Implementation Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Create React forms for login and signup.
     - **Reading:** [React Forms](https://react.dev/reference/react/forms)  
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ)

- **Deliverables:**
  - A functional login/signup system.

---

### **Week 3: Dashboard and Workout Management**
- **Goal:** Enable users to log and track their workouts.

- **Tasks:**
  1. Build the workout schema in MongoDB.
     - **Reading:** [MongoDB Schema Design](https://www.mongodb.com/docs/manual/data-modeling/)  
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Create APIs for adding, updating, and deleting workouts.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)  
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pgpFFLCk6Lg)
  3. Design a React dashboard to display statistics using Chart.js.
     - **Reading:** [Chart.js Documentation](https://www.chartjs.org/docs/latest/)  
     - **Video:** [React Chart.js Tutorial](https://www.youtube.com/watch?v=Ly-9VTXJlnA)

- **Deliverables:**
  - Fully functional dashboard with interactive charts.

---

### **Week 4: Profile Management**
- **Goal:** Allow users to update their profiles and upload pictures.

- **Tasks:**
  1. Integrate Cloudinary for profile picture uploads.
     - **Reading:** [Cloudinary Setup](https://cloudinary.com/documentation)  
     - **Video:** [Image Upload with React and Cloudinary](https://www.youtube.com/watch?v=GML8Mw449O4)
  2. Build React forms for profile updates.
     - **Reading:** [React Forms](https://reactjs.org/docs/forms.html)  
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ)
  3. Ensure proper validation for all inputs.
     - **Reading:** [React Input Validation](https://reactjs.org/docs/forms.html#controlled-components)  
     - **Video:** [Form Validation in React](https://www.youtube.com/watch?v=HcOy6jQ8-dc)

- **Deliverables:**
  - A responsive profile management page.

---

### **Week 5: Deployment**
- **Goal:** Deploy the FitnessTrack app and test all features.

- **Tasks:**
  1. Deploy the frontend to Netlify/Vercel.
     - **Reading:** [Deploying React Apps](https://vercel.com/docs)  
     - **Video:** [Netlify Deployment Tutorial](https://www.youtube.com/watch?v=YdYyYMFPa44)
  2. Deploy the backend to Render.
     - **Reading:** [Render Deployment Guide](https://render.com/docs)  
     - **Video:** [Deploying Node.js Apps](https://www.youtube.com/watch?v=l134cBAJCuc)
  3. Test the entire app for bugs and optimize performance.
     - **Reading:** [Testing React Applications](https://reactjs.org/docs/testing.html)  
     - **Video:** [React Testing Tutorial](https://www.youtube.com/watch?v=8EogWSvGfWY)

- **Deliverables:**
  - A live FitnessTrack application accessible via a public URL.

---

### **Screenshots**
![Screenshot (286)](https://github.com/user-attachments/assets/f78fe6d2-5bf3-48fb-baca-f2f911edb936)
![Screenshot (287)](https://github.com/user-attachments/assets/8100bbb7-500c-40ae-9c16-bec82b3e262e)
![Screenshot (288)](https://github.com/user-attachments/assets/eaf160d8-e6f3-4ada-a07c-db2b98a9d883)
![Screenshot (289)](https://github.com/user-attachments/assets/7220c8b4-eda6-4492-bab2-2682079a8883)
![Screenshot (281)](https://github.com/user-attachments/assets/99fdb477-8e80-431c-b677-0a1f133df664)
![Screenshot (282)](https://github.com/user-attachments/assets/cac4b67f-0818-4846-95ac-a739893bc4bc)
![Screenshot (283)](https://github.com/user-attachments/assets/557b94aa-561a-4464-9f73-b4d76fb3a033)
![Screenshot (284)](https://github.com/user-attachments/assets/9fae0013-66aa-4432-9d77-c082b83401ab)
![Screenshot (285)](https://github.com/user-attachments/assets/af331be6-3778-4ca8-952d-72fb2e458b21)

---

## **References**
1. [React.js Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Styled Components Docs](https://styled-components.com/)
4. [MUI Documentation](https://mui.com/)
5. [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
6. https://github.com/rishavchanda/FItnessTrack
7. https://www.youtube.com/watch?v=HISjHTE2vnM
