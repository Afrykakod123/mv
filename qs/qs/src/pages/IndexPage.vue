<template>
  <q-page class="flex flex-center">
    <q-list bordered>
      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal"
              >You can learn any language that you want</q-item-label
            >
            <q-item-label caption lines="2"
              >Audio pronunciation for common languages via Google
              Translate</q-item-label
            >
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Multi languages</q-item-label>
            <q-icon class="q-pt-xs" name="language" />
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              You can add words or import a dictionary from excel file.
              Different languages (Portuguese, Spanish, French, German, Chinese,
              Italian ect.)
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-separator />

      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal"
              >Google Translate provides multiple possible translations along
              with rating of how common they are</q-item-label
            >
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Google Translate</q-item-label>
            <q-icon class="q-pt-xs" name="g_translate" color="gray" />
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              Tap notification , translation , quiz question to get Google
              Translation
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal">Category words</q-item-label>
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Category words</q-item-label>
            <q-icon class="q-pt-xs" name="category" color="gray" />
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              You can make a categories and learn only the words in this
              category
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-separator />
      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal"
              >Vocabulary notifier with smartwatch mode</q-item-label
            >
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Vocabulary notifier</q-item-label>
            <q-icon class="q-pt-xs" name="notifications_active" color="gray" />
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              You can set tune the number of notifications and frequency
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-separator />
      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal">Excel import/export</q-item-label>
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Excel import/export </q-item-label>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              x="0px"
              y="0px"
              width="27"
              height="27"
              viewBox="0 0 24 24"
              style="fill: rgb(132, 71, 202)"
            >
              <path
                d="M 12 3 L 2 5 L 2 19 L 12 21 L 12 3 z M 14 5 L 14 7 L 16 7 L 16 9 L 14 9 L 14 11 L 16 11 L 16 13 L 14 13 L 14 15 L 16 15 L 16 17 L 14 17 L 14 19 L 21 19 C 21.552 19 22 18.552 22 18 L 22 6 C 22 5.448 21.552 5 21 5 L 14 5 z M 18 7 L 20 7 L 20 9 L 18 9 L 18 7 z M 4.1757812 8.296875 L 5.953125 8.296875 L 6.8769531 10.511719 C 6.9519531 10.692719 7.0084063 10.902625 7.0664062 11.140625 L 7.0917969 11.140625 C 7.1247969 10.997625 7.1919688 10.779141 7.2929688 10.494141 L 8.3222656 8.296875 L 9.9433594 8.296875 L 8.0078125 11.966797 L 10 15.703125 L 8.2714844 15.703125 L 7.1582031 13.289062 C 7.1162031 13.204062 7.0663906 13.032922 7.0253906 12.794922 L 7.0097656 12.794922 C 6.9847656 12.908922 6.934375 13.079594 6.859375 13.308594 L 5.7363281 15.703125 L 4 15.703125 L 6.0605469 11.996094 L 4.1757812 8.296875 z M 18 11 L 20 11 L 20 13 L 18 13 L 18 11 z M 18 15 L 20 15 L 20 17 L 18 17 L 18 15 z"
              ></path>
            </svg>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              Import Execel file .xlsx 2 or 4 columns, export to Excel file
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-separator />
      <q-expansion-item group="somegroup">
        <template v-slot:header>
          <q-item-section>
            <q-item-label class="text-teal">Random quizzes</q-item-label>
          </q-item-section>
          <q-item-section side top class="text-teal">
            <q-item-label caption>Quizzes</q-item-label>
            <q-icon class="q-pt-xs" name="quiz" color="gray" />
          </q-item-section>
        </template>
        <q-card>
          <q-card-section
            ><h2 class="text-h3 text-blue-grey-8 ">
              Questions based on a selected category
            </h2>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-separator />
    </q-list>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
