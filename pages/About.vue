<template>
  <div class="container animate__animated animate__fadeIn">
    <div class="row">
      <div class="col-md-6">
        <div class="about">
          <h1 class="line-after">About Me</h1>
          <h4 class="mt-4">Hey 👋</h4>
          <p>
            My name is Luthfi Hakim, I am a <b>Backend Engineer</b> and <b>Cloud Engineer</b>
            I specialize in <b>Designing</b> and <b>Implementing</b> scalable <b>Backend Systems</b> and <b>Cloud Infrastructure</b>.
          </p>
          <p>
            I have <b>{{ currYear - startYear }}+ years experience</b> in
            designing and implementing backend systems. Plus I am an agile
            learner, I learn new cool stuffs everyday. Love coffee ☕ and code 😇.
          </p>
          <h4 class="mt-5">Tech Stacks</h4>
          <p>Below are some of the technologies I use daily:</p>
          <div class="animate__animated animate__fadeInUp">
            <div class="col">
              <ul style="list-style-type: circle;">
                <li>Golang</li>
                <li>Typescript</li>
                <li>Nest JS</li>
              </ul>
            </div>
            <div class="col">
              <ul style="list-style-type: circle;">
                <li>Docker</li>
                <li>Postman</li>
                <li>Nginx</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <img
          src="@/assets/working.png"
          alt="About Illustration"
          class="abt-img"
        />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      startYear: 2022,
      currYear: new Date().getFullYear(),
    };
  },
  head: {
    title: "About 🕵️‍♂️ - Luthfi Hakim",
    meta: [
      {
        hid: "description",
        name: "description",
        content: `Hey there 👋 My name is Luthfi Hakim, specialize in Designing and Implementing scalable Backend Systems and Cloud Infrastructure. With a strong foundation in server-side technologies and cloud platforms, I ensure robust and efficient solutions that meet the demands of modern applications.`
      }
    ]
  }
};
</script>
<style scoped>
.container {
  margin-top: 140px;
  text-align: left;
}
.line-after {
  overflow: hidden;
}
.line-after::after {
  content: "";
  display: inline-block;
  height: 0.5em;
  vertical-align: bottom;
  width: 100%;
  margin-right: -100%;
  margin-left: 10px;
  border-top: 2px solid rgb(211, 46, 46);
}
.abt-img {
  width: inherit;
  height: inherit;
  border-radius: 5px;
}
</style>
