<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Neha Maheshwari - Corporate Trainer & Leadership Coach</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
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
      border: 3px solid #0d9488; /* Teal color for border */
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      width: 192px; /* w-48 */
      height: 256px; /* h-64 */
      object-fit: cover; /* Ensures the image covers the area without distortion */
    }
    .certification-item {
      position: relative;
      padding-left: 1.5rem;
    }
    .certification-item::before {
      content: "✓";
      position: absolute;
      left: 0;
      color: #0d9488; /* Teal color */
      font-weight: bold;
    }
    /* Enhanced Sidebar Styling */
    #sidebar {
      background-color: #004d4d; /* Darker Teal for sidebar */
      transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
      box-shadow: 2px 0 10px rgba(0,0,0,0.1);
    }
    #sidebar h1 {
      color: #e0f2f1; /* Lighter teal for title */
    }
    #sidebar p.italic {
      color: #b2dfdb; /* Softer teal for subtitle */
    }
    #sidebar ul li a {
      color: #e0f2f1;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }
    #sidebar ul li a:hover {
      background-color: #00796b; /* Slightly lighter teal on hover */
      color: #ffffff;
      text-decoration: none;
    }
    #sidebar ul li a i {
      color: #80cbc4; /* Icon color */
      transition: color 0.3s ease;
    }
    #sidebar ul li a:hover i {
      color: #ffffff;
    }
    #sidebar .border-t {
      border-color: #00796b; /* Separator color */
    }
    #sidebar .social-icons a i {
      transition: transform 0.2s ease-in-out;
    }
    #sidebar .social-icons a:hover i {
      transform: scale(1.1);
    }
    /* More appealing scrollbar for webkit browsers */
    ::-webkit-scrollbar {
        width: 8px;
    }
    ::-webkit-scrollbar-track {
        background: #f1f1f1;
    }
    ::-webkit-scrollbar-thumb {
        background: #0d9488; /* Teal scrollbar */
        border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
        background: #00796b; /* Darker teal on hover */
    }
  </style>
