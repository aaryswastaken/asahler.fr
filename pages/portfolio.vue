<script>
  definePageMeta({
    layout: false
  })
</script>


<template>
  <div>
    <NuxtLayout name="precise">
      <template #root>asahler</template>
      <template #page>portfolio.md </template>

      <Pgraph>
      	During my life, I have had a couple of opportunities, leading to multiple projects that I think could be interesting to present here.
      </Pgraph>

      <H1> Main projects </H1>
      <ul>
	<li> <a href="https://github.com/aaryswastaken/ruthenium"> Ruthenium</a> is a LDAP server written in rust, providing a directory service based around Plex's SSO. </li>
	<li> <a href="https://github.com/aaryswastaken/MBN-Ma-Moyenne"> MBN-Ma-Moyenne</a> is a js-based chrome plugin to automate modifications on my high school's grade web page, adding average and color coding. This plugin has been downloaded 4.4k times. <b> Currently not maintained. </b> </li> 
	<li> <a href="https://github.com/eTh3r-network"> eTh3r</a> is an end-to-end encrypted communication service based on custom open-source hardware, enabling higher security by bypassing common malwares. </li>
	<li> <a href="https://github.com/aaryswastaken/ndi-control"> ndi-control</a> is a python-based central dashboard to manage ndi.tv "Studio Monitor" with gui, midi support and extensive config. </li> 
      </ul>
      <H1> Side projects </H1>
      <ul>
	<li> <a href="https://github.com/aaryswastaken/speedrun"> speedrun</a> is a react native mobile application designed to record timing when speedruning my high school's restaurant. </li>
	<li> <a href="https://github.com/aaryswastaken/chesss"> chesss</a> is a python-based chess game, client and server. </li>
	<li> <a href="https://github.com/aaryswastaken/gandi-rush"> Gandi-rush</a> is a python-based Candy Crush alternative, written for our 1st semester finals. The developpement featured full ci/cd pipelines to validate according to pylint our merge requests. </li>
	<li> <a href="https://github.com/aaryswastaken/usb-serial-mouse"> Usb-serial-mouse</a> is a daemon to convert a usb mouse to an old serial version </li>
      </ul>
    </NuxtLayout>
</div>
</template>
