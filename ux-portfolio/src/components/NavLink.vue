<script>
export default {
	name: 'NavLink',
	props: ['url', 'text']
}
</script>

<template>
	<a :href="url">{{ text }}</a>
</template>
<style>
    a{
        color: blue;
        text-decoration: none;
    }
</style>