<template>
	<h2>Getting a cool domain</h2>
	<content>
		<ul>
			<li>Create a Github account</li>
			<li>
				Go to the
				<a href="https://github.com/ismakingsomethingdotcool/coolmains-dns"
					>ismakingsomethingdotcool/coolmains-dns</a
				>
			</li>
			<li>Fork the repo</li>
			<li>
				Edit one of the files in the domains folder to add your nameservers
			</li>
			<li>Create a pull request, and wait for it to get merged</li>
		</ul></content
	>
	<h2>Contact Us</h2>
	<content>
		<h3>Abuse of the service</h3>
		If you believe that the service is being used in an abusive manner,
		<a href="mailto:ismakingsomething.cool+abuse@outlook.com"
			>send us an email</a
		>. We will try to respond to email sent to that address as soon as possible.
		<h3>Other stuff</h3>
		If you have any other questions, feel free to
		<a href="mailto:ismakingsomething.cool@outlook.com">send an email</a>, join
		<a href="https://discord.gg/K2nBQa9zv4">William Horning's Discord server</a
		>, or join
		<a href="https://matrix.to/#/#.ismakingsomething.cool:matrix.org"
			>the Matrix channel</a
		>.
	</content>
	<h2>Core Contributors</h2>
	<contributors>
		<a v-for="contributor in contributors" :href="contributor.url">
			<div>
				<img
					:src="contributor.image"
					:alt="`${contributor.name}'s profile picture`"
				/>
				<p>{{ contributor.name }}</p>
			</div>
		</a>
	</contributors>
</template>
<script>
	import contribs from '/src/contributors.ts';
	export default {
		data() {
			return contribs;
		},
	};
</script>

