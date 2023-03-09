<template>
  <q-layout>
    <q-page>
      <div class="headings q-px-lg">
        <h2 class="text-weight-bolder">Headings</h2>
        <q-separator class="" />
        <div class="styles q-pt-xl">
          <p class="text-h1 text-grey-5">Headline 1</p>
          <p class="text-h2 text-grey-5">Headline 2</p>
          <p class="text-h3 text-grey-5">Headline 3</p>
          <p class="text-h4 text-grey-5">Headline 4</p>
          <p class="text-h5 text-grey-5">Headline 5</p>
          <p class="text-h6 text-grey-5">Headline 6</p>
          <q-separator class="q-mt-xl" />
        </div>
      </div>
      <div class="font-weights q-px-lg">
        <h2 class="text-weight-bolder">Font Weights</h2>
        <q-separator class="" />
        <div class="styles q-pt-xl">
          <p class="text-h2 text-grey-5 text-weight-light">text-weight-thin</p>
          <p class="text-h2 text-grey-5 text-weight-light">text-weight-light</p>
          <p class="text-h2 text-grey-5 text-weight-regular">
            text-weight-regular
          </p>
          <p class="text-h2 text-grey-5 text-weight-medium">
            text-weight-medium
          </p>
          <p class="text-h2 text-grey-5 text-weight-bold">text-weight-bold</p>
          <p class="text-h2 text-grey-5 text-weight-bolder">
            text-weight-bolder
          </p>
          <q-separator class="q-mt-xl" />
        </div>
      </div>
      <div class="css-helper-classes q-px-lg">
        <h2 class="text-weight-bolder">CSS Helper Classes</h2>
        <q-separator class="" />
        <div class="styles q-pt-xl">
          <p class="text-h2 text-grey-5 text-weight-light text-right">
            Align text to the right
          </p>
          <p class="text-h2 text-grey-5 text-weight-light text-left">
            Align text to the left
          </p>
          <p class="text-h2 text-grey-5 text-weight-regular text-center">
            Align text to the center
          </p>
          <p class="text-h2 text-grey-5 text-weight-medium text-justify">
            Text will be justified
          </p>
          <p class="text-h2 text-grey-5 text-weight-bold text-bold">
            Text will be in bold
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-italic">
            Text will be in italic
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-no-wrap">
            Non wrappable text (applies white-space: nowrap)
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-strike">
            Applies text-decoration: line-through
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-uppercase">
            Transform text to uppercase
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-lowercase">
            Transform text to lowercase
          </p>
          <p class="text-h2 text-grey-5 text-weight-bolder text-capitalize">
            Capitalize first letter of the text
          </p>
          <q-separator class="q-mt-xl" />
        </div>
      </div>
    </q-page>
  </q-layout>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
