<template>
  	<div id="app">
	  	<div class="container">
			<navigation app-name="Vue Starter"></navigation>
			<div class="justify-content-center align-items-center jumbo">
				<img src="./assets/ensibuuko.png" class="logo mt-lg-5"><br>
				<h1 class="text-center title">Vue Bootstrap</h1>
				<p class="text-center">The vue bootsrap 4 webpack starter template you have been waiting for. Bootstrap your website in no time.</p>
				<div class="links text-center">
                    <a class="links-item" href="https://github.com/Ensibuuko/vue-bootstrap#make-vue-awesome">Documentation</a>
                    <a class="links-item" href="https://lhttps://laracasts.com/series/learn-vue-2-step-by-step">Vue Tuts</a>
                    <a class="links-item" href="https://github.com/Ensibuuko/vue-bootstrap#contribute">Contributors</a>
                    <a class="links-item" href="https://github.com/Ensibuuko/vue-bootstrap">GitHub</a>
                </div>
			</div>
	  	</div>
  	</div>
</template>

<script>
	import Navigation from './components/Navigation.vue';
	export default {
	   	name: 'app',
	  	components: {
	  		Navigation
	  	}
	}
</script>

<style lang="scss">
@import './styles/custom.scss';
@import './styles/splash.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>
