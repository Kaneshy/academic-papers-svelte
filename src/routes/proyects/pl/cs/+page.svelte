<script>
	let arrayMl = [
    {
      title: "Rich Standard Library",
      desc: "C# comes with a comprehensive standard library, simplifying development tasks and accelerating the coding process."
    },
    {
      title: "Versatility",
      desc: "C# is a versatile language suitable for various applications, including web development, desktop applications, mobile app development, game development, and cloud-based services."
    },
    {
      title: "Unified Development Environment",
      desc: "Visual Studio, Microsoft's integrated development environment (IDE), offers a feature-rich environment with powerful debugging tools, code completion, and a user-friendly interface."
    },
    {
      title: "Object-Oriented Paradigm",
      desc: "Rooted in the object-oriented programming (OOP) paradigm, C# promotes code reusability, maintainability, and enhances the overall structure of software systems."
    },
    {
      title: "Type Safety",
      desc: "C# is a statically-typed language, ensuring type safety at compile-time and reducing the chances of runtime errors, contributing to code reliability."
    },
    {
      title: "Automatic Memory Management",
      desc: "C# incorporates automatic memory management through garbage collection, relieving developers from manual memory management and enhancing overall code efficiency."
    },
    {
      title: "Cross-Language Integration",
      desc: "C# seamlessly integrates with other languages targeting the Common Language Infrastructure (CLI), facilitating interoperability and enhancing the flexibility of C# applications."
    }
  ]
	let applications = [
    {
      title: "Web Development",
      desc: "C# is widely used for web development, particularly with the ASP.NET framework, allowing developers to build dynamic and scalable web applications."
    },
    {
      title: "Desktop Applications",
      desc: "C# is extensively employed in creating desktop applications for the Windows operating system, utilizing frameworks like Windows Presentation Foundation (WPF) and Windows Forms."
    },
    {
      title: "Game Development",
      desc: "C# is prominent in the gaming industry, especially through the Unity game development engine, supporting C# scripting for the creation of immersive and interactive games."
    },
    {
      title: "Mobile App Development",
      desc: "C# is used for mobile app development, leveraging the Xamarin framework to build cross-platform applications for various mobile devices."
    },
    {
      title: "Cloud-Based Services",
      desc: "C# finds application in developing cloud-based services, with Microsoft Azure providing a platform for building scalable and reliable cloud solutions."
    }
  ]
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">C#</h1>
		<p>
			C# (pronounced C sharp) stands as a formidable programming language in the world of software development. Created by Microsoft in the early 2000s, C# has since evolved into a versatile and powerful language that caters to a wide range of applications. In this essay, we will delve into the key features, advantages, and applications of C# programming language, shedding light on why it has become a preferred choice for developers worldwide.
		</p>

		<div>
			<a target="_blank" class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500" href="https://drive.google.com/file/d/1-AXDSgPBhupjqUR0OjmnVvTx64toCDA0/preview">Cheat Sheet C#</a>
		</div>
		<h2 class="font-bold">Introduction video</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/ravLFzIguCM?si=1HWNQnyHs7_lRK1Y"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/6GQAE7iLOhY?si=rBIZ9TYxJnpkx0ah"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>


		<h2 class="font-bold">Key Features of C#</h2>

		<div class="grid-a">
			{#each arrayMl as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h2 class="font-bold">Applications of C#</h2>

		<div class="grid-a">
			{#each applications as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>


		<h1 class="font-bold">C# Course for Beginners (4 hours course)</h1>
		<p>This course will give you a full introduction into all of the core concepts in C# (aka C Sharp). Follow along with the course and you'll be a C# programmer in no time!</p>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/GhQdlIFylQ8?si=tozVUNXOMQPkT2G"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C# Full Course for Beginners (9 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/M5ugY7fWydE?si=ASaDLZJK_7hsdeg0"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Microsoft C# Fundamentals</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/0QUgvfuKvWU?si=ZzVUekQb6ZSYKGw5"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">C# (8 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/YrtFtdTTfv0?si=XWFHeuwSBrLUYSfx"
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
