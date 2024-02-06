<script>
  definePageMeta({
    layout: false
  })
</script>


<template>
  <div>
    <NuxtLayout name="precise">
      <template #root>asahler</template>
      <template #page>about_me.md </template>

      <H1> Myself </H1>

      <Pgraph>
	I'm Aarys Sahler, a 2nd year CS student. I used to say that I answer stack overflow for fun but I don't got time anymore for this sadly. 
	<br>
	I'm passionate about photography, especially in the context of events and flowers but also other forms of art such as music (I dont practice but I do enjoy listening to it) or danse.
	<br>
	I enjoy sunsets because I find them very pretty :D
      </Pgraph>

      <H2> Konputerz </H2>
      <Pgraph>
      	I started C when I was 6 years old. I then moved to python for a couple of years, then to JavaScript for quite some time. I've done a couple of projects in both of these languages (ie. oxygen, ndi-control).
	I then wanted to go deeper in my CS knowledge. I then started rust, then c again and finally assembly. I've done quite some go too, I really enjoy this language.
      </Pgraph>
      <Pgraph>
	I'm really passionate about the concept of information and expression, in all of its forms but especially sound. That's why I hope to get chosen for the Telecom department at INSA of Lyon.
	<br>
	Thats also why I started <i>ether</i>, an end-to-end telecommunication system based off open source hardware to ensure maximum security.
      </Pgraph>

      <H2> Photography </H2>
      <Pgraph>
	I used to work as a professional photographer for an association, resulting in quite some experiences in the real world. It was great :D <br>

	Since, I've been taking pictures for myself (mainly flowers and sunsets) or for others, mainly for other INSA students or during INSA events.
      </Pgraph>
    </NuxtLayout>
</div>
</template>
