<script>
	import './styles.css';

	let  pagesDocs = [
    {
        title: 'Getting started',
        categories: [
            {
                label:'Introduction',
                route:'/documentation/analytics'
            },
            {
                label:'Examples',
                route:'/documentation/analytics'
            }
        ]
    },
    {
        title: 'Inventory',
        categories: [
            {
                label:'Total inventory value',
                route:'/documentation/products'
            },
            {
                label:'Total stock',
                route:'/documentation/products'
            }
        ]
    },
    {
        title: 'API',
        categories: [
            {
                label:'Products',
                route:'/documentation/products'
            },
            {
                label:'Total inventory value',
                route:'/documentation/products'
            }
        ]
    }
]
</script>

<div class="app">
	<nav class="w-full p-4">
		Programmig section
	</nav>
	<main class="flex flex-row">
		<section class=" w-auto h-screen bg-neutral-950">
			<main
				class="select-none  flex flex-col gap-6 custom-scrollbar min-w-fit px-10  min-h-screen p-4  border-r border-neutral-700"
			>
				{#each pagesDocs as target, i}
					<section  class="flex flex-col gap-4">
						<p class="t text-body-bold">{target.title}</p>

						<div class="text-small-semibold text-neutral-400  flex flex-col gap-4">
							{#each target.categories as y, i}
								<div class="hover:text-white" >{y.route} {y.label}</div>
							{/each}
						</div>
					</section>
				{/each}
			</main>
		</section>

		<section class="w-full items-center justify-center flex">
			<div class=" max-w-4xl">
				<slot />
			</div>
		</section>
	</main>

	<footer>
		<p>Derechos <a href="https://kit.svelte.dev">kit.svelte.dev</a></p>
	</footer>
</div>

<style>
	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
