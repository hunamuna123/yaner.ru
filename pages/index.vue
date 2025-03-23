<template>
    <div class="container">
      <div class="header">
        <img src="/dog.WEBP" alt="Янер" class="avatar" />
        <h1>Янер</h1>
        <p class="subtitle">👇 Тут необходимые ссылки 👇</p>
      </div>
      <div class="links">
        <a href="https://t.me/yaner_4" target="_blank" class="link">
          <img src="/telegram.png" alt="" style="width: 24px;">
          Тг(название - Янер)
        </a>
        <a href="https://twitch.tv/yaner_4" target="_blank" class="link">
          <img src="/twitch.png" alt="" style="width: 24px;">
          Twitch
        </a>
        <a href="https://vk.com/id656800680" target="_blank" class="link">
          <img src="/vk.png" alt="" style="width: 24px;">
          По рекламе
        </a>
        <a href="https://t.me/yaner_for_all" target="_blank" class="link">
          <img src="/telegram.png" alt="" style="width: 24px;">
          Написать мне
        </a>
        <a href="https://www.instagram.com/yanerjk?igsh=eWNxZnY4ZXd6aTl3&utm_source=qr" target="_blank" class="link">
          <img src="/instagram.png" alt="" style="width: 24px;">
          Instagram
        </a>

      </div>
    </div>
  </template>


  <style scoped>
  .container {
    display: flex;
    font-family: Nunito;
    flex-direction: column;
    align-items: center;
    background: #1a1a1a;
    color: white;
    height: 100vh;
    padding-top: 20px;
  }
  
  .header {
    text-align: center;
  }
  
  .avatar {
    margin-top: 30px;
    width: 120px;
    height: 120px;
  }
  
  .subtitle {
    margin: 10px 0;
  }
  
  .links {
    display: flex;
    flex-direction: column;
    width: 90%;
    max-width: 400px;
  }
  
  .link {
    background: #2c2c2c;
    color: white;
    border: none;
    padding: 12px;
    margin: 5px 0;
    font-size: 16px;
    cursor: pointer;
    border-radius: 8px;
    font-family: Nunito;
    transition: background 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    text-decoration: none;
  }
  
  .link:hover {
    background: #444;
  }
  </style>
  