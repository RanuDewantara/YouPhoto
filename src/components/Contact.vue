<template>
	<div id="contact" class="bg-zinc-900 border-t border-t-orange-200 pb-40">
		<div class="grid grid-cols-1 p-4 mx-auto gap-10 max-w-7xl items-start font-['Oxanium'] px-5 md:px-20 md:grid-cols-2">
			<h1 class="text-4xl text-white font-bold text-center pt-10 pb-20 md:col-span-2">Contact us</h1>
			<div class="font-semibold text-white text-2xl">
				<div class="mb-10">
					<h1 class="text-xl  ">Office:</h1>
					<h2 class="font-normal text-base">90 Sandown Crest, Lehenagh Beg</h2>
					<h2 class="font-normal text-base">Cork, Ireland</h2>
				</div>
				<div class="mb-10">
					<h1 class="text-xl  ">Email:</h1>
					<h2 class="font-normal text-base">henry-youphoto@voxmail.com</h2>
				</div>
				<div class="mb-10">
					<h1 class="text-xl  ">Phone:</h1>
					<h2 class="font-normal text-base">+353 21 143 7865</h2>
				</div>
			</div>
			<form class="space-y-4">
				<input type='text' placeholder='ex: Robert Arok'
				       class="w-full p-4 bg-gray-100 border text-black text-sm outline-none transition-all" />
				<input type='email' placeholder='ex: user@email.com'
				       class="w-full p-4 bg-gray-100 border text-black text-sm outline-none transition-all" />
				<input type='text' placeholder='Subject'
				       class="w-full p-4 bg-gray-100 border text-black text-sm outline-none transition-all" />
				<textarea placeholder='Message' rows="4"
				          class="w-full px-4 bg-gray-100 border text-black text-sm pt-3 outline-none transition-all"></textarea>
				<button type='button'
				        class="text-white bg-black hover:bg-gray-900 tracking-wide text-sm px-4 py-2.5 w-full outline-none">Send Message</button>
			</form>
		</div>
	</div>
</template>