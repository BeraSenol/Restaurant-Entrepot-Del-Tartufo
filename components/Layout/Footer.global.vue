<template>
	<div class="bg-gray-50 dark:bg-gray-950">
		<UContainer class="flex flex-col md:flex-row text-center gap-y-12 py-8">
			<div class="flex flex-col gap-y-1 basis-1/3 px-2">
				<NuxtLink to="/">
					<h5>ENTREPOT DEL TARTUFO</h5>
				</NuxtLink>
				<p class="italic">Italian food with a touch of truffle</p>
				<div class="flex justify-center">
					<IconFacebook />
					<IconInstagram />
				</div>
			</div>
			<div class="flex flex-col gap-y-1 basis-1/3 px-2">
				<NuxtLink to="/contact">
					<h5>CONTACT</h5>
				</NuxtLink>
				<NuxtLink href="https://maps.app.goo.gl/i2vfzT5QpC8Rm1QT8" target="_blank">
					<p class="hover:underline underline-offset-2 decoration-1">Hemelrijk 22 / 3500 Hasselt</p>
				</NuxtLink>
				<NuxtLink href="tel:0472930869">
					<p class="hover:underline underline-offset-2 decoration-1">0472 93 08 69</p>
				</NuxtLink>
				<NuxtLink href="mailto:info@entrepotdeltartufo.com">
					<p class="hover:underline underline-offset-2 decoration-1">info@entrepotdeltartufo.com</p>
				</NuxtLink>
				<p>BTW: OD BV BE0734.961.476</p>
			</div>
			<div class="flex flex-col basis-1/3 px-2">
				<h5 class="mb-2">OPENINGSUREN</h5>
				<div class="grid grid-cols-2 gap-x-10 gap-y-2 tracking-widest">
					<p class="text-right">Ma / Do / Vr</p>
					<p class="text-left">12h - 14h<br>18h - 22h</p>
					<p class="text-right">Za / Zo</p>
					<p class="text-left">18h - 22h</p>
					<p class="text-right">Di / Wo</p>
					<p class="text-left italic ml-1">Gesloten</p>
				</div>
			</div>
		</UContainer>
		<UContainer class="flex justify-center">
			<p class="text-sm">Made by Bera Senol Using Nuxt.js&nbsp;</p>
			<IconNuxt />
		</UContainer>
	</div>
</template>
