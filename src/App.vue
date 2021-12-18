<template>
  <Navbar />
  <Header />
  <Services />
  <SpecialApps />
  <button class="circular-btn chat"><ChatProcessing title="Chat Button" /></button>
  <button class="circular-btn to-top">
    <ArrowUpBold title="Back to Top"/>
  </button>
  <Footer />
</template>

<script>
import Navbar from './components/Navbar';
import Header from './components/Header';
import Services from './components/Services';
import SpecialApps from './components/SpecialApps';
import Footer from './components/Footer';
import ChatProcessing from 'vue-material-design-icons/ChatProcessing.vue';
import ArrowUpBold from "vue-material-design-icons/ArrowUpBold.vue";
import './assets/styles.css';

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    Services,
    SpecialApps,
    ArrowUpBold,
    Footer,
    ChatProcessing
  }
}
</script>

