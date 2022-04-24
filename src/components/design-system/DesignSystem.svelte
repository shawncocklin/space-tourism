<script>
  import Colors from './Colors.svelte'
  import Typography from './Typography.svelte'
  import Interactive from './Interactive.svelte'
</script>

<main class="container">
  <h1 style="margin-bottom: 2rem;">Design System</h1>
  <div class="flow">
    <section id="colors">
      <Colors />
    </section>
    <section id="typography">
      <Typography />
    </section>
    <section id="interactive">
      <Interactive />
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
