<template>
  <h1>
    TOP
  </h1>
  <nav id="breadcrumbs">
    <ul>
      <li>
        TOP
      </li>
    </ul>
  </nav>
  <section>
    <NuxtLink v-bind:to="{ name: 'member-memberList' }">
      会員登録はこちら
    </NuxtLink>
  </section>
</template>