<template>
  <div class="logo">
    <a>
      <svg xmlns="http://www.w3.org/2000/svg" :width="width" :height="height" viewBox="0 0 62 14">
        <g fill-rule="evenodd">
          <path d="M40,2 C40,1 41,1.53477231e-14 42,1.53477231e-14 C42,1.53477231e-14 60,1.27897692e-14 60,1.53477231e-14 C61,1.27897692e-14 62,1 62,2 C62,2 62,12 62,12 C62,13 61,14 60,14 C60,14 42,14 42,14 C41,14 40,13 40,12 C40,12 40,2 40,2 Z M44,3.5 C44,3.5 44,10.5 44,10.5 C44,11 44.5,11.5 45,11.5 C45,11.5 57,11.5 57,11.5 C57.5,11.5 58,11 58,10.5 C58,10.5 58,3.5 58,3.5 C58,3 57.5,2.5 57,2.5 C57,2.5 45,2.5 45,2.5 C44.5,2.5 44,3 44,3.5 Z"/>
          <rect width="4" height="2" x="32" y="6" rx=".5"/>
          <path d="M2,0 L26,0 C27,-2.04003481e-15 28,1 28,2 L28,14 L24,14 L24,3.5 C24,3 23.5,2.5 23,2.5 L16,2.5 L16,14 L12,14 L12,2.5 L5,2.5 C4.5,2.5 4,3 4,3.5 L4,14 L0,14 L0,2 C0,1 1,-2.04003481e-15 2,0 Z"/>
        </g>
      </svg>
    </a>
  </div>
</template>

<script>
  export default {
    name: 'mo-logo',
    props: {
      width: {
        type: Number,
        default: 62
      },
      height: {
        type: Number,
        default: 14
      }
    }
  }
</script>

<style lang="scss">
.logo {
  display: inline-block;
  margin: 0;
  padding: 0;
  > a {
    display: block;
    width: 100%;
    height: 100%;
    outline: none;
    border: none;
    text-align: center;
    font-size: 0;
    color: $--app-logo-color;
  }
  svg {
    fill: currentColor;
  }
}
</style>
