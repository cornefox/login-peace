<template>
    <!-- Columns -->
    <div class="grid grid-cols-12">        
        <div class="col-span-4 text-white font-sans font-bold bg-black min-h-screen pl-7">
            <!-- Rows -->
            <div class="grid grid-rows-6 grid-flow-col min-h-screen items-center justify-items-start ">
                <!-- Title -->
                <div class="row-span-4 row-start-2 text-4xl ">
                    Sign In
                    <!-- username -->
                    <div class="pt-10 pr-20">
                        <!-- Icon -->
                        <i class='bx bx-user-plus absolute py-14 px-3 icon' style='font-size: 22px' ></i>
                        <label class="text-sm font-sans font-medium">
                            Username
                        </label>
                        <input 
                            type="text" 
                            name="username" 
                            placeholder="Write your username" 
                            class=" w-full bg-black py-3 px-12 border hover: border-gray-500 rounded shadow text-base font-sans"/>                            
                    </div>
                    <!-- Password -->
                    <div class="pt-2 pr-20">
                        <!-- Icon -->
                        <i class='bx bx-low-vision absolute py-14 px-3 icon' style='font-size: 22px' ></i>
                        <label class="text-sm font-sans font-medium">
                            Password
                        </label>
                        <input 
                            type="password" 
                            name="password" 
                            placeholder="Write your password" 
                            class=" w-full bg-black py-3 px-12 border hover: border-gray-500 rounded shadow text-base font-sans"/>
                        <!-- Text -->
                        <a href="" class="text-sm font-sans font-medium text-gray-600 underline">
                            Forgot password?
                        </a>
                    </div>
                    <!-- Button -->
                    <div class=" text-sm font-sans font-medium w-full pr-20 pt-14">
                        <button 
                            type="button"   
                            class="text-center w-full py-4 bg-blue-700 hover:bg-blue-400 rounded-md text-white ">
                                SIGN IN
                        </button>
                    </div>
                </div>
                <!-- Text -->
                <a href="" class="text-sm font-sans font-medium text-gray-400 underline">
                    Don´t have an account? Sign up
                </a>
            </div>         
        </div>

        <!-- Second column image -->
        <div class="col-span-8 login text-white font-sans font-bold ">
            <!-- Aquí iría algún omentario -->
        </div>

    </div>
</template>

<script>

</script>

<style>

    .login {
        background: url( '../assets/image/login.jpg' );
        background-repeat: no-repeat;
        background-size: cover;
    }

    .icon {
        color:#155085
    }

</style>
