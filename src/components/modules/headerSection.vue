<template>
  <header class="navigation w-full flex items-center shadow-md fixed">
    <div class="container mx-auto flex justify-between items-center px-3">
      <div class="flex items-center">
          <p class="proj-text-primary whitespace-nowrap">競選倒數：</p>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">40</p>
            <p class="proj-text-secondary text-xs">DAY</p>
          </div>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">03</p>
            <p class="proj-text-secondary text-xs">HOUR</p>
          </div>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">33</p>
            <p class="proj-text-secondary text-xs">MIN</p>
          </div>
        </div>
      <nav>
        <div class="nav-mobile"><a id="nav-toggle" href="#!"><span></span></a></div>
        <ul class="nav-list">
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">委員介紹</a></li>
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">競選主張</a></li>
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">最新消息</a></li>
          <li>
            <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl text-white">小額捐款
              <img src="@/assets/img/heart.png" alt="heart" class="ml-2">
            </a>
          </li>
          <li>
            <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl text-white">服務信箱
              <img src="@/assets/img/mailbox.png" alt="mailbox" class="ml-2">
            </a>
          </li>
          <!-- <li><a href="#!">About</a></li> -->
          <!-- <li class="dropdown"><a href="#!">Services</a>
              <ul class="nav-dropdown">
                <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">委員介紹</a></li>
                <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">競選主張</a></li>
                <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">最新消息</a></li>
                <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl">小額捐款
                  <img src="@/assets/img/heart.png" alt="heart" class="ml-2">
                </a></li>
                <li><a href="https://2022.thef2e.com/signup" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button cursor-pointer text-sm tracking-wider rounded-3xl">服務信箱
                  <img src="@/assets/img/mailbox.png" alt="mailbox" class="ml-2">
                </a></li>
              </ul>
            </li> -->
            <!-- <li><a href="#!">Pricing</a></li>
            <li><a href="#!">Contact</a></li> -->
        </ul>
        <!-- <ul class="nav-list">
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">委員介紹</a></li>
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">競選主張</a></li>
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">最新消息</a></li>
          <li><a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl">小額捐款
            <img src="@/assets/img/heart.png" alt="heart" class="ml-2">
          </a></li>
          <li><a href="https://2022.thef2e.com/signup" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button cursor-pointer text-sm tracking-wider rounded-3xl">服務信箱
            <img src="@/assets/img/mailbox.png" alt="mailbox" class="ml-2">
          </a></li>
        </ul> -->
      </nav>
    </div>
  </header>
</template>
<script>
import { ref } from 'vue'
export default({
  setup () {
    const isOpen = ref(true)
    const toggleMenu = () => {
      isOpen.value = !isOpen.value
    }
    return {
      isOpen, toggleMenu
    }
  },
})
</script>

<style lang="scss" scoped>
header {
  background: white;
  .button {
    color: white;
    background: #7d6035;
  }
}

.navigation {
  height: 70px;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 99;
}

.brand {
  float: left;
  line-height: 70px;
  font-size: 1.4em;
  padding-left: 20px;
 }

.brand a {
  text-decoration: none;
  text-transform: uppercase;
}

nav {
  float: right;
}

nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

nav ul li {
  float: left;
  position: relative;
}

nav ul li a {
  // display: block;
  color: #7d6035;
  // padding: 0 20px;
  text-decoration: none;
  // line-height: 70px;
}

nav ul li a:hover {
  color: rgba(125, 96, 53, 50%);
  transition: .4s;
}

nav ul li a:not(:only-child):after {
  padding-left: 4px;
  content: '  ▾'; }

nav ul li ul li {
  min-width: 160px;
  }

nav ul li ul li a {
  padding: 15px;
  line-height: 20px;
}

.nav-dropdown {
  position: absolute;
  z-index: 1;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.15);
  display: none;  }

/* Mobile Hamburger Menu */

.nav-mobile {
  display: none;
  height: 70px;
  width: 70px;
  position: absolute;
  top: 0;
  right: 0;
}

/* Media Query for Navigation */

@media only screen and (max-width: 800px) {

  .nav-mobile {
    display: block;
  }

  nav {
    width: 100%;
    padding: 0 15px;
  }
  
  nav ul {
    display: none;
  }
  
  nav ul li {
    float: none;
  }
  
   nav ul li a {
          padding: 15px;
          line-height: 20px; 
  }

  nav ul li ul li a {
          padding-left: 40px;
          background-color: gray;
  }
  
  .nav-dropdown {
    position: static;
  }
}

@media screen and (min-width: 800px) {
  .nav-list {
    display: block !important; } }
#nav-toggle {
  position: absolute;
  left: 18px;
  top: 22px;
  cursor: pointer;
  padding: 10px 35px 16px 0; }
  #nav-toggle span,
  #nav-toggle span:before,
  #nav-toggle span:after {
    cursor: pointer;
    border-radius: 1px;
    height: 4px;
    width: 30px;
    background: #7d6035;
    position: absolute;
    display: block;
    content: '';
    transition: all 300ms ease-in-out; }
  #nav-toggle span:before {
    top: -10px; }
  #nav-toggle span:after {
    bottom: -10px; }
  #nav-toggle.active span {
    background-color: transparent; }
    #nav-toggle.active span:before, #nav-toggle.active span:after {
      top: 0; }
    #nav-toggle.active span:before {
      transform: rotate(45deg); }
    #nav-toggle.active span:after {
      transform: rotate(-45deg); }


</style>
