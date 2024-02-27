
<script>
    let arrayA = [1,1,1,,2,3,4,4]
</script>
<main>
    <section class="max-w-main flex flex-col p-4 gap-4">
        <h1 class="text-center text-3xl font-bold">Academic Papers</h1>
        <p>
            Algorithms are the backbone of modern computing, playing a pivotal role in solving complex problems efficiently and effectively. These step-by-step procedures guide computers in executing tasks, making them an integral part of various applications and technologies. In this essay, we delve into the importance of algorithms, examining their significance and exploring different types that cater to diverse computational needs. 
        </p>

    </section>
    <section class="max-w-b">
        <h1 class="p-4">CATEGORIES</h1>
        <div class="grid-a">
            {#each arrayA as target, i}
            <div class="b">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure veniam doloremque omnis, odio a eveniet deleniti mollitia excepturi ipsa laudantium molestias ducimus nam. Ea accusamus, iste repellat vel exercitationem voluptas. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis ullam facilis, impedit repudiandae minus explicabo est nam debitis saepe possimus quas ea facere veniam fugit fugiat commodi beatae distinctio odit! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Provident omnis id fugit ipsam aliquam amet vel, mollitia iste eaque exercitationem est, officia autem consectetur ipsum ut, dignissimos harum. Aut, et?
            </div>
            {/each}
        </div>
        <li>
            <a href="/proyects/algorithms" class="p-2 bg-white text-black rounded-xl">go</a>
        </li>
    </section>
</main>

<style>
    .b {
        padding: 3px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
	h1 {
		color: white;
	}
</style>
