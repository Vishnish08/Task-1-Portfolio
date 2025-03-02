# Task-1-Portfolio


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Vishakha's Portfolio</title>
</head>
<body class="bg-gray-900 text-white">
    <!-- Navbar -->
    <header class="fixed top-0 left-0 w-full bg-gray-800 p-4 flex justify-between items-center shadow-md">
        <a href="#" class="text-2xl font-bold text-blue-400">Vishakha's Portfolio</a>
        <nav>
            <ul class="flex space-x-6">
                <li><a href="#home" class="hover:text-blue-400">Home</a></li>
                <li><a href="#services" class="hover:text-blue-400">Services</a></li>
                <li><a href="#skills" class="hover:text-blue-400">Skills</a></li>
                <li><a href="#projects" class="hover:text-blue-400">Projects</a></li>
                <li><a href="#contact" class="hover:text-blue-400">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="h-screen flex flex-col justify-center items-center text-center px-6">
        <h1 class="text-5xl font-extrabold mt-4">Vishakha Bhavsar</h1>
        <p class="mt-4 text-lg max-w-2xl">Passionate Web Developer, Data Analyst, and UI/UX Designer dedicated to crafting innovative digital experiences.</p>
        <div class="flex mt-6 space-x-4">
            <a href="#" class="text-blue-400 hover:text-white"><i class="fab fa-instagram"></i> Instagram</a>
            <a href="#" class="text-blue-400 hover:text-white"><i class="fab fa-github"></i> GitHub</a>
            <a href="#" class="text-blue-400 hover:text-white"><i class="fab fa-linkedin"></i> LinkedIn</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 px-6 bg-gray-800 text-center">
        <h2 class="text-3xl font-bold">My Services</h2>
        <div class="grid md:grid-cols-3 gap-8 mt-10">
            <div class="p-6 bg-gray-700 rounded-lg shadow-lg hover:bg-blue-500 transition">
                <h3 class="text-xl font-semibold">Web Development</h3>
                <p class="mt-2">Designing and developing user-friendly, responsive websites with a modern touch.</p>
            </div>
            <div class="p-6 bg-gray-700 rounded-lg shadow-lg hover:bg-blue-500 transition">
                <h3 class="text-xl font-semibold">Data Analysis</h3>
                <p class="mt-2">Turning raw data into actionable insights using advanced analytics and visualization.</p>
            </div>
            <div class="p-6 bg-gray-700 rounded-lg shadow-lg hover:bg-blue-500 transition">
                <h3 class="text-xl font-semibold">UI/UX Design</h3>
                <p class="mt-2">Creating visually appealing and user-friendly digital experiences.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 px-6 text-center">
        <h2 class="text-3xl font-bold">My Skills</h2>
        <div class="flex justify-center mt-8 gap-6">
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">HTML</span>
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">CSS</span>
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">JavaScript</span>
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">Python</span>
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">React</span>
            <span class="px-4 py-2 bg-gray-700 rounded-lg hover:bg-blue-500 transition">Tailwind CSS</span>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 px-6 bg-gray-800 text-center">
        <h2 class="text-3xl font-bold">My Projects</h2>
        <div class="mt-10 grid md:grid-cols-2 gap-8">
            <div class="p-6 bg-gray-700 rounded-lg shadow-lg hover:bg-blue-500 transition">
                <h3 class="text-xl font-semibold">E-commerce Website</h3>
                <p class="mt-2">A fully functional online store with seamless user experience and secure payment integration.</p>
            </div>
            <div class="p-6 bg-gray-700 rounded-lg shadow-lg hover:bg-blue-500 transition">
                <h3 class="text-xl font-semibold">Portfolio Website</h3>
                <p class="mt-2">A personal portfolio showcasing my work, skills, and experience in web development.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-6 bg-gray-900 text-center">
        <h2 class="text-3xl font-bold">Contact Me</h2>
        <p class="mt-4">Email: <a href="mailto:vishakha@example.com" class="text-blue-400 hover:underline">mansvi@example.com</a></p>
        <p>LinkedIn: <a href="#" class="text-blue-400 hover:underline">linkedin.com/in/vishakha-bhavsar-/</a></p>
        <p>Phone: <span class="text-blue-400">+1234567890</span></p>
    </section>

    <!-- Footer -->
    <footer class="py-4 bg-gray-900 text-center text-gray-400">
        <p>&copy; 2025 Vishakha's Portfolio | All Rights Reserved</p>
    </footer>
</body>
</html>
