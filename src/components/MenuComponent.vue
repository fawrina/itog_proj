<template>
    <div style="width: 100%; ">
      <ul>
        <li v-for="item in menuItems" :key="item.id">
          {{ item.text }}
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "menu-component",
    data() {
      return {
        menuItems: [
          { id: 1, text: 'Зарегистрироваться' },
          { id: 2, text: 'Лента предпочтений' },
          { id: 3, text: 'Моя анкета' },
          { id: 4, text: 'Пожаловаться' },
          { id: 5, text: 'Войти' },
          { id: 6, text: 'VIP подписка' }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    background-color: #FD72C1;
    width: 100%;
    justify-content: space-around;
    
  }
  
  li {
    font-family: "Arial";
    font-weight: 700;
    padding: 15px;
    cursor: pointer;
    color: #0900A7;
  }
  
  li:last-child {
    Border-right: none;
  }
  </style>
  