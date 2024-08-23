<script>


</script>

<svelte:head>
	<title>LalaDog!</title>
	<meta name="description" content="Dog walking app" />
</svelte:head>

<section>

	<h1>
	     LalaDog
	</h1>

    <img src="/images/laladog-welcome.png">

	<table>
		<tr>
			<td>
				Log In:
			</td>
			<td>
				 <button type="button">Click Me!</button> 
			</td>
		</tr>
		<tr>
			<td>
				Say hello:
			</td>
			<td>
				 <button type="button">Click Me!</button> 
			</td>
		</tr>
	</table>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
