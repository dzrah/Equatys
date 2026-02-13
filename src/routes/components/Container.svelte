<script>
	let { class: className = '', children, id: idName = '' } = $props();
</script>

<div class="mx-auto w-full max-w-7xl px-5 sm:px-10 md:px-20 lg:px-25 {className} {idName}">
	{@render children()}
</div>
