# README for Streams CRUD Application

This project demonstrates a basic CRUD (Create, Read, Update, Delete) application for managing streams of data. It uses React, Redux, and JSON Server as the backend. Semantic UI is utilized for styling components.

---

## **Getting Started**

### 1. Prerequisites

- Node.js and npm installed on your system.

### 2. Clone the Repository

```bash
git clone <repository-url>
cd streams-client
```

### 3. Install Project Dependencies

#### Frontend Dependencies:

Navigate to the `streams-client` directory and run:

```bash
npm install
```

#### Backend Dependencies:

Navigate to the `streams-server` directory and run:

```bash
npm install
```

---

## **Running the Application**

### 1. Start the Backend (JSON Server)

Navigate to the `streams-server` directory and start the server:

```bash
npm start
```

- The backend server runs on `http://localhost:3005`.

### 2. Start the React Frontend

Navigate to the `streams-client` directory and start the frontend:

```bash
npm start
```

- The frontend runs on `http://localhost:3000`.

---

## **Key Features**

1. **List Streams**: Fetch and display a list of streams from the backend.
2. **Add Streams**: Use a form to create new streams.
3. **Edit Streams**: Update details of existing streams.
4. **Delete Streams**: Remove unwanted streams.

---

## **Technologies Used**

- **React**: Component-based frontend library.
- **React Redux**: Simplified state management.
- **Axios**: API communication.
- **JSON Server**: Mock backend server.
- **Semantic UI**: Prebuilt UI components.

---

## **File Overview**

```
rubix-assignment/
├── src/
|   ├──  actions
|   |   ├── index.js
│   ├── components/
│   │   ├── CreateStream.js  // Form to add new streams.
│   │   ├── StreamEdit.js  // Modal to confirm deletion.
│   │   └── StreamList.js  // Displays all streams.
│   ├── reducers
│   │   ├── streamsReducer  // Reducer for streams.
│   ├── App.js  // Main app layout.
│   ├── store.js  // Configures the Redux store.
│   └── index.js  // Entry point.
```

rubix-assignment/
├── db.json
