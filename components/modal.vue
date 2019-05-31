<template>
    <div :class="{'modal': true, 'is-active': show()}">
      
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
                <p class="title is-4">{{ title }}</p>
                <p class="subtitle is-6">{{ subtitle }}</p>
              </div>
            </div>
          </div>

          <button class="delete" aria-label="close" @click="hide()"></button>
        </header>

        <section class="modal-card-body">

          <slot></slot>

        </section>
        <footer class="modal-card-foot"></footer>
      </div>
    </div>
</template>

<script>

export default {

    props: {
        show: {
            type: Function,
            required: true,
        },
        hide: {
            type: Function,
            required: true,
        },
        title: {
            type: String,
            required: false,
        },
        subtitle: {
            type: String,
            required: false,
        }
    },
}
</script>

<style>

</style>
