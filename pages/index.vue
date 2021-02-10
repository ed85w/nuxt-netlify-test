<template>
  <div class="container">
    <h1>hellozz</h1>
<form 
  name="contactus" 
  action="/thanks" 
  method="post" 
  netlify
  netlify-honeypot="bot-field"
>
  <!-- // Hidden input to check for bots -->
  <input type="hidden" name="form-name" value="contactus" />
  <div>  
    <label for="name">Name:</label> 
    <input type="text" name="name" required/>
  </div>
  <div>
    <input type="email" name="email" required/>
    <label for="email">Email:</label>
  </div>
  <div>
    <textarea name="message" required></textarea>
    <label for="message">Message:</label>
  </div>
  <button type="submit" value="Send message">Send</button>
</form>
    <div>
      <Logo />
      <h1 class="title">
        nuxt-netlify-test
      </h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
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
