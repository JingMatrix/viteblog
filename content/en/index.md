---
title: Homepage
sidebar: false
layout: page
---

<script>
import CardImg from "../../components/card/img.vue";
export default {
  components: {
    CardImg,
  },
  created() {
    this.mathfeature = {
      title: "do math",
      description:
        "I like the idea that mathematics is the art of giving the same name to different things. When exploring new concepts there, I feel that I am finding connections between mysteries.",
      content: [
        {
          title: "M2 Internship Report",
          description: "Barycenter of two countries in the image above",
          img: "/img/barycenter.png",
          link: "https://drive.google.com/file/d/1DgcO-M13q4x_sCYsJTPjR9Wx154C0tnh/view",
          tags: ["Riemannian Geometry"],
        },
        {
          title: "M1 Topology Homework",
          description: "A homework of algebraic topology",
          img: "/img/function_with_hole.png",
          link: "/pdf/DM_topology_Jianyu_MA.pdf",
          tags: ["Latex Draw", "Topology"],
        },
      ],
    };
  },
};
</script>

<CardImg :features="mathfeature" />
