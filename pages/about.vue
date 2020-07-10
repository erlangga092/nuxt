<template>
	<div class="container">
		<h5>About Page</h5>
		<nuxt-link to='/'>Home</nuxt-link>
	</div>
</template>

<script>
	export default {
		head: () => {
			return {
				title: 'About - Erlangga Blog',
				meta: [
					{
						hid: 'About',
						name: 'About',
						content: 'About blog of Erlangga'
					}
				]
			}
		}
	}
</script>