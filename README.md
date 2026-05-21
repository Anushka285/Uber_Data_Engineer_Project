# 🚖 Uber Real-Time Data Engineering Project

A real-time ride booking simulation system built using **FastAPI**, **Azure Event Hub**, and **Python**.  
This project demonstrates how ride booking events can be generated, streamed, and processed in a modern data engineering workflow.

---

## 📌 Project Overview

This application simulates an Uber-style ride booking platform where:

- Users can book rides through a web interface
- Ride data is dynamically generated using Faker
- Booking events are streamed into Azure Event Hub
- FastAPI powers the backend APIs
- HTML/CSS frontend provides an interactive user experience

The project showcases a simple but realistic real-time event streaming architecture commonly used in modern data engineering systems.

---

## 🛠️ Tech Stack

- Python
- FastAPI
- Azure Event Hub
- Faker
- HTML/CSS
- Jinja2 Templates
- Uvicorn

---

## ✨ Features

- 🚗 Ride booking simulation
- ⚡ Real-time event streaming
- 📡 Azure Event Hub integration
- 🎨 Modern responsive frontend
- 🔄 Dynamic ride generation using Faker
- 🧩 FastAPI backend architecture

---

## 🏗️ Architecture

<img width="1290" height="867" alt="image" src="https://github.com/user-attachments/assets/f5c74f7b-f08a-4e37-8ebb-d2eae76fbbfa" />

The architecture demonstrates a real-time event-driven pipeline where ride booking events are generated from the web application, streamed through Azure Event Hub, processed using Spark/Databricks, and transformed into analytical star-schema structures for downstream analytics and reporting.

---

## ⚙️ Azure Data Factory Ingestion Pipeline

<img width="824" height="421" alt="image" src="https://github.com/user-attachments/assets/867d9cc7-4e05-48fe-81c9-f9db3c3c1fdf" />

The project uses Azure Data Factory (ADF) to orchestrate and automate the real-time data ingestion workflow. The pipeline dynamically processes incoming ride booking files/events and triggers downstream streaming activities for scalable data processing.

---

## 📷 Application Screenshots

### Home Page

<img width="938" height="902" alt="image" src="https://github.com/user-attachments/assets/e877e956-3778-419f-a6e8-ad81b79ab218" />

The homepage provides a modern ride booking interface where users can initiate ride requests that trigger real-time event streaming workflows.

### Ride Confirmation Page

<img width="943" height="903" alt="image" src="https://github.com/user-attachments/assets/7d8f82ec-d9c9-4dbe-bc35-8f942949fc9c" />

After booking a ride, the application confirms successful event ingestion and demonstrates the end-to-end integration between the frontend, FastAPI backend, and Azure Event Hub.

---

## ▶️ Run The Project Locally

### 1. Clone Repository

```bash
git clone https://github.com/Anushka285/Uber_Data_Engineer_Project.git
