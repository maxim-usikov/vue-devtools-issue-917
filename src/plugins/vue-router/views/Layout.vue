<template>
  <div>
    <Nav />
    <main>
      <RouterView />
    </main>
  </div>
</template>

<script>
import Nav from '@/components/Nav';

export default {
  name: "Layout",
  components:{
    Nav,
  }
};
</script>
