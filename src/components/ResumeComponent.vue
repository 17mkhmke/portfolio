<template>
  <section class="container-fluid py5" id="Education">
 <div class="position-relative d-flex align-items-center justify-content-center">
          <h2 class="display-2 text-uppercase text-black">My Resume</h2>
        </div>
        <h3 class="mb-4">Education and Experience</h3>
        <div v-for="item in resume" :key="item" class="row align-items-center">
          <div class="col-lg">
            <div class="boarder-left border-black pt-2 pl-4 ml-2">
              <div class="position-relative ex-me mb-4">
                <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left:-35px; font-size: 22px;"></i>
                <h5 class="font-width-bold mb-1">{{ item.level }}</h5>
                <p class="mb-2"><strong>{{ item.institution }}</strong><small>{{ item.year }}</small></p>
                <p>{{ item.reflection }}</p>
              </div>
            </div>
          </div>
        </div>
      </section>
</template>

<script>
export default {
  name: 'ResumeComponent',
  data () {
    return {
      resume: [{
        institution: 'Mdingi J.S.S',
        level: 'Junior School',
        year: '2006 - 2008',
        reflection: 'Learned the basic behaviour of a human being and how to carry myself around other people basic form of creativity was implemented in my system.'
      },
      {
        institution: 'Masivuke Primary School',
        level: 'Primary School',
        year: '2009',
        reflection: 'Learned about the culture around the world basic logical thinking wa implemented into my system.'
      },
      {
        institution: 'Dominican Grimley School',
        level: 'Junior High',
        year: '2010 - 2016',
        reflection: 'Learned basic English through lip-reading advanced my logical thinking into more complex problems.'
      },
      {
        institution: 'Wynberg Boys High School',
        level: 'High School',
        year: '2017 - 2020',
        reflection: 'Mastered my public speaking skills and got introduced into more advanced subjects such as Information Technology'
      },
      {
        institution: 'Cilmor Cold Storage',
        level: 'Working Environment',
        year: '2021 - 2022',
        reflection: 'Mastered my computing literacy as a clerk exposed to the working environment'
      },
      {
        institution: 'Life Choices Coding Academy',
        level: 'College',
        year: '2022 - 2023',
        reflection: 'Advanced my computing and coding skills and acquired more coding languages'
      }
      ]
    }
  }
}
</script>
