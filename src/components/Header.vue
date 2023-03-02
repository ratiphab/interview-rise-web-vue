<template>
    <div class="a">
        <div class="logo">
            <img src="@/assets/logo-full.png"/>
        </div>
        <ul class="menu">
                <li v-for="(item, index) in menuItems" :key="index">
                    <a :href="item.link">{{ item.label }}</a>
                </li>
            </ul>
        <div class="logout">
            <p>Logout</p>
            <img src="@/assets/profile.png"/>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        { label: "Explore products", },
        { label: "Products design", },
        { label: "Pricing", }
      ]
    }
  }
}
</script>

<style>
.a {
    display: flex;
    justify-content: space-between; 
    position: sticky;
    top: 0;
    background-color: #FFFFFF;
}

.menu {
  list-style: none;
  display: flex;
  flex : 0.6;
  justify-content: space-between;
  align-items: center;
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 0px;
}


.menu li {
  margin: 0 50px;
}

.menu a {
  color: #000000;
  text-decoration: none;
}
.logo {
    display : flex;
    flex : 0.2;
    align-items: center;
    padding-left : 10%
    
}
.logout {
    display : flex;
    flex : 0.2;
    align-items: center;
    justify-content: flex-end;
}

.logout img{
    margin-left:20px;
}
</style>
