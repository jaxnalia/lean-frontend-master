<script>
	import { TwitterLogo, DiscordLogo, PaperPlane, GithubLogo } from 'radix-icons-svelte';
	import lean_cup from '../../images/logo.png';
	const footStyle =
		'supports-[backdrop-filter]:bg-background/60 sticky top-0 z-40 w-full px-3 pt-4 lg:px-9 bg-background/95 backdrop-blur';
	const link = {
		tele: 'https://t.me/plsLEAN',
		cord: 'https://discord.gg/NRg34Rawc6',
		xapp: 'https://x.com/pls_lean',
		chart: 'https://dexscreener.com/pulsechain/0x9961c2652b301c4a25256db05316d2be11cebab1',
		swap: 'https://bafybeihiwe3inbfru7h6pesaj4siacbyx7t6o5qp3vwdz25n3p6ewlbnie.ipfs.dweb.link/#/?outputCurrency=0x1c9b5e57AA89f8b58CA28249E347A6C933726449',
		explorer: 'https://bafybeicjuszlj6w3gg5mfszvo7z6ux4iaafhw62vfyfw27nm65bexodov4.ipfs.dweb.link/#/address/0x1c9b5e57AA89f8b58CA28249E347A6C933726449',
		git: 'https://github.com/LEAN-Token'
	};
	import { Github, Send, Twitter } from "lucide-svelte";
</script>


<footer class={footStyle}>
	<div class="flex flex-col container items-center">
		<a href="/" class="inline-flex items-center">
			<img src={lean_cup} alt="Lean" class="h-10" />
		</a>
		<div class="flex flex-row gap-2 text-lg">
			<a class="font-bold tracking-wide uppercase" target="_blank" href={link.swap}>buy on PulseX</a
			>
			|
			<a class="font-bold tracking-wide uppercase" target="_blank" href={link.explorer}>contract</a>
		</div>
		<span class="block text-sm text-center">
			© 2024 
			<a
				style=""
				href="https://leantoken.org/"
				class="text-purple-600 hover:underline dark:text-violet-500"
			>
				LEAN
			</a>| Built by
			<a
				style=""
				href="https://x.com/bigjaxcapital"
				class="text-purple-600 hover:underline dark:text-violet-500"
			>
				BigJax
			</a>
		</span>
		<div>
			<div class="flex items-center gap-1 px-2">
				<a target="_blank" class="p-2 min-w-xl" href={link.xapp}>
					<Twitter size="20" />
				</a>
				<a target="_blank" href={link.tele} class="p-2 min-w-xl">
					<Send size="20" />
				</a>
				<a target="blank" class="p-2 min-w-xl" href={link.git}>
					<Github size="20" />
				</a>
			</div>
		</div>
	</div>
</footer>
