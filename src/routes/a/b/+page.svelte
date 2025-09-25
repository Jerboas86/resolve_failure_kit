<script lang="ts">
	import { resolve } from '$app/paths';
</script>

<h1>The page B</h1>
<a href={resolve('/a')}>Go to the page A</a>
<a href={resolve('/a/b')}>Go to the page B</a>
