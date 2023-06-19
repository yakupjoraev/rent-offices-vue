<template>
  <header class="header">
    <nav class="nav">
      <a class="nav__logo" href="#">
        <img class="nav__logo-img" src="./icons/logo.svg" alt="logo" />
      </a>
      <ul class="nav__list">
        <li class="nav__item">
          <a class="nav__link" href="#">Popular offices</a>
        </li>

        <li class="nav__item">
          <a class="nav__link" href="#">About company</a>
        </li>

        <li class="nav__item">
          <a class="nav__link" href="#">Office showreel</a>
        </li>

        <li class="nav__item">
          <a class="nav__link" href="#">Contacts</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
</script>

<style scoped lang="scss">
.header {
  padding-top: 80px;
  padding-bottom: 40px;
  background-color: transparent;
}
.nav {
  display: flex;
  align-items: center;
  // .nav__logo

  &__logo {
    margin-right: 120px;
  }

  // .nav__logo-img

  &__logo-img {
  }

  // .nav__list

  &__list {
    display: flex;
    align-items: center;
    column-gap: 60px;
  }

  // .nav__item

  &__item {
  }

  // .nav__link

  &__link {
    border-bottom: 1px solid transparent;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #383838;

    transition: border-color 0.2s linear;

    &:hover {
      border-color: #383838;
    }
  }
}
</style>