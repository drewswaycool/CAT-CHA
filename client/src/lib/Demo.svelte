<!-- Component for centering the demo of this whole circus -->
<svelte:head>
  <title>CAT-CHA</title>
</svelte:head>

<div class="demo">
  <slot />
</div>

<style>
  .demo {
    display: flex;
    justify-content: center;
    margin-top: 20vh;
  }

  @media (max-width: 600px) {
    .demo {
      margin-top: 0;
    }
  }
</style>
