<script>
  import { onMount } from 'svelte';

  let testing = true; // Set this to false when not testing

  onMount(() => {
    if (!testing) {
      window.location.href = "https://bsky.app/profile/kittenzexe.bsky.social";
    }
  });
</script>

<style>
  @media (orientation: landscape) {
    #backgroundImage {
      transform: translateY(-40%);
      height: 175%;
    }
  }
</style>

<body class="w-screen h-screen overflow-hidden relative">
  <img id="backgroundImage" class="absolute w-screen h-screen" alt="arona blue archive" src="/__arona_blue_archive_drawn_by_pla0658__0e36463634a509021cc8f707536b30c6.webp" style="object-fit: cover; transform-origin: 50% 50%;">
  <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center">
    <p class="text-3xl font-semibold text-sky-900">Redirecting...</p>
    <p class="font-semibold text-sky-900">(If you are not redirected, <span><a href="https://bsky.app/profile/kittenzexe.bsky.social">click here</a></span>)</p>
  </div>
</body>