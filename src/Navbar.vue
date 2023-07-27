<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar >
      <template #logo>
        <NavbarLogo link="https://www.google.com/"  image-url="https://www.48hourslogo.com/48hourslogo_data/2019/07/23/86762_1563852941.png">
          Survival
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Beranda</NavbarLink>
          <NavbarLink link="#">Hewan</NavbarLink>
          <NavbarLink link="#">Makanan</NavbarLink>
          <NavbarLink link="#">Tempat camping</NavbarLink>
          <NavbarLink link="#">Saran</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
    
</template>