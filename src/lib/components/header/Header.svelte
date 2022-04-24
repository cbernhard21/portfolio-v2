<header class="header">
    <nav class="nav">
      <a href="/" class="logo">
        <div class="logo-container">
          <h1 class="logo-name">Christopher Bernhard</h1>
        </div>
      </a>
      <ul class="nav-main">
        <li class="nav-list-item"><a href="/" class="nav-list-link">Home</a></li>
        <li class="nav-list-item"><a href="#projects" class="nav-list-link">Projects</a></li>
        <li class="nav-list-item"><a href="#about" class="nav-list-link">About</a></li>
        <li class="nav-list-item"><a href="#contact" class="nav-list-link">Contact</a></li>
      </ul>
    </nav>
</header>

<style>
.header {
  position: fixed;
  width: 100%;
  z-index: 1000;
  background-color: var(--bg-header);
  padding: 2rem 0;
}

.nav {
  margin: 0 auto;
  width: 90%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-transform: uppercase;
  letter-spacing: 2px;
}

.nav a:link,
.nav a:visited {
  color: var(--text-secondary);
}

.logo-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo-name {
  font-weight: 700;
  font-size: 2.4rem;
  color: var(--text-faded);
  transition: .2s all ease-in-out;
}

.logo-name:hover {
  color: var(--text-main);
}

.nav-main {
  list-style: none;
  display: flex;
  flex-direction: row;
}

.nav-list-item {
  font-weight: 700;
  font-size: 1.6rem;
  margin-right: 4rem;
}

.nav-list-item:last-child {
  margin-right: 0;
}

</style>
