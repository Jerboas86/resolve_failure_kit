<script>
	import { resolve } from '$app/paths';
</script>

<h1>The page A</h1>

<a href={resolve('/a/b')}>Go to the page B</a>
<!-- the following line is not working in v1.42 -->
<!-- i thought it would work with v1.43 but it doesnt either -->
<!-- <a href={resolve('/b')}>Go to the page B</a> -->
