<template>
  <nav class="navbar navbar-expand-lg" style="background-color: #FFFDFD;">
    <div class="container-fluid d-flex justify-content-between">
      <a class="navbar-brand" href="#">
        <img src="../assets/img/logo.png" alt="THEF2E" class="w-16">
      </a>
      <button class="navbar-toggler" type="button"
      data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav"
      aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav" style="flex-grow:0;">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/" class=" px-4 py-2 me-3 bg-black rounded text-white">
              服務介紹
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/" class=" px-4 py-2 me-3 bg-black rounded text-white">
              簽署文件
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/" class=" px-4 py-2 me-3 bg-black rounded text-white">
              註冊
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/" class=" px-4 py-2 me-3 bg-black rounded text-white">
              登入
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
