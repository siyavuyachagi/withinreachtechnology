<template>
    <footer class="bg-gray-900 text-white">
        <div class="container-max section-padding">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div class="col-span-1 md:col-span-2">
                    <div class="flex items-center space-x-2 mb-4">
                        <div class="w-10 h-10 bg-green-600 rounded-lg flex items-center justify-center">
                            <span class="text-white font-bold text-xl">WR</span>
                        </div>
                        <span class="text-xl font-bold">WithinReachTechnology</span>
                    </div>
                    <p class="text-gray-300 mb-4">
                        A black-owned company established with the objective of actively participating
                        in the South African economy by providing integrated business solutions across
                        all sectors of the economy.
                    </p>
                </div>

                <div>
                    <h3 class="font-semibold text-lg mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li>
                            <NuxtLink to="/story" class="text-gray-300 hover:text-green-400 transition-colors">Our Story
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/about" class="text-gray-300 hover:text-green-400 transition-colors">About Us
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/impact" class="text-gray-300 hover:text-green-400 transition-colors">Our
                                Impact</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/testimonials" class="text-gray-300 hover:text-green-400 transition-colors">
                                Testimonials</NuxtLink>
                        </li>
                    </ul>
                </div>

                <div>
                    <h3 class="font-semibold text-lg mb-4">Contact Info</h3>
                    <ul class="space-y-2 text-gray-300">
                        <li>📧 withinreachtech@gmail.com</li>
                        <li>📞 +27 62 109 0221</li>
                        <li>📍 44 Bentley Avenue, Willow Park, East London, South Africa</li>
                    </ul>
                </div>
            </div>

            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; {{ currentYear }} WithinReachTechnology. All rights reserved.</p>
            </div>
        </div>
    </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear()
</script>