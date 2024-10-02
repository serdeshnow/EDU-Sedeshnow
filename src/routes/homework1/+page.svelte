<script lang="js">
	let date = "7.10.2024";
	const сascadingStyleSheets = "Ждем вас в четверг на дистанте!";
	let spoiler = `А также ${date}!`;
</script>

<div>
	<h1>... Тут написана ваша домашняя работа! ...</h1>
	<p id="css">{сascadingStyleSheets}</p>
	<p class="spoiler">{spoiler}</p>
</div>

<style lang="css">
	div {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	div p {
		font-size: 20px;
	}

	#css {
		color: blue;
	}

	.spoiler {
		border: 1px solid orange;
	}
</style>
