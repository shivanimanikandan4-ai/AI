<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Random Background Color</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      transition: background-color 0.5s ease;
    }
    button {
      margin-top: 20%;
      padding: 12px 20px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      background: #4CAF50;
      color: white;
    }
    button:hover {
      background: #45a049;
    }
  </style>
</head>
<body>
  <h1>Click the Button to Change Background Color</h1>
  <button onclick="changeColor()">Change Color</button
