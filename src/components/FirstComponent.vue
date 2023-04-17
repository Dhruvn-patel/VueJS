<template>
  <div>
    <h1>{{ msg }}</h1>
    <!-- <div v-if="data">My if</div>
    <div v-else>else</div>
    <button v-on:click="fun()">click here</button> -->
    <table border="1">
      <thead>
        <tr>
          <th>name</th>
          <th>age</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="item in items" :key="item.id">
          <td>{{ item.id }}</td>
          <td>{{ item.name }}</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "FirstCompoenent",
  props: {
    msg: String,
  },
  data() {
    return {
      data: true,
      items: [
        { id: 1, name: "dhruv" },
        { id: 2, name: "patel" },
        { id: 3, name: "Nareshbhai" },
      ],
    };
  },
  methods: {
    fun() {
      this.data = !this.data;
    },
  },
};
</script>
