<script>
	const title =
		'font-bebas-neue uppercase text-6xl sm:text-7xl font-black flex flex-col leading-none';

	import { ArrowRight } from 'radix-icons-svelte'
	import vegeta from '$lib/images/vegeta.png'
	import { Badge } from "$lib/components/ui/badge";

</script>

<div class="bannerimg rounded-3xl p-5 sm:p-10 mx-auto flex relative font-medium">
	<style>
		.bannerimg{
			background-position: center;
			background-size: cover;
			background-repeat: no-repeat;
			background-image: URL("https://c.tenor.com/MHKfTqZCZrQAAAAd/tenor.gif");
		}
	</style>
	<div class="flex flex-col relative z-20">
		
		<!-- <h1 class={title}>
			<span><span
				class="text-5xl sm:text-8xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-violet-600"
				>$LEAN</span
			> is</span>
			leverage on the ecosystem.
		</h1> -->
		<span class="w-20 h-2 xl:h-10 mb-12" />
		<h1 class="scroll-m-20 text-4xl xl:text-5xl font-extrabold tracking-tight drop-shadow-md">
			<span
				class="text-5xl xl:text-6xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-violet-600"
				>$LEAN</span
			>
			is the dankest liquidity on PulseChain
		  </h1>
		  <!-- <p class="leading-7 drop-shadow-md">
			Making memes and sippin'
		</p> -->
		<span class="w-20 h-2 xl:h-10 mb-12" />
		<!-- <div class="h-6 md:h-5" /> -->
		
		<div class="flex">
			<!-- <a
				style="font-size: 32px;"
				href="/farm"
				class="bg-primary hover:bg-muted font-bold py-2 px-5 rounded-full border-2 border-transparent text-md mr-4"
			>
				Farm
				<svg style="display: inline-block;" width="52" height="52" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M8.14645 3.14645C8.34171 2.95118 8.65829 2.95118 8.85355 3.14645L12.8536 7.14645C13.0488 7.34171 13.0488 7.65829 12.8536 7.85355L8.85355 11.8536C8.65829 12.0488 8.34171 12.0488 8.14645 11.8536C7.95118 11.6583 7.95118 11.3417 8.14645 11.1464L11.2929 8H2.5C2.22386 8 2 7.77614 2 7.5C2 7.22386 2.22386 7 2.5 7H11.2929L8.14645 3.85355C7.95118 3.65829 7.95118 3.34171 8.14645 3.14645Z" fill="currentColor" fill-rule="evenodd" clip-rule="evenodd"></path></svg>
			</a> -->
			
			<div class="ml-3 flex flex-col justify-center">
				<a href="https://x.com/pls_lean">
					<Badge class="rounded-full" variant="default">X</Badge>
				</a>
				
			</div>
			<div class="ml-3 flex flex-col justify-center">
				<a href="https://t.me/plsLEAN">
					<Badge class="rounded-full" variant="default">Telegram</Badge>
				</a>
				
			</div>
			<div class="ml-3 flex flex-col justify-center">
				<a href="/bridge">
					<Badge class="rounded-full" variant="default">Bridge</Badge>
				</a>
				
			</div>
			<div class="ml-3 flex flex-col justify-center">
				<a href="/bridge">
					<Badge class="rounded-full" variant="default">DexScreener</Badge>
				</a>
				
			</div>
			<!-- <div class="ml-3 flex flex-col justify-center">
				<a href="https://www.dextools.io/app/en/pulse/pair-explorer/0x9961c2652b301c4a25256db05316d2be11cebab1?t=1724347481947">
					<Badge class="rounded-full" variant="default">DexTools</Badge>
				</a>
				
			</div>
			<div class="ml-3 flex flex-col justify-center">
				<a href="https://www.geckoterminal.com/pulsechain/pools/0x9961c2652b301c4a25256db05316d2be11cebab1">
					<Badge class="rounded-full" variant="default">GeckoTerminal</Badge>
				</a>
				
			</div>
			<div class="ml-3 flex flex-col justify-center">
				
				<Badge class="rounded-full" variant="secondary">Copy Token Address</Badge>
				
				
			</div> -->
			<!-- <div class="ml-3 flex flex-col justify-center">
				<a href="/bridge">
					<Badge class="rounded-full" variant="secondary">Docs</Badge>
				</a>
				
			</div> -->
			<!-- <div class="ml-3 flex flex-col justify-center">
				<Badge class="" variant="secondary">Bridge</Badge>
			</div> -->
			

			<!-- <a
				href="/paper"
				class="text-xl font-bold uppercase py-2 px-4 rounded-lg bg-transparent border-2 border-purple-500 text-purple-500 dark:text-white hover:bg-purple-900 hover:text-white text-md"
			>
				Lean Paper
			</a> -->
		</div>
	</div>
	<!-- <div class="hidden sm:block sm:w-2/3 lg:w-4/5 relative">
		<img
			class="h-auto w-full rounded-full object-cover object-center p-20"
			src={vegeta}
			alt="steeve"
		/>
		
	</div> -->
</div>
