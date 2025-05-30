<template>
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <nav class="container-max">
            <div class="flex justify-between items-center py-4">
                <NuxtLink to="/" class="flex items-center space-x-2">
                    <div class="w-10 h-10 bg-green-600 rounded-lg flex items-center justify-center">
                        <span class="text-white font-bold text-xl">WR</span>
                    </div>
                    <span class="text-xl font-bold text-gray-800">WithinReachTechnology</span>
                </NuxtLink>

                <!-- Desktop Navigation -->
                <div class="hidden md:flex space-x-8">
                    <NuxtLink to="/" class="text-gray-700 hover:text-green-600 font-medium transition-colors">Home
                    </NuxtLink>
                    <NuxtLink to="/story" class="text-gray-700 hover:text-green-600 font-medium transition-colors">Our
                        Story</NuxtLink>
                    <NuxtLink to="/about" class="text-gray-700 hover:text-green-600 font-medium transition-colors">About
                    </NuxtLink>
                    <NuxtLink to="/impact" class="text-gray-700 hover:text-green-600 font-medium transition-colors">
                        Impact</NuxtLink>
                    <NuxtLink to="/testimonials"
                        class="text-gray-700 hover:text-green-600 font-medium transition-colors">Testimonials</NuxtLink>
                    <NuxtLink to="/contact" class="text-gray-700 hover:text-green-600 font-medium transition-colors">
                        Contact</NuxtLink>
                </div>

                <!-- Mobile Menu Button -->
                <button @click="toggleMobileMenu" class="md:hidden">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>

            <!-- Mobile Navigation -->
            <div v-if="mobileMenuOpen" class="md:hidden py-4 border-t">
                <div class="flex flex-col space-y-4">
                    <NuxtLink to="/" @click="closeMobileMenu" class="text-gray-700 hover:text-green-600 font-medium">
                        Home</NuxtLink>
                    <NuxtLink to="/story" @click="closeMobileMenu"
                        class="text-gray-700 hover:text-green-600 font-medium">Our Story</NuxtLink>
                    <NuxtLink to="/about" @click="closeMobileMenu"
                        class="text-gray-700 hover:text-green-600 font-medium">About</NuxtLink>
                    <NuxtLink to="/impact" @click="closeMobileMenu"
                        class="text-gray-700 hover:text-green-600 font-medium">Impact</NuxtLink>
                    <NuxtLink to="/testimonials" @click="closeMobileMenu"
                        class="text-gray-700 hover:text-green-600 font-medium">Testimonials</NuxtLink>
                    <NuxtLink to="/contact" @click="closeMobileMenu"
                        class="text-gray-700 hover:text-green-600 font-medium">Contact</NuxtLink>
                </div>
            </div>
        </nav>
    </header>
</template>

<script setup lang="ts">
const mobileMenuOpen = ref(false)

const toggleMobileMenu = () => {
    mobileMenuOpen.value = !mobileMenuOpen.value
}

const closeMobileMenu = () => {
    mobileMenuOpen.value = false
}
</script>