<template>
  <div>

    <section class="hero is-light is-bold">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-mobile is-vcentered">
            <div class="column is-narrow">
              <figure class="image is-96x96">
                <img src="~/assets/mike.png">
              </figure>
            </div>
            <div class="column">
              <h2 class="title is-2 is-size-4-mobile">Mike Donnici</h2>
              <h4 class="subtitle is-4 is-size-6-mobile">Full-stack web developer</h4>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="content">
          <h3 class="title is-3 is-marginless">Tech</h3>
          <p class="is-size-4">
            AWS, Git, Go, Heroku, Linux, MongoDB, MySQL, PHP, VueJS
          </p>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Employment</h3>
            <h5 class="title is-5">Web Systems Manager, CSANZ</h5>
            <p class="subtitle is-6">Feb 2014 - present // Remote, AU</p>
            <ul class="top-margin">
              <li>Management and ongoing development of the HeartOne platform</li>
              <li>Consult to CPD committee on tech & dev issues</li>
            </ul>
            <h5 class="title is-5">Owner / Director, Mesa</h5>
            <p class="subtitle is-6">2004 - present // Remote, AU</p>
            <ul>
              <li>Web development and services, AWS, Heroku</li>
              <li>MappCPD system operations</li>
              <li>Online ordering system for
                <a href="https://order.gelatomessina.com" target="_blank">Gelato Messina</a></li>
            </ul>
            <h5 class="title is-5">Previous</h5>
            <ul>
              <li>2000 - 2004: Linux sys admin, LAMP stack development</li>
              <li>1997 - 2000: data cable installation, hardware & network admin</li>
              <li>1995 - 1997: Quarantine officer, kickboxing instructor</li>
              <li>1992 - 1995: farmhand, trades assistant</li>
            </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Current Projects</h3>
            <h5 class="title is-5">MappCPD Web Services</h5>
            <p class="subtitle is-6">Backend services written in Go, aimed at dismantling a monolithic web application
              and extending functionality and flexibility. Includes a REST(ish) API, GraphQL API, short-link redirector,
              Algolia indexer, Pubmed article fetcher and more.</p>
            <p class="buttons">
              <a class="button is-warning is-outlined" href="https://github.com/mappcpd/web-services/"
                 target="_blank">
                <span class="icon"><i class="fab fa-github"></i></span>
                <span>Repo</span>
              </a>
              <a class="button is-info is-outlined" href="https://api-docs.mappcpd.com/" target="_blank">
                <span class="icon"><i class="fas fa-file"></i></span>
                <span>API Docs</span>
              </a>
              <a class="button is-dark is-outlined" href="http://mappcpd-csanz-graphql.herokuapp.com/graphql" target="_blank">
                <span class="icon"><i class="fas fa-file"></i></span>
                <span>GraphiQL</span>
              </a>
            </p>
          <article>
            <h5 class="title is-5">MappCPD Web App</h5>
            <p class="subtitle is-6">A new front end for the MappCPD member application developed with VueJS / Nuxt.</p>
            <p class="buttons">
              <a class="button is-warning is-outlined" href="https://github.com/cardiacsociety/h1-bulma" target="_blank">
                <span class="icon"><i class="fab fa-github"></i></span>
                <span>Repo</span>
              </a>
              <button class="button is-info is-outlined" disabled target="_blank">
                <span class="icon"><i class="fas fa-external-link-alt"></i></span>
                <span>Demo (soon)</span>
              </button>
            </p>
          </article>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Education</h3>
          <ul>
            <li>1998 Grad. Cert. Computing, Monash University</li>
            <li>1992 B.Sc.Agr (Crop Sciences), University of Sydney</li>
          </ul>
        </div>
      </div>
    </section>


    <div :class="{'modal': true, 'is-active': bioModal}">
      <div class="modal-background"></div>
      <div class="modal-card">
        <header class="modal-card-head">
          <p class="modal-card-title">... a brief bio.</p>
          <button class="delete" aria-label="close" @click="bioModal = false"></button>
        </header>
        <section class="modal-card-body">
          <div class="content">
            <p>
              In 1997 I made the jump from Quarantine officer to IT and scored a gig installing Cat5 data cable for a
              small company in Port Macquarie, NSW. I showed a keen interest in server builds and network administration
              and was soon looking after the network at the local hospital.
            </p>
            <p>
              I then moved to Western Australia and started work for a small, but feisty computer business located near
              Margaret River - South West ComputeAble. Whilst working here I completed the MCSE qualification which
              helped to solidify my network experience. I also started to tinker with Linux systems and web development.
            </p>
            <p>
              In 2000 I moved back to NSW to do a short stint at a small ISP in Goulburn as a linux sys admin. I then
              moved back to Sydney and set up as a freelance web developer (LAMP stack), until starting Mesa Group Pty
              Ltd in 2004.
            </p>
            <p>
              Our small team at Mesa created all manner of web sites and data-driven applications, culminating in the
              MappCPD project deployed for the Cardiac Society of Australia and New Zealand, where I was offered a
              permanent part-time position as the Web Systems Manager.
            </p>
            <p>
              My current focus is on backend web services in Go, and front ends with VueJS.
            </p>
            <p>
              I'm open to new opportunities with good people. I currently work remotely, from Callala Bay and travel to
              Sydney as required.
            </p>
            <p>
              I'm the proud Dad of two kids, I have a darling wife and a crazy Kelpie. I love sailing
              (although it's been a while), fishing and have a purple belt in Brazilian Jiu Jitsu.
            </p>
          </div>
        </section>
        <footer class="modal-card-foot">

        </footer>

      </div>
    </div>


    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          <p class="buttons">
            <button class="button is-outline" @click="bioModal = true">
              <span class="icon"><i class="fas fa-user"></i></span>
              <span>brief bio</span>
            </button>
            <a href="https://github.com/mikedonnici" target="_blank" class="button is-outline">
              <span class="icon"><i class="fab fa-github"></i></span>
              <span>GitHub</span>
            </a>
            <a :href="'mailto:'+email" class="button">
              <span class="icon"><i class="fas fa-envelope"></i></span>
              <span>Email</span>
            </a>
          </p>
        </div>
      </div>
    </footer>

  </div>
</template>

<script>

  export default {

    data() {
      return {
        bioModal: false,
        email: "michael@mesa.net.au",
      }
    }
  }
</script>

<style>
  .section {
    padding-bottom: 0;
  }
  .content ul {
    margin-top: -0.6rem;
    margin-left: 1.8rem;
  }
  .footer {
    margin-top: 2rem;
  }
  img {
    border-radius: 8%;
  }

</style>
