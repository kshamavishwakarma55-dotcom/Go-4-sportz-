body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f7fb;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #0b3d91;
  padding: 15px 20px;
  color: white;
}

.logo {
  font-size: 20px;
  font-weight: bold;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

nav a:hover {
  color: #ffcc00;
}

/* Hero */
.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(to right, #0b3d91, #1e90ff);
  color: white;
}

.hero button {
  padding: 12px 20px;
  border: none;
  background: #ffcc00;
  font-weight: bold;
  cursor: pointer;
  margin-top: 10px;
}

/* Sections */
.section {
  padding: 40px;
  text-align: center;
}

.dark {
  background: #0b3d91;
  color: white;
}

/* Cards */
.cards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
}

.card {
  background: white;
  padding: 20px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Contact */
.contact {
  padding: 40px;
  text-align: center;
}

.contact form {
  display: flex;
  flex-direction: column;
  width: 300px;
  margin: auto;
}

.contact input,
.contact textarea {
  margin: 10px 0;
  padding: 10px;
}

.contact button {
  background: #0b3d91;
  color: white;
  padding: 10px;
  border: none;
  cursor: pointer;
}

/* Footer */
footer {
  background: black;
  color: white;
  text-align: center;
  padding: 10px;
}
