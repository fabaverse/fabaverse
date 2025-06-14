

<script lang="ts">
  import '../global.css'; // or app.css depending on your setup
  import '../app.css';
</script>

<svelte:head>
  <title>Fabaverse — Create Your Universe</title>
  <meta name="description" content="The Fabaverse awaits. A digital realm for creation, automation, and storytelling." />
  <link rel="icon" href="/favicon.png" />
</svelte:head>

<!-- 🌌 Background wrapper -->
<div class="min-h-screen bg-[url('/stars-bg.png')] bg-cover bg-center bg-no-repeat text-foreground font-sans">
  <!-- Page content will slot in here -->
  <slot />
</div>

