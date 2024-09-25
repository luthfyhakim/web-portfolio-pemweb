<template>
  <b-row style="margin-left: 0;margin-right: 0;">
    <b-col md="4">
      <b-img
        :src="avatar"
        id="avatar-img"
        alt="Aulia Luthfi Hakim"
        @mouseenter="changeAvatar"
        @mouseleave="changeAvatar"
      />
    </b-col>

    <b-col md="8">
      <h2 class="intro animate__animated animate__fadeInUp animate__fast">
        Hi 👋,
        <br />I<span>'m Aulia Luthfi&nbsp;Hakim</span>.
      </h2>

      <div class="col-md-10 info">
        A <b>Backend Engineer</b> and <b>Cloud Engineer</b>
        <br />
        I specialize in <b>Designing</b> and <b>Implementing</b> scalable <b>Backend Systems</b> and <b>Cloud Infrastructure</b>.
        With a strong foundation in server-side technologies and cloud platforms,
        I ensure robust and efficient solutions that meet the demands of modern applications.
        <br />
        <b-button
          class="action-btn animate__animated animate__wobble animate__delay-4s animate__fast"
          to="/projects"
        >
          Explore >
        </b-button>

        <b-button class="action-btn" to="/contact" variant="primary">
          Get In Touch
        </b-button>

        <!-- .SOCIAL LINKS SECTION -->
        <div
          class="social-icons animate__animated animate__fadeInUp animate__delay-1s"
        >
          <social-link :to="socialLinks.github">
            <GithubIcon />
          </social-link>

          <social-link :to="socialLinks.linkedin">
            <LinkedinIcon />
          </social-link>

          <social-link :to="socialLinks.twitter">
            <TwitterIcon />
          </social-link>

          <social-link :to="socialLinks.instagram">
            <InstagramIcon />
          </social-link>

          <social-link :to="socialLinks.mail">
            <MailIcon />
          </social-link>
        </div>
      </div>
    </b-col>
  </b-row>
</template>

<script>
import GithubIcon from "vue-ionicons/dist/logo-github.vue";
import LinkedinIcon from "vue-ionicons/dist/logo-linkedin.vue";
import TwitterIcon from "vue-ionicons/dist/logo-twitter.vue";
import InstagramIcon from "vue-ionicons/dist/logo-instagram.vue";
import MailIcon from "vue-ionicons/dist/md-mail.vue";

export default {
  components: {
    GithubIcon,
    LinkedinIcon,
    TwitterIcon,
    InstagramIcon,
    MailIcon
  },

  data() {
    return {
      avatar: require("@/assets/avatar-1.webp"),
      // ADD YOUR SOCIAL LINKS HERE 👇
      socialLinks: {
        github: "https://github.com/luthfyhakim",
        linkedin: "https://linkedin.com/in/luthfyhakim",
        twitter: "https://twitter.com/luthfyhakim_",
        instagram: "https://instagram.com/fy.hakim_",
        mail: "mailto:luthfyhakim250404@gmail.com",
      }
    };
  },

  head: {
    title: "Web Portfolio ⚡ - Luthfi Hakim",
    meta: [
      {
        hid: "description",
        name: "description",
        content:
          "Luthfi Hakim specialize in Designing and Implementing scalable Backend Systems and Cloud Infrastructure. With a strong foundation in server-side technologies and cloud platforms, I ensure robust and efficient solutions that meet the demands of modern applications."
      },
      {
        hid: "og:title",
        name: "og:title",
        content: "Web Portfolio ⚡ - Luthfi Hakim"
      },
      {
        property: "og:description",
        content:
          "Luthfi Hakim specialize in Designing and Implementing scalable Backend Systems and Cloud Infrastructure. With a strong foundation in server-side technologies and cloud platforms, I ensure robust and efficient solutions that meet the demands of modern applications."
      },
      {
        hid: "og:image",
        name: "og:image",
        content: require("@/assets/coding.png")
      }
    ]
  },
  methods: {
    changeAvatar() {
      if (this.avatar == require("@/assets/avatar-2.webp")) {
        this.avatar = require("@/assets/avatar-1.webp");
      } else {
        this.avatar = require("@/assets/avatar-2.webp");
      }
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start();

      setTimeout(() => this.$nuxt.$loading.finish(), 500);
    });
  }
};
</script>
