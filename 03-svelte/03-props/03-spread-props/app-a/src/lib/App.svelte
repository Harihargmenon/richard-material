<script>
	import PackageInfo from './PackageInfo.svelte';

	const pkg = {
		name: 'svelte',
		speed: 'blazing',
		version: 3,
		website: 'https://barabariproject.org'
	};
</script>

<PackageInfo
	name={pkg.name}
	speed={pkg.speed}
	website={pkg.website}
/>
