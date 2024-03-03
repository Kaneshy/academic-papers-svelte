<script>
	let arrayMl = [
		{
			title: 'DataFrame and Series',
			desc: 'At the heart of Pandas lie two primary data structures: DataFrame and Series. The DataFrame is a two-dimensional table with labeled axes (rows and columns), while the Series is a one-dimensional labeled array. These structures provide a versatile foundation for organizing and analyzing data.'
		},
		{
			title: 'Data Cleaning and Preprocessing:',
			desc: 'Pandas simplifies the process of cleaning and preprocessing data. It offers functions for handling missing values, filtering data, and removing duplicates. The librarys powerful capabilities aid in ensuring that the data is in a suitable form for analysis.'
		},
		{
			title: 'Data Indexing and Selection:',
			desc: 'Pandas provides powerful indexing and selection mechanisms, allowing users to access, modify, and manipulate data efficiently. The ability to index data using labels or positions provides flexibility in working with different types of datasets.'
		},
		{
			title: 'Grouping and Aggregation:',
			desc: ' Grouping data based on specific criteria and performing aggregation operations is straightforward with Pandas. The librarys groupby function allows users to split data, apply a function, and combine the results, facilitating the analysis of subsets within a dataset..'
		},
		{
			title: 'Merging and Joining:',
			desc: ' Combining datasets is a common task in data analysis. Pandas offers functions for merging and joining datasets based on specified keys, making it seamless to integrate information from multiple sources.'
		},
		{
			title: 'Time Series Analysis:',
			desc: 'Pandas is well-suited for handling time series data. It provides specialized tools for resampling, time-based indexing, and calculations related to time intervals, making it a go-to choice for time series analysis..'
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">Pandas</h1>
		<p>
			In the realm of data science and analysis, the Pandas library stands as a stalwart, providing a robust and flexible toolset for handling and manipulating structured data. Developed in the early 2000s by Wes McKinney, Pandas has since become an indispensable asset for data scientists, analysts, and researchers. This essay aims to delve into the key features, functionality, and significance of the Pandas library.
		</p>
		<p>
			Pandas is an open-source data manipulation and analysis library for Python. It is built on top of the NumPy library and offers data structures such as Series and DataFrame that are tailored for handling diverse types of data efficiently. The library excels in tasks related to cleaning, transforming, analyzing, and visualizing data, making it a quintessential tool in the data science toolkit.
		</p>

		<div>
			<a target="_blank" class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500" href="https://drive.google.com/file/d/1-qjgCLyaMGjG88G0WFHQRCf9L2fXC4d5/view">Cheat Sheet Pandas</a>
		</div>
		<h2 class="font-bold">Introduction video</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/CIQJtJ38-hI?si=_iojez79b5kot4Wv"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/CIQJtJ38-hI?si=_iojez79b5kot4Wv"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>


		<h2 class="font-bold">Key Features:</h2>

		<div class="grid-a">
			{#each arrayMl as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>


		<h1 class="font-bold">Data Analysis with Python Course - Numpy, Pandas, Data Visualization  (9 hours course)</h1>
		<p>Learn the basics of Python, Numpy, Pandas, Data Visualization, and Exploratory Data Analysis in this course for beginners. This was originally presented as a live course.</p>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/GPVsHOlRBBI?si=m58v88MXDBm_DJR1"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Pandas & Python for Data Analysis</h1>
		<p>Learn how to use Pandas and Python for Data Analysis, to Data Cleaning and Data Wrangling. You will learn by creating real life projects interactively to help you take the next step in your Data Science Career.</p>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/gtjxAH8uaP0?si=fDvxMzkfI49e8k4x"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<div class="w-full flex justify-end">
			<a href="/proyects/ml" class="p-4 border select-none hover:bg-neutral-500">Next Step Machine Learning </a>
		</div>



        
        
	</section>
</main>

<style>
	p {
		color: rgb(175, 175, 175);
	}
</style>
