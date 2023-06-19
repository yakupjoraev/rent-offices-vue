<template>
  <section class="hero">
    <div class="hero__inner">
      <div class="hero__info">
        <div class="hero__brokers">#49 AMONG BROKERS</div>

        <h1 class="hero__title">
          Office rental in<br />
          Moscow
        </h1>

        <div class="hero__news">
          <div class="hero__news-label">News</div>
          <div class="hero__news-descr">
            A new skyscraper "825 Third Ave" with 37 offices has been added to
            our portfolio …
          </div>
        </div>
      </div>

      <div class="hero__picture">
        <img class="hero__pic" src="./img/hero-bg.png" alt="" />
      </div>
    </div>

    <div class="hero__footer">
      <h3 class="hero__footer-title">
        Fair rental<br />
        conditions
      </h3>

      <p class="hero__footer-descr">
        Rent an office for several months or several years without long-term
        obligations and commissions
      </p>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped lang="scss">
.hero {
  background: #f2f2f2;
  // .hero__inner

  &__inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  // .hero__info

  &__info {
    padding-left: 100px;
  }

  // .hero__brokers

  &__brokers {
    margin-bottom: 40px;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    opacity: 0.5;
  }

  // .hero__title

  &__title {
    margin-bottom: 260px;
    font-weight: 400;
    font-size: 85px;
    line-height: 100px;
  }

  // .hero__news

  &__news {
    display: flex;
    align-items: flex-start;
    column-gap: 70px;
  }

  // .hero__news-label

  &__news-label {
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
  }

  // .hero__news-descr

  &__news-descr {
    max-width: 230px;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
  }

  // .hero__picture

  &__picture {
  }

  // .hero__pic

  &__pic {
    margin-bottom: -5px;
  }

  // .hero__footer

  &__footer {
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 60px;
    width: fit-content;
    margin-left: auto;
    padding: 50px 150px 0;
    background-color: #fff;
  }

  // .hero__footer-title

  &__footer-title {
    font-weight: 400;
    font-size: 25px;
    line-height: 30px;
  }

  // .hero__footer-descr

  &__footer-descr {
    max-width: 345px;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
  }
}
</style>