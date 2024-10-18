<script>
  import { onMount } from 'svelte';

  let testing = false; // Set this to false when not testing

  onMount(() => {
    if (!testing) {
      window.location.href = "https://bsky.app/profile/kittenzexe.com";
    }
  });
</script>

<style>
  @media (orientation: landscape) {
    #backgroundImage {
      transform: translateY(-20%);
      height: 175%;
    }
  }
</style>

<body class="w-screen h-screen overflow-hidden relative">
    <img id="backgroundImage" class="absolute w-full h-full object-cover" alt="manuka!" src="https://raw.githubusercontent.com/KittenzExe/KittenzExe/refs/heads/main/VRChat_2024-09-24_08-47-38.802_2560x1440.png">
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center">
      <p class="text-3xl font-semibold text-black">Redirecting...</p>
      <p class="font-semibold text-black">(If you are not redirected, <span class="text-blue-800"><a href="https://bsky.app/profile/kittenzexe.com">click here</a></span>)</p>
    </div>
</body>
