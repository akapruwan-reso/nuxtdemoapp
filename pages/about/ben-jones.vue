<template>
  <div>
    <h1>About Ben Jones</h1>
    <p>This is a nested route, contained in a <code>nuxt</code> tag in the About page</p>
  </div>
</template>

<script>
  export default {
    mounted() {
    const script = document.createElement("script");
    script.src="https://js.hsforms.net/forms/v2.js";
    document.body.appendChild(script);
    script.addEventListener("load", () => {
      if (window.hbspt) {
        window.hbspt.forms.create({
          portalId: "42449409",
          formId: "5a267040-7219-464e-83f9-4a3d9a49f39a",
          target: "#hubspotForm"
        })
      }
    })
  }
}
</script>