<script>
  import '~/assets/css/index.css'

  import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome"
  import { faInstagram } from "@fortawesome/free-brands-svg-icons"
</script>

<template>
  <div id="mainBody">
    <div id="name"></div>
    <div id="bar"/>
    <div id="position">CS Student @ INSA Lyon</div>
  </div>
  <div id="body">
    <div id="gridWrapper">
      <div id="grid">
	<div class="gridOne" id="portfolio">
	  <BigButton @clicked="() => {navigateTo('/portfolio')}">
	    Portfolio
	  </BigButton>
	</div>

	<div class="gridTwo" id="blog">
	  <BigButton @clicked="() => {navigateTo('https://blog.asahler.fr', {external: true});}">
	    Blog
	  </BigButton>
	</div>

	<div class="gridThree" id="about">
	  <BigButton @clicked="() => {navigateTo('/about')}">
	    About Me :D
	  </BigButton>
	</div>

	<div class="gridFour" id="fTh">
	  <BigButton>
	    4th button
	  </BigButton>
	</div>
      </div>
    </div>
  </div>
  <footer id="footer">
    <div class="socials">
      <Social redirect="https://www.instagram.com/aaryswastaken">
	<font-awesome-icon icon="fa-brands fa-instagram" />
      </Social>
      <Social redirect="https://www.github.com/aaryswastaken">
      	<font-awesome-icon icon="fa-brands fa-github" />
      </Social>
    </div>
  </footer>

  <Script async>

    // *************************
    const name = "Aarys Sahler "

    async function writeName(_name) {
      buff = "";
      dest = document.getElementById("name")

      for (let letter in _name) {
        buff += _name[letter];
      
        dest.innerText = buff + "#";
        await new Promise(r => setTimeout(r, 50 + 300*Math.random()))
      }
    }

    writeName(name)
  </Script>
</template>
