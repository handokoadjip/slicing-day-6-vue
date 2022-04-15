<template>
  <YamaLabComponent />
  <CraiglistComponent />
  <NidoComponent />
  <QorosComponent />
</template>

<script>
import YamaLabComponent from "@/components/YamaLabComponent.vue";
import CraiglistComponent from "@/components/CraiglistComponent.vue";
import NidoComponent from "@/components/NidoComponent.vue";
import QorosComponent from "@/components/QorosComponent.vue";

export default {
  name: "HomePage",
  components: {
    YamaLabComponent,
    CraiglistComponent,
    NidoComponent,
    QorosComponent,
  },
  mounted() {
    document.title = "Design Inspiration | YAMA"
  }
}
</script>
