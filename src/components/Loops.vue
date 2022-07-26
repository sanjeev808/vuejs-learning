<template>
  <h1>this is for loop component</h1>
  <table>
    <tr>
      <td>Id</td>
      <td>Name</td>
      <td>Email</td>
    </tr>
    <tr v-for="user in users" :key="user.id">
      <td>{{ user.id }}</td>
      <td>{{ user.name }}</td>
      <td>{{ user.email }}</td>
    </tr>
  </table>
</template>
<script>
export default {
  name: "Loops",
  props: {
    data: String,
  },
  data() {
    return {
      users: [
        { id: 1, name: "sanjeev", email: "sanjeev@gmail.com" },
        { id: 2, name: "Ajeet", email: "ajeet@gmail.com" },
        { id: 3, name: "Ankit", email: "Ankit@gmail.com" },
        { id: 4, name: "Aditya", email: "Aditya@gmail.com" },
        { id: 5, name: "Shivanshu", email: "Shivanshu@gmail.com" },
      ],
    };
  },
};
</script>
<style scoped>
h1{
  background-color: yellow;
}
</style>