<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
  illum eos consequatur incidunt sequi dolorem non dolores vero
  architecto, iure eligendi asperiores repellat pariatur! Ad placeat
  exercitationem eum unde assumenda."
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
  illum eos consequatur incidunt sequi dolorem non dolores vero
  architecto, iure eligendi asperiores repellat pariatur! Ad placeat
  exercitationem eum unde assumenda."
    />
    <Service
      title="Banco de Dados"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus
  illum eos consequatur incidunt sequi dolorem non dolores vero
  architecto, iure eligendi asperiores repellat pariatur! Ad placeat
  exercitationem eum unde assumenda."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Service } from '@/components/molecules';

export default defineComponent({
  components: { Service }
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
