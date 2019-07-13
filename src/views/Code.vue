<template>
  <div class="code">
    <MarkupChallenge miniData="This is data passed of my component"></MarkupChallenge>
  </div>
</template>

<script>
  import MarkupChallenge from '@/components/markup_challenge/MarkupChallenge';

  export default {
    name: 'code',
    components: {
      MarkupChallenge
    }
  }

</script>
