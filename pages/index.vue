<template>
  <div class="container">
    <div class="header">
      <img src="/dog.WEBP" alt="Янер" class="avatar" />
      <h1>Янер</h1>
      <p class="subtitle">👇 Тут необходимые ссылки 👇</p>
    </div>
    
    <div class="links">
      <a href="https://t.me/+oLlP0CrtlYRlZTAy" target="_blank" class="link">
        <img src="/telegram.png" alt="" style="width: 24px; justify-content: left;">
        Мой телеграм канал
      </a>
      <a href="https://twitch.tv/yaner_4" target="_blank" class="link">
        <img src="/twitch.png" alt="" style="width: 24px;">
        Твич
      </a>
      <a href="mailto:janerjk@gmail.com" class="link">
        <img src="/mail.png" alt="" style="width: 24px;">
        По рекламе
      </a>
      <a href="https://t.me/yaner_for_all" target="_blank" class="link">
        <img src="/telegram.png" alt="" style="width: 24px;">
        Написать мне
      </a>

      <div class="hint">
        ❓ Если не открывается:
        нажми сверху справа <br> «три точки» -> «открыть в браузере»

      </div>
    </div>


    <div style="margin-top: auto; margin-bottom: 30px;">
      <a href="https://t.me/hunadev" target="_blank" class="secret">
        by huna.muna
      </a>
    </div>
  </div>
</template>

<style>
.container {
  display: flex;
  font-family: Nunito;
  flex-direction: column;
  align-items: center;
  background: #1a1a1a;
  color: white;
  height: 100vh;
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

.hint {
  color: #ccc;
  font-size: 12px;
  padding: 10px 14px;
  border-radius: 6px;
  margin: 3px 0;
  text-align: center;
  line-height: 1.4;
}

.hint a {
  color: #66ccff;
  text-decoration: underline;
}

.hint a:hover {
  color: #99ddff;
}

.secret {
  text-decoration: none;
  color: white;
}

.secret:hover {
  text-decoration: underline;
  color: white;
}
</style>
