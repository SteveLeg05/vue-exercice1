<template>
  <footer>
    <p>
      Made with <span>React</span> by
      <a href="https://www.lereacteur.io/" target="_blank">Steve Legrand</a>
    </p>
  </footer>
</template>

<style scoped>
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  border-top: solid 2px var(--main-yellow);
  /* border: solid 2px red; */
  height: var(--footer-height);
}

footer a {
  text-decoration: none;
  color: var(--main-yellow);
}
</style>
