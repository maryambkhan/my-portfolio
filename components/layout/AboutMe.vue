<template>
  <div>
   <div class="text-center mt-4 text-pink-800 gap-4 text">
      <h1 class="sm:text-3xl md:text-4xl lg:text-4xl mb-4 mt-4">About Me</h1>
    </div>
     <!-- <pre> {{ abouts.data }} </pre>-->
			<div v-for="about in abouts.data" :key="about.id">
     <p class=" sm:text-sm
            md:text-xl
            text-pink-800 text-center text">
						{{about.attributes.detail}}
						</p>
		<div class="text-center mt-4 text-pink-800 gap-4 text">
		 <h1 class="sm:text-3xl md:text-4xl lg:text-4xl mb-4 mt-4">{{about.attributes.title}}</h1>
		</div>
		 <p  class="sm:text-sm
            md:text-xl
            text-pink-800 text-center text">
						{{about.attributes.info}}
						</p>
			</div>
      <!--Icons-->
          <section class="ml-8 text-violet-700 text-xl text-center mt-8">
            <a href="http://www.codepen.io/maryambkhan">
              <font-awesome-icon
                :icon="['fab', 'codepen']"
                class="hover:text-2xl"
              />
            </a>
            <a href="http://www.github.com/maryambkhan">
              <font-awesome-icon
                :icon="['fab', 'github']"
                class="ml-4 mr-4 hover:text-2xl"
            /></a>
            <a href="https://www.linkedin.com/in/maryam-khan-214a44232"
              ><font-awesome-icon
                :icon="['fab', 'linkedin']"
                class="hover:text-2xl"
              />
            </a>
          </section>
        </div>
</template>


<script>
import gql from "graphql-tag";

export default {
  data() {
    return {
      abouts: [],
    };
  },
  apollo: {
    abouts: {
      query: gql`
        query {
          abouts {
            data {
              id
              attributes {
                detail
                title
                info
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
      `,
    },
  },
};
</script>
