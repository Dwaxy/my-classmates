<template>
  <nav>
      <ul>
        <li>
          <router-link :to="{
            name: 'anton'
            }"
          >Antons Screen</router-link>
        </li>
        <li>
          <router-link :to="'/keziah'">Keziah</router-link>
        </li>
      </ul>
  </nav>
</template>

<script>
export default {

}
</script>

<style>

li {
  list-style: none;
}
</style>