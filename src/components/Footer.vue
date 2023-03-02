<template>
    <div class="a">
        <div class="b">
            <div>
                <img src="@/assets/logo-alone.png"/>
            </div>
        </div>
        <ul class="menu">
            <li v-for="(item, index) in menuItems" :key="index">
                <a :href="item.link">{{ item.label }}</a>
            </li>
        </ul>
        <div class="social-media">
            <img src="@/assets/facebook-logo.png"/>
            <img src="@/assets/twitter-logo.png"/>
            <img src="@/assets/instagram-logo.png"/>
            <img src="@/assets/youtube-logo.png"/>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        { label: "Ornare", },
        { label: "Accumasan", },
        { label: "Mattis", }
      ]
    }
  }
}
</script>

<style>
.a {
    display : flex;
    justify-content: space-between; 
}
.b {
    display : flex;
    flex:0.2;
}

.social-media {
    flex:0.3;
    display : flex;
    justify-content: space-evenly; 
    align-items: center;
    height: 100%;
    padding: 15px;
    gap: 5px;
}

.menu {
  list-style: none;
  display: flex;
  flex : 0.4;
  justify-content: flex-start; 
  align-items: center;
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 0px;
}


.menu li {
  margin: 0 20px;
}

.menu a {
  color: #000000;
  text-decoration: none;
}


</style>
