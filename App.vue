<template>
	<div>
		<p v-if="msg.length > 0">{{ msg }}</p>
		<p v-else>no text</p>
	</div>
</template>

<script>
export default {
	data() {
		return {
			msg: "Hello World!",
		};
	},
};
</script>
