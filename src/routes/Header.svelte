<script>
	import * as config from '$lib/config';
</script>

<nav>
	<!-- Title -->
	<a href="/" class="title">
		<b>{config.title}</b>
	</a>

	<!-- Navigation -->
	<ul class="links">
		<li>
			<a href="/rulebook">Rule Book</a>
		</li>
		<li>
			<a href="/rulebook/players">Character Creation</a>
		</li>
		<li>
			<a href="/rulebook/gm">GM Resources</a>
		</li>
		<li>
			<a href="/setting">The World</a>
		</li>
		<li>
			<a href="/wip">WIPS</a>
		</li>
	</ul>
</nav>

<style>
	nav {
		padding-block: var(--size-7);
	}

	.links {
		display: flex;
		margin: 40px;
		text-decoration: none;
		list-style: none;
	}
	li {
		padding-right: 5px;
		border-right: 1px solid black;
	}

	a {
		color: inherit;
		text-decoration: none;
		margin-left: 10px;
	}

	@media (min-width: 768px) {
		nav {
			display: flex;
			justify-content: space-between;
		}

		.links {
			display: flex;
			gap: var(--size-7);
			margin-block: 0;
		}
	}
</style>
