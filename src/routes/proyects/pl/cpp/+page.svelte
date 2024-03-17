<script>
	const features = [
		{
			title: 'Object-Oriented Programming (OOP)',
			desc: 'Supports classes, objects, polymorphism, and encapsulation for modular and maintainable code.'
		},
		{
			title: 'Memory Management',
			desc: 'Provides both manual and automatic memory management, including pointers, smart pointers, and the Standard Template Library (STL).'
		},
		{
			title: 'STL (Standard Template Library)',
			desc: 'A powerful set of template classes and functions for general-purpose programming, including containers, iterators, and algorithms.'
		},
		{
			title: 'Performance',
			desc: 'Known for high-performance capabilities with features like inline functions and template metaprogramming.'
		},
		{
			title: 'Portability',
			desc: 'Designed to be platform-independent, allowing code to be compiled and run on different operating systems.'
		}
	];

	// Significance of C++
	const significance = [
		{
			title: 'System Programming',
			desc: 'Widely used for low-level control over hardware and memory in system programming, including operating systems and device drivers.'
		},
		{
			title: 'Game Development',
			desc: 'Prevalent in the gaming industry for developing high-performance and resource-efficient games.'
		},
		{
			title: 'Application Development',
			desc: 'Employed in various application domains, such as desktop applications, financial systems, and complex software solutions.'
		},
		{
			title: 'Large-scale Software Projects',
			desc: 'Well-suited for large-scale projects due to support for modular design, encapsulation, and efficient memory management.'
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">C++</h1>
		<p>
			C++ stands as one of the most influential and enduring programming languages in the world of
			software development. Developed by Bjarne Stroustrup in the early 1980s as an extension of the
			C programming language, C++ has played a pivotal role in shaping the landscape of modern
			programming. This essay explores the evolution, features, and significance of C++ in the realm
			of computer science.
		</p>

		<div class="flex gap-4">
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1nt5sj5iwO7wYgNzYUAbYYmSdd35MoKAx/preview"
				>Cheat Sheet C++</a
			>
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1vS0j2F2eA80exwP3e2RS2yM8dE-_s33O/preview"
				>Cheat Sheet C++</a
			>

			
		</div>
		<h2 class="font-bold">Introduction video</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/MNeX4EGtR5Y?si=spv4iMtm3lfNOm5l"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/ZzaPdXTrSb8?si=nQyKVWH_RPkg-avZ"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h1 class="text-center text-3xl font-bold">Evolution of C++</h1>
		<p>
			C++ originated as an extension of the C programming language, incorporating object-oriented
			programming (OOP) principles. Bjarne Stroustrup sought to enhance C by introducing features
			like classes, polymorphism, and encapsulation, aiming to make software development more
			modular and maintainable. The first edition of C++ was released in 1985, and over the years,
			it has undergone several revisions, with the latest standard being C++20.
		</p>

		<h1 class="text-center text-3xl font-bold">Why Use C++</h1>
		<p>
			C++ is one of the world's most popular programming languages.
		</p>
		<p>
			C++ can be found in today's operating systems, Graphical User Interfaces, and embedded systems.
		</p>
		<p>
			C++ is an object-oriented programming language which gives a clear structure to programs and allows code to be reused, lowering development costs.
		</p>
		<p>
			C++ is portable and can be used to develop applications that can be adapted to multiple platforms
		</p>

		<h2 class="font-bold">Key Features of C#</h2>

		<div class="grid-a">
			{#each features as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h2 class="font-bold">Applications of C#</h2>

		<div class="grid-a">
			{#each significance as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h1 class="font-bold">C++ Full Course (6 hours course)</h1>
		<p>
			This video serves as an introduction to the C++ programming language
			C++ is a beast of a language. We're only scratching the surface.		
		</p>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/-TkoO8Z07hI?si=WxJjOTXpiUacP8Eu"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C++ Programming Course - Beginner to Advanced  (30 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/8jLOx1hD3_o?si=6vE7hOZ7xczSCDib"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C++ Tutorial for Beginners </h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/vLnPwxZdW4Y?si=coe08J0YjRngFBQQ"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>


		<div class="w-full flex justify-end">
			<a href="/proyects/ml" class="p-4 border select-none hover:bg-neutral-500"
				>Next Step Machine Learning
			</a>
		</div>
	</section>
</main>

<style>
	p {
		color: rgb(175, 175, 175);
	}
</style>
