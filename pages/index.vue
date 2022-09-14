<template>
  <v-main fluid>
    <v-row justify="left" align="center" class="headline">
      <h2>34 results for "Vuejs"</h2>
    </v-row>
    <v-row >
      <v-col cols="12" sm="8" md="3" class="filters">
        <!-- <v-expansion-panels>
          <v-expansion-panel>
            <v-expansion-panel-header> Item </v-expansion-panel-header>
            <v-expansion-panel-content>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </v-expansion-panel-content>
          </v-expansion-panel>

          <v-expansion-panel>
            <v-expansion-panel-header> Item </v-expansion-panel-header>
            <v-expansion-panel-content>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </v-expansion-panel-content>
          </v-expansion-panel>

          <v-expansion-panel>
            <v-expansion-panel-header> Item </v-expansion-panel-header>
            <v-expansion-panel-content>
              <v-checkbox
                class="m-0"
                v-model="checkbox"
                :label="`Checkbox 1: ${checkbox.toString()}`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                :label="`Checkbox 1: ${checkbox.toString()}`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                :label="`Checkbox 1: ${checkbox.toString()}`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                :label="`Checkbox 1: ${checkbox.toString()}`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                :label="`Checkbox 1: ${checkbox.toString()}`"
              ></v-checkbox>
            </v-expansion-panel-content>
          </v-expansion-panel>

          <v-expansion-panel>
            <v-expansion-panel-header> Item </v-expansion-panel-header>
            <v-expansion-panel-content>
              <v-list shaped>
                <v-list-item-group v-model="model" multiple>
                  <template v-for="(item, i) in items">
                    <v-divider v-if="!item" :key="`divider-${i}`"></v-divider>

                    <v-list-item
                      v-else
                      :key="`item-${i}`"
                      :value="item"
                      active-class="deep-purple--text text--accent-4"
                    >
                      <template v-slot:default="{ active }">
                        <v-list-item-content>
                          <v-list-item-title v-text="item"></v-list-item-title>
                        </v-list-item-content>

                        <v-list-item-action>
                          <v-checkbox
                            :input-value="active"
                            color="deep-purple accent-4"
                          ></v-checkbox>
                        </v-list-item-action>
                      </template>
                    </v-list-item>
                  </template>
                </v-list-item-group>
              </v-list>
            </v-expansion-panel-content>
          </v-expansion-panel>

          <v-expansion-panel>
            <v-expansion-panel-header> Item </v-expansion-panel-header>
            <v-expansion-panel-content>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels> -->


        <v-list>
      <!-- <v-list-item>
        <v-list-item-icon>
          <v-icon>mdi-apps</v-icon>
        </v-list-item-icon>

        <v-list-item-title>Filters</v-list-item-title>
      </v-list-item> -->

      <!-- Programming Filter  -->
      <!-- <v-list-group
        :value="true"
        prepend-icon="mdi-account-circle"
      >
        <template v-slot:activator>
          <v-list-item-title>Programming</v-list-item-title>
        </template>

              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`All (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Frontend (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Backend (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Android (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Flutter (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`IOS (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Web Design (200)`"
              ></v-checkbox>
      </v-list-group> -->

      <!-- Language Courses Filter  -->
      <!-- <v-list-group
        :value="true"
        prepend-icon="mdi-account-circle"
      >
        <template v-slot:activator>
          <v-list-item-title>Languages</v-list-item-title>
        </template>

              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`All (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`English (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Russian (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Arabic (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Korean (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`German (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`French (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Chinese (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Turkish (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Spanish (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Italian (200)`"
              ></v-checkbox>
      </v-list-group> -->

      <!-- Finance Courses Filter -->
      <!-- <v-list-group
        :value="true"
        prepend-icon="mdi-account-circle"
      >
        <template v-slot:activator>
          <v-list-item-title>Finance </v-list-item-title>
        </template>

              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`All (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`ACCA (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Accounting (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Mental Algebra (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Flutter (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`IOS (200)`"
              ></v-checkbox>
              <v-checkbox
                v-model="checkbox"
                style="height: 35px"
                class="pl-3"
                :label="`Web Design (200)`"
              ></v-checkbox>
      </v-list-group> -->
      </v-list>

      <h3>Filters</h3>
      <hr>
      <v-list>
      <v-list-group
        v-for="item in items"
        :key="item.title"
        v-model="item.active"
        :prepend-icon="item.action"
        no-action
      >
        <template v-slot:activator>
          <v-list-item-content>
            <v-list-item-title v-text="item.title"></v-list-item-title>
          </v-list-item-content>
        </template>
        
        <v-list-item
          v-for="child in item.items"
          :key="child.title"
        >
          <v-list-item-content class="filter-option">
            <v-checkbox
                v-model="checkbox"
                style="height: 35px; display: inline-block;"
              ></v-checkbox>
            <v-list-item-title
            style="display: inline-block;"
            v-text="`${child.title} (23)`"
            ></v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <hr>
      </v-list-group>
    </v-list>



      </v-col>
      <v-col cols="12" md="9" class="results">
        <v-card
          elevation="2"
          rounded="true"
          outlined
          shaped
          tile
          rounded-xl
          v-for="card in 10"
          :key="card"
          class="card mb-3"
        >
          <v-img
            class="white--text align-end"
            height="auto"
            width="260px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          />
          <div class="card-elements">
            <v-card-title>Cambridge Learning Center</v-card-title>
          <v-card-subtitle
            >This is one of the best learning centers to learn english
            language</v-card-subtitle
          >
          <v-card-text
            >Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Repudiandae corporis vero molestias odio, corrupti
            porro?</v-card-text
          >
          <v-card-actions>
            <v-btn elevation="2" color="blue">Add to Wishlist</v-btn>
            <v-btn elevation="2" color="blue">Read More</v-btn>
          </v-card-actions>
          </div>
        </v-card>
      </v-col>
    </v-row>
  </v-main>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      checkbox: true,
      items: ['Dog Photos', 'Cat Photos', '', 'Potatoes', 'Carrots'],
      model: ['Carrots'],
      items: [
        {
          action: 'mdi-code-braces',
          items: [
            { title: 'All' },
            { title: 'Comp. Basics' },
            { title: 'Frontend' },
            { title: 'Backend' },
            { title: 'Android' },
            { title: 'Flutter' },
            { title: 'IOS' },
            { title: 'Web Design' },
            { title: 'Animation' },
          ],
          title: 'Programming',
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'English' },
            { title: 'Arabic' },
            { title: 'Korean' },
            { title: 'German' },
            { title: 'French' },
            { title: 'Chinese' },
            { title: 'Turkish' },
            { title: 'Spanish' },
            { title: 'Uzbek' },
            { title: 'Italian' },
          ],
          title: 'Languages',
          // All, English, Russian, Arabic, Korean, German, French, Chinese, Turkish, Spanish, Ona Tili, Italian
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'ACCA' },
            { title: 'Accounting' },
          ],
          title: 'Finance',
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'Soft Skills' },
            { title: 'Business Training' },
            { title: 'Psychology' },
          ],
          title: 'Personal Development',
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'Marketing' },
            { title: 'SMM' },
            { title: 'Design' },
            { title: 'Targeting' },
            { title: 'Copywriting' },
            { title: 'Story Making' },
          ],
          title: 'Marketing',
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'English' },
            { title: 'History' },
            { title: 'Math' },
            { title: 'Biology' },
            { title: 'Chemistry' },
            { title: 'Ona tili' },
            { title: 'Majburiy fan' },
            { title: 'President Maktabi' }

          ],
          title: 'Abiturient',
        },
        {
          action: 'mdi-chat',
          active: true,
          items: [
            { title: 'All' },
            { title: 'IELTS' },
            { title: 'CEFR' },
            { title: 'SAT' },
            { title: 'GMAT' },
            { title: 'GRE' },
            { title: 'National Certificates' },
            { title: 'ACCA' },
            { title: 'Duolingo' }

          ],
          title: 'Certifications',
        },
      ],
    }
  },
}
</script>

<style scoped>
.headline {
  /* background: wheat; */
  padding: 20px 0;
  font-weight: 600;
  color: #555;
}
.filters {
  /* background: rgb(200, 220, 255); */
  border-radius: 12px 0 0 12px;
}

.results {
  /* background: rgb(200, 220, 255); */
  border-radius: 0 12px 12px 0;
}

v-main {
  padding: 0;
}

.card {
  display: flex;
}

.v-input--selection-controls.v-input {
  margin: 0;
  /* border: 1px solid #555; */
}

.v-list-item__content{
  display: block;
  padding: 0;
}
</style>
