<script>
	import '../app.css';
	import Button from '../components/Button/button.svelte';
	let name = 'Kime';
</script>

<div>{name}</div>
<Button text="button" />

<slot />
