<template>
    <header class="header">
      <div class="contact-list">
        <a href="https://github.com/b1nqu" target="_blank" class="contact-item">
          GitHub
        </a>
        <a href="mailto:bpatrykqwerty@gmail.com" class="contact-item">
          Email
        </a>
      </div>
    </header>
  </template>
  
  <style scoped>
  .header {
    text-align: center;
    margin-bottom: 16px;
    padding: 20px;
    background: #3c0b38;
    color: #ffffff;
    border-radius: 8px;
    max-width: 1200px;
    width: 100%;
    max-height: 400px;
    height: 100%;
  }
  h1 {
    font-size: 4rem;
    margin-bottom: 10px;
  }
  h2 {
    font-size: 2rem;
    color: #76c7c0;
  }
  .contact-list {
    display: flex;
    justify-content: center;
    gap: 20px;
  }
  .contact-item {
    display: flex;
    align-items: center;
    color: #ffffff;
    text-decoration: none;
    font-size: 1.2rem;
  }
  .contact-item i {
    margin-right: 8px;
    font-size: 1.5rem;
  }
  .contact-item:hover {
    color: #A3CFFF;
  }
  </style>
  G