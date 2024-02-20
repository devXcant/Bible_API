<!-- eslint-disable vue/multi-word-component-names -->

<script setup>
	import Player from '../assets/Components/Player.vue'
</script>

<template>
  <!-- daialy things -->
    <div class="flex justify-center align-center  w-screen ">
      <div class="bg-red-200 text-black m-10 p-20  rounded-2xl">
        <p class="leading-2 text-2xl">
          Daily Bible Verse's
        </p>
        <h3 class=" leading-5 p-5"> Dummy yext goes here</h3>
      </div>

      <div class="bg-red-200 text-black m-10 p-20  rounded-2xl">
        <p class="leading-2 text-2xl">
          Daily Memory Verse's
        </p>
        <h3 class=" leading-5 p-5 whitespace-break-spaces"> Dummy yext goes here</h3>
      </div>    
      
    </div>

 

	<div class="flex flex-col justify-center items-center">
			<h3><span class="leading-3 text-2xl font-medium">
				Generate styled images for Bible Texts
			</span></h3>
			<button>
				<img class="w-20 h-20" src="../assets/images/gallery.png" alt="">
			</button>
	</div>


	  <div>
		<Player />
	  </div>

	  <div>
		<BibleCard />
	  </div>

  
</template>