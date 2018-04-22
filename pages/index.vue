<template>
  <div>

    <section class="hero is-small is-info is-bold">
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
          <p>
            <a class="has-text-warning" href="https://github.com/mappcpd/web-services/" target="_blank">
              <span class="icon"><i class="fab fa-github"></i></span>
              <span>Repo</span>
            </a>&nbsp;
            <a class="has-text-info" href="https://h1-resources.netlify.com" target="_blank">
              <span class="icon"><i class="fas fa-external-link-alt"></i></span>
              <span>Search Demo</span>
            </a>&nbsp;
            <a class="has-text-dark" href="https://api-docs.mappcpd.com/" target="_blank">
              <span class="icon"><i class="fas fa-file"></i></span>
              <span>API Docs</span>
            </a>&nbsp;
            <a class="has-text-dark" href="http://mappcpd-csanz-graphql.herokuapp.com/graphql" target="_blank">
              <span class="icon"><i class="fas fa-file"></i></span>
              <span>GraphiQL</span>
            </a>&nbsp;
          </p>
          <article>
            <h5 class="title is-5">MappCPD Web App</h5>
            <p class="subtitle is-6">A new front end for the MappCPD member application developed with VueJS / Nuxt.</p>
            <p>
              <a class="has-text-warning" href="https://github.com/cardiacsociety/h1-bulma" target="_blank">
                <span class="icon"><i class="fab fa-github"></i></span>
                <span>Repo</span>
              </a>&nbsp;
              <a class="has-text-info" href="https://h1-demo.csanz.io" target="_blank">
                <span class="icon"><i class="fas fa-external-link-alt"></i></span>
                <span>App Demo</span>
              </a>&nbsp;
              <span class="is-italic is-size-7">(login: member@mappcpd.com / demoMember1)</span>
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
              In 1997 I made the jump from Quarantine officer to IT by scoring a gig installing Cat5 data cable for a
              small company in Port Macquarie. I showed a keen interest in all aspects of networking and was
              soon looking after a local hospital network.
            </p>
            <p>
              In 1999 I moved to Western Australia to start a new job at a small, feisty computer business located near
              Margaret River - South West ComputeAble. Whilst there I completed the Microsoft Certified Systems Engineer
              course and gained a lot of hands-on networking experience. I started to tinker with Linux systems and
              web development.
            </p>
            <p>
              In 2000 I did as short stint as a sys admin with a small ISP in Goulburn before moving back to Sydney and
              working as a freelance LAMP stack developer.
            </p>
            <p>
              In 2004 I started a small company called Mesa which provided a range of web services from design,
              development and systems administration. We developed a range of web database applications over more than
              10 years, culminating in the MappCPD project deployed for the
              <a href="http://www.csanz.edu.au" title="Cardiac Society of Australia and New Zealand" target="_blank">CSANZ</a>.
            </p>
            <p>
              I am currently employed with CSANZ as the Web Systems Manager, and my focus is on backend web services in
              Go, and front end development with VueJS.
            </p>
            <p>
              I'm a proud father of two, husband, occasional sailor and fisherman, and a regular Brazilian Jiu Jitsu
              practitioner.
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
