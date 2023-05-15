<template>
  <div>
    <div class="alert alert-primary" role="alert">
      <strong>Primary!</strong> This is a primary alert—check it out!
    </div>

    <div class="alert alert-secondary" role="alert">
      <strong>Secondary!</strong> This is a secondary alert—check it out!
    </div>

    <div class="alert alert-info" role="alert">
      <strong>Info!</strong> This is a info alert—check it out!
    </div>

    <div class="alert alert-success" role="alert">
      <strong>Success!</strong> This is a success alert—check it out!
    </div>

    <div class="alert alert-danger" role="alert">
      <strong>Danger!</strong> This is a danger alert—check it out!
    </div>

    <div class="alert alert-warning" role="alert">
      <strong>Warning!</strong> This is a warning alert—check it out!
    </div>
    <textarea style="width: 100%; height: 650px" readonly>

      <div class="alert alert-primary" role="alert">
          <strong>Primary!</strong> This is a primary alert—check it out!
      </div>
      
      <div class="alert alert-secondary" role="alert">
          <strong>Secondary!</strong> This is a secondary alert—check it out!
      </div>
      
      <div class="alert alert-info" role="alert">
          <strong>Info!</strong> This is a info alert—check it out!
      </div>
      
      <div class="alert alert-success" role="alert">
          <strong>Success!</strong> This is a success alert—check it out!
      </div>
      
      <div class="alert alert-danger" role="alert">
          <strong>Danger!</strong> This is a danger alert—check it out!
      </div>
      
      <div class="alert alert-warning" role="alert">
          <strong>Warning!</strong> This is a warning alert—check it out!
      </div>
      </textarea
    >
    <div class="alert alert-warning" role="alert">
      <span class="alert-icon"><i class="ni ni-like-2"></i></span>
      <span class="alert-text"
        ><strong>Warning!</strong> This is a warning alert—check it out that has
        an icon too!</span
      >
    </div>
    <textarea style="width: 100%; height: 120px" readonly>
  <div class="alert alert-warning" role="alert">
      <span class="alert-icon"><i class="ni ni-like-2"></i></span>
      <span class="alert-text"><strong>Warning!</strong> This is a warning alert—check it out that has an icon too!</span>
  </div></textarea
    >
    <button type="button" class="btn btn-default">
      <span>Unread messages</span>
      <span class="badge badge-primary">24</span>
    </button>
    <button type="button" class="btn btn-primary">
      <span>Notifications</span>
      <span
        class="badge badge-sm badge-circle badge-danger border border-white border-2"
        >4</span
      >
    </button>

    <span class="badge bg-gradient-primary">Primary</span>
    <span class="badge bg-gradient-secondary">Secondary</span>
    <span class="badge bg-gradient-info">Info</span>
    <span class="badge bg-gradient-success">Success</span>
    <span class="badge bg-gradient-danger">Danger</span>
    <span class="badge bg-gradient-warning">Warning</span>
  </div>
</template>

<script>
export default {
  name: "BootstrapvueDocsView",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped></style>
