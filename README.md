# FemCare - Period Awareness Website & App

FemCare is a comprehensive platform designed to empower individuals with knowledge, tools, and resources related to menstrual health and wellness. It offers period tracking, personalized health insights, wellness recommendations, and an interactive chatbot for user engagement. FemCare is built to address not only physical but also mental and emotional health during menstruation, ensuring a holistic approach to well-being.

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Setup Instructions](#setup-instructions)


## Features

- **Period Tracking**: 
  - Track menstrual cycles, predict upcoming cycle lengths, and store historical data.
  - Use a Decision Tree Regressor model to predict future menstrual cycles based on user inputs and historical data.

- **Vaginal Health Monitoring**: 
  - Track and assess vaginal health, such as odor, rashes, pain, breast sensitivity, and digestion.
  - Suggest possible health interventions or steps to take based on user inputs.

- **Personalized Nutrition & Exercise Recommendations**: 
  - Provide tailored nutrition and exercise plans depending on the menstrual cycle stage (pre-menstruation, menstruation, post-menstruation).
  - Suggestions are based on a combination of scientific data and user inputs.

- **Chatbot Assistance**: 
  - Interactive chatbot powered by the Gemini LLM (or OpenAI) to provide quick responses to period-related questions.
  - The chatbot offers suggestions on menstrual health, period tracking, and general wellness.

- **Educational Content**: 
  - Access a collection of blogs and articles on menstrual health, hygiene, and lifestyle changes to make menstruation more manageable.
  - Features guides on different types of menstrual products and proper care techniques.

- **Product Integrations** (Future Plan): 
  - Plan to integrate e-commerce for sanitary products, supplements, and other wellness items tailored to the user's needs.

## Tech Stack

- **Frontend**:
  - **React.js**: A JavaScript library for building user interfaces, enabling dynamic and responsive pages.
  - **HTML/CSS**: Standard web technologies for creating structured and styled content.
  - **Axios**: For making HTTP requests to the backend API.

- **Backend**:
  - **Python**:
    - **Flask/Django**: For building the API to handle requests and integrate with the frontend.
    - **Flask-SQLAlchemy**: ORM for connecting to the database.
    - **Scikit-learn**: For building the Decision Tree Regressor model to predict the menstrual cycle.
    - **Pandas & NumPy**: For data manipulation and analysis.

- **Machine Learning**:
  - **Decision Tree Regressor**: To predict the next menstrual cycle length based on user input data.
  - **Custom Data Models**: For assessing health and providing personalized recommendations.

- **AI/Chatbot Integration**:
  - **Gemini LLM (or OpenAI GPT)**: For conversational interfaces that respond to user queries related to menstrual health.

- **Authentication**:
  - **JWT (JSON Web Tokens)**: For secure user authentication and session management.

## Setup Instructions
To set up and run FemCare on your local machine, follow these steps:
```bash
git clone https://github.com/Cdisha/Femcare-Your menstrual health assistant.git
cd Femcare-Your menstrual health assistant.git
