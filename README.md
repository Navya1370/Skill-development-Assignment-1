# 📚 AI-Based Student Productivity Assistant

## 🔹 Project Description
The AI-Based Student Productivity Assistant is a Generative AI application developed using Python and Google Colab. It helps students create personalized study plans based on inputs such as subject, deadline, topics, study hours, and goal.

The application uses the Gemini API to generate structured outputs including:
- Day-wise study plan
- Time management tips
- Motivational message

This project demonstrates the concept of prompt-based content generation in Generative AI.

---

## 🔹 Features
- Generates customized study plans
- Provides time management tips
- Includes motivational messages
- Simple and user-friendly interface
- Works in real-time using Gemini API

---

## 🔹 Technologies Used
- Python
- Google Colab
- Gemini API (google-genai SDK)

---

## 🔹 How It Works
1. User enters study details (subject, deadline, topics, etc.)
2. The program constructs a structured prompt
3. The prompt is sent to the Gemini model
4. The model generates a study plan and suggestions
5. Output is displayed to the user

---

## 🔹 Sample Input
- Subject: Data Structures  
- Deadline: 5 days  
- Topics: Stacks, Queues, Trees  
- Daily Study Hours: 3  
- Goal: Exam Preparation  

---

## 🔹 Sample Output
- Day-wise study schedule  
- Tips for better time management  
- Short motivational message  

---

## 🔹 Installation & Usage

### Step 1: Open Google Colab
Go to https://colab.research.google.com

### Step 2: Install library
```python
!pip install google-genai
