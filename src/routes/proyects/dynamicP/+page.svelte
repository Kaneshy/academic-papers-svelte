<script>
	let arrayA = [1, 1, 1, , 2, 3, 4, 4];
	let arrayMl = [
		{
			title: 'Optimal Solutions',
			desc: 'Dynamic programming guarantees optimal solutions to subproblems, leading to an optimal solution for the overall problem.'
		},
		{
			title: 'Efficiency',
			desc: 'By avoiding redundant computations through the use of memoization or tabulation, dynamic programming significantly improves the efficiency of algorithmic solutions.'
		},
		{
			title: 'Versatility',
			desc: 'Dynamic programming is a versatile technique applicable to a wide range of problems, from numerical optimization to combinatorial challenges.'
		},
		{
			title: 'Simplicity',
			desc: 'While some problems may initially seem complex, dynamic programming allows for breaking them down into simpler, manageable subproblems, making them more tractable.'
		}
	];
	let graphA = [
		{
			title: 'Breadth-First Search (BFS)',
			subtitle: 'Objective',
			description:
				'BFS explores a graph level by level, visiting all neighbors of a node before moving on to the next level.',
			applications: [
				'Shortest path finding in unweighted graphs',
				'Connected components',
				'Network broadcasting',
				'Web crawling'
			]
		},
		{
			title: 'Depth-First Search (DFS)',
			subtitle: 'Objective',
			description:
				'DFS explores a graph by going as deep as possible along each branch before backtracking.',
			applications: [
				'Topological sorting',
				'Cycle detection',
				'Connected components',
				'Pathfinding'
			]
		},
		{
			title: "Dijkstra's Algorithm",
			subtitle: 'Objective',
			description:
				"Dijkstra's algorithm finds the shortest path from a source node to all other nodes in a weighted graph.",
			applications: ['Shortest path in road networks', 'Network routing', 'Resource optimization']
		},
		{
			title: 'Bellman-Ford Algorithm',
			subtitle: 'Objective',
			description:
				"Bellman-Ford finds the shortest paths in a weighted graph, even when it contains negative weight edges (unlike Dijkstra's algorithm).",
			applications: [
				"Similar to Dijkstra's algorithm but applicable in graphs with negative weights"
			]
		},
		{
			title: "Minimum Spanning Tree (Prim's and Kruskal's Algorithms)",
			subtitle: 'Objective',
			description:
				'Find the minimum spanning tree (MST) of a graph, a tree that spans all nodes with the minimum possible total edge weight.',
			applications: ['Network design', 'Clustering', 'Optimization of connected systems']
		},
		{
			title: 'Floyd-Warshall Algorithm',
			subtitle: 'Objective',
			description:
				'Floyd-Warshall calculates the shortest paths between all pairs of nodes in a weighted graph.',
			applications: [
				'All-pairs shortest path',
				'Network connectivity analysis',
				'Routing protocols'
			]
		},
		{
			title: 'Topological Sorting',
			subtitle: 'Objective',
			description:
				'Arrange the nodes of a directed acyclic graph (DAG) in a linear order respecting the partial order given by the edges.',
			applications: ['Task scheduling', 'Dependency resolution', 'Symbolic reasoning']
		},
		{
			title: 'Maximum Flow (Ford-Fulkerson Algorithm)',
			subtitle: 'Objective',
			description:
				'Find the maximum flow in a network, representing the maximum amount of flow that can be sent from a source to a sink.',
			applications: ['Network flow optimization', 'Transportation planning', 'Capacity planning']
		},
		{
			title: 'Graph Coloring',
			subtitle: 'Objective',
			description:
				'Assign colors to the nodes of a graph in such a way that no two adjacent nodes share the same color.',
			applications: [
				'Register allocation in compilers',
				'Scheduling of exams',
				'Frequency allocation in wireless networks'
			]
		}
	];
</script>

