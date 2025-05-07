# AI-Powered-Analytics-module-utilizing-Langflow-and-DataStax-With-GPT-integration

This project demonstrates the development of an AI-powered analytics module for analyzing engagement metrics from social media data using **Langflow**, **DataStax Astra DB**, and **GPT integration**.

The solution leverages a no-code, visual approach (Langflow) to create workflows that automate data querying and insight generation based on input post types (e.g., Reels, Carousels, Static Posts).

---

## 🧠 Project Summary

📌 **Objective**:  
Build a scalable and intelligent analytics module that:
- Accepts a post type as input
- Queries Astra DB for average engagement metrics
- Uses GPT to generate natural language insights

📌 **Example Insight**:  
> "Reels have 2x more comments compared to static posts."

---

## 🛠️ Tools & Technologies Used

- **Langflow** – Visual workflow builder for LLM-powered apps  
- **GPT** – Natural Language Generation  
- **DataStax Astra DB** – Cloud-based Vector database  
- **JSON** – Data format for engagement metrics  
- **Python (optional)** – For data generation or testing

---

## 🧾 Dataset Overview

The dataset simulates engagement data from 100 mock social media users, including:
- User ID
- Post Type (Reel, Carousel, Static Image)
- Likes, Comments, Shares

> 📁 File: `data/social_media_engagement.json`

---

## 🔧 How to Set Up and Run the Project

### Step 1: Prepare the Environment
- Sign up at [Astra DB](https://www.datastax.com/astra)
- Create a database and keyspace
- Load the `social_media_engagement.json` into a collection

### Step 2: Setup Langflow
- Go to [https://langflow.io](https://langflow.io)
- Login or deploy locally using:
  ```bash
  pip install langflow
  langflow run

## 🗂️ Project Structure
```
📦 social-media-analytics-langflow-gpt/
├── data/
│   └── social_media_engagement.json
├── langflow/
│   └── flow.json
├── screenshots/
│   ├── workflow.png
│   └── insight_example.png
├── README.md
```

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/85576306-a7d1-4416-9c57-4e339673ab6a)
![image](https://github.com/user-attachments/assets/ce3acb12-5e87-40d4-96ad-d6a45116518c)

## 📌 Key Features

- 🧠 GPT-based natural language insight generation
- 🔗 Vector DB querying using Astra DB
- 🎯 Real-world use case for content performance analysis
- 🚫 No-code solution: Ideal for non-technical users

## Contact
- saiganeshganoju@gmail.com
