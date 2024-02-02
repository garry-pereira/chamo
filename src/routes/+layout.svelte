<script>
  import '../app.css'
</script>

<header>
  <p class="bg-rose-950 text-center text-rose-400 h-auto">this website is under maintainence</p>
</header>

<section class="flex items-center justify-around mx-auto w-11/12 h-12">
  <div>
    <a class="px-3 py-1" href="/">Home</a>
  </div>
  <nav class="flex">
    <a class="px-3 py-1" href="/items">Items</a>
    <a class="px-3 py-1" href="/login">Login</a>
  </nav>
</section>

<slot />

<style>

</style>