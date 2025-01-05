# InsightXfactor 

#Social Media Analytics Platform

![Insightly Banner](https://via.placeholder.com/1200x400?text=Insightly+-+Social+Media+Analytics+Platform)

### Complete Technical Documentation

---

## Table of Contents
- [Project Overview](#project-overview)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Deployment](#deployment)
- [API Documentation](#api-documentation)
- [Features Overview](#features-overview)
- [Contributors](#contributors)

---

## Project Overview
**Insightly** is a cutting-edge Social Media Analytics Platform designed to empower users with deep insights into their social media engagement. By leveraging AI-powered tools like LangFlow and OpenAI GPT, Insightly helps users track, analyze, and optimize their social media performance.

### **Core Highlights**
- **Platform**: Web-based solution
- **Objective**: Deliver actionable insights for social media growth
- **Key Technologies**: React, Node.js, DataStax Astra DB, LangFlow, OpenAI GPT

![Social Media Analytics](https://via.placeholder.com/800x400?text=Social+Media+Analytics)

---

## System Architecture
| **Component**          | **Technology**         |
|-------------------------|-------------------------|
| **Frontend**            | React.js               |
| **Backend**             | Node.js with Express   |
| **Database**            | DataStax Astra DB      |
| **AI Integration**      | LangFlow, OpenAI APIs  |

### **Workflow Overview**
1. **Data Input**: Social media engagement data is ingested from various sources.
2. **Data Processing**: Data is parsed, chunked, and sent to the AI for insights.
3. **Insights Generation**: GPT generates actionable analytics.
4. **Visualization**: Data is visualized on a React-based frontend dashboard.

![System Workflow](https://via.placeholder.com/800x400?text=System+Architecture+Workflow)

---

## Installation

To set up **Insightly** locally, follow these steps:

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- [Git](https://git-scm.com/)
- DataStax Astra DB account
- OpenAI API key

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/Social-Media-Analytics.git
   cd Social-Media-Analytics
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file with the following:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   DATASTAX_DB_URL=your_datastax_db_url
   DATASTAX_DB_KEY=your_datastax_db_key
   ```

4. **Start the application**:
   ```bash
   npm start
   ```

5. **Access the platform**:
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser.

---

## Deployment

### **Live Application**
- **URL**: [Insightly Analytics](https://socialanalytics-client.onrender.com/)
- **Status**: Active

### **Deployment Infrastructure**
| **Component**          | **Platform**         |
|-------------------------|----------------------|
| **Frontend**            | Render Web Services  |
| **Backend**             | Render Web Services  |
| **Database**            | DataStax Astra DB    |
| **AI Integration**      | LangFlow & OpenAI    |

### Steps to Deploy
1. Push your changes to the `main` branch.
2. Deploy the frontend and backend on [Render](https://render.com/).
3. Connect to your DataStax Astra DB instance.
4. Monitor deployment logs for errors.

---

## API Documentation
### **Endpoints**
#### 1. Chat API
- **Endpoint**: `POST /chat`
- **Payload**:
  ```json
  {
    "input_value": "string",
    "requestId": "string"
  }
  ```
- **Description**: Forwards user input to LangFlow and streams GPT responses.

#### 2. Analytics API
- **Endpoint**: `GET /api/posts`
- **Query Parameters**:
  - `startDate`: ISO date string
  - `endDate`: ISO date string
  - `postTypes`: Array of post types
  - `page`: Page number (default: 1)
  - `limit`: Items per page (default: 50)
- **Response**:
  ```json
  {
    "posts": [ ... ],
    "totalCount": 100
  }
  ```

---

## Features Overview

| **Feature**                | **Description**                                           |
|----------------------------|-----------------------------------------------------------|
| Real-time Analytics        | Analyze engagement metrics in real time                  |
| GPT Insights               | Generate AI-powered recommendations and reports          |
| Custom Metric Tracking     | Define and track custom social media KPIs                |
| Data Visualization         | Beautiful charts and dashboards for quick understanding  |
| Engagement Metrics         | Measure likes, comments, shares, and engagement rates    |

---

## Contributors
- [Chahat Kesharwani](https://github.com/chahatkesh)  
- [Davinder Singh](https://github.com/Davinder1436)  
- [Vatsal Khanna](https://github.com/VatsalKhanna5)  
- [Rishi Ahuja](https://github.com/RishiAhuja)

---

## Screenshots

### Dashboard Overview
![Dashboard Screenshot](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

### Insights Panel
![Insights Panel](https://via.placeholder.com/800x400?text=Insights+Panel)

---


_Insightly - Empowering Social Media Analytics, 2025_
