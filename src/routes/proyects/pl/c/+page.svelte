<script>
	const features = [
		{
			title: 'Syntax',
			desc: 'C syntax is relatively straightforward, making it easy for programmers to learn and understand. It follows a structured approach with functions, loops, and conditional statements.'
		},
		{
			title: 'Data Types',
			desc: ' C supports a wide range of data types, including integers, floating-point numbers, characters, and arrays. Additionally, programmers can define custom data types using structures and unions.'
		},
		{
			title: 'Pointers',
			desc: ' One of the most powerful features of C is its support for pointers. Pointers allow direct memory manipulation and facilitate efficient memory management.'
		},
		{
			title: 'Functions',
			desc: ' C encourages modular programming through the use of functions. Functions enable code reuse, improve readability, and enhance maintainability.'
		},
		{
			title: 'Standard Library',
			desc: 'C provides a comprehensive standard library that includes functions for input/output operations, string manipulation, memory allocation, and mathematical computations.'
		}
	];

	// Significance of C++
	const significance = [
		{
			title: 'Operating Systems',
			desc: ' C is the language of choice for developing operating systems due to its low-level capabilities and close proximity to hardware. Major operating systems like Unix, Linux, and Windows are written in C.'
		},
		{
			title: 'Embedded Systems',
			desc: 'C is widely used in embedded systems programming, where resource constraints and performance are critical factors. It allows developers to write efficient code for microcontrollers, IoT devices, and other embedded platforms.'
		},
		{
			title: 'System Programming',
			desc: 'C is well-suited for system programming tasks such as device drivers, kernel development, and network programming. Its ability to interact closely with hardware makes it indispensable in this domain.'
		},
		{
			title: 'Application Development',
			desc: ' Although higher-level languages have gained popularity in application development, C still plays a significant role in building performance-critical applications. Software such as databases, compilers, and graphics engines often utilize C for optimal performance.'
		},
		{
			title: 'Game Development',
			desc: 'Many game engines and graphics libraries are implemented in C or C++. Game developers leverage the speed and efficiency of C to create immersive gaming experiences across various platforms.'
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">C++</h1>
		<p>
			The C programming language stands as a cornerstone in the world of software development.
			Revered for its efficiency, portability, and versatility, C has been instrumental in shaping
			modern computing. Developed by Dennis Ritchie at Bell Labs in the early 1970s, C quickly
			gained popularity and became the lingua franca of programming languages. Its influence extends
			across various domains, from operating systems to embedded systems, from system programming to
			application development. This essay delves into the fundamentals and applications of the C
			programming language, highlighting its enduring relevance in the ever-evolving landscape of
			technology.
		</p>

		<div class="flex gap-4">
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1mnQ5Ju2j15vtNs8ddhSOMKAOZKVzGxEY/preview"
				>Cheat Sheet C</a
			>
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1DTZ8mRkokGaY0MGpDJSJB-HuY9G-ziRM/preview"
				>Cheat Sheet C</a
			>
		</div>
		<h2 class="font-bold">Introduction video</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/U3aXWizDbQ4?si=mOHjNUZRoS_MC2Pt"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/EjavYOFoJJ0?si=H5p9X2Q7RvhCSOaM"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h1 class="text-center text-3xl font-bold">Fundamentals of C Programming:</h1>
		<p>
			At its core, C is a procedural programming language with a simple and elegant syntax. It provides a rich set of features that enable developers to write efficient and concise code. Some fundamental aspects of C programming include:.
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
		<p>
			The versatility of C makes it suitable for a wide range of applications. Some prominent areas where C finds extensive usage include:
		</p>

		<div class="grid-a">
			{#each significance as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h1 class="font-bold">C Programming Full Course  (5 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/87SH2Cn0s9A?si=XmIaFFYYgDG7Lsu3"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C Programming Tutorial for Beginners (4 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/KJgsSFOSQv0?si=ziEBYGlcoHFDZ77T"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C Programming with Dr. Chuck (feat. classic book by Kernighan and Ritchie)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/j-_s8f5K30I?si=TmXHKih-axftW4CH"
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
