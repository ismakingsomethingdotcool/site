<template>
	<nav>
		<div id="header">
			<img src="/logo.svg" />
			<h1>coolmains</h1>
		</div>
		<div>
			<p>very cool domains, for free</p>
			<p>|</p>
			<router-link to="/">home</router-link>
			<a href="https://discord.gg/K2nBQa9zv4">discord</a>
			<a href="mailto:ismakingsomething.cool@outlook.com">email</a>
			<a href="https://github.com/ismakingsomethingdotcool/coolmains-dns"
				>github</a
			>
			<a href="https://matrix.to/#/#.ismakingsomething.cool:matrix.org"
				>matrix</a
			>
		</div>
	</nav>
	<main>
		<router-view />
	</main>
</template>