</head>
<body class="bg-gray-50 font-sans flex flex-col md:flex-row min-h-screen">
  <aside id="sidebar" class="w-full md:w-64 h-auto md:h-screen fixed top-0 left-0 z-40 transform -translate-x-full md:translate-x-0">
    <div class="p-6">
      <h1 class="text-2xl font-bold mb-2">Neha Maheshwari</h1>
      <p class="text-sm mb-8 italic">Corporate Trainer & Leadership Coach</p>
      <ul class="space-y-3">
        <li><a href="#about" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-user mr-3 w-5 text-center"></i>About</a></li>
        <li><a href="#services" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-cogs mr-3 w-5 text-center"></i>Services</a></li>
        <li><a href="#portfolio" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-briefcase mr-3 w-5 text-center"></i>Portfolio</a></li>
        <li><a href="#testimonials" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-quote-left mr-3 w-5 text-center"></i>Testimonials</a></li>
        <li><a href="#certifications" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-certificate mr-3 w-5 text-center"></i>Certifications</a></li>
        <li><a href="#blog" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-blog mr-3 w-5 text-center"></i>Blog</a></li>
        <li><a href="#gallery" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-images mr-3 w-5 text-center"></i>Gallery</a></li>
        <li><a href="#contact" class="flex items-center py-2" onclick="closeSidebar()"><i class="fas fa-envelope mr-3 w-5 text-center"></i>Contact</a></li>
      </ul>
      <div class="mt-10 pt-5 border-t">
        <div class="flex space-x-4 justify-center social-icons">
          <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-white hover:text-teal-200"><i class="fab fa-linkedin-in text-xl"></i></a>
          <a href="mailto:nh.maheshwari@gmail.com" class="text-white hover:text-teal-200"><i class="fas fa-envelope text-xl"></i></a>
        </div>
      </div>
    </div>
  </aside>

  <main class="flex-1 md:ml-64">
    <button id="menu-toggle" class="md:hidden p-3 text-teal-600 focus:outline-none fixed top-2 left-2 z-50 bg-white shadow-lg rounded-md">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
      </svg>
    </button>

    <section id="about" class="bg-teal-50 py-20 md:py-24 text-center">
      <div class="container mx-auto px-4">
        <img src="https://drive.google.com/thumbnail?id=1wC6t8-m7lM7pY5yLwDaCZQmej0uGd-hV" alt="Neha Maheshwari Headshot" class="rounded-lg mx-auto mb-8 headshot">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">Welcome to My Portfolio</h2>
        <p class="text-lg text-gray-700 max-w-2xl mx-auto mb-8">
          I’m Neha Maheshwari, a dedicated Corporate Trainer and Leadership Development Coach with over 14 years of experience in empowering teams through transformative learning. For the past 7+ years, I’ve specialized in crafting dynamic, activity-based training programs that ignite growth, foster engagement, and deliver lasting impact for organizations.
        </p>
        <div class="max-w-3xl mx-auto bg-white p-8 rounded-xl shadow-xl text-left">
          <h3 class="text-2xl font-semibold text-teal-700 mb-5">My Expertise</h3>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-x-6 gap-y-4">
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-3 text-lg"></i>
              <span class="text-gray-700">Leadership Development</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-3 text-lg"></i>
              <span class="text-gray-700">Soft Skills Training</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-3 text-lg"></i>
              <span class="text-gray-700">Sales Training</span>
            </div>
            <div class="flex items-start">
              <i class="fas fa-check-circle text-teal-500 mt-1 mr-3 text-lg"></i>
              <span class="text-gray-700">Employee Engagement</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="services" class="py-20 md:py-24 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Services Offered</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">Customized training solutions designed to empower individuals and organizations to reach their full potential.</p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
          <div class="bg-teal-50 p-8 rounded-xl shadow-lg service-card transition duration-300">
            <div class="text-teal-600 mb-5 text-center">
              <i class="fas fa-chess-king text-4xl"></i>
            </div>
            <h3 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Leadership Development</h3>
            <p class="text-gray-700 mb-5 text-sm">Enhance managerial effectiveness through tailored workshops and coaching, improving decision-making and team leadership.</p>
            <ul class="text-gray-700 space-y-2 text-sm">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Executive coaching</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Team leadership</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Strategic thinking</span>
              </li>
            </ul>
          </div>
          <div class="bg-teal-50 p-8 rounded-xl shadow-lg service-card transition duration-300">
            <div class="text-teal-600 mb-5 text-center">
              <i class="fas fa-comments text-4xl"></i>
            </div>
            <h3 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Soft Skills Training</h3>
            <p class="text-gray-700 mb-5 text-sm">Develop communication, emotional intelligence, and interview skills to excel in professional settings.</p>
            <ul class="text-gray-700 space-y-2 text-sm">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Effective communication</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Emotional intelligence</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Interview preparation</span>
              </li>
            </ul>
          </div>
          <div class="bg-teal-50 p-8 rounded-xl shadow-lg service-card transition duration-300">
            <div class="text-teal-600 mb-5 text-center">
              <i class="fas fa-chart-line text-4xl"></i>
            </div>
            <h3 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Sales Training</h3>
            <p class="text-gray-700 mb-5 text-sm">Boost sales performance with practical strategies for candidate engagement and closing deals.</p>
            <ul class="text-gray-700 space-y-2 text-sm">
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Sales techniques</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Client engagement</span>
              </li>
              <li class="flex items-start">
                <i class="fas fa-circle text-xs text-teal-500 mt-1 mr-3"></i>
                <span>Negotiation skills</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="portfolio" class="bg-teal-50 py-20 md:py-24">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Portfolio of Work</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">Selected projects and engagements that demonstrate my training expertise.</p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
          <!-- Row 1 -->
          <div class="bg-white p-8 rounded-xl shadow-xl h-auto">
            <div class="mb-5">
              <h3 class="text-xl font-semibold text-gray-800">Leadership Training at NeoSOFT Technologies</h3>
            </div>
            <p class="text-gray-700 mb-5 text-base">At NeoSOFT Technologies (2022–Present), I designed and delivered leadership training programs, conducting 25+ workshops to enhance managerial effectiveness for 70+ employees.</p>
            <div class="bg-gray-100 p-5 rounded-lg">
              <h4 class="font-semibold text-teal-700 mb-3 text-base">Key Achievements:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-2 text-sm">
                <li>Developed 25+ leadership workshops</li>
                <li>Trained 70+ employees in managerial skills</li>
                <li>Enhanced decision-making and team leadership</li>
              </ul>
            </div>
          </div>
          <div class="bg-white p-8 rounded-xl shadow-xl h-auto">
            <div class="mb-5">
              <h3 class="text-xl font-semibold text-gray-800">Sales Training at NeoSOFT Technologies</h3>
            </div>
            <p class="text-gray-700 mb-5 text-base">At NeoSOFT Technologies (2022–Present), I led sales training initiatives, delivering 50+ webinars, resulting in a 25% increase in sales performance for the team.</p>
            <div class="bg-gray-100 p-5 rounded-lg">
              <h4 class="font-semibold text-teal-700 mb-3 text-base">Key Achievements:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-2 text-sm">
                <li>Increased sales performance by 25%</li>
                <li>Conducted 50+ sales webinars</li>
                <li>Improved client engagement strategies</li>
              </ul>
            </div>
          </div>
          <!-- Row 2 -->
          <div class="bg-white p-8 rounded-xl shadow-xl h-auto">
            <div class="mb-5">
              <h3 class="text-xl font-semibold text-gray-800">Soft Skills Training</h3>
            </div>
            <p class="text-gray-700 mb-5 text-base">With over 14 years of experience, I’ve delivered soft skills training across various organizations, focusing on communication, emotional intelligence, and interview preparation to drive professional growth.</p>
            <div class="bg-gray-100 p-5 rounded-lg">
              <h4 class="font-semibold text-teal-700 mb-3 text-base">Key Focus Areas:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-2 text-sm">
                <li>Effective communication skills</li>
                <li>Emotional intelligence development</li>
                <li>Interview preparation techniques</li>
              </ul>
            </div>
          </div>
          <div class="bg-white p-8 rounded-xl shadow-xl h-auto">
            <div class="mb-5">
              <h3 class="text-xl font-semibold text-gray-800">Teachers' Training at The Teacher Foundation</h3>
            </div>
            <p class="text-gray-700 mb-5 text-base">At The Teacher Foundation (2019–2022), I facilitated interactive training for teachers in classroom management and leadership for school heads, contributing to academic growth.</p>
            <div class="bg-gray-100 p-5 rounded-lg">
              <h4 class="font-semibold text-teal-700 mb-3 text-base">Key Contributions:</h4>
              <ul class="list-disc list-inside text-gray-700 space-y-2 text-sm">
                <li>Improved classroom management</li>
                <li>Enhanced leadership for school heads</li>
                <li>Supported academic growth</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="testimonials" class="py-20 md:py-24 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Client Testimonials</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">What clients and participants say about my training programs.</p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
          <div class="bg-teal-50 p-8 rounded-xl testimonial-card shadow-lg">
            <div class="flex items-center mb-5">
              <div class="bg-teal-200 p-3 rounded-full mr-4">
                <i class="fas fa-user-tie text-teal-700 text-xl"></i>
              </div>
              <div>
                <p class="font-semibold text-gray-800 text-lg">George, Vice President, International Sales</p>
                <p class="text-sm text-gray-600">NeoSOFT Technologies</p>
              </div>
            </div>
            <p class="italic text-gray-700 relative z-10 text-md leading-relaxed">"Neha's training programs transformed our team's leadership capabilities, driving measurable performance improvements. Her interactive approach kept everyone engaged, and the practical strategies we learned were immediately applicable to our work."</p>
            <div class="flex mt-5 text-yellow-400">
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="bg-teal-50 p-8 rounded-xl testimonial-card shadow-lg">
            <div class="flex items-center mb-5">
              <div class="bg-teal-200 p-3 rounded-full mr-4">
                <i class="fas fa-user-graduate text-teal-700 text-xl"></i>
              </div>
              <div>
                <p class="font-semibold text-gray-800 text-lg">Swapnil Sawakhande, Principal</p>
                <p class="text-sm text-gray-600">The Prestige Public School</p>
              </div>
            </div>
            <p class="italic text-gray-700 relative z-10 text-md leading-relaxed">"Her engaging workshops equipped our teachers with innovative strategies, enhancing classroom outcomes. Neha's ability to connect with educators at all levels and tailor her approach to our specific needs was truly impressive."</p>
            <div class="flex mt-5 text-yellow-400">
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star mr-1"></i>
              <i class="fas fa-star-half-alt"></i>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="certifications" class="py-20 md:py-24 bg-teal-50">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Certifications</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">Professional credentials that validate my expertise.</p>
        <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-10">
          <div class="bg-white p-8 rounded-xl shadow-lg">
            <h3 class="text-xl font-semibold text-teal-700 mb-5">Training & Development</h3>
            <ul class="space-y-3 text-gray-700">
              <li class="certification-item">Learning & Development Manager</li>
              <li class="certification-item">Instructional Designer</li>
              <li class="certification-item">Certified Train the Trainer</li>
              <li class="certification-item">Articulate Rise 360</li>
              <li class="certification-item">Learning Management System</li>
            </ul>
          </div>
          <div class="bg-white p-8 rounded-xl shadow-lg">
            <h3 class="text-xl font-semibold text-teal-700 mb-5">Specialized Certifications</h3>
            <ul class="space-y-3 text-gray-700">
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

    <section id="blog" class="py-20 md:py-24 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Blog & Resources</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">Insights and articles on leadership, training, and professional development.</p>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <div class="bg-teal-50 p-6 rounded-xl shadow-lg blog-card transition duration-300 flex flex-col">
            <div class="h-48 bg-teal-100 rounded-lg mb-5 flex items-center justify-center overflow-hidden">
              <i class="fas fa-chess text-5xl text-teal-600"></i>
            </div>
            <h3 class="text-lg font-semibold text-gray-800 mb-3">VUCA Leadership</h3>
            <p class="text-gray-700 text-sm mb-4 flex-grow">Learn how to lead effectively in a volatile, uncertain, complex, and ambiguous world with adaptable strategies.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_vuca-leadership-activity-7325863257238331393-WsXz" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center mt-auto self-start">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-xl shadow-lg blog-card transition duration-300 flex flex-col">
            <div class="h-48 bg-teal-100 rounded-lg mb-5 flex items-center justify-center overflow-hidden">
              <i class="fas fa-book-open text-5xl text-teal-600"></i>
            </div>
            <h3 class="text-lg font-semibold text-gray-800 mb-3">Leadership Lessons from the Mahabharata: Part 2</h3>
            <p class="text-gray-700 text-sm mb-4 flex-grow">Discover strategic decision-making insights drawn from the Mahabharata for modern leadership.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_leadership-mahabharata-lesson2-activity-7315720160089186308-yKTK" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center mt-auto self-start">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-xl shadow-lg blog-card transition duration-300 flex flex-col">
            <div class="h-48 bg-teal-100 rounded-lg mb-5 flex items-center justify-center overflow-hidden">
              <i class="fas fa-lightbulb text-5xl text-teal-600"></i>
            </div>
            <h3 class="text-lg font-semibold text-gray-800 mb-3">Decoding Leadership: Mahabharata & Self-Awareness</h3>
            <p class="text-gray-700 text-sm mb-4 flex-grow">Explore how self-awareness, inspired by Mahabharata stories, enhances leadership effectiveness.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_decodingleadership-mahabharata-selfawareness-activity-7310994018165821440-NdWv" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center mt-auto self-start">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
          <div class="bg-teal-50 p-6 rounded-xl shadow-lg blog-card transition duration-300 flex flex-col">
            <div class="h-48 bg-teal-100 rounded-lg mb-5 flex items-center justify-center overflow-hidden">
              <i class="fas fa-chart-bar text-5xl text-teal-600"></i>
            </div>
            <h3 class="text-lg font-semibold text-gray-800 mb-3">Career Goals & Growth Plans</h3>
            <p class="text-gray-700 text-sm mb-4 flex-grow">Learn strategies to set achievable career goals and create effective growth plans for professional success.</p>
            <a href="https://www.linkedin.com/posts/nehamaheshwari-corporatetrainer_careergoals-growthplans-progress-activity-7298555896756895744-2N3v" target="_blank" class="text-teal-600 hover:text-teal-800 font-medium inline-flex items-center mt-auto self-start">
              Read More <i class="fas fa-arrow-right ml-2"></i>
            </a>
          </div>
        </div>
      </div>
    </section>

    <section id="gallery" class="py-20 md:py-24 bg-teal-50">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Gallery</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">A visual showcase of my training sessions, highlighting engagement and impact.</p>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 gap-6">
          <div class="bg-white rounded-xl shadow-lg overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1IuZJiewzwG8tE1WvxwbS9oh1PhsB5XqS&sz=w400-h300" alt="Neha Maheshwari leading a corporate training session with participants" class="w-full h-auto">
          </div>
          <div class="bg-white rounded-xl shadow-lg overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1FVo-PIb-bBUBz_hcytdOOZ_i3hcukXGf&sz=w400-h300" alt="Group discussion during a leadership workshop facilitated by Neha Maheshwari" class="w-full h-auto">
          </div>
          <div class="bg-white rounded-xl shadow-lg overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1wLX1IDmZgmp9Qw-8m2qXVH_bnldzrzkF&sz=w400-h300" alt="Neha Maheshwari conducting an interactive soft skills training session" class="w-full h-auto">
          </div>
          <div class="bg-white rounded-xl shadow-lg overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1V5M0x6zrzO-Vf2J14a3fegM9we1Q2OpG&sz=w400-h300" alt="Participants engaged in a team-building activity led by Neha Maheshwari" class="w-full h-auto">
          </div>
        </div>
      </div>
    </section>

    <section id="contact" class="bg-teal-50 py-20 md:py-24">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-5">Reach Out to Me</h2>
        <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">Ready to discuss your training needs? Contact me for a consultation.</p>
        <form action="https://formspree.io/f/yourformid" method="POST" class="max-w-lg mx-auto mb-12">
          <div class="mb-4">
            <label for="name" class="block text-lg text-gray-800 mb-2">Name</label>
            <input type="text" id="name" name="name" class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-500" required>
          </div>
          <div class="mb-4">
            <label for="email" class="block text-lg text-gray-800 mb-2">Email</label>
            <input type="email" id="email" name="email" class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-500" required>
          </div>
          <div class="mb-4">
            <label for="message" class="block text-lg text-gray-800 mb-2">Message</label>
            <textarea id="message" name="message" class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-500" rows="4" required></textarea>
          </div>
          <button type="submit" class="bg-orange-500 text-white px-6 py-3 rounded-lg hover:bg-orange-600 transition duration-300 w-full md:w-auto">Send Message</button>
        </form>
        <p class="text-center text-gray-700 mt-4 mb-12">Or reach me at: <a href="mailto:nh.maheshwari@gmail.com" class="text-teal-600 hover:underline">nh.maheshwari@gmail.com</a> | <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-teal-600 hover:underline">LinkedIn</a></p>
        
        <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-10">
          <div class="bg-white p-6 rounded-xl shadow-lg">
            <h3 class="text-xl font-semibold text-teal-700 mb-5">Contact Information</h3>
            <ul class="space-y-4 text-gray-700">
              <li class="flex items-center">
                <i class="fas fa-envelope text-teal-500 mr-3 text-lg"></i>
                <a href="mailto:nh.maheshwari@gmail.com" class="text-gray-700 hover:text-teal-600">nh.maheshwari@gmail.com</a>
              </li>
              <li class="flex items-center">
                <i class="fab fa-linkedin-in text-teal-500 mr-3 text-lg"></i>
                <a href="https://www.linkedin.com/in/nehamaheshwari-corporatetrainer" target="_blank" class="text-gray-700 hover:text-teal-600 break-words">linkedin.com/in/nehamaheshwari-corporatetrainer</a>
              </li>
              <li class="flex items-center">
                <i class="fas fa-map-marker-alt text-teal-500 mr-3 text-lg"></i>
                <span>Mumbai, India</span>
              </li>
            </ul>
          </div>
          <div class="bg-white p-6 rounded-xl shadow-lg">
            <h3 class="text-xl font-semibold text-teal-700 mb-5">Training Specializations</h3>
            <ul class="space-y-3 text-gray-700">
              <li class="certification-item">Leadership</li>
              <li class="certification-item">Soft Skills</li>
              <li class="certification-item">Sales Training</li>
              <li class="certification-item">Employee Engagement</li>
              <li class="certification-item">Corporate Training</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <footer class="bg-teal-600 text-white text-center p-4">
      <p>© 2025 Neha Maheshwari. All rights reserved.</p>
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
  </script>
</body>
</html>
