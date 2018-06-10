<template>
  <div>
    <nuxt/>
  </div>
</template>

<script>
import BasicHeader from '../components/BasicHeader'

export default {
  components: {
    BasicHeader
  }
}
</script>


<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

@font-face { font-family: open-sans; src: url('OpenSans-Regular.ttf'); } 
@font-face { font-family: lato; src: url('Lato-Regular.ttf'); } 
.background{
    background-color:  rgba(124, 110, 110, 0.548);
    font-family: open-sans;
    text-color: black;
}
.date{
    margin: 25px;
    font-size: 60;
  }
.hora{
    font-size: 50;
    position:absolute;
    z-index: 0;
    display: flex;
    align-items: center;
    justify-content: center;

    width: 220px;
    height: 80px;
    background-color:#02C6D1;
    right: 0;
}
.tags{
    font-size: 35;
    position: relative;
    display: flex;
    align-items: flex-end;
    color: #52595B;
    background-color: rgb(245, 243, 243);
  }
.descripcao{
    margin: 25px;
    font-size: 35;
    display: flex;
    position: relative;
    align-items: flex-start;
  }
.title{
    margin: 25px;
    font-size: 60;
    display: flex;
    align-items: center;
  }
.boxed {
    margin: 25px;
    background-color:#0095AD;
    position: relative;
  }
.boxed img{
    height: 450px;
    width: 100%;
    object-fit: cover;
}
.horario{
    margin: 25px;
    font-size: 45;
    display: flex;
    align-items: center;
}
.tags{
    margin: 25px;
    font-size: 35;
    position: relative;
    display: flex;
    align-items: flex-end;
    bottom: 10px;
    color: rgb(94, 89, 89);
  }
.descripcao{
    margin: 25px;
    font-size: 15;
    display: flex;
    position: relative;
    align-items: flex-start;
  }
.title{
    margin: 25px;
    font-size: 60;
    display: flex;
    align-items: center;
  }
.boxed {
    margin: 25px;
    background-color:#82b3c9;
    position: relative;
    border-radius: 20px 20px 20px 20px;
    -moz-border-radius: 20px 20px 20px 20px;
    -webkit-border-radius: 20px 20px 20px 20px;
  }
.boxed img{
    height: 450px;
    width: 100%;
    border-radius: 20px 20px 0px 0px;
    -moz-border-radius: 20px 20px 0px 0px;
    -webkit-border-radius: 20px 20px 0px 0px;
    object-fit: cover;
}
.header-menu {
  margin-top: -3.1em;
  height: 3em;
  text-align: left;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  background-color: #2286c3
}

.img {
  height: 1em;
}

.h1, .h2, .h3, .h4, .h5, .h6, .h7, .h8 {
  color: black;
}

.signup {
  padding: 1em;
  position: relative;
  overflow: hidden;
}

form {
  padding: 20px 50px 20px 20px;
}

form .form-group {
  display: flex;
  flex-direction: column;
  font-size: .9em;
  margin: 0 0 20px 0;
}

.form-group input[type="text"], 
.form-group input[type="password"] {
  border: none;
  outline: none;
  font-size: 1em;
  padding: 0.4em;
}

form .form-group:last-child {
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  
}

button {
  
}

</style>
