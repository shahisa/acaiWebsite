<template>
  <div id="app">
    <h1>Açaí: Invest in The Community and Yourself </h1>
    <h3>What is Açaí?</h3>
    <p>
      The struggle is real. Sometimes you need some quick cash.
    </p>
    <p>
      Maybe your looking for financial freedom through the stock market and saving.   
    </p> 
    <h3>Açaí Can Help</h3>
    <p>It makes it so you can invest and borrow money at the same time.</p>
    <div>
      <ul>You link your debit or credit card to the mobile app and it takes your space change and automatically invests it in the stock market.</ul>
      <ul>But it also gives you the power to lend money to your friends, family and even strangers. And you recieve a little some interest on your loan. </ul>
      <ul>If you are borrowing money, you set your own repayment plan and interest rate. You develop your own credit rating within the app ecosystem. Don't worry about your "real credit score".</ul>

    <div style="position: relative;">
      <parallax :fixed="true">
        <img src="static/img/pexels-photo-196416.jpeg">
      </parallax>
    <div>

    <div style="background-color: #fff; height: 100vh;">
      <md-card>
        <md-card-header>
          <div clas="md-title">
            More Inforamtion Alerts
          </div>
        </md-card-header>
      </md-card>
      <form novalidate @submit.stop.prevent="submit">
        <md-input-container>
          <label>First Name</label>
          <md-input v-model="initialValue"></md-input>
        </md-input-container>

        <md-input-container>
          <label>With label</label>
          <md-input placeholder="My nice placeholder"></md-input>
        </md-input-container>

        <md-input-container>
          <md-icon>phone</md-icon>
          <label>Phone</label>
          <md-input type="number"></md-input>
        </md-input-container>   
      </form>
    </div>
  </div>
</template>

<script>
import Parallax from './components/Parallax'

export default {
  name: 'app',
  components: {
    Parallax
  }
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #581845;
  position: relative;
}
</style>
