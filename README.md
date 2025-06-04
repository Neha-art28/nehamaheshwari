<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Neha Maheshwari - Corporate Trainer & Leadership Coach</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- SEO Meta Tags -->
  <meta name="description" content="Neha Maheshwari - Corporate Trainer and Leadership Coach with over 14 years of experience in leadership development, soft skills, and sales training.">
  <meta name="keywords" content="corporate trainer, leadership coach, soft skills training, sales training, Neha Maheshwari">
  <meta name="author" content="Neha Maheshwari">
  <style>
    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0, 128, 128, 0.2);
    }
    .blog-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }
    .testimonial-card {
      position: relative;
    }
    .testimonial-card::before {
      content: '"';
      font-size: 5rem;
      position: absolute;
      top: -20px;
      left: 10px;
      color: rgba(0, 128, 128, 0.1);
      font-family: Georgia, serif;
    }
    .headshot {
      border: 3px solid #0d9488;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }
    .certification-item {
      position: relative;
      padding-left: 1.5rem;
    }
    .certification-item::before {
      content: "✓";
      position: absolute;
      left: 0;
      color: #0d9488;
      font-weight: bold;
    }
  </style>
</head>
<body class="bg-gray-50 font-sans flex flex-col md:flex-row min-h-screen">
  <!-- Sidebar -->
  <aside id="sidebar" class="bg-teal-600 text-white w-full md:w-1/5 h-auto md:h-screen fixed top-0 left-0 z-40 transform -translate-x-full md:translate-x-0 transition-transform duration-300 ease-in-out">
    <div class="p-6">
      <h1 class="text-2xl font-bold mb-6">Neha Maheshwari</h1>
      <p class="text-teal-100 mb-8 italic">Corporate Trainer & Leadership Coach</p>
      <ul class="space-y-4">
        <li><a href="#about" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-user mr-3"></i>About</a></li>
        <li><a href="#services" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-cogs mr-3"></i>Services</a></li>
        <li><a href="#portfolio" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-briefcase mr-3"></i>Portfolio</a></li>
        <li><a href="#testimonials" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-quote-left mr-3"></i>Testimonials</a></li>
        <li><a href="#certifications" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-certificate mr-3"></i>Certifications</a></li>
        <li><a href="#blog" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-blog mr-3"></i>Blog</a></li>
        <li><a href="#contact" class="hover:underline flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-envelope mr-3"></i>Contact</a></li>
      </ul>
      <div class="mt-12 pt-6 border-t border-teal-500">
        <div class="flex space-x-4 justify-center">
          <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-white hover:text-teal-200"><i class="fab fa-linkedin-in text-xl"></i></a>
          <a href="mailto:nh.maheshwari@gmail.com" class="text-white hover:text-teal-200"><i class="fas fa-envelope text-xl"></i></a>
        </div>
      </div>
    </div>
  </aside>

  <!-- Main Content -->
  <main class="flex-1 md:ml-[20%]">
    <!-- Mobile Menu Toggle Button -->
    <button id="menu-toggle" class="md:hidden p-4 text-teal-600 focus:outline-none fixed top-0 left-0 z-50 bg-white shadow-md rounded-br-lg">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
      </svg>
    </button>

    <!-- Hero Section -->
    <section id="about" class="bg-teal-50 py-16 text-center">
      <div class="container mx-auto px-4">
        <!-- Headshot with rectangular shape -->
        <img src="https://drive.google.com/thumbnail?id=1wC6t8-m7lM7pY5yLwDaCZQmej0uGd-hV" alt="Neha Maheshwari Headshot" class="w-48 h-56 rounded-lg mx-auto mb-6 object-cover headshot">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Welcome to My Portfolio</h2>
        <p class="text-lg text-gray-800 max-w-2xl mx-auto mb-6">
          I'm Neha Maheshwari, a Corporate Trainer and Leadership Development Coach with over 14 years of experience in knowledge transfer and 7+ years delivering impactful, activity-based training programs.
        </p>
        <div class="max-w-2xl mx-auto bg-white p-6 rounded-lg shadow-md text-left">
          <h3 class="text-xl font-semibold text-teal-600 mb-3">My Expertise</h3>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-2"></i>
              <span>Leadership Development</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-2"></i>
              <span>Soft Skills Training</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-2"></i>
              <span>Sales Training</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-2"></i>
              <span>Employee Engagement</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-4">Services Offered</h2>
        <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Customized training solutions designed to empower individuals and organizations to reach their full potential</p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-teal-50 p-6 rounded-lg shadow-md service-card transition duration-300">
            <div class="text-teal-600 mb-4">
              <i class="fas fa-chess-king text-3xl"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Leadership Development</h3>
            <p class="text-gray-800 mb-4">Enhance managerial effectiveness through tailored workshops and coaching, improving decision-making and team leadership.</p>
            <ul class="text-gray-700 space-y-2">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Executive coaching</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Team leadership</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Strategic thinking</span>
              </li>
            </ul>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg shadow-md service-card transition duration-300">
            <div class="text-teal-600 mb-4">
              <i class="fas fa-comments text-3xl"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Soft Skills Training</h3>
            <p class="text-gray-800 mb-4">Develop communication, emotional intelligence, and interview skills to excel in professional settings.</p>
            <ul class="text-gray-700 space-y-2">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Effective communication</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Emotional intelligence</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Interview preparation</span>
              </li>
            </ul>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg shadow-md service-card transition duration-300">
            <div class="text-teal-600 mb-4">
              <i class="fas fa-chart-line text-3xl"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Sales Training</h3>
            <p class="text-gray-800 mb-4">Boost sales performance with practical strategies for candidate engagement and closing deals.</p>
            <ul class="text-gray-700 space-y-2">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Sales techniques</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Client engagement</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-2 mr-2"></i>
                <span>Negotiation skills</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="bg-teal-50 py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-4">Portfolio of Work</h2>
        <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Selected projects and engagements that demonstrate my training expertise</p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="bg-white p-6 rounded-lg shadow-md">
            <div class="flex items-center mb-4">
              <div class="bg-teal-100 p-3 rounded-full mr-4">
                <i class="fas fa-laptop-code text-teal-600 text-xl"></i>
              </div>
              <h3 class="text-xl font-semibold text-gray-800">Leadership & Sales Training at NeoSOFT Technologies</h3>
            </div>
            <p class="text-gray-800 mb-4">Designed and delivered 25+ interactive training programs and 50+ webinars for 70+ employees, resulting in a 25% increase in sales performance and enhanced managerial effectiveness (2022–Present).</p>
            <div class="bg-gray-100 p-4 rounded">
              <h4 class="font-semibold text-teal-600 mb-2">Key Achievements:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-1">
                <li>Increased sales performance by 25%</li>
                <li>Developed 25+ training programs</li>
                <li>Conducted 50+ webinars</li>
                <li>Trained 70+ employees</li>
              </ul>
            </div>
            <img src="https://via.placeholder.com/600x400/0d9488/ffffff?text=NeoSOFT+Training" alt="NeoSOFT Training" class="mt-4 rounded-lg w-full h-auto">
          </div>
          <div class="bg-white p-6 rounded-lg shadow-md">
            <div class="flex items-center mb-4">
              <div class="bg-teal-100 p-3 rounded-full mr-4">
                <i class="fas fa-chalkboard-teacher text-teal-600 text-xl"></i>
              </div>
              <h3 class="text-xl font-semibold text-gray-800">Teacher Training at The Teacher Foundation</h3>
            </div>
            <p class="text-gray-800 mb-4">Facilitated interactive teacher training in classroom management and leadership sessions for school heads, contributing to academic growth (2019–2022).</p>
            <div class="bg-gray-100 p-4 rounded">
              <h4 class="font-semibold text-teal-600 mb-2">Key Contributions:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-1">
                <li>Improved classroom management techniques</li>
                <li>Enhanced leadership skills for school heads</li>
                <li>Developed interactive training modules</li>
                <li>Contributed to measurable academic growth</li>
              </ul>
            </div>
            <img src="https://via.placeholder.com/600x400/0d9488/ffffff?text=Teacher+Training" alt="Teacher Foundation Training" class="mt-4 rounded-lg w-full h-auto">
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-4">Client Testimonials</h2>
        <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">What clients and participants say about my training programs</p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="bg-teal-50 p-6 rounded-lg testimonial-card">
            <div class="flex items-center mb-4">
              <div class="bg-teal-100 p-2 rounded-full mr-3">
                <i class="fas fa-user-tie text-teal-600"></i>
              </div>
              <div>
                <p class="font-semibold text-gray-800">IT Manager</p>
                <p class="text-sm text-gray-600">NeoSOFT Technologies</p>
              </div>
            </div>
            <p class="italic text-gray-800 relative z-10">"Neha's training programs transformed our team's leadership capabilities, driving measurable performance improvements. Her interactive approach kept everyone engaged, and the practical strategies we learned were immediately applicable to our work."</p>
            <div class="flex mt-4">
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
            </div>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg testimonial-card">
            <div class="flex items-center mb-4">
              <div class="bg-teal-100 p-2 rounded-full mr-3">
                <i class="fas fa-user-graduate text-teal-600"></i>
              </div>
              <div>
                <p class="font-semibold text-gray-800">School Principal</p>
                <p class="text-sm text-gray-600">The Teacher Foundation</p>
              </div>
            </div>
            <p class="italic text-gray-800 relative z-10">"Her engaging workshops equipped our teachers with innovative strategies, enhancing classroom outcomes. Neha's ability to connect with educators at all levels and tailor her approach to our specific needs was truly impressive."</p>
            <div class="flex mt-4">
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star text-yellow-400"></i>
              <i class="fas fa-star-half-alt text-yellow-400"></i>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Certifications Section -->
    <section id="certifications" class="py-16 bg-teal-50">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-4">Certifications</h2>
        <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Professional credentials that validate my expertise</p>
        <div class="max-w-3xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="bg-white p-6 rounded-lg shadow-sm">
            <h3 class="text-lg font-semibold text-teal-600 mb-3">Training & Development</h3>
            <ul class="space-y-2">
              <li class="certification-item">Learning & Development Manager</li>
              <li class="certification-item">Instructional Designer</li>
              <li class="certification-item">Certified Train the Trainer</li>
              <li class="certification-item">Articulate Rise 360</li>
              <li class="certification-item">Learning Management System</li>
            </ul>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm">
            <h3 class="text-lg font-semibold text-teal-600 mb-3">Specialized Certifications</h3>
            <ul class="space-y-2">
              <li class="certification-item">Talent Management Analyst, Middle Earth HR (2024)</li>
              <li class="certification-item">TESOL, University of Maryland, Baltimore County (2016)</li>
              <li class="certification-item">Certified Soft Skills Trainer</li>
              <li class="certification-item">POSH Trainer</li>
              <li class="certification-item">Emotional Intelligence Trainer</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-4">Blog & Resources</h2>
        <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Insights and articles on leadership, training, and professional development</p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          <div class="bg-teal-50 p-6 rounded-lg shadow-sm blog-card transition duration-300">
            <div class="h-40 bg-teal-100 rounded-lg mb-4 flex items-center justify-center">
              <i class="fas fa-chess text-4xl text-teal-600"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">VUCA Leadership</h3>
            <p class="text-gray-800 mb-4">Learn how to lead effectively in a volatile, uncertain, complex, and ambiguous world with adaptable strategies.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_vuca-leadership-activity-7325863257238331393-WsXz" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg shadow-sm blog-card transition duration-300">
            <div class="h-40 bg-teal-100 rounded-lg mb-4 flex items-center justify-center">
              <i class="fas fa-book-open text-4xl text-teal-600"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Leadership Lessons from the Mahabharata: Part 2</h3>
            <p class="text-gray-800 mb-4">Discover strategic decision-making insights drawn from the Mahabharata for modern leadership.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_leadership-mahabharata-lesson2-activity-7315720160089186308-yKTK" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg shadow-sm blog-card transition duration-300">
            <div class="h-40 bg-teal-100 rounded-lg mb-4 flex items-center justify-center">
              <i class="fas fa-brain text-4xl text-teal-600"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Decoding Leadership: Mahabharata & Self-Awareness</h3>
            <p class="text-gray-800 mb-4">Explore how self-awareness, inspired by Mahabharata stories, enhances leadership effectiveness.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_decodingleadership-mahabharata-selfawareness-activity-7310994018165821440-NdWv" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-lg shadow-sm blog-card transition duration-300">
            <div class="h-40 bg-teal-100 rounded-lg mb-4 flex items-center justify-center">
              <i class="fas fa-bullseye text-4xl text-teal-600"></i>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-3">Career Goals & Growth Plans</h3>
            <p class="text-gray-800 mb-4">Learn strategies to set achievable career goals and create effective growth plans for professional success.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_careergoals-growthplans-progress-activity-7298555896756895744-2N3v" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-teal-600 py-16 text-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-4">Get in Touch</h2>
        <p class="text-center text-teal-100 mb-12 max-w-2xl mx-auto">Ready to discuss your training needs? Contact me for a consultation</p>
        <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12">
          <div>
            <h3 class="text-xl font-semibold mb-6">Contact Information</h3>
            <div class="space-y-4">
              <div class="flex items-start">
                <i class="fas fa-envelope text-teal-200 mt-1 mr-4"></i>
                <div>
                  <p class="font-medium">Email</p>
                  <a href="mailto:nh.maheshwari@gmail.com" class="text-teal-100 hover:text-white">nh.maheshwari@gmail.com</a>
                </div>
              </div>
              <div class="flex items-start">
                <i class="fab fa-linkedin-in text-teal-200 mt-1 mr-4"></i>
                <div>
                  <p class="font-medium">LinkedIn</p>
                  <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-teal-100 hover:text-white">linkedin.com/in/nehamaheshwari-corporatetrainer</a>
                </div>
              </div>
              <div class="flex items-start">
                <i class="fas fa-map-marker-alt text-teal-200 mt-1 mr-4"></i>
                <div>
                  <p class="font-medium">Location</p>
                  <p class="text-teal-100">Mumbai, India</p>
                </div>
              </div>
            </div>
            <div class="mt-8">
              <h4 class="font-semibold mb-4">Training Specializations</h4>
              <div class="flex flex-wrap gap-2">
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm">Leadership</span>
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm">Soft Skills</span>
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm">Sales Training</span>
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm">Employee Engagement</span>
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm">Corporate Training</span>
              </div>
            </div>
          </div>
          <div>
            <!-- Formspree Integration -->
            <form action="https://formspree.io/f/yourformid" method="POST" class="bg-white p-6 rounded-lg shadow-md">
              <h3 class="text-xl font-semibold text-gray-800 mb-6">Send Me a Message</h3>
              <div class="mb-4">
                <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
                <input type="text" id="name" name="name" class="w-full p-3 border border-gray-300 rounded focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required>
              </div>
              <div class="mb-4">
                <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
                <input type="email" id="email" name="email" class="w-full p-3 border border-gray-300 rounded focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required>
              </div>
              <div class="mb-4">
                <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Subject</label>
                <input type="text" id="subject" name="subject" class="w-full p-3 border border-gray-300 rounded focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required>
              </div>
              <div class="mb-4">
                <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                <textarea id="message" name="message" rows="4" class="w-full p-3 border border-gray-300 rounded focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required></textarea>
              </div>
              <button type="submit" class="w-full bg-teal-600 text-white py-3 px-4 rounded hover:bg-teal-700 transition duration-300">
                Send Message <i class="fas fa-paper-plane ml-2"></i>
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-teal-700 text-white text-center p-6">
      <div class="container mx-auto">
        <div class="flex justify-center space-x-6 mb-4">
          <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-white hover:text-teal-200">
            <i class="fab fa-linkedin-in text-xl"></i>
          </a>
          <a href="mailto:nh.maheshwari@gmail.com" class="text-white hover:text-teal-200">
            <i class="fas fa-envelope text-xl"></i>
          </a>
        </div>
        <p class="mb-2">© 2025 Neha Maheshwari. All rights reserved.</p>
        <p class="text-sm text-teal-200">Corporate Trainer & Leadership Coach</p>
      </div>
    </footer>
  </main>

  <script>
    const menuToggle = document.getElementById('menu-toggle');
    const sidebar = document.getElementById('sidebar');

    menuToggle.addEventListener('click', () => {
      sidebar.classList.toggle('-translate-x-full');
    });

    function closeSidebar() {
      if (window.innerWidth < 768) {
        sidebar.classList.add('-translate-x-full');
      }
    }

    // Close sidebar when clicking outside on mobile
    document.addEventListener('click', function(event) {
      const isClickInsideSidebar = sidebar.contains(event.target);
      const isClickOnMenuToggle = menuToggle.contains(event.target);
      
      if (!isClickInsideSidebar && !isClickOnMenuToggle && window.innerWidth < 768) {
        sidebar.classList.add('-translate-x-full');
      }
    });
  </script>
</body>
</html>
