:root{
  /* change this value to switch the background image */
  --bg-image: url("https://images.unsplash.com/photo-1464618663641-bbdd760ae84a?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=**1170**");
  --bg-fallback: #0f172a; /* shown while image loads or if it fails */
}

html, body {
  height: 100%;
  margin: 0;
}

body {
  background-color: var(--bg-fallback);
  background-image: var(--bg-image);
  background-size: cover;          /* image covers whole viewport */
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;    /* remove if you don't want parallax-like effect */
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
}
