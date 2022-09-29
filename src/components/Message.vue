<template>
  <p className="message">{{ message }}</p>
</template>

<script>
export default {
  name: "Message",
  props: {
    message: {
      type: String,
      default: "",
    },
  },
};
</script>




<template>
  <div className="actions">
    <i class="far fa-comment"></i>
    <i class="fas fa-retweet"></i>
    <i class="far fa-heart"></i>
    <i class="fas fa-share"></i>
  </div>
</template>

<script>
export default {
  name: "Actions",
};
</script>

