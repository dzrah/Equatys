<script>
	let {
		class: className = '',
		bgClass = 'bg-white',
		bgImage = '',
		style = '',
		children,
		...restProps
	} = $props();

	const computedStyle = $derived(
		[bgImage ? `background-image: url(${bgImage})` : '', style].filter(Boolean).join('; ')
	);
</script>

<section
	class="w-full {bgClass} {className}"
	style={computedStyle || undefined}
	{...restProps}
>
	{@render children()}
</section>
