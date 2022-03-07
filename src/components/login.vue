<template>
    <div class="login">
        <div class="login__container">
            <div class="login__container--rows">
                <div class="login__container--title">
                    Sign In                    
                    <div class="login__container--form">
                        <i class='bx bx-user-plus absolute py-14 px-3 icon' style='font-size: 22px'></i>
                        <label class="login__container--form-text">
                            Username
                        </label>
                        <input 
                            type="text" 
                            name="username" 
                            placeholder="Write your username" 
                            class="w-full bg-black py-3 px-12 border hover: border-gray-500 rounded shadow text-base font-sans"/>                            
                    </div>
                    <div class="login__container--form-password">
                        <i 
                            class='bx bx-low-vision absolute py-14 px-3 icon' 
                            style='font-size: 22px' >                
                        </i>
                        <label class="login__container--form-text">
                            Password
                        </label>
                        <input 
                            type="password" 
                            name="password" 
                            placeholder="Write your password" 
                            class=" w-full bg-black py-3 px-12 border hover: border-gray-500 rounded shadow text-base font-sans"/>
                        <a href="" class="login__item">
                            Forgot password?
                        </a>
                    </div>
                    <!-- Button -->
                    <div class="login__button">
                        <button 
                            type="button"   
                            class="login__button--items">
                                SIGN IN
                        </button>
                    </div>
                </div>
                <!-- Text -->
                <a href="" class="login__item--i">
                    Don´t have an account? Sign up
                </a>
            </div>         
        </div>

        <!-- Second column image -->
        <div class="banner">
            <!-- Aquí iría algún omentario -->
        </div>

    </div>
</template>

<script>

</script>

<style lang="scss">

    .login {
        @apply grid grid-cols-12;

        &__container {
            @apply col-span-4 text-white font-sans font-bold bg-black min-h-screen pl-7;

            &--rows {
                @apply grid grid-rows-6 grid-flow-col min-h-screen items-center justify-items-start;
            }

            &--title {
                @apply row-span-4 row-start-2 text-4xl;
            }

            &--form {
                @apply pt-10 pr-20;

                &-text {
                    @apply text-sm font-sans font-medium;
                }

                &-password {
                    @apply pt-2 pr-20;
                }
            }
        }

        &__item {
            @apply text-sm font-sans font-medium text-gray-600 underline;

            &--i {
                @apply text-sm font-sans font-medium text-gray-400 underline;
            }
        }

        &__button {
            @apply text-sm font-sans font-medium w-full pr-20 pt-14;

            &--items {
                @apply text-center w-full py-4 bg-blue-700 hover:bg-blue-400 rounded-md text-white;
            }
        }        

    }

    .banner {
        @apply col-span-8 text-white font-sans font-bold;
        background: url( '../assets/image/login.jpg' );
        background-repeat: no-repeat;
        background-size: cover        
    }

    .icon {
        color:#155085
    }

</style>