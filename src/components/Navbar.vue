<template >
  <nav class="nav">
    <article class="nav--logo">
      <img src="/public/img/logo.svg" alt="logo">
      <span>vue weather</span>
    </article>
    <div class="nav--city">
      <img src="/public/img/city.svg" alt="drop">
      <select>
        <option disabled>Выберите город</option>
        <option value="Uzbekistan">Uzbekistan</option>
        <option value="UAE">UAE</option>
        <option value="Turky">Turky</option>
      </select>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
}
</script>