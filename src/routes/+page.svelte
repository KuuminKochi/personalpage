<script lang="ts">
</script>

	<head>
		<title>kuumin's webpage</title>
	</head>

	<body>

		<h1 style="text-align: center;">welcome to my webpage</h1>
	<div class="container">
		<img class="img" src="https://i.pinimg.com/736x/af/0e/4e/af0e4ea3fe63288cb21bc0de408b2739.jpg" alt="">
		<div class="image-next">
			<p>As you can see, I am quite terrible at webdesign</p>
			<p>I have no idea what the fuck I'm doing right now<br> but it looks like it is working</p>
			<p>It's decently minimalistic on desktop as well</p>
			<p>I kinda like it</p>
			<p>In a way, it's kinda aesthetic considering <br> I literally have no idea what I'm doing</p>
			<p>Looks terrible on mobile though</p>
		</div>
	</div>
	</body>

<style>
	@font-face {
	  font-family: 'ArcadeClassic';
	  src: url('/fonts/ArcadeClassic.ttf') format('truetype');
	  font-weight: normal;
	  font-style: normal;
	}
	
	html, body {
		background-color: black;
		color: white;
	}

	.main_content {
		display: flex;
		justify-content: center;
	}

	@media screen and (max-width: 600px){
		.img {
			display: block;
			max-width: 80%;
			height: auto;
			margin-left: auto;
			margin-right: auto;
		}

		.image-next {
			text-align: center;
		}
	}
	@media screen and (min-width: 601px){
		.img {
			float: right;
			max-width: 50%;
			height: auto;
			margin-right: 10%;
		}
		
		.image-next {
			display: inline-block;
			text-align: right;
			margin-left: 500px;
			margin-top: 50px;
		}
	}
</style>
