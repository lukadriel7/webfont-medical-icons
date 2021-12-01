Webfont Medical Icons
=====================

# Description
This library is based on the original [Webfont Medical Icons](https://samcome.github.io/webfont-medical-icons/). The particularity of this version is the compatibility with [Quasar Framework SVG Icons](https://quasar.dev/vue-components/icon#svg-icons).

# Usage
Import the icons you want to use as follow:

```html
<template>
  <div>
    <q-icon :name="medAccessibility" />
    <q-btn :icon="medAdministration" />
  </div>
</template>

<script>
    import { medAccessibility, medAdministration } from '@lukadriel/webfont-medical-icons';
    export default {
    // ...
    setup () {
        return {
            medAccessibility,
            medAdministration
        }
    }
    }
</script>
```