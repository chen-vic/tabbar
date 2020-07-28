<template>
	<tab-bar>	
		<tabbar-item link="/home" activeColor='blue'>
			<img slot='item-icon' src="../assets/img/tabbar/home.svg" alt="">
			<img slot='item-icon-active' src="../assets/img/tabbar/s_home.svg" alt="">
			<div slot='item-text'>首页</div>
		</tabbar-item>
		<tabbar-item link="/category" activeColor='blue'>
			<img slot='item-icon' src="../assets/img/tabbar/category.svg" alt="">
			<img slot='item-icon-active' src="../assets/img/tabbar/s_category.svg" alt="">
			<div slot='item-text'>分类</div>
		</tabbar-item>
		<tabbar-item link="/cart" activeColor='blue'>
			<img slot='item-icon' src="../assets/img/tabbar/shopcart.svg" alt="">
			<img slot='item-icon-active' src="../assets/img/tabbar/s_shopcart.svg" alt="">
			<div slot='item-text'>购物车</div>
		</tabbar-item>
		<tabbar-item link="/profile" activeColor='blue'>
			<img slot='item-icon' src="../assets/img/tabbar/profile.svg" alt="">
			<img slot='item-icon-active' src="../assets/img/tabbar/s_profile.svg" alt="">
			<div slot='item-text'>我的</div>
		</tabbar-item>
	</tab-bar>
</template>

<script>
	import TabBar from './tabbar/TabBar.vue'
	import TabbarItem from './tabbar/TabbarItem.vue'

	export default {
	  name: 'MainTabBar',
	  components:{
		  TabBar,
		  TabbarItem
	  }
	}
</script>

<style>
</style>
