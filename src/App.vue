<template>
  <Navbar />
  <Header />
  <Services />
  <Footer />
</template>

<script>
import Navbar from './components/Navbar';
import Header from './components/Header';
import Services from './components/Services';
import Footer from './components/Footer';
import './assets/styles.css';

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    Services,
    Footer
  }
}
</script>

