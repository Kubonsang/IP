<template>
  <div id="app">
    <NameCard></NameCard>
    <AboutMe></AboutMe>
    <Info></Info>
    <Contact></Contact>
    <Education></Education>
    <Project></Project>
  </div>
</template>

<script>
// 포트폴리오 제목 컴포넌트
import NameCard from './NameCard.vue'
// 자기 소개 컴포넌트
import AboutMe from './AboutMe.vue'
// 정보 컴포넌트
import Info from './Info.vue'
// 연락처 컴포넌트
import Contact from './Contact.vue'
// 교육 컴포넌트
import Education from "./Education.vue"
// 프로젝트 컴포넌트
import Project from "./Project.vue"
export default {
  name: 'App',
  components: {
    NameCard,
    Info,
    AboutMe,
    Contact,
    Education,
    Project,
  }
}
</script>