<template>
  <b-container class="page  animate__animated animate__fadeIn">
    <h2>Recent Articles</h2>
    <b-row class="articles">
      <div class="col-md-6">
        <div>
          <b-card-group deck>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
          </b-card-group>
        </div>
        <div>
          <b-card-group deck>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
          </b-card-group>
        </div>
      </div>
      <div class="col-md-6">
        <div>
          <b-card-group deck>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
          </b-card-group>
        </div>
        <div>
          <b-card-group deck>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
            <b-card
              img-src=""
              img-alt="ini gambar"
              img-top
              tag="article"
              class="mb-2"
            >
              <h4>Title Project</h4>
              <hr />
              <b-card-text>Deskripsi Project</b-card-text>

              <b-button
                rel="noopener"
                variant="default"
                >Read More..</b-button
              >
            </b-card>
          </b-card-group>
        </div>
      </div>
    </b-row>
  </b-container>
</template>
<script>
import HeartIcon from "vue-ionicons/dist/md-heart.vue";
export default {
  components: { HeartIcon },
  head: {
    title: "Recent Articles 📚 - Luthfi Hakim",
    meta: [
      {
        hid: "description",
        name: "description",
        content: "Read articles written by Luthfi Hakim, articles include topics under web development (html, css, javascript), mobile app development and many more."
      },
      {
        hid: "og:title",
        name: "og:title",
        content: "Recent Articles 📚 - Luthfi Hakim"
      },
      {
        property: "og:description",
        content: "Read articles written by Luthfi Hakim, articles include topics under web development (html, css, javascript), mobile app development and many more."
      },
    ]
  },
};
</script>
<style scoped>
.container {
  margin-top: 120px;
}
.row {
  margin-top: 40px;
}
.spinner-border {
  margin-top: 40px;
}
.card {
  text-align: left;
  color: #000;
}
</style>
