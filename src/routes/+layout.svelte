<script>
  import '../app.css'
</script>

<header>
  <p class="bg-rose-950 text-center text-rose-400 h-auto">this website is under maintainence</p>
</header>

<section class="flex items-center justify-around mx-auto w-11/12 h-12">
  <div>
    <a class="px-3 py-1" href="/"><i class="fa-solid fa-house"></i></a>
  </div>
  <nav class="flex">
    <a class="px-3 py-1" href="/items"><i class="fa-solid fa-shop"></i></a>
    <a class="px-3 py-1" href="/login"><i class="fa-solid fa-right-to-bracket"></i></a>
  </nav>
</section>

<slot />

<style>

</style>