<div class="relative mx-auto max-w-7xl pt-10" data-cta>
	<div class="mx-auto max-w-7xl px-6 lg:px-8">
		<div class="text-centerX mx-auto max-w-2xl">
			<div
				data-content
				class="text-5xl font-black tracking-tighter antialiased dark:text-white lg:text-8xl"
			>
				<span> lets craft something greate together </span>
			</div>
			<div class="mt-5">
				<a
					class="relative mt-6 rounded-full bg-accent p-2 text-xs font-light hover:bg-surface"
					href="#contact">Get help</a
				>
			</div>
		</div>
	</div>
</div>

<style>
	[data-cta] > div {
		background-size: cover;
		min-height: min(100vh, 560px);
		display: flex;
		align-items: center;
	}

	[data-cta] a {
		text-shadow: none;
		transition: 0.2s ease-in-out;
		padding: 24px 74px;
		display: inline-block;
		font-size: calc(16px + min(1.125vw, 8px));
	}

	[data-cta] [data-content] {
		display: flex;
		flex-direction: column;
		text-align: left;
		text-shadow: 3px 4px 6px rgba(0, 0, 0, 0.2);
		font-size: calc(36px + min(3.15vw, 54px));
	}

	@media only screen and (max-width: 1023px) {
		[data-cta] [data-content] span:nth-child(1) {
			justify-content: center;
		}
	}
</style>
