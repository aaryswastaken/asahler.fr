<<script>
  import '~/assets/css/index.css'
</script>

<template>
  <div id="mainBody">
    <div id="name"></div>
    <div id="bar"/>
    <div id="position">CS Student</div>
  </div>
  <div id="body">
    <div id="grid">
      <div class="gridOne" id="portfolio">
        <BigButton>
          Portfolio
        </BigButton>
      </div>

      <div class="gridTwo" id="blog">
        <BigButton>
          Blog
        </BigButton>
      </div>

      <div class="gridThree" id="about">
        <BigButton>
          About Me :D
        </BigButton>
      </div>

      <div class="gridFour" id="socials">
        <BigButton>
          Socials
        </BigButton>
      </div>
    </div>
  </div>

  <Script async>
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
