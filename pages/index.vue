<template>
	<div class="container">
		<h5>Hello Vue</h5>
		<nuxt-link to="/about">About</nuxt-link>
	</div>
</template>

<script>
export default {
	head: () => {
		return {
			title: 'Home - Erlangga',
			meta: [
				{
					hid: 'Home',
					description: 'Home',
					content: 'Home of Blog'
				}
			]
		}
	}
}
</script>