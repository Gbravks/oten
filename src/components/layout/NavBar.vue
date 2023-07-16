<template>
    <nav class="bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <router-link to="/" class="text-white font-bold text-lg">Home</router-link>
                    </div>
                    <div class="hidden md:block">
                        <div class="ml-10 flex items-baseline space-x-4">
                            <router-link to="/about"
                                class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">About</router-link>
                            <router-link to="/contact"
                                class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Contact</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'NavBar',
};
</script>

<style scoped>/* Add Tailwind classes and custom styles here */</style>