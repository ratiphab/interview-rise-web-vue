<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header/> 
  <body>
    <div class="context1">
      <div class="stytext">
        <span>
          <h1 >Higher click-through rates for your product</h1><br/>
          Don't stop tracking your product and better analyze your
          customers just too easy steps.
        </span> 
      </div>
      <div class="styimage">
        <img src="@/assets/click-through-rate.png"/>
      </div>
    </div>

    <div class="context2">
      <span class="headtext">
      <h1 style="font-size:44px">How BetterGoods works?</h1><br/>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, Purus ipsum est facilisi
      mi sed nec ultrices, Ullamcorper ut proin arcu mi vel erat</p>
      </span>
      <div class="context2_1">
        <div>
          <img src="@/assets/how-it-work-1.png"/><br/>
          <b>1. dwogeqwed asdqeogeg aweghjo</b><br/>
          <p>qeelrkjle oriefoio asldfjqw af qiwepowfqp idsfpqw</p>
        </div>
        <div>
          <img src="@/assets/how-it-work-2.png"/><br/>
          <b>2. qgqewed asdrtthrtjeg efgewert</b><br/>
          <p>erjerrgerg wewegwetwu et ertegergerge rgerhaeaererg erahaerhaergaerg argr</p>
        </div>
        <div>
          <img src="@/assets/how-it-work-3.png"/><br/>
          <b>3. egwerher rethrtjrty wewrghwer</b><br/>
          <p>ewfwerhert sdgwrjhreyryhtkuyea ergertje wrgwerhgaerharghwregwe wefwwe efwefwef</p>
        </div>
        <div>
          <img src="@/assets/how-it-work-4.png"/><br/>
          <b>4. rfgheargaewrgawerga wefwyjrtet </b><br/>
          <p>eretuertgergeargsrtujityityjnrtyhsrtjsyj eatujaertyjaertghaerthearth aeryhaerthaeruwetje</p>
        </div>
      </div>
    </div>

    <div class="context3">
      <b style="font-size:44px">Power-up your performance</b>
      <p>Augue pellentesque egestas ipsum justa, dictum commodo in erat a. Vel bibendům consectetur convallis faucibus velit
      elementum lacus, ac. Rhoncus, risus tellus convallis, gravida. Vestibulum odia dapibus ut laoreet. Quis aliquam-massa
      arcu commodo enim, aenean, eget at tellus. Blandit viverra nascetur amet tristique nunc iaoreet. Massa elit semper nec
      eleifend tristique tristique. Tempor êu euismod tincidunt vestibulumn nulla curabityr habitant. sit consectetur et amet
      scelerisque adipiscing in sed adipiscing neque. Imperdiet in sed et imperdiet gravida facilisi.morbi</p>
      <p style="margin-top:4%">Egestas lectus amet volutpat turpis orci neque purus elementum, Eu ultrices laoreet facilisis diam sit- elementum nunc
      egestas maecènas. At nisl ut amet, cursus ac imperdiet mauris rįdiculus daplbus. Praesent vitae, eu'nunc auctor ut
      pharetra. Adipiscing amnet in commoda duis gravida sem mi. Consectetur, et at sagittis vulputate sed orci viverra sem
      amiet Tristique sit rhoncus sit enim cras consectetur quam vel interdum.</p>
    </div>
  </body>

  <div class="context4">
    <div class="content4_1">
      <img src="@/assets/power-up-2.png"/><br/>
      <b style="font-size : 26px">Yopus orem ipsum oder</b><br/>
      <p>Lorem ipsum dolor sit amet, conuectetur ad ipiacing eltFurus ipsum eet fociil mi aod noc ulitrices</p>
    </div>
    <div class="content4_1">
      <img src="@/assets/power-up-3.png"/><br/>
      <b style="font-size : 26px">Odee lorem ipsum</b><br/>
      <p>Lorem ipsum dolor sit amet, conuectetur ad ipiacing eltFurus ipsum eet fociil mi aod noc ulitrices</p>
    </div>
  </div>
  <Footer/>
  
</template>

<style scoped>
.header-css {
  z-index: 100;
  position: fixed;
  top: 0;
}

.context1 {
  weight: 100%;
  height: 100%;
  display : flex;
  flex : 1;
  margin: 5%;
}

.context1 .stytext {
  display : flex;
  flex : 0.5;
  white-space: pre;
  align-items: center;
  font-size: large; 
}
.context1 .styimage {
  display : flex;
  flex : 0.8;
  margin-left : 5%;
}

.context2 {
  background-color: #E8E8E8;
  padding : 5%
}


.context2 .headtext {
  text-align: center;
}

.context2 .context2_1{
  display: flex;
  justify-content: space-evenly; 
  flex-direction: row;
  margin-top : 2%;
  gap : 10px
}

.context2 .context2_1 p{
  margin-top :3%
}

.context3 {
  background-image: url('@/assets/power-up-1.png');
  background-repeat: round;
  color: #FFFFFF;
  text-align: center;
  padding : 5% 7%
}

.context4 {
  display : flex;
  flex : 1;
  flex-direction: row;
  background-color: #E8E8E8;
  justify-content: center; 
  text-align: center;
  padding : 5% 7%;
  gap:20px;
}

.context4 .content4_1 {
  display : flex;
  flex : 0.5;
  flex-direction: column;
}



</style>
