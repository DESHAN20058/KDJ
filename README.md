
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K.D. Jayakody | Tech Innovator & Educator</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'brand-blue': '#2C3E50',
                        'brand-accent': '#3498DB',
                        'brand-gray': '#34495E'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gray-100 text-brand-gray font-sans leading-normal tracking-normal">
    <div id="app" class="container mx-auto px-4 max-w-6xl">
        <!-- Header -->
        <header class="flex items-center justify-between py-8">
            <div class="text-3xl font-bold text-brand-blue">
                K.D. Jayakody
                <span class="block text-sm text-brand-accent">Tech Innovator & Educator</span>
            </div>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#about" class="hover:text-brand-accent transition-colors">About</a></li>
                    <li><a href="#skills" class="hover:text-brand-accent transition-colors">Skills</a></li>
                    <li><a href="#projects" class="hover:text-brand-accent transition-colors">Projects</a></li>
                    <li><a href="#contact" class="hover:text-brand-accent transition-colors">Contact</a></li>
                </ul>
            </nav>
        </header>

        <!-- Hero Section -->
        <section class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center py-16">
            <div>
                <h1 class="text-5xl font-bold mb-4 text-brand-blue">Transforming Ideas into Digital Solutions</h1>
                <p class="text-xl mb-6">Full-stack developer, cloud architect, and passionate tech educator committed to continuous learning and innovation.</p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-brand-accent text-white px-6 py-3 rounded-lg hover:bg-opacity-90 transition-all">
                        Get in Touch
                    </a>
                    <a href="#projects" class="border-2 border-brand-accent text-brand-accent px-6 py-3 rounded-lg hover:bg-brand-accent hover:text-white transition-all">
                        View Projects
                    </a>
                </div>
            </div>
            <div class="bg-brand-blue text-white p-8 rounded-lg shadow-lg">
                <h2 class="text-2xl font-bold mb-4">Professional Snapshot</h2>
                <ul class="space-y-3">
                    <li class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-3 text-brand-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z" />
                        </svg>
                        CEO at KDJ Lanka
                    </li>
                    <li class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-3 text-brand-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        DevOps Specialist
                    </li>
                    <li class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-3 text-brand-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                        </svg>
                        ICT Educator
                    </li>
                </ul>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-16 bg-white rounded-lg shadow-md">
            <h2 class="text-3xl font-bold text-center mb-10 text-brand-blue">Technical Skills</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="bg-gray-100 p-6 rounded-lg text-center hover:shadow-lg transition-all">
                    <h3 class="font-bold text-brand-accent mb-2">Full-Stack Development</h3>
                    <p>React, Node.js, Python, JavaScript</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg text-center hover:shadow-lg transition-all">
                    <h3 class="font-bold text-brand-accent mb-2">Cloud Architecture</h3>
                    <p>AWS, Azure, DevOps Principles</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg text-center hover:shadow-lg transition-all">
                    <h3 class="font-bold text-brand-accent mb-2">AI & Machine Learning</h3>
                    <p>AI Enthusiast, OpenAI Developer</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg text-center hover:shadow-lg transition-all">
                    <h3 class="font-bold text-brand-accent mb-2">Cybersecurity</h3>
                    <p>Network Security, Ethical Hacking</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16">
            <div class="bg-brand-blue text-white p-12 rounded-lg">
                <h2 class="text-3xl font-bold mb-6 text-center">Let's Connect</h2>
                <form class="max-w-xl mx-auto">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                        <input type="text" placeholder="Your Name" class="w-full p-3 rounded bg-brand-gray text-white focus:outline-none focus:ring-2 focus:ring-brand-accent">
                        <input type="email" placeholder="Your Email" class="w-full p-3 rounded bg-brand-gray text-white focus:outline-none focus:ring-2 focus:ring-brand-accent">
                    </div>
                    <textarea placeholder="Your Message" class="w-full p-3 rounded mb-4 bg-brand-gray text-white h-32 focus:outline-none focus:ring-2 focus:ring-brand-accent"></textarea>
                    <button class="w-full bg-brand-accent text-white py-3 rounded hover:opacity-90 transition-all">
                        Send Message
                    </button>
                </form>
            </div>
        </section>

        <!-- Footer -->
        <footer class="py-8 text-center">
            <p class="text-brand-gray">&copy; 2024 K.D. Jayakody. All Rights Reserved.</p>
            <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="text-brand-accent hover:text-opacity-80">YouTube</a>
                <a href="#" class="text-brand-accent hover:text-opacity-80">GitHub</a>
                <a href="#" class="text-brand-accent hover:text-opacity-80">LinkedIn</a>
            </div>
        </footer>
    </div>

    <script>
        // Optional: Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
