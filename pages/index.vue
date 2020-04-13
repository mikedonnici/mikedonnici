<template>
  <div>
    <Top />

    <section class="section">
      <div class="container">
        <div class="content">
          <div class="columns">
            <div class="column is-8">
              <h3 class="title is-3 is-marginless">Me:</h3>
              <p class="is-size-4">
                Proud father, husband, collector of carnivorous
                plants, occasional fisherman, regular Brazilian Jiu Jitsu
                practitioner, genetically motivated, always learning.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="content">
          <h3 class="title is-3 is-marginless">Tech in use:</h3>
          <p class="is-size-4">AWS, Docker, Git, Go, Kotlin, Linux, PostgreSQL</p>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="content">
          <h3 class="title is-3 is-marginless">Learning focus:</h3>
          <p class="is-size-4">AWS, Docker, Go, Kotlin</p>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Employment:</h3>
          
          <h5 class="title is-5">Software Developer, <a href="http://humanetix.com.au/" target="_blank">Humanetix</a></h5>
          <p class="subtitle is-6">Sep 2019 - present // Remote, Canberra</p>
          <ul class="top-margin">
            <li>Maintenance and development of web services for health care application (Go, Kotlin, Postgres)</li>
            <li>Micro-services environment (AWS, Docker, Jenkins) 
            <li>Agile (scrum) workflow (Jira, Bitbucket)</li>
          </ul>
          
          <h5 class="title is-5">IT Manager (Web Systems), CSANZ</h5>
          <p class="subtitle is-6">Feb 2014 - Sep 2019 // Remote, Sydney</p>
          <ul class="top-margin">
            <li>Development of web services and api to extend MappCPD (Golang, GraphQL, MySQL, MongoDB)</li>
            <li>Maintenance and operational management of MappCPD membership system (PHP, MySQL, AWS, Heroku, Docker)</li>
            <li>General web development and site maintenance (WordPress, VuePress, Nuxt.js/Vue.js)</li>
            <li>Liaise with IT &amp; Education Committees</li>
          </ul>
          
          <h5 class="title is-5">Owner / Director, Mesa</h5>
          <p class="subtitle is-6">2004 - 2018 // Remote, Sydney</p>
          <ul>
            <li>Web design, development and systems services (LAMP stack &amp; Linux)</li>
            <li>
              MappCPD system operations from 2013-2018
              <span class="is-italic is-size-7">
                (ownership
                transferred to CSANZ June 2018)
              </span>
            </li>
            <li>
              <a href="https://order.gelatomessina.com" target="_blank">Gelato Messina</a>'s
              online ordering system maintenance and operation - Linux, PHP(ZF), MySQL
            </li>
          </ul>
          <h5 class="title is-5">Previous</h5>
          <ul>
            <li>2000 - 2004: Linux sys admin, LAMP stack development</li>
            <li>1997 - 2000: data cable installation, hardware &amp; network admin</li>
            <li>1994 - 1997: Quarantine officer, kickboxing instructor</li>
            <li>1992 - 1994: farmhand, trades assistant, travel, youthful exuberance</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Work samples:</h3>

          <article>
            <h5 class="title is-6 is-marginless">RTCL.</h5>
            <p>
              Pubmed articles search and notification. Back-end
              <a
                href="https://golang.org"
                target="_blank"
              >Go</a>
              &amp;
              <a href="https://www.mongodb.com" target="_blank">MongoDB</a>, front-end web
              <a href="https://nuxtjs.org/" target="_blank">Nuxt.js</a>.
            </p>
            <p>
              <a class="has-text-warning" href="https://github.com/8o8/rtcl-api" target="_blank">
                <span class="icon">
                  <i class="fab fa-github"></i>
                </span>
                <span>Repo (api)</span>
              </a>&nbsp;
              <a class="has-text-warning" href="https://github.com/8o8/rtcl" target="_blank">
                <span class="icon">
                  <i class="fab fa-github"></i>
                </span>
                <span>Repo (app)</span>
              </a>&nbsp;
              <a class="has-text-info" href="https://rtcl.io/" target="_blank">
                <span class="icon">
                  <i class="fas fa-external-link-alt"></i>
                </span>
                <span>rtcl.io</span>
              </a>&nbsp;
            </p>
          </article>

          <article>
            <h5 class="title is-6 is-marginless">pubmed</h5>
            <p>
              Basic Go package for
              <a
                href="https://www.ncbi.nlm.nih.gov/pubmed/"
                target="_blank"
              >Pubmed</a> queries.
            </p>
            <p>
              <a
                class="has-text-warning"
                href="https://github.com/mikedonnici/pubmed"
                target="_blank"
              >
                <span class="icon">
                  <i class="fab fa-github"></i>
                </span>
                <span>Repo</span>
              </a>
            </p>
          </article>

          <article>
            <h5 class="title is-6 is-marginless">MappCPD Web Services</h5>
            <p>
              Web services written in Go to extend a monolithic PHP application.
              Includes a web API, GraphQL API, short-link redirector, Pubmed article fetcher, Algolia
              indexer.
            </p>
            <p>
              <a
                class="has-text-warning"
                href="https://github.com/mikedonnici/mappcpd-services"
                target="_blank"
              >
                <span class="icon">
                  <i class="fab fa-github"></i>
                </span>
                <span>Repo</span>
              </a>&nbsp;
              <a class="has-text-info" href="https://articles.netlify.com" target="_blank">
                <span class="icon">
                  <i class="fas fa-external-link-alt"></i>
                </span>
                <span>Article Search Demo</span>
              </a>&nbsp;
              <a class="has-text-dark" href="https://api-docs.mappcpd.com/" target="_blank">
                <span class="icon">
                  <i class="fas fa-file"></i>
                </span>
                <span>API Docs</span>
              </a>&nbsp;
            </p>
          </article>

          <article>
            <h5 class="title is-6 is-marginless">CSANZ Static Site</h5>
            <p>
              Static web site developed with
              <a
                href="https://vuepress.vuejs.org/"
                target="_blank"
              >VuePress</a>.
            </p>
            <p>
              <a class="has-text-info" href="https://csanz.netlify.com/" target="_blank">
                <span class="icon">
                  <i class="fas fa-external-link-alt"></i>
                </span>
                <span>Demo</span>
              </a>&nbsp;
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
            <li>1988 HSC, Sydney Technical High School</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Certification</h3>
          <ul>
            <li>2000 Microsoft Certified Systems Engineer (NT4)</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container">
          <h3 class="title is-3">Short courses</h3>
          <ul>
            <li>
              2020-04 Python 3 (Coursera/UMich)
              <a 
                href="https://www.coursera.org/account/accomplishments/specialization/certificate/P9WXFP3YY67R" 
                target="_blank"
              >
                <span class="icon">
                  <i class="fas fa-external-link-alt"></i>
                </span>
              </a>
            <li>
              2019-07 Programming with Go (Coursera/UCI)
              <a
                href="https://www.coursera.org/account/accomplishments/specialization/certificate/G2DCUC4YWEYW"
                target="_blank"
              >
                <span class="icon">
                  <i class="fas fa-external-link-alt"></i>
                </span>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </section>

    <Modal
      :show="showWorkHistoryModal"
      :hide="hideWorkHistoryModal"
      title="Work History"
      subtitle="...a brief overview"
    >
      <WorkHistory />
    </Modal>

    <Modal
      :show="showProjectsModal"
      :hide="hideProjectsModal"
      title="Projects"
      subtitle="...a few of the meatier ones"
    >
      <Projects />
    </Modal>

    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          <p class="buttons">
            <button class="button is-outline" @click="workHistoryModal = true">
              <span class="icon">
                <i class="fas fa-history"></i>
              </span>
              <span>Work History</span>
            </button>
            <button class="button is-outline" @click="projectsModal = true">
              <span class="icon">
                <i class="fas fa-clone"></i>
              </span>
              <span>Projects</span>
            </button>
            <a href="https://github.com/mikedonnici" target="_blank" class="button is-outline">
              <span class="icon">
                <i class="fab fa-github"></i>
              </span>
              <span>GitHub</span>
            </a>
            <a :href="'mailto:'+email" class="button">
              <span class="icon">
                <i class="fas fa-envelope"></i>
              </span>
              <span>Email</span>
            </a>
            <a
              href="https://www.google.com.au/maps/place/Callala+Bay+NSW+2540"
              target="_blank"
              class="button"
            >
              <span class="icon">
                <i class="fas fa-map-marker"></i>
              </span>
              <span>Location</span>
            </a>
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Top from "~/components/top"
import Modal from "~/components/modal"
import WorkHistory from "~/components/workHistory"
import Projects from "~/components/projects"

