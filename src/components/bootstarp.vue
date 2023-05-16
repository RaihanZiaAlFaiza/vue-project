<template>
  <header>
    <div>
      <a1>القرأن</a1>
    </div>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">

      <a class="nav-link active" aria-current="page" href="/surah">Surah</a>
      <a class="nav-link active" aria-current="page" href="/about">About</a>
    </div>
  </nav>
  </header>
</template>

<script>

export default {
  name: "bootstarp"

}
</script>

<style scoped>
a1{
  font-size: 50px;
  text-align: center;
}

header {
  line-height: 1.5;
  max-height: 100vh;
  background-color: rgba(143, 182, 182, 0.96);
}

nav {
  width: 100%;
  font-size: 25px;
  text-align: center;
  margin-top: 2rem;
}

nav a {

  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;

    padding-right: calc(var(--section-gap) / 2);
  }


  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: 59rem;
    font-size: 1rem;


    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>