<template>
    <div>
        <!-- Hero Section -->
        <section class="bg-gradient-to-r from-gray-800 to-gray-900 text-white section-padding">
            <div class="container-max">
                <div class="text-center">
                    <h1 class="text-4xl md:text-5xl font-bold mb-6">Contact Us</h1>
                    <p class="text-xl max-w-3xl mx-auto">
                        Ready to transform your business? Get in touch with our team of experts today
                    </p>
                </div>
            </div>
        </section>

        <!-- Contact Information & Form -->
        <section class="bg-white section-padding">
            <div class="container-max">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                    <!-- Contact Information -->
                    <div>
                        <h2 class="text-3xl font-bold text-gray-800 mb-8">Get In Touch</h2>

                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div
                                    class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-green-600 text-xl">📍</span>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-gray-800 mb-1">Office Address</h3>
                                    <p class="text-gray-600">
                                        44 Bentley Avenue,<br> 
                                        Willow Park,<br> 
                                        East London,<br> 
                                        South Africa
                                    </p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div
                                    class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-green-600 text-xl">📞</span>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-gray-800 mb-1">Phone Numbers</h3>
                                    <p class="text-gray-600">
                                        Main: +27 62 109 0221<br>
                                        Mobile: +27 82 345 6789<br>
                                        Fax: +27 11 123 4568
                                    </p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div
                                    class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-green-600 text-xl">📧</span>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-gray-800 mb-1">Email Addresses</h3>
                                    <p class="text-gray-600">
                                        General Inquiries: withinreachtech@gmail.com<br>
                                        Business Development: business@withinreachtech.co.za<br>
                                        Support: support@withinreachtech.co.za
                                    </p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div
                                    class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-green-600 text-xl">⏰</span>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-gray-800 mb-1">Business Hours</h3>
                                    <p class="text-gray-600">
                                        Monday - Friday: 8:00 AM - 5:00 PM<br>
                                        Saturday: 9:00 AM - 1:00 PM<br>
                                        Sunday: Closed<br>
                                        <span class="text-sm italic">Public holidays by appointment</span>
                                    </p>
                                </div>
                            </div>
                        </div>

                        <!-- Social Media Links -->
                        <div class="mt-8">
                            <h3 class="font-semibold text-gray-800 mb-4">Follow Us</h3>
                            <div class="flex space-x-4">
                                <a href="#"
                                    class="w-10 h-10 bg-blue-600 rounded-full flex items-center justify-center text-white hover:bg-blue-700 transition-colors">
                                    <span class="text-sm font-bold">Li</span>
                                </a>
                                <a href="#"
                                    class="w-10 h-10 bg-blue-400 rounded-full flex items-center justify-center text-white hover:bg-blue-500 transition-colors">
                                    <span class="text-sm font-bold">Tw</span>
                                </a>
                                <a href="#"
                                    class="w-10 h-10 bg-blue-800 rounded-full flex items-center justify-center text-white hover:bg-blue-900 transition-colors">
                                    <span class="text-sm font-bold">Fb</span>
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Contact Form -->
                    <div class="bg-gray-50 p-8 rounded-lg">
                        <h2 class="text-2xl font-bold text-gray-800 mb-6">Send Us a Message</h2>

                        <form @submit.prevent="submitForm" class="space-y-6">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-gray-700 font-medium mb-2">First Name *</label>
                                    <input v-model="form.firstName" type="text" required
                                        class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                        placeholder="Enter your first name">
                                </div>
                                <div>
                                    <label class="block text-gray-700 font-medium mb-2">Last Name *</label>
                                    <input v-model="form.lastName" type="text" required
                                        class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                        placeholder="Enter your last name">
                                </div>
                            </div>

                            <div>
                                <label class="block text-gray-700 font-medium mb-2">Email Address *</label>
                                <input v-model="form.email" type="email" required
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                    placeholder="Enter your email address">
                            </div>

                            <div>
                                <label class="block text-gray-700 font-medium mb-2">Phone Number</label>
                                <input v-model="form.phone" type="tel"
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                    placeholder="Enter your phone number">
                            </div>

                            <div>
                                <label class="block text-gray-700 font-medium mb-2">Company Name</label>
                                <input v-model="form.company" type="text"
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                    placeholder="Enter your company name">
                            </div>

                            <div>
                                <label class="block text-gray-700 font-medium mb-2">Service Interest</label>
                                <select v-model="form.service"
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none">
                                    <option value="" disabled>Select a service</option>
                                    <option value="accounting">Accounting Services</option>
                                    <option value="tax">Tax Services</option>
                                    <option value="consulting">Business Consulting</option>
                                    <option value="governance">Corporate Governance</option>
                                    <option value="training">Training Programs</option>
                                    <option value="other">Other</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-gray-700 font-medium mb-2">Message *</label>
                                <textarea v-model="form.message" required rows="5"
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-transparent outline-none"
                                    placeholder="Tell us about your requirements..."></textarea>
                            </div>

                            <button type="submit" :disabled="isSubmitting"
                                class="w-full btn-primary disabled:opacity-50 disabled:cursor-not-allowed">
                                <span v-if="isSubmitting">Sending Message...</span>
                                <span v-else>Send Message</span>
                            </button>
                        </form>

                        <!-- <div v-if="formStatus.message" class="mt-4 p-4 rounded-lg"
                            :class="formStatus.type === 'success' ? 'bg-green-100 text-green-700' : 'bg-red-100 text-red-700'">
                            {{ formStatus.message }}
                        </div> -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Map Section -->
        <section class="bg-gray-100 section-padding">
            <div class="container-max">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Find Our Office</h2>
                    <p class="text-gray-600">Located in the heart of Johannesburg's business district</p>
                </div>

                <!-- Map Placeholder -->
                <div class="bg-gray-300 h-96 rounded-lg flex items-center justify-center">
                    <div class="text-center">
                        <div class="text-4xl mb-4">🗺️</div>
                        <p class="text-gray-600">Interactive Map</p>
                        <p class="text-sm text-gray-500">44 Bentley Avenue, Willow Park, East London, South Africa</p>
                    </div>
                </div>

                <!-- Directions -->
                <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="text-center p-6 bg-white rounded-lg shadow">
                        <div class="text-2xl mb-3">🚗</div>
                        <h3 class="font-semibold mb-2">By Car</h3>
                        <p class="text-sm text-gray-600">Ample parking available. Take M1 to Sandton exit. Professional
                            accounting solutions for businesses of all sizes</p>
                    </div>

                    <div class="text-center p-6 rounded-lg border hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">📊</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Tax Services</h3>
                        <p class="text-gray-600">Expert tax planning and compliance services</p>
                    </div>

                    <div class="text-center p-6 rounded-lg border hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">💡</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Business Consulting</h3>
                        <p class="text-gray-600">Strategic guidance to help your business grow</p>
                    </div>

                    <div class="text-center p-6 rounded-lg border hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">🎓</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Corporate Training</h3>
                        <p class="text-gray-600">Governance and skills development programs</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Mission & Vision Preview -->
        <section class="bg-gray-50 section-padding">
            <div class="container-max">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-3xl font-bold text-gray-800 mb-6">Our Mission</h2>
                        <p class="text-lg text-gray-600 mb-6">
                            To develop and provide innovative, knowledge-based services through high
                            quality partnerships, thus ensuring sustainable empowerment for all our stakeholders.
                        </p>
                        <h2 class="text-3xl font-bold text-gray-800 mb-6">Our Vision</h2>
                        <p class="text-lg text-gray-600 mb-8">
                            To be the preferred provider of competitive knowledge-based services that
                            creates sustainable partnerships with all stakeholders.
                        </p>
                        <NuxtLink to="/about" class="btn-primary">Learn More About Us</NuxtLink>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Our Values</h3>
                        <ul class="space-y-3">
                            <li class="flex items-center">
                                <span class="w-2 h-2 bg-green-600 rounded-full mr-3"></span>
                                <span class="text-gray-700">Excellence in everything we do</span>
                            </li>
                            <li class="flex items-center">
                                <span class="w-2 h-2 bg-green-600 rounded-full mr-3"></span>
                                <span class="text-gray-700">Integrity and transparency</span>
                            </li>
                            <li class="flex items-center">
                                <span class="w-2 h-2 bg-green-600 rounded-full mr-3"></span>
                                <span class="text-gray-700">Innovation and continuous improvement</span>
                            </li>
                            <li class="flex items-center">
                                <span class="w-2 h-2 bg-green-600 rounded-full mr-3"></span>
                                <span class="text-gray-700">Sustainable partnerships</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA Section -->
        <section class="bg-green-600 text-white section-padding">
            <div class="container-max text-center">
                <h2 class="text-3xl font-bold mb-4">Ready to Transform Your Business?</h2>
                <p class="text-xl mb-8">Let's discuss how we can help you achieve your goals</p>
                <NuxtLink to="/contact" class="btn-secondary">Contact Us Today</NuxtLink>
            </div>
        </section>
    </div>
</template>


<script setup lang="ts">
import { reactive, ref } from 'vue';

interface FormModel {
    firstName: string;
    lastName: string;
    email: string;
    phone?: string;
    company?: string;
    service?: string;
    message: string;
}

// Reactive form state
const form = reactive<FormModel>({
    firstName: '',
    lastName: '',
    email: '',
    phone: '',
    company: '',
    service: '',
    message: '',
});

// Track if the form is submitting
const isSubmitting = ref(false);

function submitForm() {
    isSubmitting.value = true;

    // Example: log the form data
    console.log(form);

    // Simulate submission delay
    setTimeout(() => {
        isSubmitting.value = false;
        alert('Form submitted successfully!');
    }, 1000);
}
</script>