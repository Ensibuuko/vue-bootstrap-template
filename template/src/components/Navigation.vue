<template>
	<nav class="navbar navbar-light">
	  	<a class="navbar-brand" href="#">
	    	<img src="../assets/vue-logo.svg" width="30" height="30" class="d-inline-block align-top" alt="">
	    		<strong>{{ appName }}</strong>
	  	</a>
	  	<ul class="navbar-nav">
	      	<li class="nav-item">
	        	<a class="btn btn-primary" href="https://github.com/Ensibuuko/vue-bootstrap">Fork it on Github</a>
	      	</li>
	    </ul>
	</nav>
</template>
<script>
	export default {
		name: "Navigation",
		props: {
			appName: {
				type: String,
				required: true
			}
		}
	}
</script>