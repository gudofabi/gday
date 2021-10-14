<template>
  <nav class="navbar navbar-expand-lg bg-white">
    <div class="menu-button-container">
        <div class="menu-container">
            <a href="" class="menu-button">
                <font-awesome-icon icon="bars" class="text-white"/>
            </a>
        </div>
        <span class="ml-2 menu">MENU</span>
        <span class="malouf-icon ml-2">M</span>
    </div>
    
    <div class="left-corner">
        <a class="navbar-brand" href="#">
            <img src="../assets/img/malouf-dark-logo.svg" alt="Malouf Logo">
        </a>
    </div>

    <div class="links-container">
        <ul class="links d-flex">
            <li class="p-2">
                <a>PRODUCTS</a>
            </li>
            <li class="p-2">
                <a>WHOLESALE</a>
            </li>
            <li class="p-2">
                <a>COMPANY</a>
            </li>
            <li class="p-2">
                <a>SUPPORT</a>
            </li>
        </ul>
    </div>
    <div class="right-corner">
        <ul>
            <li>
                <a class="cart">
                    <img src="../assets/img/shopping-cart.svg" width="18" alt="Shopping Cart">
                </a>
            </li>
            <li>
                <a class="d-flex align-items-center">
                    <img src="../assets/img/padlock.svg" width="10" height="10" alt="padlock" class="lock">
                    Log In
                </a>
            </li>
        </ul>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'MainNavigation'
}
</script>