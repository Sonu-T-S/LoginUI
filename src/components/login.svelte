<div class="space-y-4 w-full max-w-sm mx-auto rounded-lg">
    <form class="space-y-4">
      <div>
        <input type="email" id="email" name="email" placeholder="Email address" required
               class="w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
      </div>
      <div>
        <input type="password" id="password" name="password" placeholder="Password" required
               class="w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
      </div>
  
      <div class="flex items-center justify-between text-sm">
        <div class="flex items-center">
          <input id="remember-me" name="remember-me" type="checkbox" class="h-4 w-4 text-blue-600 focus:ring-blue-500 border-gray-300 rounded">
          <label for="remember-me" class="ml-2 text-gray-700">Remember me</label>
        </div>
        <a href="#" class="font-medium text-blue-600 hover:text-blue-500">Forgot password?</a>
      </div>
  
      <div>
        <button type="submit"
                class="w-full flex justify-center py-2 px-4 border border-transparent rounded-full shadow-sm text-sm font-medium text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">
          Sign in
        </button>
      </div>
    </form>
  
    <div class="relative">
      <div class="absolute inset-0 flex items-center">
        <div class="w-full border-t border-gray-300"></div>
      </div>
      <div class="relative flex justify-center text-xs uppercase">
        <span class="px-2 bg-white text-gray-500">Or continue with</span>
      </div>
    </div>
  
    <div>
      <a href="#"
         class="w-full flex items-center justify-center px-4 py-2 border border-gray-300 rounded-full shadow-sm text-sm font-medium text-gray-700 bg-white hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">
        <svg class="h-5 w-5 text-red-500 mr-2" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
          <path d="M12.48 10.92v3.28h7.84c-.24 1.84-.853 3.187-1.787 4.133-1.147 1.147-2.933 2.4-6.053 2.4-4.827 0-8.6-3.893-8.6-8.72s3.773-8.72 8.6-8.72c2.6 0 4.507 1.027 5.907 2.347l2.307-2.307C18.747 1.44 16.133 0 12.48 0 5.867 0 .307 5.387.307 12s5.56 12 12.173 12c3.573 0 6.267-1.173 8.373-3.36 2.16-2.16 2.84-5.213 2.84-7.667 0-.76-.053-1.467-.173-2.053H12.48z"/>
        </svg>
        Sign in with Google
      </a>
    </div>
  
    <p class="text-center text-xs text-gray-600">
      Not a member?
      <a href="#" class="font-medium text-blue-600 hover:text-blue-500">Register now</a>
    </p>
  </div>