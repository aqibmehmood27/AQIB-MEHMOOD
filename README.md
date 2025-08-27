<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pakistan Flood Relief - Donate Now</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .donation-option {
            transition: all 0.3s ease;
        }
        .donation-option:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .progress-bar {
            transition: width 2s ease-in-out;
        }
        .copy-btn {
            transition: all 0.2s ease;
        }
        .copy-btn:hover {
            background-color: #2563eb;
        }
        .donate-btn {
            background: linear-gradient(135deg, #dc2626, #ef4444);
            transition: all 0.3s ease;
        }
        .donate-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(220, 38, 38, 0.3);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/46ec2034-c156-403e-8e91-b0606b2380a1.png" alt="Pakistan Flood Relief Organization Logo - Green crescent and star with water relief symbol" class="h-12 w-12 mr-3 rounded-full">
                    <h1 class="text-2xl font-bold text-green-600">Pakistan Flood Relief</h1>
                </div>
                <nav class="hidden md:flex space-x-6">
                    <a href="#about" class="text-gray-700 hover:text-green-600">About</a>
                    <a href="#donate" class="text-gray-700 hover:text-green-600">Donate</a>
                    <a href="#impact" class="text-gray-700 hover:text-green-600">Impact</a>
                    <a href="#contact" class="text-gray-700 hover:text-green-600">Contact</a>
                </nav>
                <button class="md:hidden text-gray-700">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-r from-blue-900 to-green-900 text-white">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        <div class="container mx-auto px-4 py-20 relative z-10">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-4xl md:text-6xl font-bold mb-6">Emergency Relief for Pakistan Flood Victims</h2>
                <p class="text-xl mb-8">Your donation can provide immediate aid to thousands affected by devastating floods</p>
                <a href="#donate" class="donate-btn text-white px-8 py-4 rounded-full text-lg font-semibold inline-block">
                    Donate Now <i class="fas fa-heart ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Crisis Overview -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold text-gray-800 mb-6">The Crisis in Pakistan</h2>
                    <p class="text-gray-600 mb-4">
                        Pakistan is facing one of the most devastating flood disasters in its history. Millions of people have been displaced, homes destroyed, and livelihoods washed away. The floods have affected over 33 million people across the country.
                    </p>
                    <p class="text-gray-600 mb-6">
                        Your support is urgently needed to provide:
                    </p>
                    <ul class="space-y-2 mb-6">
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-3"></i> Emergency shelter and tents</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-3"></i> Clean drinking water and food supplies</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-3"></i> Medical aid and hygiene kits</li>
                        <li class="flex items-center"><i class="fas fa-check-circle text-green-500 mr-3"></i> Support for rebuilding communities</li>
                    </ul>
                </div>
                <div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1e73b128-ce5a-4660-900a-115d68dde7c9.png" alt="Aerial view of flooded areas in Pakistan showing submerged houses and people in rescue boats" class="rounded-lg shadow-lg w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Donation Section -->
    <section id="donate" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Make a Difference Today</h2>
            
            <!-- Progress Bar -->
            <div class="max-w-4xl mx-auto mb-12">
                <div class="flex justify-between mb-2">
                    <span class="text-gray-600">Raised: $2.5M</span>
                    <span class="text-gray-600">Goal: $10M</span>
                </div>
                <div class="w-full bg-gray-200 rounded-full h-4">
                    <div class="progress-bar bg-green-600 h-4 rounded-full" style="width: 25%"></div>
                </div>
            </div>

            <!-- Donation Options -->
            <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto">
                <!-- International Donation -->
                <div class="donation-option bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">
                        <i class="fas fa-globe-americas text-blue-500 mr-2"></i>
                        International Donation
                    </h3>
                    <p class="text-gray-600 mb-6">Make a direct bank transfer using our IBAN number</p>
                    
                    <div class="bg-gray-50 p-4 rounded-lg mb-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="font-semibold text-gray-700">IBAN Number:</span>
                            <button onclick="copyToClipboard('PK85SADA0000003398580800')" class="copy-btn bg-blue-500 text-white px-3 py-1 rounded text-sm">
                                Copy <i class="fas fa-copy ml-1"></i>
                            </button>
                        </div>
                        <div class="bg-white p-3 rounded border">
                            <code class="text-lg font-mono text-gray-800">PK85SADA0000003398580800</code>
                        </div>
                    </div>

                    <div class="space-y-3">
                        <div class="flex items-center">
                            <i class="fas fa-university text-green-500 mr-3"></i>
                            <span>Bank: Sada Foundation Bank</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-user text-green-500 mr-3"></i>
                            <span>Account Name: Pakistan Flood Relief Fund</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-info-circle text-green-500 mr-3"></i>
                            <span>SWIFT/BIC: SADAPKKA</span>
                        </div>
                    </div>
                </div>

                <!-- Local Donation -->
                <div class="donation-option bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">
                        <i class="fas fa-mobile-alt text-green-500 mr-2"></i>
                        Local Donation (Pakistan)
                    </h3>
                    <p class="text-gray-600 mb-6">Donate instantly via mobile wallets</p>

                    <!-- Easypaisa -->
                    <div class="bg-gray-50 p-4 rounded-lg mb-4">
                        <div class="flex items-center mb-3">
                            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/b1ecf316-8c64-46b6-991a-28d836386fd6.png" alt="Easypaisa mobile payment service logo with orange branding" class="h-8 w-8 mr-3">
                            <span class="font-semibold text-orange-600">Easypaisa</span>
                        </div>
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-gray-700">Send to:</span>
                            <button onclick="copyToClipboard('03398580800')" class="copy-btn bg-orange-500 text-white px-3 py-1 rounded text-sm">
                                Copy <i class="fas fa-copy ml-1"></i>
                            </button>
                        </div>
                        <div class="bg-white p-3 rounded border">
                            <code class="text-lg font-mono text-gray-800">03398580800</code>
                        </div>
                    </div>

                    <!-- SadaPay -->
                    <div class="bg-gray-50 p-4 rounded-lg">
                        <div class="flex items-center mb-3">
                            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0680619e-35c4-49b6-9e63-f3604f8ebdae.png" alt="SadaPay digital wallet logo with purple and pink gradient branding" class="h-8 w-8 mr-3">
                            <span class="font-semibold text-purple-600">SadaPay</span>
                        </div>
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-gray-700">Send to:</span>
                            <button onclick="copyToClipboard('03398580800')" class="copy-btn bg-purple-500 text-white px-3 py-1 rounded text-sm">
                                Copy <i class="fas fa-copy ml-1"></i>
                            </button>
                        </div>
                        <div class="bg-white p-3 rounded border">
                            <code class="text-lg font-mono text-gray-800">03398580800</code>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Quick Donate Form -->
            <div class="max-w-2xl mx-auto mt-12 bg-white p-8 rounded-lg shadow-lg">
                <h3 class="text-2xl font-bold text-center text-gray-800 mb-6">Quick Donation</h3>
                <form class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-gray-700 mb-2">Amount (USD)</label>
                            <input type="number" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-500" placeholder="Enter amount" min="1">
                        </div>
                        <div>
                            <label class="block text-gray-700 mb-2">Payment Method</label>
                            <select class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-500">
                                <option>Credit/Debit Card</option>
                                <option>PayPal</option>
                                <option>Bank Transfer</option>
                            </select>
                        </div>
                    </div>
                    <button type="submit" class="w-full donate-btn text-white py-3 rounded-lg text-lg font-semibold">
                        Donate Securely <i class="fas fa-lock ml-2"></i>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Impact Stories -->
    <section id="impact" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Your Impact Matters</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="w-20 h-20 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-home text-3xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">5,000+ Families</h3>
                    <p class="text-gray-600">Provided with emergency shelter and basic necessities</p>
                </div>
                <div class="text-center">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-tint text-3xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Clean Water</h3>
                    <p class="text-gray-600">Access to safe drinking water for over 50,000 people</p>
                </div>
                <div class="text-center">
                    <div class="w-20 h-20 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-first-aid text-3xl text-red-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Medical Aid</h3>
                    <p class="text-gray-600">Healthcare services provided to 15,000+ affected individuals</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <h4 class="text-lg font-semibold mb-4">Pakistan Flood Relief</h4>
                    <p class="text-gray-300">Providing emergency aid and support to flood-affected communities across Pakistan.</p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Info</h4>
                    <p class="text-gray-300 mb-2"><i class="fas fa-phone mr-2"></i> +92 339 8580800</p>
                    <p class="text-gray-300 mb-2"><i class="fas fa-envelope mr-2"></i> info@pakistanfloodrelief.org</p>
                    <p class="text-gray-300"><i class="fas fa-map-marker-alt mr-2"></i> Islamabad, Pakistan</p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-gray-300 hover:text-white">About the Crisis</a></li>
                        <li><a href="#donate" class="text-gray-300 hover:text-white">Donate Now</a></li>
                        <li><a href="#impact" class="text-gray-300 hover:text-white">Our Impact</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">Privacy Policy</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Stay Connected</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-300 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-300 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-300 hover:text-white"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-300 hover:text-white"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-300">
                <p>© 2024 Pakistan Flood Relief. All rights reserved. Registered Charity #123-456-789</p>
            </div>
        </div>
    </footer>

    <script>
        function copyToClipboard(text) {
            navigator.clipboard.writeText(text).then(() => {
                alert('Copied to clipboard: ' + text);
            }).catch(err => {
                console.error('Failed to copy: ', err);
            });
        }

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Animate progress bar on scroll
        window.addEventListener('scroll', function() {
            const progressBar = document.querySelector('.progress-bar');
            const rect = progressBar.getBoundingClientRect();
            if (rect.top < window.innerHeight && rect.bottom >= 0) {
                progressBar.style.width = '25%';
            }
        });
    </script>
</body>
</html>


