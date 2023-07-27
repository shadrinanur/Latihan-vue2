<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
      <template #logo>
        <NavbarLogo link="" alt="" image-url="https://e7.pngegg.com/pngimages/494/693/png-clipart-logo-shopping-list-design-product-shopping-list-purple-angle-thumbnail.png" >
          Eyyo Store
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Home</NavbarLink>
          <NavbarLink>Man</NavbarLink>
          <NavbarLink>Woman</NavbarLink>
          <NavbarLink>Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>