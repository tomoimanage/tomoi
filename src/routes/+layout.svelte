<script lang="ts">
  import favicon from "$lib/assets/favicon.svg";
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

<header>
  <img src="logo.svg" alt="Logo" width="164" />
</header>
<slot />
<footer>This is Footer</footer>
