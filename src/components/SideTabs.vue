<template>
    <div class="tabs">
      <div class="tab-buttons">
        <button class="tab-button">Applicant Login</button>
        <button class="tab-button"> Tab 1</button>
        <button class="tab-button"> Tab 2</button>
        <button class="tab-button"> Tab 3</button>
        <button class="tab-button"> Tab 4</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    // Component logic goes here
  };
  </script>
  
  <style scoped>
.tabs {
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  width: 20%; /* Adjust the width as needed */
}
  
  .tab-buttons {
    display: flex;
    flex-direction: column;
  }
  
  .tab-button {
    background-color: #888;
    color: #fff;
    border: none;
    padding: 24px 36px;
    border-radius: 3px;
    margin-bottom: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  .tab-button:hover {
    background-color: #666;
  }
  
  /* Add any other component-specific styles here */
  </style>
  