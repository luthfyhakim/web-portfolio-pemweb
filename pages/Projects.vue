<template>
  <div class="about page  animate__animated animate__fadeIn">
    <h2>Recent Project</h2>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>

          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>
        </div>

        <div class="col-md-4">
          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>

          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>
        </div>

        <div class="col-md-4">
          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>

          <h2 class="mt-3" style="text-align: left;">
            Project Title
            <hr class="dope" />
          </h2>
          <b-card class="mt-3 mb-3 text-left text-dark">
            <p>Project Deskripsi</p>
            <b-link href=""
              >Check it out! <LinkIcon style="color: #000;"
            /></b-link>
            <hr />
            <b-link href=""
              >View source code <GithubIcon style="color: #000;"
            /></b-link>
          </b-card>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import LinkIcon from "vue-ionicons/dist/md-link.vue";
import GithubIcon from "vue-ionicons/dist/logo-github.vue";

export default {
  components: {
    GithubIcon,
    LinkIcon
  },

  head: {
    title: "Recent Projects 💻 - Luthfi Hakim",
    meta: [
      {
        hid: "description",
        name: "description",
        content:
          "View all the recents open-sourced projects built with ♥ by Luthfi Hakim, open-sourced means this project source code are publicly available for everyone to use or modify."
      },
      {
        hid: "og:title",
        name: "og:title",
        content: "Recent Projects 💻 - Luthfi Hakim"
      },
      {
        property: "og:description",
        content:
          "View all the recents open-sourced projects built with ♥ by Luthfi Hakim, open-sourced means this project source code are publicly available for everyone to use or modify."
      },
      {
        hid: "og:image",
        name: "og:image",
        content: require("@/assets/man-computer.png")
      }
    ]
  }
};
</script>
<style scoped>
.row {
  margin-top: 70px;
}
.project-cover {
  width: inherit;
  border-radius: 3px;
}
hr.dope {
  border: 0;
  width: 90px;
  border-top: 2px solid #dc3545;
  text-align: left;
  margin: initial;
  margin-top: 7px;
  margin-left: 5px;
}
</style>
