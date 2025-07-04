<template>
    <div>
        <!-- Hero Section -->
        <section class="bg-gradient-to-br from-green-600 to-green-800 text-white">
            <div class="container-max section-padding">
                <div class="text-center">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6">
                        Integrated Business Solutions
                    </h1>
                    <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto">
                        Empowering South African businesses through innovative accounting services,
                        tax solutions, business consulting, and corporate governance training.
                    </p>
                    <div class="space-x-4">
                        <NuxtLink to="/contact" class="btn-primary">Get Started</NuxtLink>
                        <NuxtLink to="/story" class="btn-secondary">Learn More</NuxtLink>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Overview -->
        <section class="bg-white section-padding">
            <div class="container-max">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Our Services</h2>
                    <p class="text-gray-600 max-w-2xl mx-auto">
                        We provide comprehensive business solutions across all sectors of the economy
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center p-6 rounded-lg border hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">💼</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Accounting Services</h3>
                        <p class="text-gray-600 mb-4">
                            Helping businesses achieve sustainable growth through strategic planning,
                            financial management, and operational excellence.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• Revenue optimization strategies</li>
                            <li>• Cost management solutions</li>
                            <li>• Market expansion support</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mb-6">
                            <span class="text-2xl">📚</span>
                        </div>
                        <h3 class="text-xl font-bold mb-4">Skills Development</h3>
                        <p class="text-gray-600 mb-4">
                            Empowering individuals and teams through comprehensive training programs
                            that build capacity and enhance professional capabilities.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• Corporate governance training</li>
                            <li>• Financial literacy programs</li>
                            <li>• Leadership development</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mb-6">
                            <span class="text-2xl">🤝</span>
                        </div>
                        <h3 class="text-xl font-bold mb-4">Economic Participation</h3>
                        <p class="text-gray-600 mb-4">
                            Facilitating meaningful participation of black-owned businesses in the
                            South African economy through strategic partnerships and support.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• B-BBEE compliance support</li>
                            <li>• Supplier development programs</li>
                            <li>• Enterprise development initiatives</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mb-6">
                            <span class="text-2xl">⚖️</span>
                        </div>
                        <h3 class="text-xl font-bold mb-4">Compliance Excellence</h3>
                        <p class="text-gray-600 mb-4">
                            Ensuring businesses maintain the highest standards of regulatory compliance
                            and corporate governance across all operations.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• Tax compliance management</li>
                            <li>• Regulatory advisory services</li>
                            <li>• Risk management frameworks</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mb-6">
                            <span class="text-2xl">💡</span>
                        </div>
                        <h3 class="text-xl font-bold mb-4">Innovation & Technology</h3>
                        <p class="text-gray-600 mb-4">
                            Driving digital transformation and innovation adoption to help businesses
                            stay competitive in the modern economy.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• Digital process optimization</li>
                            <li>• Technology integration support</li>
                            <li>• Innovation strategy development</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <div class="w-16 h-16 bg-teal-100 rounded-full flex items-center justify-center mb-6">
                            <span class="text-2xl">🌱</span>
                        </div>
                        <h3 class="text-xl font-bold mb-4">Sustainable Development</h3>
                        <p class="text-gray-600 mb-4">
                            Promoting sustainable business practices that contribute to long-term economic
                            growth and social development in South Africa.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1">
                            <li>• ESG consulting services</li>
                            <li>• Sustainability reporting</li>
                            <li>• Community development programs</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Success Stories -->
        <section class="bg-white section-padding">
            <div class="container-max">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Success Stories</h2>
                    <p class="text-gray-600 max-w-2xl mx-auto">
                        Real examples of how our partnerships have created lasting positive impact
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-green-50 p-8 rounded-lg">
                        <h3 class="text-xl font-bold mb-4">Manufacturing Sector Transformation</h3>
                        <p class="text-gray-600 mb-4">
                            Helped a mid-sized manufacturing company achieve 40% revenue growth over
                            18 months through strategic financial planning and operational optimization.
                        </p>
                        <div class="flex items-center text-sm text-green-600 font-medium">
                            <span class="mr-2">📈</span>
                            40% Revenue Growth • 25% Cost Reduction • 15 New Jobs Created
                        </div>
                    </div>

                    <div class="bg-blue-50 p-8 rounded-lg">
                        <h3 class="text-xl font-bold mb-4">SME Development Program</h3>
                        <p class="text-gray-600 mb-4">
                            Supported 50+ small and medium enterprises through our comprehensive
                            business development program, resulting in improved sustainability and growth.
                        </p>
                        <div class="flex items-center text-sm text-blue-600 font-medium">
                            <span class="mr-2">🎯</span>
                            50+ SMEs Supported • 85% Survival Rate • R12M Additional Revenue
                        </div>
                    </div>

                    <div class="bg-purple-50 p-8 rounded-lg">
                        <h3 class="text-xl font-bold mb-4">Corporate Training Initiative</h3>
                        <p class="text-gray-600 mb-4">
                            Delivered comprehensive corporate governance training to over 200 professionals
                            across various industries, enhancing their leadership capabilities.
                        </p>
                        <div class="flex items-center text-sm text-purple-600 font-medium">
                            <span class="mr-2">🎓</span>
                            200+ Professionals • 95% Completion Rate • 20+ Companies
                        </div>
                    </div>

                    <div class="bg-orange-50 p-8 rounded-lg">
                        <h3 class="text-xl font-bold mb-4">Tax Compliance Excellence</h3>
                        <p class="text-gray-600 mb-4">
                            Achieved 100% tax compliance rate for all clients while helping them
                            optimize their tax positions and reduce overall tax burden legally.
                        </p>
                        <div class="flex items-center text-sm text-orange-600 font-medium">
                            <span class="mr-2">✅</span>
                            100% Compliance Rate • R5M Tax Savings • Zero Penalties
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Future Impact Goals -->
        <section class="bg-green-600 text-white section-padding">
            <div class="container-max">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold mb-4">Our 2025-2027 Impact Goals</h2>
                    <p class="text-xl opacity-90">
                        Committed to creating even greater positive impact across South Africa
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center">
                        <div class="text-3xl font-bold mb-2">500+</div>
                        <div class="opacity-90">Businesses to Partner With</div>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold mb-2">1000+</div>
                        <div class="opacity-90">Professionals to Train</div>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold mb-2">R50M+</div>
                        <div class="opacity-90">Economic Value Creation</div>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold mb-2">25+</div>
                        <div class="opacity-90">Industry Sectors</div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>