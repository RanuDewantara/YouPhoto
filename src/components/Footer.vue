<template>
	<footer class="bg-slate-900 font-['Orbitron'] text-white">
		<div class="max-w-7xl mx-auto flex flex-wrap justify-between p-5 md:px-24 md:pt-20">
			<div class="font-semibold text-xl w-full text-center py-5 md:w-fit md:text-3xl">
				<span class="h-52 bg-sky-700 text-slate-900 ps-2 py-1 rounded-s-full">You</span>
				<span class="h-52 bg-transparent border-4 text-sky-700 ps-1 pe-2 rounded-e-full">Photo</span>
				<h1 class="font-['ProstoOne'] text-gray-400 text-sm text-center py-5">Est. 2020</h1>
			</div>
			<div class="font-['ProstoOne'] text-sm py-5">
				<h1 class="font-semibold mb-2">Site Navigation</h1>
				<ul class="space-y-2 text-gray-400">
					<li class="hover:underline hover:text-white">
						<a href="#">Home</a>
					</li>
					<li class="hover:underline hover:text-white">
						<a href="#about">About</a>
					</li>
					<li class="hover:underline hover:text-white">
						<a href="#services">Services</a>
					</li>
					<li class="hover:underline hover:text-white">
						<a href="#portfolio">Portfolio</a>
					</li>
					<li class="hover:underline hover:text-white">
						<a href="#contact">Contact</a>
					</li>
				</ul>
			</div>
			<div class="font-['ProstoOne'] text-sm py-5">
				<h1 class="font-semibold mb-2">Follow us</h1>
				<ul class="space-y-3">
					<li>
						<a href="#" class="flex items-center gap-2">
							<img src="../assets/img/ig.svg" class="h-6" alt="IG">
							<span class="">Instagram</span>
						</a>
					</li>
					<li>
						<a href="#" class="flex items-center gap-2">
							<img src="../assets/img/fb.svg" class="h-6" alt="FB">
							<span class="">Facebook</span>
						</a>
					</li>
					<li>
						<a href="#" class="flex items-center gap-2">
							<img src="../assets/img/x.svg" class="h-6" alt="X">
							<span class="">X (Twitter)</span>
						</a>
					</li>
					<li>
						<a href="#" class="flex items-center gap-2">
							<img src="../assets/img/yt.svg" class="h-6" alt="YT">
							<span class="">YouTube</span>
						</a>
					</li>
				</ul>
			</div>
		</div>
		<div class="font-['ProstoOne'] text-center text-sm pt-2 pb-5 px-20">
			© {{ new Date().getFullYear() }} YouPhoto - All Rights Reserved.
		</div>
	</footer>
</template>
<script setup lang="ts">
</script>