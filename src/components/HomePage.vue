<template>
  <div class="homepage">
      <h1>Welcome to the IE Bank!</h1>
      <p>Your trusted partner for financial success.</p>
      <div class="links">
          <router-link to="/accounts" class="link-button">Accounts</router-link>
          <router-link to="/skull" class="link-button">Skull</router-link>
      </div>
  </div>
</template>

<script>
export default {
    name: "HomePage",
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700&family=Open+Sans&display=swap'); /* Custom fonts added */

/* Main container styles */
.homepage {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100vh;
    background-color: #f4c2c2; /* Baby pink background */
    padding: 20px;
    box-sizing: border-box;
}

/* Title (h1) styles */
h1 {
    font-family: 'Roboto', sans-serif; /* Custom font for the title */
    font-size: 64px;
    background: -webkit-linear-gradient(right, #0648d7, #2ea901); /* Gradient in text */
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    color: transparent; /* Fallback for non-webkit browsers */
    margin-bottom: 10px;
    text-align: center;
}

/* Paragraph (p) styles */
p {
    font-family: 'Open Sans', sans-serif; /* Custom font for the paragraph */
    color: #0e0630;
    font-size: 24px;
    text-align: center;
    margin-bottom: 30px;
}

/* Button container styles */
.links {
    display: flex;
    width: 100%;
    justify-content: center;
    gap: 0 20px;
}

/* Button styles */
.link-button {
    padding: 12px 24px;
    font-size: 18px;
    color: white;
    background-color: #0648d7;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

/* Button hover effect */
.link-button:hover {
    background-color: #043a9b;
}
</style>
