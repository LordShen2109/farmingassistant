# 🌾 CropXpert

**CropXpert** is a smart AI-powered platform designed to support farmers with vital agricultural information and assistance.  
Users can upload images, input personal and farming details, and receive instant, intelligent feedback powered by the Gemini AI API.

🔗 [Live Demo](https://farmingassistant-dc9u.onrender.com/)

---

## 🚀 Key Features

- 📸 **Soil & Pest Analysis via Image Upload**  
  Upload an image of your soil or pest-affected plant to get AI-generated insights and recommendations for improvement or treatment.

- 🏛️ **Government Scheme Recommender**  
  Based on your age, location, and crops grown, the app provides personalized government scheme suggestions.

- 🌱 **Best Farming Practices**  
  Get AI-curated tips for sustainable farming, low-cost soil testing methods, and organic pest control.

- 🌘 **Dark Mode Support**  
  CropXpert supports a clean and user-friendly dark mode for better accessibility and visual comfort.

- 🔐 **Authentication with Login/Register**  
  Users can register and log in securely. Authentication and user data are managed using PostgreSQL.

- 🤖 **All AI-Powered with Gemini API**  
  Every suggestion is generated using intelligent prompts through Google's Gemini API on the free tier.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Database**: PostgreSQL (hosted on Railway)  
- **AI Integration**: Gemini AI API  
- **Frontend Hosting**: Render  
- **Backend Hosting**: Railway  
- **Version Control**: Git & GitHub  
- **Collaboration**: GitHub for team contributions and workflow management

---

## 📂 Running the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/LordShen2109/farmingassistant.git
cd farmingassistant
```
### 2. Install Dependencies

```bash
npm i
```
### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add the following:

```env
GEMINI_API_KEY=your_google_gemini_api_key
SECRET_KEY=your_custom_secret_key
```
You can generate your Gemini API key at Google AI Studio

### 4. Create Datbase Tables
Run the SQL queries from the queries.sql file in your PostgreSQL database to create the necessary tables.

### 5. Start the Server
```bash
node server.js
```

### 6. Access the App
Visit http://localhost:3000 in your browser to use the app locally.

## Future Improvements
-**Add multi-language support for regional farmers.**

-**Push notifications for seasonal updates and alerts.**

-**Real-time chat with agri-experts powered by AI.**
