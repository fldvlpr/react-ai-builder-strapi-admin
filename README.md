# 🚀 AI Resume Builder - Strapi Backend
A powerful **Strapi CMS** backend providing API services for the AI Resume Builder application.
<br/>

## 🌟 Features
- 📊 **Content Management** for resumes and templates
- 🔐 **JWT Authentication** with secure endpoints
- 📝 **Resume Data Models** with structured content types
- 🎨 **Template Management** system
- 📡 **RESTful API** endpoints
- 🔒 **Role-based Access Control**

## 🔗 Connected React Frontend Repo
👉 [React Frontend Repository](https://github.com/fldvlpr/react-ai-resume-builder-app)
<br/>

## 🚀 Live Demo
Backend API deployed on **Render**:
<br/>
👉 [Check Live Web App URL](https://tg-react-ai-resume-builder.netlify.app/)
<br/>

## 📱 Web Preview
[https://github.com/user-attachments/assets/59365e9e-fa2f-417e-a3aa-30152bad2af8
<br/>](https://github.com/user-attachments/assets/9bff0916-4bbe-48c6-ae7e-c1bb9eb07c35)

## 📦 Tech Stack
- Strapi v4
- AlwaysData (Database)
- Render (Deployment)
- JWT Authentication

## 🛠️ Setup Instructions

1. **Clone this repository:**
   ```bash
   git clone https://github.com/fldvlpr/react-ai-builder-strapi-admin.git
   cd ai-resume-builder-backend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   
   Create a **.env** file in the root directory and paste your strapi environment variables as following:
   ```bash
   HOST=0.0.0.0
   PORT=1337
   APP_KEYS=your_app_keys_here
   API_TOKEN_SALT=your_api_token_salt
   ADMIN_JWT_SECRET=your_admin_jwt_secret
   JWT_SECRET=your_jwt_secret
   
   # Database (AlwaysData)
   DATABASE_CLIENT=postgres
   DATABASE_HOST=your_alwaysdata_host
   DATABASE_PORT=5432
   DATABASE_NAME=your_database_name
   DATABASE_USERNAME=your_alwaysdata_username
   DATABASE_PASSWORD=your_alwaysdata_password
   ```

4. **Start the Development Server**
   ```bash
   npm run develop
   ```

Admin panel available at: `http://localhost:1337/admin`
