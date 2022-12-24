
<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <h2>Hi.</h2>
    <div class="about-body">
      <p>I'm a journalist interested in technology, politics, and the politics of technology. </p>
      <p>After starting my career in London, then moving to Montréal, I'm now based in New York where I attended the
        <a href="https://www.recurse.com/" target="_blank">Recurse Center</a> programming retreat in 2019.</p>
      <p>Since then I've worked at global nonprofit <a href='https://www.witness.org/'>WITNESS</a> researching deepfakes and media manipulation, at <a href='https://themarkup.org/'>The Markup</a> on the 
      <a href="https://themarkup.org/series/citizen-browser">Citizen Browser</a> Facebook accountability project, and as a <a href='https://www.theverge.com/authors/corin-faife'>senior reporter at The Verge</a> covering privacy, surveillance and cybersecurity.</p>
      <p>Currently I'm the inaugural <a href="https://www.dli.tech.cornell.edu/members/Faife">Peggy J. Koenig Civic Innovation Fellow</a> at Cornell Tech university, based at the Digital Life Initiative under the supervision of Professor Helen Nissenbaum.</p>
      <p>Use the info <a href='https://corinfaife.co/#/contact'>here</a> to say hello!</p>
   </div>

    <br>
    <span>
      <a href="#/" > home</a>
    </span>
       |
    <span>
      <a href="#/portfolio" > portfolio </a>
    </span>
       |
    <span>
      <a href="#/contact" > contact </a>
    </span>

  </div>

</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'About'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about {
  width: 50%;
  margin: auto;
}

.about-body{
  text-align: left;
}

#subscribe {
    margin-block-start: .2em;
}

</style>
