# Accessible Me
Starting files for Accessible Me assignment

Fork this repository to start your assignment Accessible me.
body {
  font-family: 'Roboto', Helvetica, sans-serif;
  background-color: grey;
  margin: 0;
  padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Stick No Bills', 'Roboto', Helvetica, sans-serif;
}

.container {
  max-width: 1080px;
  margin: 0 auto;
  padding: 0 1rem;
}

img {
  width: 100%;
}

.main-nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  margin: 0;
  padding: 0;
}

.main-nav ul li {
  flex: 1;
  text-align: center;
}

.main-nav ul li a {
  display: block;
  color: inherit;
  text-decoration: none;
  font-size: 1.25rem;
}

form input,
form textarea {
  display: block;
  width: 100%;
  margin-bottom: 1rem;
  padding: .5rem 1rem;
}

form textarea {
  min-height: 150px;
  max-height: 150px;
  height: 150px;
  resize: none;
}

form button {
  background: none;
  border: 2px solid black;
  padding: 1rem;
  text-transform: uppercase;
}

.site-footer {
  padding: 2rem 0;
}