<script>
  import Colors from './Colors.svelte'
  import Typography from './Typography.svelte'
</script>

<main class="container">
  <h1>Design System</h1>
  <div class="flow">
    <section id="colors">
      <Colors />
    </section>
    <section id="typography">
      <Typography />
    </section>
  </div>
</main>

<style>
  .flow {
    --spacer: 148px;
  }

  .container {
    --width: 80rem;
  }
</style>