export default {
  head() {
    return {
      title:
        "Full stack web developer (AWS, Docker, Git, Go, Heroku, Linux, MongoDB, MySQL, PHP, Vue.js / Nuxt.js)",
      meta: [
        {
          hid: "description",
          name: "description",
          content:
            "Michael Donnici: Full stack web developer NSW South Coast. Working primarily with Go and Vue.js. Pragmatic, reliable, always learning."
        }
      ]
    }
  },
  components: {
    Top,
    Modal,
    WorkHistory,
    Projects
  },
  data() {
    return {
      workHistoryModal: false,
      projectsModal: false,
      email: "michael@mesa.net.au"
    }
  },
  methods: {
    showWorkHistoryModal() {
      return this.workHistoryModal
    },
    hideWorkHistoryModal() {
      this.workHistoryModal = false
      return this.workHistoryModal
    },
    showProjectsModal() {
      return this.projectsModal
    },
    hideProjectsModal() {
      this.projectsModal = false
      return this.projectsModal
    }
  }
}
</script>

<style>
.section {
  padding-bottom: 0;
}

article {
  margin-bottom: 1.4rem;
}

.content ul {
  margin-top: -0.6rem;
  margin-left: 1.8rem;
}

.footer {
  margin-top: 2rem;
}

img {
  border-radius: 50%;
  border: solid 3px #dff3fa;
}
</style>
