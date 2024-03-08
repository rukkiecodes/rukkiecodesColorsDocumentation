<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <h1>Overview</h1>
        <p>
          rukkiecodes-colors is an npm library designed to provide developers with a diverse range of colors in various
          shades. This library is tailored for ease of use, enabling developers to effortlessly integrate colors into
          their JavaScript or TypeScript projects. With a wide array of readily available colors, rukkiecodes-colors
          simplifies the process of selecting and using colors in your applications.
        </p>
      </v-col>

      <v-col cols="12" class="mt-10">
        <h1>Installation</h1>

        <p>
          You can install rukkiecodes-colors using either npm or yarn. Choose the package manager that suits your
          project:
        </p>

        <h3 class="mt-5">Using npm</h3>
        <v-card flat color="blue-grey">
          <v-card-text>
            <code>npm install rukkiecodes-colors</code>
          </v-card-text>
        </v-card>

        <h3 class="mt-5">Using yarn</h3>
        <v-card flat color="blue-grey">
          <v-card-text>
            <code>yarn add rukkiecodes-colors</code>
          </v-card-text>
        </v-card>
      </v-col>


      <v-col cols="12" class="mt-10">
        <h1>Usage</h1>

        <p>
          Once installed, you can import the colors from rukkiecodes-colors into your JavaScript or TypeScript files.
          The library provides a variety of color palettes, each with a range of shades. Below is an example of how you
          can import and use the colors:
        </p>

        <v-card color="blue-grey">
          <v-card-text>
            <pre><code class="language-javascript">
    // Importing a color palette
    import { red, blue, green } from 'rukkiecodes-colors';

    // Accessing color properties
    console.log('Red Color:', red.hex); // Output: #FF0000
    console.log('Blue Color:', blue.name); // Output: blue
    console.log('Green Color:', green.hex); // Output: #00FF00
  </code></pre>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" class="mt-10">
        <h1>Color Palettes</h1>

        <Primarry />
        <Offwhite />
        <Grey />
        <Red />
        <Pink />
        <Green />
        <Teal />
        <Blue />
        <Indigo />
        <SkyBlue />
        <OceanBlue />
        <Amber />
        <Gold />
        <Purple />
        <Brown />
        <Khaki />
        <Yellow />
        <Silver />
        <SandBlack />
        <SpaceGrey />
        <Copper />
        <Aluminum />
      </v-col>
    </v-row>
  </v-container>
</template>


<script setup>
import Primarry from './components/Primarry.vue'
import Offwhite from './components/Offwhite.vue'
import Grey from './components/Grey.vue'
import Red from './components/Red.vue'
import Green from './components/Green.vue'
import Teal from './components/Teal.vue'
import Blue from './components/Blue.vue'
import Indigo from './components/Indigo.vue'
import SkyBlue from './components/SkyBlue.vue'
import OceanBlue from './components/OceanBlue.vue'
import Amber from './components/Amber.vue'
import Purple from './components/Purple.vue'
import Pink from './components/Pink.vue'
import Gold from './components/Gold.vue'
import Brown from './components/Brown.vue'
import Khaki from './components/Khaki.vue'
import Yellow from './components/Yellow.vue'
import Silver from './components/Silver.vue'
import SandBlack from './components/SandBlack.vue'
import SpaceGrey from './components/SpaceGrey.vue'
import Copper from './components/Copper.vue'
import Aluminum from './components/Aluminum.vue'
</script>
