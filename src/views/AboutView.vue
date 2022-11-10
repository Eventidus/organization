<template>
  <swiper
    :modules="modules"
    navigation
    loop
    :autoplay="{ delay: 3000 }"
    :pagination="{ clickable: true }"
    :scrollbar="{ draggable: true }"
  >
    <swiper-slide
      ><img src="../assets/images/members/wulijie.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/funiuhai.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/hejunfu.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/liukaiwen.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/songxiangyi.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/wanghongxiang.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/wangyiyu.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/xukaifeng.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/yangzhuofan.png" alt=""
    /></swiper-slide>
    <swiper-slide
      ><img src="../assets/images/members/zhangsiyuan.png" alt=""
    /></swiper-slide>
  </swiper>
  <img src="../assets/images/introduction.png" alt="" />
  <p>
    DEAF无国界组织于2022年7月5日正式成立，经过初步筹备和发展，现有30名听障青年经过多重考核后被接纳为正式成员。本组织是一家以高校与社会上的多元化听障青年组成的公益性组织，并积极面向国际。组织致力于通过多维度和多层次的对策，改善当下全球地区的听障青年和其他类型青年所面对的社会处境。
    DEAF无国界组织旨在希望以自身能力通过创新和创业，为听障青年赋能，支持听障青年的可持续发展，并鼓励手语者、口语者、双语者等多样性听障人士融合，实现全社会建设。
    被吸收后的听障青年会员将与组织内技术型专职、文化创新型、领导型和商业领域的其他成员一道，共同探索建设全民的包容性社会。
    迄今为止，DEAF无国界组织涉及的领域十分广泛，并跟随中国听障青年的步伐不断发展完善，立足于中国放眼于世界。协会主要专注于四个领域：包容平等和可持续，自立与培养明日的领导力，多元化与无国界合作，信息无障碍建设——作为促进中国听障青年和其他国家听障青年之间建立发展伙伴关系国际平台。
  </p>
  <img src="../assets/images/goal.png" alt="" />
  <p>
    DEAF无国界组织的工作目标是为世界听障青年提供技术方面的指导和一些基础性的技能培训，与多样性群体合作改进信息无障碍建设。致力于推动听障青年的可持续发展，协助听障青年提高社会生存能力，帮助世界各国的听障青年们创造更美好的生活。
    组织建立以来，计划充分利用全球网络和发展经验，支持听障青年制定应对发展挑战的解决之道，并为听障青年们开展国际合作和参与全球发展提供协助。目前在大中华地区的重点工作领域为：为听障青年科普，促进听障青年资源流通，改善听障青年之间个体差异过大的现象。
  </p>
  <img src="../assets/images/organization.png" alt="" />
  <p>
    弘扬人道主义思想，发展无障碍事业，促进聋人平等和充分参与社会生活，共享社会经济和物质文化交流。认真履行民间组织的职能，坚持对广大成员进行团结、帮助、引导、教育。联合全球有志于此的听障人士，促进成员之间的资源互通，保障成员的合法权益，促进组织的繁荣和发展，帮助每一个听障朋友立足社会发展。通过教育、科学及文化来促进各国聋人之间的合作，贡献出和平与安全的良好环境，本组织认同联合国宪章，以正义、法治及公平为主要精神，尊重世界各国聋人，积极传播聋人文化，保护成员不因种族、性别、语言以及其他具体表现而遭受歧视，保障成员基本人权不受侵害。
  </p>
</template>
<script>
// import Swiper core and required modules
import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from "swiper";

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";

// Import Swiper styles
export default {
  components: {
    Swiper,
    SwiperSlide,
  },

  setup() {
    return {
      modules: [Navigation, Pagination, Scrollbar, A11y, Autoplay],
    };
  },
};
</script>
