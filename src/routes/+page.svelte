<script>
	import main from '$lib/assets/main.jpg';
	import mike1 from '$lib/assets/mike1.jpeg';
	import mike2 from '$lib/assets/mike2.png';
</script>

<div
	class="fixed w-full h-full -right-[90%]"
	style="background-image: url({mike2}); background-repeat: repeat; background-size: 400px 400px;"
/>
<div
	class="fixed w-full h-full -left-[90%]"
	style="background-image: url({mike2}); background-repeat: repeat; background-size: 400px 400px; transform: scaleX(-1);"
/>

<div
	class="flex justify-center items-center flex-col gap-4 w-8/12 mx-auto py-16 font-metropolis text-center"
>
	<img class="w-1/3" src={main} alt="mike's party" />

	<div class="flex">
		<div class="text-4xl">🎉</div>
		<h1 class="text-4xl font-bold text-[#F3DDA2] text-center font-raleway">
			You're Invited to Mike's Roaring 30th Birthday Bash!
		</h1>
		<div class="text-4xl">🎉</div>
	</div>

	<p class="text-lg">
		Join us for a Gatsby-style celebration as we step back in time to the 1920s and 1930s! Don your
		flapper dresses, fedoras, and suspenders for an unforgettable evening.
	</p>

	<p class="text-lg font-semibold">
		📅 <span class="font-normal">Date: August 26th, 2023</span><br />
		🕓 <span class="font-normal">Time: 4:00 PM</span><br />
		📍 <span class="font-normal">Location: 101 W Jefferson St, Rockville, MD 20850</span>
	</p>

	<p class="text-lg">
		Get ready for a night of swinging jazz, glamour, and excitement! We've got games, drinks, and
		delectable bites to keep the party roaring, but feel free to bring a little extra to share.
		Don't miss out on the fun and make sure to RSVP by August 18th.
	</p>

	<img class="w-1/3" src={mike1} alt="mike's party" />

	<p class="text-lg font-italic">See you there, old sport! 🥂🎷🎂</p>

	<p class="text-sm text-xl">#MikesRoaring30 #PartyLikeIts1923</p>
</div>
