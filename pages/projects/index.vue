<template>
  <div>
    <Top/>

    <section class="section">
      <div class="content">
        <div class="container">

          <h3 class="title is-3">Projects</h3>
          <p class="subtitle is-5">A list of significant things I have worked on</p>

          <hr>

          <article>
            <h5 class="title is-5">MappCPD Web Services</h5>
            <p class="subtitle is-6">Web services API written in Go, 2017 - ongoing</p>

            <ul>
              <li><i>purpose:</i> provide new functionality, improve performance &amp; facilitate future mobile/web app development</li>
              <li><i>my role:</i> development and integration</li>
              <li><i>tech:</i> Go, GraphQL, Heroku, MongoDB, MySQL</li>
            </ul>

            <p>
              As the existing monolithic application became more difficult to maintain, I felt it was time 
              to look at a <i>sensible</i> level of deconstruction of some of the backend processes.
            </p>

            <p>
              After some experimenting I settled on Go as it was relatively easy to get going with 
              and well-suited for the development of web services.
            </p>

          </article>

          <hr>

          <div class="notification">
            <p>
              The following projects were undertaken as contracts by our company,
              <i>Mesa</i> - a small but feisty team of 3-5. For these projects my role 
              was predominately project/tech lead and was split about 70% - 30% between 
              project-related activities and development.</p>
          </div>

          <article>
            <h5 class="title is-5">CSANZ MappCPD</h5>
            <p class="subtitle is-6">Membership &amp; CPD Management Application, 2013 - present</p>

            <ul>
              <li><i>purpose:</i> Replace existing software (iMIS), improve existing business processes</li>
              <li><i>my role:</i> {{ role1 }}</li>
              <li><i>tech:</i> PHP (Zend Framework), MySQL</li>
            </ul>

            <p>
              The initial project involved a 9-month reworking of the ASAR MapPCPD application (see below)
              and a substantial data migration over 3 months. A learning management system was also 
              developed and integrated into the application. MappCPD remains in operation and has streamlined 
              many business processes at the CSANZ.
            </p>
            <p>
              I currently manage this application in my role as IT Manager at CSANZ. This involves development 
              of new features, maintenance and operations. 
            </p>
          </article>

          <hr>

          <article>
            <h5 class="title is-5">Gelato Messina Ordering System</h5>
            <p class="subtitle is-6">E-commerce and fulfilment, 2013 - present</p>

            <ul>
              <li><i>purpose:</i> Online ordering, workflow and fulfilment</li>
              <li><i>my role:</i> {{ role1 }}</li>
              <li><i>tech:</i> PHP (Zend Framework), MySQL</li>
            </ul>

            <p>
              Development of a customer facing ecommerce site was backed by a workflow management, order fulfilment
              and reporting system. Complex product availability times and location rules made this a challenging project. 
            </p>
          </article>

          <hr>

          <article>
            <h5 class="title is-5">ASAR MappCPD</h5>
            <p class="subtitle is-6">Membership &amp; CPD Management Application, 2011 - 2015</p>

            <ul>
              <li><i>purpose:</i> Replace Filemaker Pro database, improve business processes</li>
              <li><i>my role:</i> {{ role1 }}</li>
              <li><i>tech:</i> PHP (Zend Framework), MySQL</li>
            </ul>

            <p>
              This was the first iteration of our MappCPD system and was a substantial LAMP-stack project developed with Zend Framework.
              The primary objective of this project was to aggregate and improve the existing business processes, and to this end it was a great success. 
            </p>
            <p>
              Membership renewals were processed in minutes rather than weeks, members could make payments online and automated housekeeping scripts were 
              used to raise and resolve administrative issues and to issue notifications and reminders to staff and members.
            </p>
            <p>
              The application was managed and maintained by Mesa until 2015.
            </p>
          </article>

          <hr>

          <article>
            <h5 class="title is-5">ABIA Accreditation Data System</h5>
            <p class="subtitle is-6">Survey and Reporting Application, 2012</p>

            <ul>
              <li><i>purpose:</i> Replace manual data collection and reporting processes</li>
              <li><i>my role:</i> {{ role1 }}</li>
              <li><i>tech:</i> PHP, MySQL</li>
            </ul>

            <p>
              ABIA collected feedback from customers about wedding industry suppliers. This data was then 
              collated into a series of ratings which were used as a basis for industry accreditations and 
              awards. Data was collected on paper forms, manually entered into spreadsheets and the 
              results calculated. This process took approximately 6 weeks to complete each year.
            </p>
            <p>
              We designed a web application that allowed suppliers to register their customers and then request 
              customer feedback via online surveys. The reporting component allowed for progressive/predictive 
              scores to be displayed, and was able to calculate end-of-year awards and accreditations in a matter 
              of seconds.
            </p>
          </article>

          <hr>

          <article>
            <h5 class="title is-5">JobNet</h5>
            <p class="subtitle is-6">Creative Agency Workflow Application, 2005 - 2011</p>

            <ul>
              <li><i>purpose:</i> Aggregation of multiple business processes and reporting into a single application</li>
              <li><i>my role:</i> {{ role1 }}</li>
              <li><i>tech:</i> PHP, MySQL</li>
            </ul>

            <p>
              JobNet was a custom PHP application written from scratch and provided both staff and client access. It was a comprehensive 
              workflow system that tracked a high volume of work. It included resource allocation, time-tracking, invoicing and a substantial 
              reporting feature to ensure compliance with client contracts.
            </p>

            <p>
              Mesa managed and updated the application until the agency closed down in 2011.
            </p>
          </article>

          <hr>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="content">
        <div class="container"></div>
      </div>
    </section>

    <hr>
  </div>
</template>

<script>
import Top from "~/components/top";

export default {
  components: {
    Top
  },
  data() {
    return {
      role1: "Project & tech lead, business & systems analysis, data modeling, deployment & operations"
    }
  }
};
</script>

<style scoped>
</style>
