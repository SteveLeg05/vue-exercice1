<template>
  <header>
    <div class="header">
      <div class="container">
        <img
          src="https://res.cloudinary.com/lereacteur-apollo/image/upload/v1704448979/RNCP31114/cours-vue/exo-sem-1/my-blog-avatar_xhjc4e.png"
          alt="my-blog-avatar"
        />
        <h2>My Blog</h2>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: var(--header-height);
  padding: 10px 0;
  /* border: solid 2px purple; */
}
.header {
  /* border: solid 2px blue; */
  border-bottom: solid 1px var(--main-yellow);
}

.header img {
  /* border: solid 2px blue; */
  height: 100%;
}
</style>
