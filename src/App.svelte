<script>
import Router from "svelte-spa-router";
import About from "./pages/About.svelte";
import Home from "./pages/Home.svelte";
</script>

<main>
<Router
routes={{
  '/':Home,
  '/about':About
}}
/>
</main>

<style>

</style>