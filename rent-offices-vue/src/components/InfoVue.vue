<template>
  <section class="info">
    <div class="info__inner">
      <div class="info__counts">
        <div class="info__count">
          <div class="info__count-sum">89</div>

          <p class="info__count-descr">
            Properties in Brooklyn, Manhattan, the Bronx and Queens
          </p>
        </div>

        <div class="info__count">
          <div class="info__count-sum">646</div>

          <p class="info__count-descr">Current tenants in Twenty One today</p>
        </div>
      </div>

      <div class="info__about">
        <p class="info__about-label">О RENTI ONE</p>

        <h3 class="info__about-title">8 years of impeccable reputation</h3>

        <div class="info__about-descrs">
          <p class="info__about-descr">
            We help entrepreneurs from the CIS countries to find office space in
            New York, mainly in the central part of the city.
          </p>

          <p class="info__about-descr">
            Among our clients there are both small startups of 4-6 people, and
            large businesses with thousands of employees. Therefore, we can help
            any company, regardless of the scale.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped lang="scss">
.info {
  position: relative;
  max-width: 800px;
  margin: 220px auto;

  &::before {
    content: "";
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #f2f2f2;
    width: 700px;
    height: 700px;
    border-radius: 100%;
    z-index: -1;
  }
  // .info__inner

  &__inner {
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 300px;
  }

  // .info__counts

  &__counts {
    display: flex;
    flex-direction: column;
    row-gap: 70px;
  }

  // .info__count

  &__count {
    display: flex;
    flex-direction: column;
    row-gap: 30px;
  }

  // .info__count-sum

  &__count-sum {
    font-weight: 400;
    font-size: 90px;
    line-height: 95px;
  }

  // .info__count-descr

  &__count-descr {
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    letter-spacing: 0.01em;
  }

  // .info__about

  &__about {
  }

  // .info__about-label

  &__about-label {
    margin-bottom: 20px;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    opacity: 0.5;
  }

  // .info__about-title

  &__about-title {
    margin-bottom: 20px;
    font-weight: 400;
    font-size: 50px;
    line-height: 60px;
  }

  // .info__about-descrs

  &__about-descrs {
    display: flex;
    flex-direction: column;
    row-gap: 20px;
    max-width: 500px;
    font-weight: 400;
    font-size: 18px;
    line-height: 30px;
    letter-spacing: 0.01em;
  }

  // .info__about-descr

  &__about-descr {
  }
}
</style>