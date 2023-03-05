<script>
	import floral from '$lib/images/floral.png';
	import blue from '$lib/images/blue.png';
	import black from '$lib/images/black.jpg';
	import pink from '$lib/images/pink.png';
	import purple from '$lib/images/purple.png';
	import red from '$lib/images/red.png';

	let imgSrc = '/src/lib/images/';
</script>

<nav class="mx-auto mt-2 flex justify-between px-4 sm:w-2/3">
	<!-- logo text -->
	<span class="font-Poppins text-center text-4xl font-black text-yellow-200 sm:text-9xl"
		>Glammie.</span
	>
	<!-- Social links -->
	<div class="flex items-end gap-4 pb-2 sm:pb-4">
		<!-- Facebook -->
		<svg
			xmlns="http://www.w3.org/2000/svg"
			class="h-6 w-6 fill-yellow-200 hover:fill-blue-300 sm:h-14 sm:w-14"
			viewBox="0 0 24 24"
		>
			<a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer">
				<path
					d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"
				/>
			</a>
		</svg>
		<!-- Instagram -->
		<svg
			xmlns="http://www.w3.org/2000/svg"
			class="h-6 w-6 fill-yellow-200 hover:fill-fuchsia-300 sm:h-14 sm:w-14"
			viewBox="0 0 24 24"
		>
			<a href="https://www.instagram.com/" target="_blank" rel="noopener noreferrer">
				<path
					d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"
				/>
			</a>
		</svg>
	</div>
</nav>

<!-- animated text headline -->
<h1 class="font-Poppins m-4 animate-pulse text-center tracking-widest text-white sm:text-3xl">
	"Hire👗. Save💰. Help🌏. <span class="block sm:inline">Let's dress responsibly!"</span>
</h1>

<main class="mx-auto grid grid-cols-2 gap-3 px-4 sm:w-2/3">
	<img src={floral} alt="floral dress" class="rounded-lg border-2 border-yellow-200 object-cover" />
	<img src={blue} alt="blue dress" class="rounded-lg border-2 border-yellow-200 object-cover" />
	<img
		src={black}
		alt="black & yellow dress"
		class="rounded-lg border-2 border-yellow-200 object-cover"
	/>
	<img src={purple} alt="purple dress" class="rounded-lg border-2 border-yellow-200 object-cover" />
	<img src={red} alt="red dress" class="rounded-lg border-2 border-yellow-200 object-cover" />
	<img src={pink} alt="pink dress" class="rounded-lg border-2 border-yellow-200 object-cover" />
</main>

<footer class="mt-4 text-center">
	<a href="https://www.instagram.com/">
		<div class="font-Poppins tracking-widest text-white sm:text-3xl">
			Interested in hiring a dress?
			<span class="block underline decoration-dashed sm:inline">
				Check out our <span class="text-yellow-300"> Insta</span>
			</span>
			<!-- Instagram -->
			<svg
				xmlns="http://www.w3.org/2000/svg"
				class="inline-flex h-6 w-6 fill-yellow-200 hover:fill-fuchsia-300 sm:h-10 sm:w-10"
				viewBox="0 0 24 24"
			>
				<a href="https://www.instagram.com/" target="_blank" rel="noopener noreferrer">
					<path
						d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"
					/>
				</a>
			</svg>
		</div>
	</a>
</footer>
