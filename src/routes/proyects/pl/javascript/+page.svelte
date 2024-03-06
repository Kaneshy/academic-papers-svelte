<script>
	const features = [
		{
			title: 'Asynchronous Programming',
			desc: 'JavaScripts asynchronous nature allows developers to execute non-blocking code, enhancing the performance and responsiveness of web applications. Promises and async/await are examples of features that facilitate asynchronous programming in JavaScript'
		},
		{
			title: 'DOM Manipulation',
			desc: 'JavaScripts ability to manipulate the DOM in real-time enables developers to create dynamic and interactive web pages. This feature is crucial for building modern user interfaces and providing seamless user experiences.'
		},
		{
			title: 'Cross-Browser Compatibility:',
			desc: 'JavaScripts compatibility with all major web browsers makes it a versatile choice for web development. This cross-browser support ensures that applications work consistently across different platforms.'
		},
		{
			title: 'Server-Side Development',
			desc: 'With the advent of technologies like Node.js, JavaScript is no longer confined to client-side scripting. It has become a prominent language for server-side development, allowing developers to use a unified language for both front-end and back-end development.'
		}
	];

	// Significance of C++
	const significance = [
		{
			title: 'Rich User Experiences',
			desc: 'JavaScript is instrumental in creating dynamic and responsive user interfaces, leading to richer and more engaging web experiences. Single Page Applications (SPAs), powered by JavaScript frameworks like React, Angular, and Vue.js, have become increasingly popular for their seamless navigation and fast performance.'
		},
		{
			title: 'Community and Ecosystem:',
			desc: 'The vibrant JavaScript community contributes to an extensive ecosystem of libraries and frameworks. This collaborative environment fosters innovation, accelerates development, and provides developers with a wide range of tools to choose from.'
		},
		{
			title: 'Mobile Development',
			desc: 'JavaScripts influence extends beyond web browsers to mobile app development. Frameworks like React Native and Apache Cordova enable developers to build cross-platform mobile applications using JavaScript, further expanding its reach.'
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">JavaScript</h1>
		<p>
			JavaScript, the versatile programming language, has played a pivotal role in shaping the landscape of modern web development. Originally created in 1995 by Brendan Eich, JavaScript was initially designed to add interactivity to static HTML pages. Over the years, it has evolved into a powerful and ubiquitous language that runs on nearly every web browser, enabling dynamic and responsive user experiences. This essay explores the evolution of JavaScript, its key features, and its significant impact on the world of web development.
		</p>

		<div class="flex gap-4">
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1iHvRABQimZ6cm15eWfjB989g-UHwLDJd/preview"
				>JavaScript Cheat Sheet</a
			>
			<a
				target="_blank"
				class="p-2 rounded-md bg-green-800 border border-green-400 hover:bg-green-500"
				href="https://drive.google.com/file/d/1yzJNZBQizpgDOSx8BRLKMZEy3IrflGw5/preview"
				>JavaScript Cheat Sheet</a
			>

			
		</div>
		<h2 class="font-bold">Introduction videos</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/aXOChLn5ZdQ?si=ImORSZzdOpcn6XJu"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/W6NZfCO5SIk?si=hOIe4G6nJeUmSnjn"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h1 class="text-center text-3xl font-bold">Evolution of JavaScript</h1>
		<p>
			JavaScript's journey began with its incorporation into Netscape Navigator, one of the earliest web browsers. Its primary purpose was to handle client-side scripting, allowing developers to manipulate the Document Object Model (DOM) and create dynamic content. Despite initial skepticism, JavaScript gained traction as developers recognized its potential for enhancing user interfaces.		
		</p>
		<p>
			The introduction of AJAX (Asynchronous JavaScript and XML) in the early 2000s marked a turning point for JavaScript. This technology allowed web pages to retrieve and send data asynchronously without requiring a full page reload. This innovation significantly improved the user experience by enabling more responsive and interactive web applications.		</p>

		<p>
			In recent years, the ECMAScript standard, which JavaScript follows, has seen regular updates, introducing new features and enhancing the language's capabilities. Modern JavaScript, commonly referred to as ECMAScript 6 (ES6) and beyond, includes features like arrow functions, template literals, and destructuring assignments, making code more concise and readable.		</p>


		<h2 class="font-bold">Key Features of JavaScript</h2>

		<div class="grid-a">
			{#each features as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h2 class="font-bold">Impact on Web Development:</h2>

		<p>
			JavaScript's impact on web development is profound, influencing various aspects of the industry:
		</p>

		<div class="grid-a">
			{#each significance as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>




		<h1 class="font-bold">JavaScript Full Course  (12 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/lfmg-EJ8gm4?si=vqVL0clAGL8ZDiJC"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">JavaScript Full Course  (12 hours course)</h1>
		<a target="_blank" href="https://www.youtube.com/watch?v=SBmSRK3feww&ab_channel=SuperSimpleDev" class="flex flex-col items-center justify-center">
			<img class="w-full min-h-80" src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1709765075/my-uploads/Screenshot_2024-03-06_174324_kkjpyz.jpg" alt="">
		</a>


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
