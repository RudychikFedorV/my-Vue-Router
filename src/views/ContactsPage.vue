<template>
  <div>
    <button @click="addLike">likes</button>
    <button @click="addDislike">dislikes</button>
  </div>
  <div>
    Количество лайков <strong> {{ likes }}</strong>
  </div>
  <div>
    Количество дизлайков <strong> {{ dislikes }}</strong>
  </div>
</template>

<script>
export default {
  data() {
    return {
      likes: 0,
      dislikes: 0,
    };
  },
  methods: {
    addLike() {
      this.likes += 1;
    },
    addDislike() {
      this.dislikes += 1;
    },
  },
};
</script>
