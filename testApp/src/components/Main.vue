<template>
    <div>
        <app-menu-bar v-show="showBar"></app-menu-bar>
        <div class="menu">
          <div class="menu_section">
            Menu Section A blabalbablbalab
          </div>
          <div class="menu_section">
            Menu Section B
          </div>
          <div class="menu_section">
            Menu Section C balablabablablablablablaajakjkajkajk
          </div>
        </div>
        <div v-observe-visibility="visibilityChanged">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut interdum eu risus ac efficitur. Mauris quis elit gravida, dignissim libero sed, bibendum lectus. Quisque lobortis ipsum eget cursus suscipit. Donec id ipsum vel tellus porttitor egestas non ut enim. Donec lacinia odio eu sem laoreet volutpat. Donec finibus orci cursus nibh faucibus aliquet. Suspendisse potenti. Phasellus aliquam orci id ligula eleifend rhoncus. Vestibulum at pretium nulla. Curabitur maximus pulvinar mi eget consequat. Integer interdum mollis lacinia. Nulla metus mi, congue ac felis eu, gravida consequat ipsum. Aenean sit amet velit vel elit suscipit hendrerit eget nec nisl. Cras sed iaculis ex, non congue libero.

            Nulla ultrices lobortis velit, nec aliquet velit volutpat in. Phasellus interdum ex non quam ultrices malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. In hac habitasse platea dictumst. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vestibulum vitae pulvinar arcu. Donec condimentum, tortor vel vulputate laoreet, risus neque finibus turpis, eu vestibulum urna turpis at ante. Donec maximus augue vel felis pulvinar eleifend et at purus. Donec id nulla ipsum.

            Proin consequat nisi diam, vel efficitur velit ornare ac. Sed dapibus leo nec purus elementum, non convallis neque tincidunt. Mauris porta velit sed orci ultrices, et fermentum urna suscipit. In vitae tempor augue. Fusce consequat fermentum lorem, id tincidunt mi. Integer finibus eget purus non placerat. Donec id sagittis elit, a malesuada justo. Ut et nunc neque. Nulla imperdiet hendrerit nunc id posuere. Proin porta libero nec purus convallis iaculis. In vulputate, libero vel sollicitudin accumsan, velit quam interdum tortor, in ornare odio nisl id enim. Maecenas sodales mi sem, sit amet consequat tellus lobortis id. Donec dignissim erat sed mi semper, rhoncus luctus felis posuere. Nullam dapibus ex blandit purus pharetra faucibus vel nec nisl. Aliquam laoreet placerat metus, in tempor ex vestibulum vel.

            Nunc vel commodo neque. Maecenas eget ipsum ullamcorper, elementum leo sit amet, sollicitudin risus. Donec sodales purus sit amet nulla euismod porta. Curabitur lorem mauris, molestie et est in, fermentum blandit lorem. Donec non facilisis purus. Donec sed eleifend leo. Praesent aliquet commodo neque vitae auctor.

            Fusce rhoncus luctus tincidunt. Maecenas consequat nulla vel neque condimentum, non pulvinar urna sodales. Morbi sollicitudin metus vitae erat viverra, et pulvinar lectus consectetur. Ut quis felis dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Suspendisse potenti. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras et porttitor erat. Fusce eu porttitor enim. Sed auctor vestibulum turpis, et consequat eros molestie eu. Vestibulum rhoncus suscipit metus, nec placerat magna fermentum vitae. Praesent vitae sem justo. In non diam rutrum, ultrices elit a, scelerisque purus. Maecenas diam sem, venenatis in est et, tempor sagittis eros. Donec a finibus nisl. In condimentum scelerisque leo et tempor.

            Proin vulputate ante libero, sit amet accumsan odio venenatis eget. Vestibulum vulputate nisl id elit molestie, et viverra ipsum varius. Proin nec dolor purus. Vestibulum pharetra fringilla enim. Nam ullamcorper egestas metus at mollis. Mauris in gravida risus. Morbi in lectus porttitor, volutpat quam non, ultrices purus. Aenean et viverra ante, faucibus commodo libero. Donec interdum malesuada ipsum, at dapibus massa eleifend et. Etiam blandit, libero vel rutrum euismod, arcu sapien dignissim magna, in tristique est metus non nisi. Nunc vulputate dapibus tincidunt.

            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris arcu est, placerat accumsan ullamcorper sagittis, dictum sed lectus. Vestibulum ullamcorper lacus et risus ullamcorper placerat. Suspendisse id est magna. Phasellus elementum quam quis lacus egestas, vitae pellentesque nulla pellentesque. Fusce facilisis gravida erat, ut convallis leo semper non. Maecenas ex tellus, dapibus eu ex et, ullamcorper tincidunt enim. Vestibulum eu accumsan dui, id iaculis leo.
        </div>
        <br>
        <br>
        <br>
        <div>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut interdum eu risus ac efficitur. Mauris quis elit gravida, dignissim libero sed, bibendum lectus. Quisque lobortis ipsum eget cursus suscipit. Donec id ipsum vel tellus porttitor egestas non ut enim. Donec lacinia odio eu sem laoreet volutpat. Donec finibus orci cursus nibh faucibus aliquet. Suspendisse potenti. Phasellus aliquam orci id ligula eleifend rhoncus. Vestibulum at pretium nulla. Curabitur maximus pulvinar mi eget consequat. Integer interdum mollis lacinia. Nulla metus mi, congue ac felis eu, gravida consequat ipsum. Aenean sit amet velit vel elit suscipit hendrerit eget nec nisl. Cras sed iaculis ex, non congue libero.

            Nulla ultrices lobortis velit, nec aliquet velit volutpat in. Phasellus interdum ex non quam ultrices malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. In hac habitasse platea dictumst. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vestibulum vitae pulvinar arcu. Donec condimentum, tortor vel vulputate laoreet, risus neque finibus turpis, eu vestibulum urna turpis at ante. Donec maximus augue vel felis pulvinar eleifend et at purus. Donec id nulla ipsum.

            Proin consequat nisi diam, vel efficitur velit ornare ac. Sed dapibus leo nec purus elementum, non convallis neque tincidunt. Mauris porta velit sed orci ultrices, et fermentum urna suscipit. In vitae tempor augue. Fusce consequat fermentum lorem, id tincidunt mi. Integer finibus eget purus non placerat. Donec id sagittis elit, a malesuada justo. Ut et nunc neque. Nulla imperdiet hendrerit nunc id posuere. Proin porta libero nec purus convallis iaculis. In vulputate, libero vel sollicitudin accumsan, velit quam interdum tortor, in ornare odio nisl id enim. Maecenas sodales mi sem, sit amet consequat tellus lobortis id. Donec dignissim erat sed mi semper, rhoncus luctus felis posuere. Nullam dapibus ex blandit purus pharetra faucibus vel nec nisl. Aliquam laoreet placerat metus, in tempor ex vestibulum vel.

            Nunc vel commodo neque. Maecenas eget ipsum ullamcorper, elementum leo sit amet, sollicitudin risus. Donec sodales purus sit amet nulla euismod porta. Curabitur lorem mauris, molestie et est in, fermentum blandit lorem. Donec non facilisis purus. Donec sed eleifend leo. Praesent aliquet commodo neque vitae auctor.

            Fusce rhoncus luctus tincidunt. Maecenas consequat nulla vel neque condimentum, non pulvinar urna sodales. Morbi sollicitudin metus vitae erat viverra, et pulvinar lectus consectetur. Ut quis felis dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Suspendisse potenti. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras et porttitor erat. Fusce eu porttitor enim. Sed auctor vestibulum turpis, et consequat eros molestie eu. Vestibulum rhoncus suscipit metus, nec placerat magna fermentum vitae. Praesent vitae sem justo. In non diam rutrum, ultrices elit a, scelerisque purus. Maecenas diam sem, venenatis in est et, tempor sagittis eros. Donec a finibus nisl. In condimentum scelerisque leo et tempor.

            Proin vulputate ante libero, sit amet accumsan odio venenatis eget. Vestibulum vulputate nisl id elit molestie, et viverra ipsum varius. Proin nec dolor purus. Vestibulum pharetra fringilla enim. Nam ullamcorper egestas metus at mollis. Mauris in gravida risus. Morbi in lectus porttitor, volutpat quam non, ultrices purus. Aenean et viverra ante, faucibus commodo libero. Donec interdum malesuada ipsum, at dapibus massa eleifend et. Etiam blandit, libero vel rutrum euismod, arcu sapien dignissim magna, in tristique est metus non nisi. Nunc vulputate dapibus tincidunt.

            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris arcu est, placerat accumsan ullamcorper sagittis, dictum sed lectus. Vestibulum ullamcorper lacus et risus ullamcorper placerat. Suspendisse id est magna. Phasellus elementum quam quis lacus egestas, vitae pellentesque nulla pellentesque. Fusce facilisis gravida erat, ut convallis leo semper non. Maecenas ex tellus, dapibus eu ex et, ullamcorper tincidunt enim. Vestibulum eu accumsan dui, id iaculis leo.
        </div>
        <br>
        <br>
        <br>
        <div>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut interdum eu risus ac efficitur. Mauris quis elit gravida, dignissim libero sed, bibendum lectus. Quisque lobortis ipsum eget cursus suscipit. Donec id ipsum vel tellus porttitor egestas non ut enim. Donec lacinia odio eu sem laoreet volutpat. Donec finibus orci cursus nibh faucibus aliquet. Suspendisse potenti. Phasellus aliquam orci id ligula eleifend rhoncus. Vestibulum at pretium nulla. Curabitur maximus pulvinar mi eget consequat. Integer interdum mollis lacinia. Nulla metus mi, congue ac felis eu, gravida consequat ipsum. Aenean sit amet velit vel elit suscipit hendrerit eget nec nisl. Cras sed iaculis ex, non congue libero.

            Nulla ultrices lobortis velit, nec aliquet velit volutpat in. Phasellus interdum ex non quam ultrices malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. In hac habitasse platea dictumst. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vestibulum vitae pulvinar arcu. Donec condimentum, tortor vel vulputate laoreet, risus neque finibus turpis, eu vestibulum urna turpis at ante. Donec maximus augue vel felis pulvinar eleifend et at purus. Donec id nulla ipsum.

            Proin consequat nisi diam, vel efficitur velit ornare ac. Sed dapibus leo nec purus elementum, non convallis neque tincidunt. Mauris porta velit sed orci ultrices, et fermentum urna suscipit. In vitae tempor augue. Fusce consequat fermentum lorem, id tincidunt mi. Integer finibus eget purus non placerat. Donec id sagittis elit, a malesuada justo. Ut et nunc neque. Nulla imperdiet hendrerit nunc id posuere. Proin porta libero nec purus convallis iaculis. In vulputate, libero vel sollicitudin accumsan, velit quam interdum tortor, in ornare odio nisl id enim. Maecenas sodales mi sem, sit amet consequat tellus lobortis id. Donec dignissim erat sed mi semper, rhoncus luctus felis posuere. Nullam dapibus ex blandit purus pharetra faucibus vel nec nisl. Aliquam laoreet placerat metus, in tempor ex vestibulum vel.

            Nunc vel commodo neque. Maecenas eget ipsum ullamcorper, elementum leo sit amet, sollicitudin risus. Donec sodales purus sit amet nulla euismod porta. Curabitur lorem mauris, molestie et est in, fermentum blandit lorem. Donec non facilisis purus. Donec sed eleifend leo. Praesent aliquet commodo neque vitae auctor.

            Fusce rhoncus luctus tincidunt. Maecenas consequat nulla vel neque condimentum, non pulvinar urna sodales. Morbi sollicitudin metus vitae erat viverra, et pulvinar lectus consectetur. Ut quis felis dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Suspendisse potenti. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras et porttitor erat. Fusce eu porttitor enim. Sed auctor vestibulum turpis, et consequat eros molestie eu. Vestibulum rhoncus suscipit metus, nec placerat magna fermentum vitae. Praesent vitae sem justo. In non diam rutrum, ultrices elit a, scelerisque purus. Maecenas diam sem, venenatis in est et, tempor sagittis eros. Donec a finibus nisl. In condimentum scelerisque leo et tempor.

            Proin vulputate ante libero, sit amet accumsan odio venenatis eget. Vestibulum vulputate nisl id elit molestie, et viverra ipsum varius. Proin nec dolor purus. Vestibulum pharetra fringilla enim. Nam ullamcorper egestas metus at mollis. Mauris in gravida risus. Morbi in lectus porttitor, volutpat quam non, ultrices purus. Aenean et viverra ante, faucibus commodo libero. Donec interdum malesuada ipsum, at dapibus massa eleifend et. Etiam blandit, libero vel rutrum euismod, arcu sapien dignissim magna, in tristique est metus non nisi. Nunc vulputate dapibus tincidunt.

            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris arcu est, placerat accumsan ullamcorper sagittis, dictum sed lectus. Vestibulum ullamcorper lacus et risus ullamcorper placerat. Suspendisse id est magna. Phasellus elementum quam quis lacus egestas, vitae pellentesque nulla pellentesque. Fusce facilisis gravida erat, ut convallis leo semper non. Maecenas ex tellus, dapibus eu ex et, ullamcorper tincidunt enim. Vestibulum eu accumsan dui, id iaculis leo.
        </div>
        <br>
        <br>
        <br>
        <div>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut interdum eu risus ac efficitur. Mauris quis elit gravida, dignissim libero sed, bibendum lectus. Quisque lobortis ipsum eget cursus suscipit. Donec id ipsum vel tellus porttitor egestas non ut enim. Donec lacinia odio eu sem laoreet volutpat. Donec finibus orci cursus nibh faucibus aliquet. Suspendisse potenti. Phasellus aliquam orci id ligula eleifend rhoncus. Vestibulum at pretium nulla. Curabitur maximus pulvinar mi eget consequat. Integer interdum mollis lacinia. Nulla metus mi, congue ac felis eu, gravida consequat ipsum. Aenean sit amet velit vel elit suscipit hendrerit eget nec nisl. Cras sed iaculis ex, non congue libero.

            Nulla ultrices lobortis velit, nec aliquet velit volutpat in. Phasellus interdum ex non quam ultrices malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. In hac habitasse platea dictumst. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vestibulum vitae pulvinar arcu. Donec condimentum, tortor vel vulputate laoreet, risus neque finibus turpis, eu vestibulum urna turpis at ante. Donec maximus augue vel felis pulvinar eleifend et at purus. Donec id nulla ipsum.

            Proin consequat nisi diam, vel efficitur velit ornare ac. Sed dapibus leo nec purus elementum, non convallis neque tincidunt. Mauris porta velit sed orci ultrices, et fermentum urna suscipit. In vitae tempor augue. Fusce consequat fermentum lorem, id tincidunt mi. Integer finibus eget purus non placerat. Donec id sagittis elit, a malesuada justo. Ut et nunc neque. Nulla imperdiet hendrerit nunc id posuere. Proin porta libero nec purus convallis iaculis. In vulputate, libero vel sollicitudin accumsan, velit quam interdum tortor, in ornare odio nisl id enim. Maecenas sodales mi sem, sit amet consequat tellus lobortis id. Donec dignissim erat sed mi semper, rhoncus luctus felis posuere. Nullam dapibus ex blandit purus pharetra faucibus vel nec nisl. Aliquam laoreet placerat metus, in tempor ex vestibulum vel.

            Nunc vel commodo neque. Maecenas eget ipsum ullamcorper, elementum leo sit amet, sollicitudin risus. Donec sodales purus sit amet nulla euismod porta. Curabitur lorem mauris, molestie et est in, fermentum blandit lorem. Donec non facilisis purus. Donec sed eleifend leo. Praesent aliquet commodo neque vitae auctor.

            Fusce rhoncus luctus tincidunt. Maecenas consequat nulla vel neque condimentum, non pulvinar urna sodales. Morbi sollicitudin metus vitae erat viverra, et pulvinar lectus consectetur. Ut quis felis dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Suspendisse potenti. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras et porttitor erat. Fusce eu porttitor enim. Sed auctor vestibulum turpis, et consequat eros molestie eu. Vestibulum rhoncus suscipit metus, nec placerat magna fermentum vitae. Praesent vitae sem justo. In non diam rutrum, ultrices elit a, scelerisque purus. Maecenas diam sem, venenatis in est et, tempor sagittis eros. Donec a finibus nisl. In condimentum scelerisque leo et tempor.

            Proin vulputate ante libero, sit amet accumsan odio venenatis eget. Vestibulum vulputate nisl id elit molestie, et viverra ipsum varius. Proin nec dolor purus. Vestibulum pharetra fringilla enim. Nam ullamcorper egestas metus at mollis. Mauris in gravida risus. Morbi in lectus porttitor, volutpat quam non, ultrices purus. Aenean et viverra ante, faucibus commodo libero. Donec interdum malesuada ipsum, at dapibus massa eleifend et. Etiam blandit, libero vel rutrum euismod, arcu sapien dignissim magna, in tristique est metus non nisi. Nunc vulputate dapibus tincidunt.

            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris arcu est, placerat accumsan ullamcorper sagittis, dictum sed lectus. Vestibulum ullamcorper lacus et risus ullamcorper placerat. Suspendisse id est magna. Phasellus elementum quam quis lacus egestas, vitae pellentesque nulla pellentesque. Fusce facilisis gravida erat, ut convallis leo semper non. Maecenas ex tellus, dapibus eu ex et, ullamcorper tincidunt enim. Vestibulum eu accumsan dui, id iaculis leo.
        </div>
    </div>
</template>
<script>
import MenuBar from './MenuBar.vue'
export default {
  components: {
    'app-menu-bar': MenuBar
  },
  data () {
    return {
      showBar: false
    }
  },
  methods: {
    visibilityChanged (isVisible, entry) {
      this.showBar = !isVisible
      console.log(entry)
    }
  }
}
</script>

<style scoped>

div.menu_section {
  margin:5% auto;
  text-align: right;
}

div.menu {
  position: relative;
  float: right;
  top: 10%;
  border-style: solid;
  border-width: 5px;;
}
</style>
