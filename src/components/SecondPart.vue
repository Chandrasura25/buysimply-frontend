<template>
<div class="lg:w-1/2 w-full bg2 h-[100vh] flex justify-center items-center">
  <div class="p-6">
    <div class="lg:hidden block">
         <div class="flex justify-center items-center mb-4">
            <div class="w-[198px] h-[97px]">
             <img src="../assets/logo.png" class="w-full h-full object-cover" alt="logo">
            </div>
          </div>
    </div>
    <form class="mx-auto">
      <div class="flex justify-center items-center flex-col">
      <h4 class="font-bold text-2xl text-purple">Welcome Back</h4>
      <p class="text-textg">Enter your email address and password to access your account.</p>
     </div>
      <div class="my-5">
      <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Email Address <span class="text-red-600 font-bold">*</span></label>
      <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Enter your email" required />
      </div>
      <div class="mt-5">
      <label for="password" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Password <span class="text-red-600 font-bold">*</span></label>
      <div class="flex">
      <input type="text" id="website-admin" class="rounded-none rounded-s-md bg-gray-50 border border-gray-300 text-gray-900 focus:ring-blue-500 focus:border-blue-500 block flex-1 min-w-0 w-full text-sm p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Enter your password" >
      <span class="inline-flex items-center px-3 text-sm text-gray-900 bg-gray-200 border border-e-0 border-gray-300  rounded-e-lg">
        <svg class="w-5 h-5 text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: '#F7F7F7';transform: ;msFilter:;"><path d="M12 9a3.02 3.02 0 0 0-3 3c0 1.642 1.358 3 3 3 1.641 0 3-1.358 3-3 0-1.641-1.359-3-3-3z"></path><path d="M12 5c-7.633 0-9.927 6.617-9.948 6.684L1.946 12l.105.316C2.073 12.383 4.367 19 12 19s9.927-6.617 9.948-6.684l.106-.316-.105-.316C21.927 11.617 19.633 5 12 5zm0 12c-5.351 0-7.424-3.846-7.926-5C4.578 10.842 6.652 7 12 7c5.351 0 7.424 3.846 7.926 5-.504 1.158-2.578 5-7.926 5z"></path></svg>
      </span>
      </div>
      </div>
      <div class="mt-1 flex justify-between items-center">
        <div class="flex items-start">
          <div class="flex items-center h-5">
            <input id="terms" type="checkbox" value="" class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800" required />
          </div>
          <label for="terms" class="ms-2 text-sm font-medium text-textg">Remember me</label>
        </div>
        <p class="text-purple text-sm font-semibold">Forgot Password?</p>
      </div>
      <div class="mt-6">
        <button type="button" class="focus:outline-none text-white bg-purple w-full hover:bg-purple-800 focus:ring-4 focus:ring-purple-300 font-medium rounded-lg text-sm px-5 py-2.5 mb-2 dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">Sign in</button>
      </div>
      <div class="">
       <p class="text-center text-textg">Don’t have an account? <a class="text-purple font-semibold">Sign up</a></p>
      </div>
    </form>
  </div>
</div>
</template>