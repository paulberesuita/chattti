<template>
  <div class="hello">
  <section class="py-12 px-4">
    <div class="w-full max-w-2xl mx-auto">
      <p class="mt-4 mb-8 leading-tight text-left"><span class="text-sm font-semibold">Paul: </span>Hello</h2>
      <p class="mt-4 mb-8 leading-tight text-left"><span class="text-sm font-semibold">Eugen: </span>Hey man</h2>
      <p class="mt-4 mb-8 leading-tight text-left"><span class="text-sm font-semibold">Paul: </span>Ready for Demo?</h2>
      <form class="w-full mx-auto">
        <div class="flex flex-wrap mb-4">
          <div class="w-full md:w-2/3">
            <input class="appearance-none block w-full py-3 px-4 mb-4 md:mb-0 leading-snug text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded md:rounded-r-none focus:outline-none" type="text" placeholder="Your message">
          </div>
          <div class="w-full md:w-1/3">
            <button class="inline-block w-full py-4 px-8 leading-none text-white bg-indigo-500 hover:bg-indigo-600 rounded md:rounded-l-none">Send Message</button>
          </div>
        </div>
      </form>
    </div>
  </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
