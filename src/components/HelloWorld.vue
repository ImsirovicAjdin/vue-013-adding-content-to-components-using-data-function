<template>
  <div class="hello">{{ datacontent }}</div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function() {
    return {
      datacontent: `This content was added with the help of a data function's 
           returned 'datacontent' property in the Vue component 
           called HelloWorld`
    };
  }
};
</script>

