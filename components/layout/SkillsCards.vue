<template>
  <div>
    <section>
      <h1 class="text-center text-pink-800 text-2xl font-semibold mt-10 text">
        SKILLS
      </h1>
      <div class="flex flex-wrap justify-center mt-8 text-center">
        <div
          class="
            bg-slate-200
            gap-2
            mx-6
            my-4
            px-4
            py-6
            w-52
            md:56
            lg:w-64
            rounded-md
          "
        >
          <!-- <pre v-if="skills.data">{{skills.data[0].attributes.title}}</pre>-->
          <img
            v-if="skills.data"
            :src="`http://localhost:1337${skills.data[0].attributes.image.data.attributes.url}`"
            class="h-50"
          />
          <h1 class="text-xl text-pink-800 hover:underline" v-if="skills.data">
            {{ skills.data[0].attributes.title }}
          </h1>
          <p v-if="skills.data">{{ skills.data[0].attributes.detail }}</p>
        </div>
        <div
          class="
            bg-slate-200
            gap-2
            mx-6
            my-4
            px-4
            py-6
            w-52
            md:56
            lg:w-64
            rounded-md
          "
        >
          <img
            v-if="skills.data"
            :src="`http://localhost:1337${skills.data[1].attributes.image.data.attributes.url}`"
            class="h-50"
          />
          <h1 class="text-xl text-pink-800 hover:underline" v-if="skills.data">
            {{ skills.data[1].attributes.title }}
          </h1>
          <p v-if="skills.data">{{ skills.data[1].attributes.detail }}</p>
        </div>
        <div
          class="
            bg-slate-200
            gap-2
            mx-6
            my-4
            px-4
            py-6
            w-52
            md:56
            lg:w-64
            rounded-md
          "
        >
          <img
            v-if="skills.data"
            :src="`http://localhost:1337${skills.data[2].attributes.image.data.attributes.url}`"
            class="h-50"
          />
          <h1 class="text-xl text-pink-800 hover:underline" v-if="skills.data">
            {{ skills.data[2].attributes.title }}
          </h1>
          <p v-if="skills.data">{{ skills.data[2].attributes.detail }}</p>
        </div>
        <div
          class="
            bg-slate-200
            gap-2
            mx-6
            my-4
            px-4
            py-6
            w-52
            md:56
            lg:w-64
            rounded-md
          "
        >
          <img
            v-if="skills.data"
            :src="`http://localhost:1337${skills.data[3].attributes.image.data.attributes.url}`"
            class="h-50"
          />
          <h1 class="text-xl text-pink-800 hover:underline" v-if="skills.data">
            {{ skills.data[3].attributes.title }}
          </h1>
          <p v-if="skills.data">{{ skills.data[3].attributes.detail }}</p>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import gql from 'graphql-tag';

export default {
  data() {
    return {
      skills: [],
    }
  },
  apollo: {
    skills: {
      query: gql`
        query {
          skills {
            data {
              attributes {
                title
                detail
                image {
                  data {
                    attributes {
                      url
                    }
                  }
                }
              }
            }
          }
        }
      `
    }
  }
}
</script>