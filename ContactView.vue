<template>
  <div class="contact">
    <h1>Contact Me</h1>
  </div>
  <p>Phone: 0481399190</p>
  <p>Email: ericawj.chen6@gmail.com</p>
  <form action="/action_page.php">
<fieldset>
  <legend>Inquiries:</legend>
  <label for="Name">Name:</label><br>
  <input type="text" id="Name" name="Name" value="John Doe"><br>
  <label for="Email">Email:</label><br>
  <input type="text" id="Email" name="Email" value="john.doe@gmail.com"><br><br>
  <form action="/action_page.php">
<br><br>
<p>Your message is: {{ message }}</p>
	<input v-model="message" placeholder="Type your message here" />
<input type="submit">
</form>
</fieldset>
</form>
</template>

<script setup>
import { ref } from 'vue'

const message = ref('')
</script>

<style scoped>

</style>
