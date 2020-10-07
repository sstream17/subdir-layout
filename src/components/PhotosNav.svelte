<script lang="ts">
	export let segment: string;
</script>

<style>
	nav {
		float: left;
	}
</style>

<nav>
	<ul>
		<li>
			<a
				aria-current={segment === undefined ? 'page' : undefined}
				href="photos">home</a>
		</li>
		<li>
			<a
				aria-current={segment === 'funny' ? 'page' : undefined}
				href="photos/funny">funny</a>
		</li>
		<li>
			<a
				aria-current={segment === 'cool' ? 'page' : undefined}
				href="photos/cool">cool</a>
		</li>
	</ul>
</nav>