<main>
	<section class="max-w-main bg-neutral-950 flex flex-col p-4 gap-8">
		<h1 class="text-center text-3xl font-bold">Dynamic Programming</h1>
		<h2 class="font-bold">Introduction</h2>
		<p>
			Dynamic Programming (DP) is a powerful optimization technique used in computer science and
			mathematics to solve problems that can be broken down into overlapping subproblems. Unlike
			naive recursive approaches, dynamic programming efficiently solves problems by solving each
			subproblem only once and storing the results for future reference. This essay explores the
			principles, applications, and advantages of dynamic programming, shedding light on its
			significance in algorithm design.
		</p>
		<div class="flex items-center justify-center">
			<img
				src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1709150070/my-uploads/Screenshot_2024-02-28_145347_jbiae7.jpg"
				alt=""
			/>
		</div>

		<h2 class="font-bold">Introduction videos</h2>
		<section class="flex w-full gap-2 justify-between max-lg:flex-col">
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/Hdr64lKQ3e4?si=f-aWoA80PqzLE4S1"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
			<div class="flex w-full flex-col items-center justify-center">
				<iframe
					class="w-full min-h-80"
					src="https://www.youtube.com/embed/rE5h11FwiVw?si=wqYXVy8B04BiVGkK"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				></iframe>
			</div>
		</section>

		<h2 class="font-bold">Fundamental Principles:</h2>
		<p>
			At the core of dynamic programming lies the principle of optimal substructure and overlapping
			subproblems. Optimal substructure implies that an optimal solution to a problem can be
			constructed from optimal solutions to its subproblems. Overlapping subproblems occur when the
			same subproblems are solved multiple times in the course of solving the overall problem.
			Dynamic programming addresses this inefficiency by storing the solutions to subproblems in a
			table, ensuring that each subproblem is solved only once.
		</p>
		<h2 class="font-bold">Memoization vs. Tabulation:</h2>
		<p>
			Dynamic programming can be implemented using two main approaches: memoization and tabulation.
			Memoization involves storing the results of subproblems in a data structure (usually a hash
			table) to avoid redundant computations during recursive calls. Tabulation, on the other hand,
			involves building a table and filling it iteratively, starting from the smallest subproblems
			and progressing to the overall problem. Both approaches have their merits, and the choice
			between them often depends on the problem at hand and the available resources.
		</p>

		<section>
			<h2 class="font-bold">Advantages of Dynamic Programming</h2>

			<div class="grid-a">
				{#each arrayMl as content, i}
					<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
						<h2 class="font-bold">{content.title}</h2>
						<p>{content.desc}</p>
					</div>
				{/each}
			</div>
		</section>

		<h1 class="font-bold">MIT Lecture: Dynamic Programming I: Fibonacci, Shortest Paths</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/OQ5jsbhAv_M?si=k_mAoIHKyNa22Hc5"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">
			Dynamic Programming - Learn to Solve Algorithmic Problems & Coding Challenges (5 hours course)
		</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/oBt53YbR9Kk?si=-sL40K2ryNTLvWs_"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Dynamic Programming 1D - Python (3 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/_i4Yxeh5ceQ?si=CvkibEXI3RccXZee"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold">Dynamic Programming 2D - Python (3 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/qMky6D6YtXU?si=v-nWiurVNmWgQquA"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="text-center text-2xl font-bold">Graph Algorithms</h1>
		<h2 class="font-bold">Introduction</h2>
		<p>
			Graph algorithms are a set of computational procedures designed to analyze and manipulate
			graphs, which are mathematical structures consisting of nodes (vertices) and edges. These
			algorithms are fundamental in computer science, as graphs model relationships and connections
			between entities in various real-world and theoretical scenarios. Here, I'll explain some key
			graph algorithms and their applications.
		</p>

		<h1 class="font-bold">Graph Algorithms (2 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/LFKZLXVO-Dg?si=t-BJujibPND3415y"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<section>
			<h2 class="font-bold">Advantages of Dynamic Programming</h2>

			<div class="grid-a">
				{#each graphA as content, i}
					<div class="flex flex-col gap-2 bg-neutral-900 p-4 rounded">
						<h2 class="font-bold">{content.title}</h2>
						<p>{content.description}</p>
						<li class="flex rounded-md flex-col bg-black p-4">
							{#each content.applications as app, i}
								<div class=" text-sm text-purple-500">- {app}</div>
							{/each}
						</li>
					</div>
				{/each}
			</div>
		</section>

		<h1 class="font-bold">Graph Algorithms (2 hours course)</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/tWVWeAqZ0WU?si=Cnq98zOnSoel9Bk4"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h1 class="font-bold mt-10">Related videos</h1>
		<h1 class="font-bold">Watching Neural Networks Learn</h1>
		<div class="flex flex-col items-center justify-center">
			<iframe
				class="w-full min-h-80"
				src="https://www.youtube.com/embed/aPQY__2H3tE?si=rIMLVQu3WxAITOgT"
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
