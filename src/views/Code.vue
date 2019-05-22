<template>
  <div class="code">
    <div class="container-fluid py-5">
      <div class="row">
        <div class="col-4">
          <h1 class="text-right font-size-xxxxl">
            <span class="d-block">Code</span>
          </h1>
          <CodeComponent miniData="You can take data of here"></CodeComponent>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import CodeComponent from '@/components/code/code';

  export default {
    name: 'code',
    components: {
      CodeComponent
    }
  }

</script>
