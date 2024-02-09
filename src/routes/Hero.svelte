<script>
	const title =
		'font-bebas-neue uppercase text-6xl sm:text-7xl font-black flex flex-col leading-none';

	import { ArrowRight } from 'radix-icons-svelte'
</script>

<div class=" mx-auto md:px-6 flex relative py-16">
	<div class="sm:w-2/3 lg:w-2/5 flex flex-col relative z-20">
		<span class="w-20 h-2 bg-purple-900 mb-12" />
		<h1 class={title}>
			Pour 🆙
			<span
				class="text-5xl sm:text-8xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-violet-600"
				>$LEAN</span
			>
		</h1>
		<div class="h-6 md:h-5" />
		<p class="font-dm text-sm font-medium sm:text-base">
			LEAN is a unique blend of scarcity, humor, and functionality. With a commitment to being a
			scarce store of value, LEAN aims to carve out its niche in the decentralized landscape,
			providing users with a long-lasing community-driven experience.
		</p>
		<div class="flex mt-8">
			<a
				style="font-size: 32px;"
				href="/farm"
				class="font-bold py-2 px-5 rounded-full bg-purple-500 border-2 border-transparent text-md mr-4 hover:bg-purple-900"
			>
				Staking
				<svg style="display: inline-block;" width="52" height="52" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M8.14645 3.14645C8.34171 2.95118 8.65829 2.95118 8.85355 3.14645L12.8536 7.14645C13.0488 7.34171 13.0488 7.65829 12.8536 7.85355L8.85355 11.8536C8.65829 12.0488 8.34171 12.0488 8.14645 11.8536C7.95118 11.6583 7.95118 11.3417 8.14645 11.1464L11.2929 8H2.5C2.22386 8 2 7.77614 2 7.5C2 7.22386 2.22386 7 2.5 7H11.2929L8.14645 3.85355C7.95118 3.65829 7.95118 3.34171 8.14645 3.14645Z" fill="currentColor" fill-rule="evenodd" clip-rule="evenodd"></path></svg>
			</a>
			<!-- <a
				href="/paper"
				class="text-xl font-bold uppercase py-2 px-4 rounded-lg bg-transparent border-2 border-purple-500 text-purple-500 dark:text-white hover:bg-purple-900 hover:text-white text-md"
			>
				Lean Paper
			</a> -->
		</div>
	</div>
	<div class="hidden sm:block sm:w-2/3 lg:w-4/5 relative">
		<img
			class="h-auto w-full rounded-full object-cover object-center p-20"
			src="https://cdn.discordapp.com/attachments/1094571932088807547/1177311825176580156/image.png"
			alt="steeve"
		/>
		<!-- <Pic /> -->
	</div>
</div>
