<script>
	import 'bamboo.css';

	function sendEmail() {
		location.href = decodeURIComponent(escape(window.atob('bWFpbHRvOmNvbnRhY3RAbXlpc2Fhay50ZWNo')));
	}
</script>

<svelte:head>
	<title>Isaak's Corner</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />
	<meta name="description" content="Isaak Eriksson - software engineer since 2018." />
</svelte:head>

<h1>Isaak's Corner</h1>

<img src="/logo.png" alt="Isaak's logo" />
<p>
	Welcome to my personal site, where one can discover a bit about me. You can also reach me at <a
		href="#"
		on:click={sendEmail}>this email</a
	>.
</p>
<h2>Online links</h2>
<ul>
	<li><a href="https://github.com/MyIsaak/">Github</a></li>
	<li><a href="https://stackoverflow.com/users/5596912/isaak-eriksson">StackOverflow</a></li>
</ul>
<h2>Note</h2>
<p>More content will be added to this site once I find some free time.</p>
<footer>Copywright © {new Date().getUTCFullYear()}<br /><br /></footer>
