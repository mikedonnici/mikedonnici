<template>
    <div>

        <section class="hero is-small is-warning is-bold">
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
                        AWS, Docker, Git, Go, Heroku, Linux, MongoDB, MySQL, PHP, VueJS
                    </p>
                </div>
            </div>
        </section>

        <section class="section">
            <div class="content">
                <div class="container">
                    <h3 class="title is-3">Employment</h3>
                    <h5 class="title is-5">IT Manager (Web Systems), CSANZ</h5>
                    <p class="subtitle is-6">Feb 2014 - present // Remote, Sydney</p>
                    <ul class="top-margin">
                        <li>Consult to IT Committee on tech & dev issues</li>
                        <li>Dev and ops for MappCPD membership management system (PHP, MySQL, AWS, Heroku, Docker)</li>
                        <li>Develop web services (Golang, GraphQL, MySQL, MongoDB)</li>
                        <li>General web development and site maintenance (WordPress, VuePress, Nuxt/VueJS)</li>
                        <li>General network support as required (Windows, Office365)</li>
                    </ul>
                    <h5 class="title is-5">Owner / Director, Mesa</h5>
                    <p class="subtitle is-6">2004 - 2018 // Remote, Sydney</p>
                    <ul>
                        <li>Web design, development and systems services (LAMP stack &amp; Linux)</li>
                        <li>MappCPD system operations from 2013-2018 <span class="is-italic is-size-7">(ownership
                                transferred to CSANZ June 2018)</span>
                        </li>
                        <li><a href="https://order.gelatomessina.com" target="_blank">Gelato Messina</a>'s
                            online ordering system maintenance and operation - Linux, PHP(ZF), MySQL
                        </li>
                    </ul>
                    <h5 class="title is-5">Previous</h5>
                    <ul>
                        <li>2000 - 2004: Linux sys admin, LAMP stack development</li>
                        <li>1997 - 2000: data cable installation, hardware & network admin</li>
                        <li>1994 - 1997: Quarantine officer, kickboxing instructor</li>
                        <li>1992 - 1994: farmhand, trades assistant, travel, youthful exuberance</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="section">
            <div class="content">
                <div class="container">
                    <h3 class="title is-3">Projects / Work Samples</h3>

                    <article>
                        <h5 class="title is-6 is-marginless">pubmed</h5>
                        <p>
                            Basic Go package for <a href="https://www.ncbi.nlm.nih.gov/pubmed/" target="_blank">Pubmed</a>
                            queries.
                        </p>
                        <p>
                            <a class="has-text-warning" href="https://github.com/mikedonnici/pubmed" target="_blank">
                                <span class="icon"><i class="fab fa-github"></i></span>
                                <span>Repo</span>
                            </a>
                        </p>
                    </article>

                    <article>
                        <h5 class="title is-6 is-marginless">RTCL.</h5>
                        <p>
                            Search and notification app for Pubmed articles. Back-end web api in Go,
                            front-end web app using <a href="https://nuxtjs.org/" target="_blank">NUXT</a>.
                        </p>
                        <p>
                            <a class="has-text-warning" href="https://github.com/8o8/rtcl-api" target="_blank">
                                <span class="icon"><i class="fab fa-github"></i></span>
                                <span>Repo (api)</span>
                            </a>&nbsp;
                            <a class="has-text-warning" href="https://github.com/8o8/rtcl" target="_blank">
                                <span class="icon"><i class="fab fa-github"></i></span>
                                <span>Repo (app)</span>
                            </a>&nbsp;
                            <a class="has-text-info" href="https://rtcl.netlify.com/" target="_blank">
                                <span class="icon"><i class="fas fa-external-link-alt"></i></span>
                                <span>App Demo</span>
                            </a>&nbsp;
                            <!--<span class="is-italic is-size-7">(login: member@mappcpd.com / demoMember1)</span>-->
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
                            <a class="has-text-warning" href="https://github.com/mikedonnici/mappcpd-services" target="_blank">
                                <span class="icon"><i class="fab fa-github"></i></span>
                                <span>Repo</span>
                            </a>&nbsp;
                            <a class="has-text-info" href="https://articles.netlify.com" target="_blank">
                                <span class="icon"><i class="fas fa-external-link-alt"></i></span>
                                <span>Article Search Demo</span>
                            </a>&nbsp;
                            <a class="has-text-dark" href="https://api-docs.mappcpd.com/" target="_blank">
                                <span class="icon"><i class="fas fa-file"></i></span>
                                <span>API Docs</span>
                            </a>&nbsp;
                            <a class="has-text-dark" href="https://mappcpd-csanz-graphql.herokuapp.com/graphql" target="_blank">
                                <span class="icon"><i class="fas fa-file"></i></span>
                                <span>GraphiQL</span>
                            </a>&nbsp;
                        </p>
                    </article>

                    <article>
                        <h5 class="title is-6 is-marginless">CSANZ Static Site</h5>
                        <p>
                            Static web site developed with
                            <a href="https://vuepress.vuejs.org/" target="_blank">VuePress</a>.
                        </p>
                        <p>
                            <a class="has-text-info" href="https://csanz.netlify.com/" target="_blank">
                                <span class="icon"><i class="fas fa-external-link-alt"></i></span>
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
                    <h3 class="title is-3">Education &amp; Training</h3>
                    <ul>
                        <li>2000 Microsoft Certified Systems Engineer (NT4)</li>
                        <li>1998 Grad. Cert. Computing, Monash University</li>
                        <li>1992 B.Sc.Agr (Crop Sciences), University of Sydney</li>
                        <li>1988 HSC, Sydney Technical High School</li>
                    </ul>
                </div>
            </div>
        </section>


        <div :class="{'modal': true, 'is-active': bioModal}">
            <div class="modal-background"></div>
            <div class="modal-card">
                <header class="modal-card-head">

                    <div class="modal-card-title">
                        <div class="media">
                            <div class="media-left">
                                <figure class="image is-64x64">
                                    <img src="~/assets/mike.png" alt="Mike">
                                </figure>
                            </div>
                            <div class="media-content">
                                <p class="title is-4">Mike Donnici</p>
                                <p class="subtitle is-6">...a brief history</p>
                            </div>
                        </div>
                    </div>

                    <button class="delete" aria-label="close" @click="bioModal = false"></button>
                </header>
                <section class="modal-card-body">
                    <div class="content">
                        <p>
                            After completing an Ag. Science degree, lots of travel and numerous jobs, I moved back to
                            Sydney and became a Quarantine Officer. In 1997 I decided to make the jump to IT and
                            hunkered
                            down on a small farm in the Hunter Valley to work and study Computing (by distance).
                        </p>
                        <p>1998: I scored a gig installing data cable for a small company in Port Macquarie where I
                            showed
                            a keen interest in all aspects of networking. Within 12 months I was providing network
                            support
                            to local businesses including Port Macquarie Base Hospital.
                        </p>
                        <p>
                            1999: I moved to Western Australia to start a new job at a small-but-feisty computer
                            business located near Margaret River. Whilst there I completed the Microsoft Certified
                            Systems Engineer certification (MSCE NT4) and gained a lot of hands-on networking
                            experience. I started to tinker with Linux systems and web development.
                        </p>
                        <p>
                            2000: After a short stint as a Linux sys admin with an ISP in Goulburn, I headed back to
                            Sydney and contracted as a Linux sys admin and LAMP stack developer.
                        </p>
                        <p>
                            2004: I started a small company called Mesa which provided the full range of web design,
                            development and hosting services. Over more than 10 years we developed a range of custom
                            web
                            applications in PHP/MySQL. Our final project was a web-based membership system (MappCPD)
                            developed for the <a href="http://www.csanz.edu.au" title="the Cardiac Society of Australia and New Zealand" target="_blank">CSANZ</a> in 2013.
                        </p>
                        <p>
                            2014: I took up the position of IT Manager with CSANZ and have the sole responsibility for
                            the ongoing development and maintenance of their web systems.
                        </p>
                        <hr>
                        <p>
                            I'm a proud father-of-two, husband, occasional sailor and fisherman, and a regular
                            Brazilian
                            Jiu Jitsu practitioner.
                        </p>
                        <p>
                            I am genetically motivated to learn and get stuff done.
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
                            <span>Bio</span>
                        </button>
                        <a href="https://github.com/mikedonnici" target="_blank" class="button is-outline">
                            <span class="icon"><i class="fab fa-github"></i></span>
                            <span>GitHub</span>
                        </a>
                        <a :href="'mailto:'+email" class="button">
                            <span class="icon"><i class="fas fa-envelope"></i></span>
                            <span>Email</span>
                        </a>
                        <a href="https://www.google.com.au/maps/place/Callala+Bay+NSW+2540" target="_blank" class="button">
                            <span class="icon"><i class="fas fa-map-marker"></i></span>
                            <span>Location</span>
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
                email: "michael@mesa.net.au"
            };
        }
    };
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