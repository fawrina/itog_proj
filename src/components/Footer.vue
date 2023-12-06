<template>
    <footer>
      <div class="footer-content">
        <div class="contact-info">
          <p>Телефон: {{ phoneNumber }}</p>
          <p>Юридический адрес: {{ legalAddress }}</p>
        </div>
        <div class="social-links">
          <a href="https://vk.com/adyakova2021" target="_blank" rel="noopener noreferrer" style="color: #92C6E8;"><img src="../assets/vk-logo.svg" alt="" srcset=""></a>
          <a href="https://t.me/fawrina1" target="_blank" rel="noopener noreferrer" style="color: #92C6E8;"><img src="../assets/telegram-logo.svg" alt="" srcset=""></a>
          <a href="https://msng.link/o?fawrina=sk" target="_blank" rel="noopener noreferrer" style="color: #92C6E8;"><img src="../assets/skype.svg" alt="" srcset=""></a>
          <!-- Добавьте другие социальные сети по аналогии -->
        </div>
      </div>
      <p>&copy; 2023 Dating Dream. Все права защищены.</p>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer-component',
    data() {
      return {
        phoneNumber: '+7 (999) 999-9999', // Замените на ваш номер телефона
        legalAddress: 'Borovaya Ulitsa, 38, St Petersburg, Russia 191546', // Замените на ваш юридический адрес
      };
    },
  };
  </script>
  
  <style scoped>
  footer
    {
        background-color: #DDF2FF;
        color: #92C6E8;
        text-align: center;
        padding: 10px;
    }
  
  .footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .contact-info {
    text-align: left;
  }
  
  .social-links a {
    color: #fff;
    margin-right: 10px;
    text-decoration: none;
  }
  img {
    transition: 1s;
  }
  img:hover {
    transform: scale(2, 2);
  }
  </style>
