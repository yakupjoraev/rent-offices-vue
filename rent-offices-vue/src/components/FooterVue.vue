<template>
  <footer class="footer">
    <div class="footer__top">
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

        <a class="nav__phone" href="tel:8 800 010 88 12">8 800 010 88 12</a>
      </nav>
    </div>
    <div class="footer__bottom">
      <a class="footer__bottom-link" href="#">Privacy Policy</a>

      <a class="footer__bottom-link" href="#">Processing of personal data</a>
    </div>
  </footer>
</template>

<script setup>
</script>

<style scoped lang="scss">
.footer {
  // .footer__top

  &__top {
    padding-bottom: 140px;
  }

  // .footer__bottom

  &__bottom {
    position: relative;
    display: flex;
    align-self: center;
    column-gap: 50px;
    padding: 40px 0;

    &::before {
      content: "";
      position: absolute;
      left: -500%;
      bottom: 0;
      width: 1000%;
      height: 100%;
      background: #f2f2f2;
    }
  }

  // .footer__bottom-link

  &__bottom-link {
    position: relative;
    font-weight: 400;
    font-size: 15px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #383838;

    z-index: 2;
  }
}
.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  column-gap: 20px;
  // .nav__logo

  &__logo {
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
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #383838;
  }

  // .nav__phone

  &__phone {
    font-weight: 400;
    font-size: 30px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #383838;
  }
}
</style>