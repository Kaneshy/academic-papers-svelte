<script>
	import './styles.css';

	let  pagesDocs = [
    {
        title: 'Getting started',
        categories: [
            {
                label:'Algorithms',
                route:'/proyects/algorithms'
            },
            {
                label:'Dynamic Programming',
                route:'/proyects/dynamicP'
            }
        ]
    },
    {
        title: 'Machine Learning',
        categories: [
			{
                label:'Pandas',
                route:'/proyects/ml/pandas'
            },
            {
                label:'Machine Learning',
                route:'/proyects/ml'
            }
        ]
    },
    {
        title: 'Programing lenguages',
        categories: [
			{
                label:'C#',
                route:'/proyects/pl/cs'
            },
			{
                label:'C++',
                route:'/proyects/pl/cpp'
            }
        ]
    }

]
</script>

<div class="">
	<nav class="bg-neutral-950 w-full p-4 sticky font-bold ">
		PROGRAMAPEDIA
	</nav>
	<main class="flex flex-row ">
		<section class="sticky  max-w-sm custom-scrollbar left-0 top-0 z-20 flex h-screen flex-col justify-between overflow-auto pb-5 pt-10 max-md:hidden  ">
			<main
				class="select-none   flex flex-col gap-6   min-h-screen p-10  border-r border-neutral-900"
			>
				{#each pagesDocs as target, i}
					<section  class="flex flex-col gap-4">
						<p class="t text-body-bold  text-blue-950">{target.title.toUpperCase()}</p>

						<div class="text-small-semibold text-neutral-400  flex flex-col gap-4">
							{#each target.categories as y, i}
								<a href={y.route}  class="hover:text-white w-full p-2 hover:bg-neutral-900 rounded-xl" >{y.label}</a>
							{/each}
						</div>
					</section>
				{/each}
			</main>
		</section>

		<section class="w-full  items-center justify-center flex mb-10">
			<div class=" max-w-4xl p-4 max-md:p-0 ">
				<slot />
			</div>
		</section>
	</main>

	<footer class="bg-neutral-950 text-neutral-400">
		<p>Derechos Reservados</p>
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
	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
