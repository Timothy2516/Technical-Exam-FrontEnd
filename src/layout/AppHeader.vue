<template>
    <header class="header-global">
        <base-nav class="navbar-main" type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <span style="font-size: 30px; color: white;">KONGSI &nbsp;</span>
                <img v-lazy="'img/assets/ole777-white.png'">
            </router-link>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <base-button type="warning" size="sm">Login</base-button>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <base-button type="white" size="sm">Daftar sekarang</base-button>
                </li>
            </ul>
        </base-nav>

        <base-nav class="navbar-main-two" type="" expand>
            <div class="row">
                <div class="col-md-3">
                    <span class="nav-link-inner--text" style="color: #fba322;">Tentang OLE777</span>
                </div>
                <div class="col-md-2">
                    <span class="nav-link-inner--text" style="color: white;">Komisi</span>
                </div>
                <div class="col-md-2">
                    <span class="nav-link-inner--text" style="color: white;">Peraturan</span>
                </div>
                <div class="col-md-4">
                    <span class="nav-link-inner--text" style="color: white;">Pertanyaan & Jawaban</span>
                </div>
                <div class="col-md-1">
                    <base-button type="warning" size="sm">OLE777 Official</base-button>
                </div>
            </div>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
