<template>
  <div id="app" class="bg-gray-300">
    <Navbar />
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from "./components/NavBar";
import Footer from "./components/Footer";
export default {
  name: "Appvue",
  components: {
    Navbar,
    Footer,
  },
  data() {
    return {
      tabs: [
        { icon: "fas fa-home", title: "Kategory", id: "kategory" },
        { icon: "fas fa-hashtag", title: "Lokasi", id: "lokasi" },
        { icon: "far fa-bell", title: "Harga", id: "harga" },
        { icon: "far fa-envelope", title: "Pengiriman", id: "pegiriman" },
        { icon: "far fa-bookmark", title: "Penawaran", id: "penawaran" },
        { icon: "fas fa-clipboard-list", title: "Warna", id: "warna" },
        { icon: "far fa-user", title: "Kondisi", id: "kondisi" },
        { icon: "far fa-user", title: "Rating", id: "rating" },
      ],
      id: "home",
    };
  },
};
</script>
<style></style>
