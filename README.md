# SmartRoom Infrastructure 🏗️

This repository serves as the **Configuration Hub** and installation guide for the SmartRoom application ecosystem.

## 🔗 Related Repositories
* **Backend:** [Link to SmartRoom.API Repository]
* **Frontend:** [Link to SmartRoom.Web Repository]

## 🛠️ Prerequisites
Before applying these configurations, ensure your local environment has the following installed:
1. **.NET SDK 8** (For Backend)
2. **Node.js v18+** (For Frontend)
3. **SQL Server** (Local instance or via Docker)



---

## 🚀 How to Use

### 1. Backend Setup
1. Navigate to the `backend` folder in this repository.
2. Copy the `.env.example` file.
3. Paste it into the root folder of the `SmartRoom.API` repository (Backend Repo).
4. Rename the file to `.env` (or synchronize it with `appsettings.json` if you are not using a dotenv library).
5. **IMPORTANT:** Update the database `Password` and `JWT_KEY` with your own secure values.

### 2. Frontend Setup
1. Navigate to the `frontend` folder in this repository.
2. Copy the `.env.example` file.
3. Paste it into the root folder of the `SmartRoom.Web` repository (Frontend Repo).
4. Rename the file to `.env`.
5. Ensure `VITE_API_URL` matches the port where your backend is running (Default: 5000/5001).