<!-- InputForm.svelte -->

<script>
  // JavaScript/TypeScript code for your component logic
</script>

<style>
  /* CSS styling for your component */
  .input-container {
    margin-bottom: 20px;
  }

  label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
  }

  input[type="text"],
  input[type="email"],
  input[type="password"] {
    width: 100%;
    padding: 8px;
    font-size: 16px;
    border-radius: 4px;
    border: 1px solid #ccc;
    box-sizing: border-box;
  }

  /* Add more specific styles if needed for different input types */
</style>

<div class="input-container">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Enter your name" />
</div>

<div class="input-container">
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" />
</div>

<div class="input-container">
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" placeholder="Enter your password" />
</div>

<div class="input-container">
  <label for="confirmPassword">Confirm Password:</label>
  <input type="password" id="confirmPassword" name="confirmPassword" placeholder="Confirm your password" />
</div>
