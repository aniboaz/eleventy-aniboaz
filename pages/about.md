---
title: About Me
metaDescription: This is a sample meta description. If one is not present in
  your page/post's front matter, the default metadata.desciption will be used
  instead.
date: 2017-01-01T00:00:00.000Z
permalink: /about/index.html
eleventyNavigation:
  key: About
  order: 1
---
<section class="about">
more about me

## I have been specializing in graphic design and animation for over 10 years.

### I'm social, autodidact, independent and very creative.

After studying animation and film at Sapir academic college, I started working as head of graphics @ Mizmor-HD video productions. Studied User Experience design @Netcraft. then got the opportunity to be a full-time GUI expert @ Inkod-hypera. Currently Product designer [@ Cloudinary.](https://aniboaz.netlify.app/#)

<img src="https://res.cloudinary.com/aniboaz/image/upload/c_scale,f_auto,q_90,w_560/buzy.jpg" alt="a picture of Boaz looking at the screen looking smart and all" class="fancy">
</section>

<style scoped>
.about img {
    float: right;
    margin: 2rem;    grid-area: aboutimage;
}
.about {
    padding: 2rem;
    display: grid;
    display: grid;
    grid-auto-columns: 1fr;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto auto auto auto auto;
    gap: 0px 0px;
    grid-template-areas:
        ". aboutimage"
        ". aboutimage"
        ". aboutimage"
        ". aboutimage"
        ". aboutimage";
}
  </style>