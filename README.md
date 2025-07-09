# Zerodha Clone – Full Stack Web Application

This is a full-stack clone of Zerodha built with separate modules for **frontend**, **dashboard**, and **backend**.

## 📁 Folder Structure

- `frontend/` – User-facing React UI (login, register, dashboard view, charts)
- `dashboard/` – Admin dashboard with user management, stock summaries
- `Backend/` – RESTful API built with Node.js & Express, connected to a MongoDB database

## 🚀 Features

- ✅ User authentication (login/signup)
- ✅ Admin panel to monitor users/stocks
- ✅ Live charting (mock data)
- ✅ Responsive design
- ✅ Secure API integration (JWT, bcrypt)
- ✅ `.gitignore` used to exclude `node_modules` and cache folders

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Node.js, Express.js, MongoDB
- **Dashboard**: React.js + Chart.js + Admin UI libraries

## 🔧 Setup

```bash
# Install dependencies for each part
cd frontend
npm install

cd ../dashboard
npm install

cd ../Backend
npm install
