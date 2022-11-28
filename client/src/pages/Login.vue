<template>
    <div class="xl:grid place-items-center mt-[50px]">
        <div class="p-5 xl:w-[25vw] shadow-2xl">
            <form>
                <h1 class="font-squada text-3xl text-slate-700">Login</h1>
                <div class="mt-5">
                    <input type="text" placeholder="Username" class="w-full p-2 outline-none border">
                </div>
                <div class="mt-5">
                    <input type="password" placeholder="Password" class="w-full p-2 outline-none border">
                </div>
                <div class="my-5">
                    <button
                        class="bg-red-200 py-2 px-4 bg-gradient-to-tr from-cyan-500 to-pink-500 text-white hover:scale-105 transition rounded-md">Sign
                        In</button>
                </div>
            </form>
        </div>
    </div>
</template>