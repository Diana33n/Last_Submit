# Project-5: Travel Planner App

## About This Project
The **Travel Planner App** helps you organize trips effortlessly! Just enter your destination and departure date, and you'll get a **weather forecast** and an **image** of your location. 

Built with **JavaScript, Webpack, and Express**, this application also works **offline** thanks to service workers!

---

## Features
- Enter a **destination** and **departure date**
- Get the **latest weather forecast**
- View an **image of your destination**
- Works **offline** with service workers
- **Live updates** with Webpack Dev Server
---

  ## Prerequisites
- **Node.js v22.12.0**

---

## Technologies Used
- **Frontend:** JavaScript (ES6+), Webpack, SCSS
- **Backend:** Node.js, Express
- **APIs:** Geonames, Weatherbit, Pixabay
- **Testing:** Jest
- **Offline Support:** Workbox Service Workers

---

## How to Run the Project
### 1. Clone the Project
```sh
cd travel-planner-application
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Add API Keys (Create a `.env` file)
```sh
GEONAMES_USER=your_geonames_username
WEATHERBIT_KEY=your_weatherbit_api_key
PIXABAY_KEY=your_pixabay_api_key
```

### 4. Run the App in Development Mode
```sh
npm run development
```
Open **`http://localhost:8081/`**

### 5. Build & Run for Production
```sh
npm run build
npm start
```
Open **`http://localhost:8080/`**

---

## Running Tests
To test the application using Jest:
```sh
npm test
```

---



### License
This project is open-source and available under the **MIT License**.

