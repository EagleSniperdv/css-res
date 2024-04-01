<template>
        <header>
        <div id="logo">
            <a href="#">
            <h1><span>M.B.N.</span></h1>
            </a>
        </div>

        <nav>
            <ul id="nav">
            <li class="select"><a href="#">News</a></li>
            <li><a href="#">Artist</a></li>
            <li><a href="#">Production</a></li>
            <li><a href="#">Information</a></li>
            </ul>
        </nav>
        </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1rem 0;
  border-bottom: 1px solid #111;
}

nav {
  width: 100%;
}

#nav {
  display: flex;
  justify-content: flex-end;
}

h1 {
  text-shadow: 1px 1px 1px #333;
}
#nav li {
  position: relative;
  margin-left: 1rem;
  padding-bottom: 0.3rem;
}
#nav li a {
  letter-spacing: 1px;
  color: #777;
}
#nav li a:hover {
  color: #111;
}
.select::before {
  content: "";
  background-color: #777;
  width: 100%;
  height: 2px;
  position: absolute;
  bottom: 0;
}
</style>