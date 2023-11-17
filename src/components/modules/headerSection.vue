<template>
  <header class="header fixed top-0 left-0 w-full z-50 proj-text-primary">
    <nav class="container mx-auto py-3">
      <div class="flex justify-between items-center">
        <div class="flex items-center px-3">
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
        <ul class="site-nav w-full lg:w-auto" :class="{ 'site-nav--open': isOpen}">
          <li><a href="#" target="_blank" class="link block py-4 md:py-3 px-3 items-center justify-center mr-3 cursor-pointer tracking-wider">委員介紹</a></li>
          <li><a href="#" target="_blank" class="link block py-4 md:py-3 px-3 items-center justify-center mr-3 cursor-pointer tracking-wider">競選主張</a></li>
          <li><a href="#" target="_blank" class="link block py-4 md:py-3 px-3 items-center justify-center mr-3 cursor-pointer tracking-wider">最新消息</a></li>
          <li>
            <a href="#" target="_blank" class="py-4 md:py-3 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl text-white">小額捐款
              <img src="@/assets/img/heart.png" alt="heart" class="ml-2">
            </a>
          </li>
          <li>
            <a href="#" target="_blank" class="py-4 md:py-3 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl text-white">服務信箱
              <img src="@/assets/img/mailbox.png" alt="mailbox" class="ml-2">
            </a>
          </li>
        </ul>
        <div class="menu-toggle" @click="toggleMenu"  :class="{ 'open': isOpen}">
          <div class="hamburger"></div>
        </div>
      </div>
    </nav>
  </header>
</template>
<script>
import { ref } from 'vue'
export default({
  setup () {
    const isOpen = ref(false)
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

img {
  display: block;
  // margin: 0 auto;
}

nav {
  // color: #EBEBD3;
  // padding: 1em 0;
  position: relative;
}

nav::after {
  content: '';
  clear: both;
  display: table;
}

.logo {
  float: left;
  font-size: 1em;
  margin: 0;
  text-transform: uppercase;
  font-weight: 700;
}

.logo span {
  font-weight: 300;
}

.site-nav {
  // color: white;
  margin: 0;
  padding: 0;
  position: absolute;
  top: 100%;
  right: 0;
  background: #7d6035;
  height: 0px;
  overflow: hidden;
  // width: 100%;
  color: white;
  @media screen and (min-width: 1024px) {
    color: #7d6035;
  }
}

.site-nav--open {
  height: auto;
}

.site-nav li {
  border-bottom: 1px solid #beaf9a;
}

.site-nav li:last-child {
  border-bottom: none;
}

.site-nav link {
  color: white;
  text-decoration: none;
  text-transform: uppercase;
}

.site-nav--icon {
  display: inline-block;
  font-size: 1.5em;
  margin-right: 1em;
  width: 1.1em;
  text-align: right;
  color: rgba(255,255,255,0.45);
}

.menu-toggle {
  padding: 1em;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  right: 0;
  cursor: pointer;
}

.hamburger,
.hamburger::before,
.hamburger::after{
  content: '';
  display: block;
  background: #ebebd3;
  height: 3px;
  width: 25px;
  border-radius: 3px;
  transition: all ease-in-out 500ms;
}

.hamburger::before {
  transform: translatey(-7px);
}

.hamburger::after {
  transform: translatey(4px);
}

.open .hamburger {
  transform: rotate(45deg);
}

.open .hamburger::before {
  opacity: 0;
}

.open .hamburger::after {
  transform: translatey(-3px) rotate(-90deg);
}

@media (min-width: 1024px) {
  .menu-toggle {
    display: none;
  }
  .site-nav {
    height: auto;
    position: relative;
    background: transparent;
    float: right;
  }
  .site-nav li {
    display: inline-block;
    border: none;
  }
  .site-nav link {
    color: #7d6035;
  }
  .site-nav--icon {
    display: none;
  }
}
</style>
