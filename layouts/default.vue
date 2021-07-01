<template>
	<div>
		<TheHeader @sidenavToggle="displaySidenav = !displaySidenav"/>
		<TheSidenav
			:show="displaySidenav"
			@close="displaySidenav=false"
		/>
		<Nuxt />	
	</div>
</template>

<script>
import TheHeader from '@/components/Navigation/NavigationTheHeader'
import TheSidenav from '@/components/Navigation/NavigationTheSidenav'

export default {
	components: {
		TheHeader,
		TheSidenav
	},
	data() {
		return {
			displaySidenav: false
		}
	}
}
</script>


<style>
	html {
		font-family: 'Open Sans', sans-serif;
	}
	body {
		font-family: 'Open Sans', sans-serif;
		margin: 0;
		padding: 0;
	}
</style>