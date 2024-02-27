<script>
	let arrayA = [1, 1, 1, , 2, 3, 4, 4];

	let arrayMl = [
		{
			title: 'Healthcare',
			desc: 'Predicting disease outcomes, diagnosing medical conditions, and drug discovery'
		},
		{
			title: 'Finance',
			desc: 'Fraud detection, credit scoring, and stock market predictions.'
		},
		{
			title: 'Natural Language Processing (NLP)',
			desc: 'Sentiment analysis, chatbots, and language translation.'
		},
		{
			title: 'Computer Vision',
			desc: ' Image recognition, object detection, and self-driving cars.'
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">Machine Learning</h1>
		<p>
			Machine Learning (ML) has emerged as an exciting field of research within computer science and
			engineering. It is a subset of Artificial Intelligence (AI) that enables computers to extract
			meaningful patterns from data, akin to human intelligence. In this essay, well delve into the
			concepts, methods, and steps involved in ML.
		</p>
		<p>
			At its core, ML involves teaching a computer system how to make accurate predictions based on
			data. These predictions can range from identifying fruits in photos to recognizing speech for
			video captions. The key distinction between traditional software and ML lies in the approach:
			rather than explicitly coding rules, ML models learn from data.
		</p>
		<h2 class="font-bold">Introduction video</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/9gGnTQTYNaE?si=9EdS05HCC7jnfXVj"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/4RixMPF4xis?si=bFvzrjTmKCcvmDwN"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h2 class="font-bold">The ML Process</h2>
		<div class="grid-a">
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Data Collection</h2>
				<p>
					ML begins with collecting relevant data. This data serves as the foundation for training
					and evaluating models.
				</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Feature Extraction:</h2>
				<p>
					Features (attributes) are extracted from the data. For instance, in image classification,
					features might include pixel values or color histograms.
				</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Model Selection:</h2>
				<p>
					Choosing an appropriate ML model is crucial. Common models include decision trees, neural
					networks, and support vector machines..
				</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Training:</h2>
				<p>
					The model is trained using labeled data. It learns to map input features to output
					predictions.
				</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Evaluation:</h2>
				<p>
					The models performance is assessed using validation data. Metrics like accuracy,
					precision, and recall help evaluate its effectiveness..
				</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Fine-Tuning:</h2>
				<p>Based on evaluation results, the model may be fine-tuned to improve performance..</p>
			</div>
			<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
				<h2 class="font-bold">Deployment:</h2>
				<p>Once satisfactory, the model is deployed for real-world use.</p>
			</div>
		</div>

		<h2 class="font-bold">Real-World Applications</h2>

		<div class="grid-a">
			{#each arrayMl as content, i}
				<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
					<h2 class="font-bold">{content.title}</h2>
					<p>{content.desc}</p>
				</div>
			{/each}
		</div>

		<h1 class="font-bold">Machine Learning Introducion</h1>

		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/i_LwzRVP7bg?si=SRCc1VRMC84pUUse"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Machine Learning with Python and Scikit-Learn (18 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/hDKCxebp88A?si=k-EJPt1dpNVASRuN"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<div>
            <h1 class="font-bold">Learn PyTorch for Deep Learning (26 hours course)</h1>
			<p>All code on GitHub</p>
			<a target="_blank" href="https://dbourke.link/pt-github">GitHub Repository</a>
			<p>its divide in short videos</p>
		</div>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/Z_ikDlimN6A?si=dVdKVBsZ-6I8xHMI"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>


        <div>
            <h1 class="font-bold">Mathematics for Machine Learning  (9 hours course)</h1>
			<p>For a lot of higher level courses in Machine Learning and Data Science, you find you need to freshen up on the basics in mathematics - stuff you may have studied before in school or university, but which was taught in another context, or not very intuitively, such that you struggle to relate it to how it’s used in Computer Science. This specialization aims to bridge that gap, getting you up to speed in the underlying mathematics, building an intuitive understanding, and relating it to Machine Learning and Data Science   </p>
		</div>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/0z6AhrOSrRs?si=Pw4a2FvfDHD3B0cC"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>



        
        <div>
            <h1 class="font-bold">Data Structures and Algorithms with Visualizations with JAVA  (48 hours course)</h1>
			<p><strong>NOTE: </strong> Before dive in this course take a course of JAVA</p>
            <p>Data Structures and Algorithms is an important aspect of every coding interview. This Algorithms and Data Structures course will teach you everything you need to prepare for placements, coding interviews, and logic building. The course walks you through multiple Java algorithms, data structure problems, and their solutions with step-by-step visualizations, so that you are actually learning instead of blindly memorizing solutions.  </p>
            <p>All code on GitHub</p>
			<a target="_blank" href="https://github.com/dinesh-varyani/ds-algos">GitHub Repository</a>
        </div>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/2ZLl8GAk1X4?si=N29GU7nbRtR2M0SQ"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>



        <div>
            <h1 class="font-bold">Java, Spring, and Microservices course  (48 hours course)</h1>
        </div>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/4XTsAAHW_Tc?si=dU1W9295IUV4f3DT"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>
	</section>
</main>

<style>
	p {
		color: rgb(175, 175, 175);
	}
</style>
