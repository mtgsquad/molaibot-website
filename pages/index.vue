<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        MolaiBOT
      </h1>
      <div class="links">
        <a
          href="https://bot.molai.dev/invite"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Invite
        </a>

        <a
          href="https://github.com/mtgsquad/molaibot"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>

        <a
          href="https://dsc.gg/devs-gg"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Support Server
        </a>
      </div>
      <br />
      <p class="buttom-left">Developed with ❤ by <a href="https://molai.dev">molai.dev</a></p>
    </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
