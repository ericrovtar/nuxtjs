<template>
    <div>
        <h1>Hi!</h1>
        {{ $route.params.id }}
    </div>
</template>

<script>
export default {
  // asyncData ({ params, error }) {
  //   // return axios.get(`https://jsonplaceholder.typicode.com/users/${+params.id}`)
  //   // .then((res) => res.data)
  //   // .catch(() => {
  //   //   error({ message: 'User not found', statusCode: 404 })
  //   // })
  //   console.log(params)
  //   return params
  // }
}
</script>

<style scoped></style>
