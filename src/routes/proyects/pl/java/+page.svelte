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
		<h1 class="text-center text-3xl font-bold">Java: Empowering Modern Software Development</h1>
		<p>
			In the ever-evolving landscape of technology, Java stands out as a stalwart programming language that has shaped the digital world for decades. From its inception in the mid-1990s to its current status as a cornerstone of modern software development, Java has continually adapted to meet the demands of an ever-changing industry. This essay explores the significance of Java in today's software ecosystem, its key features, its impact on various domains, and its future prospects.
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
					src="https://www.youtube.com/embed/l9AzO1FMgM8?si=Cuj2vN0zwOcBvfG3"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/m4-HM_sCvtQ?si=LEeqPZgLHNY9csGX"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h1 class="text-center text-3xl font-bold">Evolution of C++</h1>
		<p>
			Java was developed by James Gosling and his team at Sun Microsystems in the early 1990s. It was designed with the vision of a platform-independent language that could run on any device with a Java Virtual Machine (JVM), providing portability and versatility. One of the key features of Java is its "write once, run anywhere" principle, which allows developers to write code on one platform and execute it on any other platform with a JVM installed, making it ideal for cross-platform development.
		</p>
		<p>
			Another crucial aspect of Java is its robustness and security. Java's strict compile-time and runtime checks help catch errors early in the development process, reducing the likelihood of system failures and vulnerabilities. Additionally, Java's built-in security features, such as sandboxing and bytecode verification, provide a secure environment for executing code, making it a preferred choice for mission-critical applications.
		</p>
		<p>
			Furthermore, Java's object-oriented nature, with features like classes, inheritance, and polymorphism, promotes code reusability, scalability, and maintainability, facilitating the development of large-scale, complex software systems. Its extensive standard library, rich ecosystem of third-party libraries and frameworks, and support for multi-threading further enhance productivity and performance in software development.
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


		<h1 class="font-bold">Java Full Course  </h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/xk4_1vDrzzo?si=U4fvw0TMcFtCxhsG"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Java Full Course  </h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/A74TOX803D0?si=FslvDzu1lLLNGzS5"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Java Full Course  </h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/yRpLlJmRo2w?si=AMdeMB5gXVW_C1f6"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Lecture 1 | Programming Methodology (Stanford)  </h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/KkMDCCdjyW8?si=wRgTBGZJXFY70-Gm"
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
