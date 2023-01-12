<script>
  let color = "#ff3e00";
</script>

<h1>Yeah man</h1>
<p>Svelte cool 👍🏽</p>
<p>I learned how to do reactivity with it. Check it out!</p>
<input type="color" bind:value={color} style="height: 50px;" />
<div style="--theme-color: {color}">
  <h1>HAPPY BIRTHDAY JESI</h1>
</div>
<a href="/love-you-so-much">-></a>


<style>
  h1 {
    color: var(--theme-color);
  }
</style>
