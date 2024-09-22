<script>
    import Login from "./login.svelte";
</script>


<div class="flex flex-col md:flex-row h-screen">
    <div class="w-full h-1/4 md:h-auto md:w-1/4 bg-blue-500 md:bg-[url('https://img.freepik.com/free-vector/abstract-background-concept_23-2148483758.jpg')] bg-cover bg-center relative">
      <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center">
        <h1 class="text-white text-3xl md:text-4xl font-bold">Welcome Back!</h1>
      </div>
    </div>
    <div class="w-full h-3/4 md:h-auto md:w-3/4 flex items-center justify-center p-4 md:p-8 bg-gray-100">
      <div class="w-full max-w-md">
        <div class="bg-white shadow-md rounded px-6 md:px-8 py-6 md:py-8">
          <h2 class="text-xl md:text-2xl mb-4 md:mb-6 text-center">Login</h2>
          <Login />
        </div>
      </div>
    </div>
  </div>