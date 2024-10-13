<template>
    <div class="welcome-container">
      <h1 class="welcome-title">Welcome to the IE Bank</h1>
      <nav class="navigation">
        <router-link to="/accounts" class="link-button">Accounts</router-link>
        <router-link to="/skull" class="link-button">Skull</router-link>
      </nav>
    </div>
  </template>
  
  <style scoped>
  .welcome-container {
    text-align: center;
    padding: 40px;
    background: linear-gradient(135deg, #f0f4f8, #e0e8f0);
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  }
  
  .welcome-title {
    font-size: 2.5em;
    margin-bottom: 30px;
    color: #333;
    font-family: 'Arial', sans-serif;
  }
  
  .navigation {
    display: flex;
    justify-content: center;
    gap: 20px;
  }
  
  .link-button {
    padding: 12px 24px;
    background-color: #33e760;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s, transform 0.2s;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  }
  
  .link-button:hover {
    background-color: #06b300;
    transform: translateY(-2px);
  }
  </style>
  