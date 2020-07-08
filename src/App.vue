<template>
  <div id="app">
    <deni/>
    <juzent/>
    <smart/>
    <office8/>
    <strayple/>
    <qos/>
    <xten/>
    <hajj/>
    <sdu/>
    <tenge/>
    <soyleu/>
    <calendario/>
  </div>
</template>

<script>
import deni from './components/deni'
import juzent from './components/juzent'
import smart from './components/smart-bridge'
import office8 from './components/office8'
import strayple from './components/strayple'
import qos from './components/qos'
import xten from './components/x-ten-mentorship'
import hajj from './components/hajj'
import sdu from './components/sdu'
import tenge from './components/tenge'
import soyleu from './components/soyleu'
import calendario from './components/calendario'
export default {
  components: {
    deni,
    juzent,
    smart,
    office8,
    strayple,
    qos,
    xten,
    hajj,
    sdu,
    tenge,
    soyleu,
    calendario
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
