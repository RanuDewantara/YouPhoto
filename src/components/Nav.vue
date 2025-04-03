<template>
	<nav class="fixed left-0 right-0 w-full z-[9999] top-0 start-0 bg-neutral-900">
		<div class="max-w-7xl flex flex-wrap items-center justify-between mx-auto py-0 md:px-5">
			<a class="flex items-center space-x-3 rtl:space-x-reverse ms-5 md:ms-0" href="#">
				<div class="font-['Orbitron'] font-semibold text-4xl py-4">
					<span class="h-52 bg-sky-700 text-neutral-900 ps-2 py-1 rounded-s-full">You</span>
					<span class="h-52 bg-transparent border-4 text-sky-700 ps-1 pe-2 rounded-e-full">Photo</span>
				</div>
			</a>
			<button aria-controls="navbar-solid-bg" aria-expanded="false"
			        class="inline-flex items-center p-2 me-3 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg bg-[#101010] hover:bg-black focus:outline-none md:hidden"
			        data-collapse-toggle="navbar-solid-bg" type="button">
				<svg aria-hidden="true" class="w-5 h-5" fill="none" viewBox="0 0 17 14" xmlns="http://www.w3.org/2000/svg">
					<path d="M1 1h15M1 7h15M1 13h15" stroke="white" stroke-linecap="round" stroke-linejoin="round"
					      stroke-width="2"/>
				</svg>
			</button>
			<div id="navbar-solid-bg"
			     class="bg-neutral-950 hidden w-full mt-0 px-6 md:block md:px-0 md:w-auto md:bg-transparent">
				<ul class="flex flex-col font-['Oxanium'] font-medium text-[11pt] mt- rounded-lg md:space-x-8 rtl:space-x-reverse md:flex-row md:border-0 md:bg-transparent lg:text-base xl:text-lg">
					<li>
						<a class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white active:text-white"
						   href="#">Home</a>
					</li>
					<li>
						<a class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white active:text-white"
						   href="#about">About</a>
					</li>
					<li>
						<a class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white active:text-white"
						   href="#services">Services</a>
					</li>
					<li>
						<a class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white active:text-white"
						   href="#portfolio">Portfolio</a>
					</li>
					<li>
						<a class="block py-2 px-3 md:p-0 text-gray-400 rounded-sm md:border-0 hover:text-white active:text-white"
						   href="#contact">Contact</a>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</template>
<script lang="ts" setup>
</script>