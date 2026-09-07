<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
    <meta charset='UTF-8'/>
    <meta content='width=device-width, initial-scale=1.0' name='viewport'/>
    <title>Md. Shiful Islam | Modern Web Developer &amp; Tech Specialist</title>

    <!-- SEO Meta Tags -->
    <meta content='Portfolio of Md. Shiful Islam - Professional WordPress &amp; Laravel Web Developer from Rajshahi, Bangladesh.' name='description'/>
    <meta content='Web Developer, WordPress Developer, Laravel Developer, Rajshahi, Bangladesh, Md. Shiful Islam' name='keywords'/>
    <meta content='Md. Shiful Islam' name='author'/>

    <!-- Required Blogger Skin Section -->
    <b:skin><![CDATA[
        /* Required Blogger Default Skin CSS Reset */
        body { margin: 0; padding: 0; }
    ]]></b:skin>

    <!-- Tailwind CSS CDN -->
    <script src='https://cdn.tailwindcss.com'/>
    <script>
    //<![CDATA[
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primary: '#3a86ff',
                        secondary: '#8338ec',
                        darkBg: '#0b0f19',
                        cardBg: 'rgba(255, 255, 255, 0.03)',
                        glassBorder: 'rgba(255, 255, 255, 0.08)',
                    },
                    fontFamily: {
                        sans: ['"Hind Siliguri"', 'sans-serif'],
                    }
                }
            }
        }
    //]]>
    </script>

    <!-- Google Fonts: Hind Siliguri -->
    <link href='https://fonts.googleapis.com' rel='preconnect'/>
    <link crossorigin='anonymous' href='https://fonts.gstatic.com' rel='preconnect'/>
    <link href='https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&amp;display=swap' rel='stylesheet'/>

    <!-- Font Awesome Icons -->
    <link href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css' rel='stylesheet'/>

    <!-- Custom Glassmorphism & Styling CSS -->
    <style>
    /*<![CDATA[*/
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background-color: #0b0f19;
            color: #f3f4f6;
            overflow-x: hidden;
        }

        /* Glassmorphism Classes */
        .glass-panel {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .glass-card:hover {
            border-color: rgba(58, 134, 255, 0.4);
            transform: translateY(-6px);
            box-shadow: 0 10px 30px -10px rgba(58, 134, 255, 0.3);
        }

        /* Project Image Long Scroll Hover Effect */
        .project-img-container {
            position: relative;
            overflow: hidden;
            height: 240px;
        }

        .project-img-container img {
            width: 100%;
            height: auto;
            position: absolute;
            top: 0;
            left: 0;
            transition: transform 4s ease-in-out;
        }

        .project-img-container:hover img {
            transform: translateY(calc(-100% + 240px));
        }

        /* Text Gradient Effect */
        .text-gradient {
            background: linear-gradient(135deg, #3a86ff 0%, #8338ec 50%, #ff007f 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .bg-gradient-btn {
            background: linear-gradient(135deg, #3a86ff 0%, #8338ec 100%);
            transition: all 0.3s ease;
        }

        .bg-gradient-btn:hover {
            opacity: 0.95;
            box-shadow: 0 0 25px rgba(58, 134, 255, 0.5);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0b0f19;
        }
        ::-webkit-scrollbar-thumb {
            background: #1f2937;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #3a86ff;
        }

        /* Floating Background Light Orbs */
        .orb {
            position: absolute;
            border-radius: 50%;
            filter: blur(100px);
            z-index: 0;
            pointer-events: none;
        }
    /*]]>*/
    </style>
</head>
<body class='relative min-h-screen selection:bg-primary selection:text-white'>

    <!-- Blogger Required Section -->
    <b:section class='main' id='main' showaddelement='no'/>

    <!-- Background Orbs -->
    <div class='orb w-96 h-96 bg-primary/20 top-10 left-[-100px]'/>
    <div class='orb w-96 h-96 bg-secondary/20 top-[40%] right-[-100px]'/>
    <div class='orb w-80 h-80 bg-primary/15 bottom-10 left-[20%]'/>

    <!-- Header / Navbar -->
    <header class='fixed top-0 left-0 w-full z-50 transition-all duration-300 py-4 glass-panel border-b border-white/5' id='navbar'>
        <div class='max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between'>
            
            <!-- Ultra-Professional Custom Brand Logo -->
            <a class='flex items-center gap-3.5 group' href='#hero'>
                <div class='relative flex items-center justify-center w-11 h-11 rounded-2xl bg-gradient-to-br from-primary via-indigo-600 to-secondary p-[1.5px] shadow-lg shadow-primary/25 group-hover:shadow-primary/40 group-hover:scale-105 transition-all duration-300'>
                    <div class='w-full h-full bg-darkBg/90 backdrop-blur-md rounded-[14px] flex items-center justify-center'>
                        <span class='text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-primary font-black text-lg tracking-wider'>SI</span>
                    </div>
                </div>
                <div class='flex flex-col'>
                    <span class='text-xl font-extrabold tracking-tight text-white leading-none group-hover:text-primary transition-colors'>
                        Shiful<span class='text-gradient'>.dev</span>
                    </span>
                </div>
            </a>

            <!-- Desktop Navigation -->
            <nav class='hidden md:flex items-center space-x-8 text-sm font-medium'>
                <a class='hover:text-primary transition-colors' href='#hero'>Home</a>
                <a class='hover:text-primary transition-colors' href='#about'>About</a>
                <a class='hover:text-primary transition-colors' href='#skills'>Skills</a>
                <a class='hover:text-primary transition-colors' href='#services'>Services</a>
                <a class='hover:text-primary transition-colors' href='#projects'>Projects</a>
                <a class='hover:text-primary transition-colors' href='#experience'>Experience</a>
                <a class='hover:text-primary transition-colors' href='#contact'>Contact</a>
            </nav>

            <!-- CTA Header Button -->
            <div class='hidden md:block'>
                <a class='px-5 py-2.5 rounded-full bg-gradient-btn text-white font-medium text-sm shadow-lg hover:scale-105 transition-transform inline-block' href='#contact'>
                    Hire Me <i class='fa-solid fa-paper-plane ml-2'/>
                </a>
            </div>

            <!-- Mobile Menu Toggle Button -->
            <button class='md:hidden text-2xl text-gray-300 focus:outline-none' id='menu-btn'>
                <i class='fa-solid fa-bars'/>
            </button>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div class='hidden md:hidden glass-panel border-t border-white/10 px-4 pt-4 pb-6 space-y-3 mt-4' id='mobile-menu'>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#hero'>Home</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#about'>About</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#skills'>Skills</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#services'>Services</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#projects'>Projects</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#experience'>Experience</a>
            <a class='block px-3 py-2 rounded-md text-base font-medium hover:bg-primary/20 hover:text-primary transition' href='#contact'>Contact</a>
        </div>
    </header>

    <!-- Main Content -->
    <main class='relative z-10 pt-20'>

        <!-- HERO SECTION -->
        <section class='min-h-[calc(100vh-80px)] flex items-center justify-center py-16 px-4 relative' id='hero'>
            <div class='max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center'>
                
                <!-- Text Intro -->
                <div class='space-y-6 text-center lg:text-left'>
                    <div class='inline-block px-4 py-1.5 rounded-full glass-panel text-primary text-sm font-semibold tracking-wide border border-primary/30'>
                        👋 Welcome to my portfolio
                    </div>
                    
                    <h1 class='text-4xl sm:text-6xl font-extrabold tracking-tight text-white leading-tight'>
                        Hi, I&#39;m <span class='text-gradient' id='hero-name'>Md. Shiful Islam</span>
                    </h1>

                    <!-- Dynamic Rotating Subtitle -->
                    <h2 class='text-2xl sm:text-3xl font-semibold text-gray-300 flex items-center justify-center lg:justify-start gap-2'>
                        I am a <span class='text-primary font-bold border-r-2 border-primary pr-1' id='typed-text'/>
                    </h2>

                    <p class='text-gray-400 max-w-xl mx-auto lg:mx-0 text-base sm:text-lg leading-relaxed' id='hero-bio'>
                        Passionate Full-Stack Web Developer specialized in building scalable Laravel web applications and custom high-performing WordPress solutions with modern UI/UX.
                    </p>

                    <!-- Buttons -->
                    <div class='flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4'>
                        <a class='px-7 py-3.5 rounded-full bg-gradient-btn text-white font-semibold text-base shadow-xl flex items-center gap-2' href='#projects'>
                            View Projects <i class='fa-solid fa-arrow-right'/>
                        </a>
                        <a class='px-7 py-3.5 rounded-full glass-panel hover:bg-white/10 text-white font-semibold text-base border border-white/20 transition flex items-center gap-2' href='#contact'>
                            Contact Me <i class='fa-solid fa-envelope'/>
                        </a>
                    </div>

                    <!-- Social Media Links -->
                    <div class='pt-6 flex items-center justify-center lg:justify-start space-x-5 text-xl' id='hero-socials'>
                        <!-- Social links dynamically populated -->
                    </div>
                </div>

                <!-- Clean Profile Image Visual (Your Image Linked Directly) -->
                <div class='flex justify-center relative'>
                    <div class='relative w-72 h-72 sm:w-96 sm:h-96'>
                        <!-- Glowing Animated Backdrop -->
                        <div class='absolute inset-0 rounded-3xl bg-gradient-to-tr from-primary to-secondary blur-2xl opacity-40 animate-pulse'/>
                        
                        <!-- Profile Card container -->
                        <div class='relative w-full h-full rounded-3xl p-3 glass-panel overflow-hidden shadow-2xl border border-white/20'>
                            <img alt='Md. Shiful Islam' class='w-full h-full object-cover rounded-2xl' id='profile-img' src='https://ibb.co.com/8npFJPsD'/>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- ABOUT SECTION -->
        <section class='py-20 px-4' id='about'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>About <span class='text-gradient'>Me</span></h2>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-1 lg:grid-cols-2 gap-12 items-center'>
                    <!-- Personal Info Card -->
                    <div class='glass-card p-8 rounded-2xl space-y-6 border border-white/10'>
                        <h3 class='text-2xl font-bold text-white'>Experienced Web Developer based in Rajshahi, Bangladesh</h3>
                        <p class='text-gray-300 leading-relaxed' id='about-text-1'>
                            With years of experience in web development, I craft fast, scalable, and visually impressive websites tailored for modern businesses. My primary focus is turning complex ideas into clean, functional code.
                        </p>
                        <p class='text-gray-400 leading-relaxed' id='about-text-2'>
                            I specialize in PHP, Laravel Framework, MySQL, WordPress Theme &amp; Plugin Customization, Tailwind CSS, and REST API Integration.
                        </p>

                        <!-- Quick Info Grid -->
                        <div class='grid grid-cols-1 sm:grid-cols-2 gap-4 pt-4 border-t border-white/10 text-sm'>
                            <div><span class='text-gray-400'>Name:</span> <span class='text-white font-medium' id='info-name'>Md. Shiful Islam</span></div>
                            <div><span class='text-gray-400'>Phone:</span> <span class='text-white font-medium' id='info-phone'>+88 01736-101177</span></div>
                            <div><span class='text-gray-400'>Email:</span> <span class='text-white font-medium break-all' id='info-email'>saifulkhan9347441@gmail.com</span></div>
                            <div><span class='text-gray-400'>Location:</span> <span class='text-white font-medium' id='info-location'>Rajshahi, Bangladesh</span></div>
                        </div>
                    </div>

                    <!-- Stats / Experience Counter Cards -->
                    <div class='grid grid-cols-2 gap-6'>
                        <div class='glass-card p-6 rounded-2xl text-center space-y-2'>
                            <h4 class='text-4xl font-extrabold text-gradient' id='stat-exp'>5+</h4>
                            <p class='text-gray-300 text-sm font-medium'>Years Experience</p>
                        </div>
                        <div class='glass-card p-6 rounded-2xl text-center space-y-2'>
                            <h4 class='text-4xl font-extrabold text-gradient' id='stat-projects'>120+</h4>
                            <p class='text-gray-300 text-sm font-medium'>Completed Projects</p>
                        </div>
                        <div class='glass-card p-6 rounded-2xl text-center space-y-2'>
                            <h4 class='text-4xl font-extrabold text-gradient' id='stat-clients'>80+</h4>
                            <p class='text-gray-300 text-sm font-medium'>Happy Clients</p>
                        </div>
                        <div class='glass-card p-6 rounded-2xl text-center space-y-2'>
                            <h4 class='text-4xl font-extrabold text-gradient'>100%</h4>
                            <p class='text-gray-300 text-sm font-medium'>Satisfaction Rate</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SKILLS SECTION -->
        <section class='py-20 px-4 bg-black/20' id='skills'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>Technical <span class='text-gradient'>Skills</span></h2>
                    <p class='text-gray-400 mt-2'>Technologies and tools I work with daily</p>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-6' id='skills-container'>
                    <!-- Populated dynamically via JS -->
                </div>
            </div>
        </section>

        <!-- SERVICES SECTION -->
        <section class='py-20 px-4' id='services'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>My <span class='text-gradient'>Services</span></h2>
                    <p class='text-gray-400 mt-2'>High-quality web development services to elevate your brand</p>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8' id='services-container'>
                    <!-- Populated dynamically via JS -->
                </div>
            </div>
        </section>

        <!-- PROJECTS / PORTFOLIO SECTION -->
        <section class='py-20 px-4 bg-black/20' id='projects'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>Featured <span class='text-gradient'>Projects</span></h2>
                    <p class='text-gray-400 mt-2'>Hover on image to view full page preview</p>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8' id='projects-container'>
                    <!-- Populated dynamically via JS -->
                </div>
            </div>
        </section>

        <!-- EXPERIENCE SECTION -->
        <section class='py-20 px-4' id='experience'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>Work <span class='text-gradient'>Experience</span></h2>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='max-w-4xl mx-auto space-y-8 relative before:absolute before:inset-0 before:left-4 sm:before:left-1/2 before:-ml-0.5 before:w-0.5 before:bg-gradient-to-b before:from-primary before:to-secondary' id='experience-container'>
                    <!-- Timeline Items populated dynamically -->
                </div>
            </div>
        </section>

        <!-- TESTIMONIALS SECTION -->
        <section class='py-20 px-4 bg-black/20' id='testimonials'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>Client <span class='text-gradient'>Feedback</span></h2>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-1 md:grid-cols-3 gap-8' id='testimonials-container'>
                    <!-- Populated dynamically via JS -->
                </div>
            </div>
        </section>

        <!-- CONTACT SECTION -->
        <section class='py-20 px-4 relative' id='contact'>
            <div class='max-w-7xl mx-auto'>
                <div class='text-center mb-16'>
                    <h2 class='text-3xl sm:text-4xl font-bold text-white tracking-wide'>Get In <span class='text-gradient'>Touch</span></h2>
                    <p class='text-gray-400 mt-2'>Have a project in mind? Let&#39;s build something awesome together!</p>
                    <div class='w-20 h-1 bg-primary mx-auto mt-3 rounded-full'/>
                </div>

                <div class='grid grid-cols-1 lg:grid-cols-3 gap-8 items-start'>
                    <!-- Contact Cards -->
                    <div class='space-y-6 lg:col-span-1'>
                        <div class='glass-card p-6 rounded-2xl flex items-center space-x-4'>
                            <div class='w-12 h-12 rounded-xl bg-primary/20 text-primary flex items-center justify-center text-xl shrink-0'>
                                <i class='fa-solid fa-phone'/>
                            </div>
                            <div>
                                <h4 class='text-gray-400 text-xs'>Call Me</h4>
                                <p class='text-white font-medium text-sm sm:text-base mt-1' id='contact-phone-val'/>
                            </div>
                        </div>

                        <div class='glass-card p-6 rounded-2xl flex items-center space-x-4'>
                            <div class='w-12 h-12 rounded-xl bg-secondary/20 text-secondary flex items-center justify-center text-xl shrink-0'>
                                <i class='fa-solid fa-envelope'/>
                            </div>
                            <div>
                                <h4 class='text-gray-400 text-xs'>Email Me</h4>
                                <p class='text-white font-medium text-sm sm:text-base mt-1 break-all' id='contact-email-val'/>
                            </div>
                        </div>

                        <div class='glass-card p-6 rounded-2xl flex items-center space-x-4'>
                            <div class='w-12 h-12 rounded-xl bg-primary/20 text-primary flex items-center justify-center text-xl shrink-0'>
                                <i class='fa-solid fa-location-dot'/>
                            </div>
                            <div>
                                <h4 class='text-gray-400 text-xs'>Location</h4>
                                <p class='text-white font-medium text-sm sm:text-base mt-1' id='contact-location-val'/>
                            </div>
                        </div>
                    </div>

                    <!-- Contact Form (Telegram API Integrated) -->
                    <div class='glass-card p-8 rounded-2xl border border-white/10 lg:col-span-2'>
                        <form class='space-y-6' id='contact-form'>
                            <div class='grid grid-cols-1 sm:grid-cols-2 gap-6'>
                                <div>
                                    <label class='block text-sm font-medium text-gray-300 mb-2'>Your Name *</label>
                                    <input class='w-full px-4 py-3 rounded-xl bg-white/5 border border-white/10 text-white placeholder-gray-500 focus:outline-none focus:border-primary transition' id='form-name' placeholder='John Doe' required='required' type='text'/>
                                </div>
                                <div>
                                    <label class='block text-sm font-medium text-gray-300 mb-2'>Phone Number *</label>
                                    <input class='w-full px-4 py-3 rounded-xl bg-white/5 border border-white/10 text-white placeholder-gray-500 focus:outline-none focus:border-primary transition' id='form-phone' placeholder='+88 01700-000000' required='required' type='tel'/>
                                </div>
                            </div>

                            <div>
                                <label class='block text-sm font-medium text-gray-300 mb-2'>Your Email *</label>
                                <input class='w-full px-4 py-3 rounded-xl bg-white/5 border border-white/10 text-white placeholder-gray-500 focus:outline-none focus:border-primary transition' id='form-email' placeholder='example@domain.com' required='required' type='email'/>
                            </div>

                            <div>
                                <label class='block text-sm font-medium text-gray-300 mb-2'>Your Message *</label>
                                <textarea class='w-full px-4 py-3 rounded-xl bg-white/5 border border-white/10 text-white placeholder-gray-500 focus:outline-none focus:border-primary transition' id='form-message' placeholder='Tell me about your project...' required='required' rows='5'/>
                            </div>

                            <button class='w-full py-4 rounded-xl bg-gradient-btn text-white font-semibold text-lg shadow-xl hover:scale-[1.01] transition-transform flex items-center justify-center gap-2' id='submit-btn' type='submit'>
                                <span>Send Message</span> <i class='fa-solid fa-paper-plane'/>
                            </button>

                            <!-- Alert Box -->
                            <div class='hidden p-4 rounded-xl text-center text-sm font-medium' id='form-status'/>
                        </form>
                    </div>
                </div>

                <!-- GOOGLE MAP SECTION -->
                <div class='mt-16 glass-card p-3 rounded-2xl overflow-hidden border border-white/10'>
                    <iframe allowfullscreen='' class='w-full h-80 rounded-xl filter grayscale contrast-125 opacity-80 hover:grayscale-0 transition-all duration-500' id='google-map-iframe' loading='lazy' src='' style='border:0;'/>
                </div>

            </div>
        </section>

    </main>

    <!-- FOOTER -->
    <footer class='glass-panel border-t border-white/10 py-8 text-center text-gray-400 text-sm relative z-10'>
        <div class='max-w-7xl mx-auto px-4 flex flex-col sm:flex-row items-center justify-between gap-4'>
            <p>&#169; 2026 <span class='text-white font-semibold' id='footer-name'>Md. Shiful Islam</span>. All Rights Reserved.</p>
            <div class='flex space-x-6 text-lg' id='footer-socials'>
                <!-- Dynamically populated -->
            </div>
        </div>
    </footer>

    <!-- DYNAMIC DATA & APP LOGIC -->
    <script>
    //<![CDATA[
        /**
         * ==========================================
         * DYNAMIC DATA CONFIGURATION
         * ==========================================
         */
        const PORTFOLIO_DATA = {
            // Personal Info
            name: "Md. Shiful Islam",
            shortName: "Shiful",
            phone: "+88 01736-101177",
            email: "saifulkhan9347441@gmail.com",
            location: "Rajshahi, Bangladesh",
            
            // Direct Blogger Image URL
            profileImage: "https://blogger.googleusercontent.com/img/a/AVvXsEj7cl0VYwjiTqxz0UG4HNCFOSij3CbsR2-8uBBh9fqH3rINYOvLHRMow6tr-9F6by13pTxIt7xOI7WTPohWYJBQO2AYskbyp1m_T_dArbn4Jptb6gvzxuPc500Wo20fKPGAlhIK6mK5Xk4byEORn-JZgCw01V7hYT79AJJ290JEhKFuncfSqkdGDqoq=s1600",
            
            // Rotating Subtitle Words (Hero Section)
            roles: ["Laravel Developer", "WordPress Expert", "Full-Stack Engineer", "UI/UX Specialist"],

            // Bio / About
            heroBio: "Passionate Full-Stack Web Developer specialized in building scalable Laravel web applications and custom high-performing WordPress solutions with modern UI/UX.",
            aboutText1: "With over 5 years of professional web development experience, I help businesses build modern, robust, and scalable digital solutions. I prioritize clean code architecture and smooth user experiences.",
            aboutText2: "Expertise in custom WordPress theme & plugin development, Laravel MVC architecture, RESTful APIs, MySQL database design, and Tailwind CSS.",

            // Stats
            stats: {
                experience: "5+",
                projects: "120+",
                clients: "80+"
            },

            // Social Media Links
            socialLinks: [
                { icon: "fa-brands fa-github", url: "https://github.com" },
                { icon: "fa-brands fa-linkedin", url: "https://linkedin.com" },
                { icon: "fa-brands fa-facebook", url: "https://facebook.com" },
                { icon: "fa-brands fa-twitter", url: "https://twitter.com" }
            ],

            // Skills List
            skills: [
                { name: "Laravel", icon: "fa-brands fa-laravel", color: "text-red-500" },
                { name: "WordPress", icon: "fa-brands fa-wordpress", color: "text-blue-400" },
                { name: "PHP", icon: "fa-brands fa-php", color: "text-purple-400" },
                { name: "JavaScript", icon: "fa-brands fa-js", color: "text-yellow-400" },
                { name: "Tailwind CSS", icon: "fa-solid fa-code", color: "text-cyan-400" },
                { name: "MySQL", icon: "fa-solid fa-database", color: "text-blue-500" },
                { name: "HTML5", icon: "fa-brands fa-html5", color: "text-orange-500" },
                { name: "CSS3", icon: "fa-brands fa-css3-alt", color: "text-blue-600" },
                { name: "Git & GitHub", icon: "fa-brands fa-github", color: "text-gray-300" },
                { name: "REST API", icon: "fa-solid fa-network-wired", color: "text-emerald-400" },
                { name: "Vue.js", icon: "fa-brands fa-vuejs", color: "text-emerald-500" },
                { name: "Figma", icon: "fa-brands fa-figma", color: "text-pink-500" }
            ],

            // Services
            services: [
                {
                    title: "Laravel Web Apps",
                    description: "Custom, highly secure, and scalable web applications engineered with clean MVC Laravel framework.",
                    icon: "fa-brands fa-laravel"
                },
                {
                    title: "WordPress Development",
                    description: "Custom WP themes, plugins customization, WooCommerce online stores, and speed optimization.",
                    icon: "fa-brands fa-wordpress"
                },
                {
                    title: "API Development & Integration",
                    description: "RESTful API creation and third-party API integration like payment gateways, SMS, and CRMs.",
                    icon: "fa-solid fa-gears"
                }
            ],

            // Portfolio / Projects
            projects: [
                {
                    title: "E-Commerce Enterprise Platform",
                    category: "Laravel / Vue.js",
                    image: "https://images.unsplash.com/photo-1557821552-17105176677c?auto=format&amp;fit=crop&amp;w=800&amp;q=80",
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "Corporate Agency Portal",
                    category: "WordPress Custom Theme",
                    image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&amp;fit=crop&amp;w=800&amp;q=80",
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "SaaS Management Dashboard",
                    category: "Laravel & Tailwind CSS",
                    image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&amp;fit=crop&amp;w=800&amp;q=80",
                    liveUrl: "#",
                    githubUrl: "#"
                }
            ],

            // Experience
            experience: [
                {
                    role: "Senior Laravel Developer",
                    company: "Tech Solutions Ltd.",
                    period: "2023 - Present",
                    description: "Leading the backend architecture for enterprise SaaS products using Laravel and MySQL."
                },
                {
                    role: "WordPress Specialist",
                    company: "Digital Web Agency",
                    period: "2021 - 2023",
                    description: "Developed 50+ custom WordPress themes and WooCommerce web applications."
                }
            ],

            // Testimonials
            testimonials: [
                {
                    name: "Alex Morgan",
                    role: "CEO, TechBrand USA",
                    text: "Shiful is an outstanding Laravel developer. He delivered our SaaS product well ahead of deadline with top-notch code quality."
                },
                {
                    name: "David Miller",
                    role: "Founder, WPify Inc.",
                    text: "His WordPress theme customization skills are top tier. Very responsive and extremely professional."
                },
                {
                    name: "Sarah Khan",
                    role: "Marketing Director",
                    text: "Extremely clean UI design and smooth integration. Highly recommended for web projects!"
                }
            ],

            // Google Map Embedded URL (Rajshahi Location)
            googleMapUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14532.583151834244!2d88.5834887!3d24.3745239!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39fbefa96a38d031%3A0x10f93a9c68d6f512!2sRajshahi%2C%20Bangladesh!5e0!3m2!1sen!2sbd!4v1700000000000!5m2!1sen!2sbd",

            // API INTEGRATIONS
            telegramBotToken: "YOUR_TELEGRAM_BOT_TOKEN",
            telegramChatId: "YOUR_TELEGRAM_CHAT_ID"
        };

        // RENDER DATA & INITIALIZE UI LOGIC
        document.addEventListener("DOMContentLoaded", function() {
            
            // Populate Personal Info
            document.getElementById("hero-name").innerText = PORTFOLIO_DATA.name;
            document.getElementById("hero-bio").innerText = PORTFOLIO_DATA.heroBio;
            
            var profileImgEl = document.getElementById("profile-img");
            if (profileImgEl) {
                profileImgEl.src = PORTFOLIO_DATA.profileImage;
            }

            document.getElementById("info-name").innerText = PORTFOLIO_DATA.name;
            document.getElementById("info-phone").innerText = PORTFOLIO_DATA.phone;
            document.getElementById("info-email").innerText = PORTFOLIO_DATA.email;
            document.getElementById("info-location").innerText = PORTFOLIO_DATA.location;
            document.getElementById("about-text-1").innerText = PORTFOLIO_DATA.aboutText1;
            document.getElementById("about-text-2").innerText = PORTFOLIO_DATA.aboutText2;

            document.getElementById("stat-exp").innerText = PORTFOLIO_DATA.stats.experience;
            document.getElementById("stat-projects").innerText = PORTFOLIO_DATA.stats.projects;
            document.getElementById("stat-clients").innerText = PORTFOLIO_DATA.stats.clients;

            document.getElementById("contact-phone-val").innerText = PORTFOLIO_DATA.phone;
            document.getElementById("contact-email-val").innerText = PORTFOLIO_DATA.email;
            document.getElementById("contact-location-val").innerText = PORTFOLIO_DATA.location;
            document.getElementById("footer-name").innerText = PORTFOLIO_DATA.name;

            document.getElementById("google-map-iframe").src = PORTFOLIO_DATA.googleMapUrl;

            // Render Social Links
            var socialContainers = [document.getElementById("hero-socials"), document.getElementById("footer-socials")];
            socialContainers.forEach(function(container) {
                if(!container) return;
                container.innerHTML = PORTFOLIO_DATA.socialLinks.map(function(s) {
                    return '<a href="' + s.url + '" target="_blank" class="text-gray-400 hover:text-primary transition-colors"><i class="' + s.icon + '"></i></a>';
                }).join('');
            });

            // Render Skills
            var skillsContainer = document.getElementById("skills-container");
            if (skillsContainer) {
                skillsContainer.innerHTML = PORTFOLIO_DATA.skills.map(function(skill) {
                    return '<div class="glass-card p-5 rounded-2xl flex flex-col items-center justify-center space-y-3"><i class="' + skill.icon + ' text-4xl ' + skill.color + '"></i><span class="text-sm font-semibold text-gray-200">' + skill.name + '</span></div>';
                }).join('');
            }

            // Render Services
            var servicesContainer = document.getElementById("services-container");
            if (servicesContainer) {
                servicesContainer.innerHTML = PORTFOLIO_DATA.services.map(function(ser) {
                    return '<div class="glass-card p-8 rounded-2xl space-y-4"><div class="w-14 h-14 rounded-2xl bg-gradient-btn flex items-center justify-center text-white text-2xl shadow-lg"><i class="' + ser.icon + '"></i></div><h3 class="text-xl font-bold text-white">' + ser.title + '</h3><p class="text-gray-400 text-sm leading-relaxed">' + ser.description + '</p></div>';
                }).join('');
            }

            // Render Projects
            var projectsContainer = document.getElementById("projects-container");
            if (projectsContainer) {
                projectsContainer.innerHTML = PORTFOLIO_DATA.projects.map(function(p) {
                    return '<div class="glass-card rounded-2xl overflow-hidden group"><div class="project-img-container"><img src="' + p.image + '" alt="' + p.title + '"/></div><div class="p-6 space-y-3"><span class="text-xs font-semibold text-primary uppercase tracking-wider">' + p.category + '</span><h3 class="text-xl font-bold text-white">' + p.title + '</h3><div class="flex items-center space-x-4 pt-2"><a href="' + p.liveUrl + '" target="_blank" class="px-4 py-2 rounded-lg bg-primary text-white text-xs font-semibold hover:bg-primary/80 transition flex items-center gap-1">Live Preview <i class="fa-solid fa-arrow-up-right-from-square"></i></a><a href="' + p.githubUrl + '" target="_blank" class="px-4 py-2 rounded-lg glass-panel text-gray-300 hover:text-white text-xs font-semibold border border-white/10 transition flex items-center gap-1">Details <i class="fa-brands fa-github"></i></a></div></div></div>';
                }).join('');
            }

            // Render Experience Timeline
            var expContainer = document.getElementById("experience-container");
            if (expContainer) {
                expContainer.innerHTML = PORTFOLIO_DATA.experience.map(function(exp) {
                    return '<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group"><div class="flex items-center justify-center w-8 h-8 rounded-full bg-primary text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2"><i class="fa-solid fa-briefcase text-xs"></i></div><div class="w-[calc(100%-2.5rem)] md:w-[calc(50%-2.5rem)] glass-card p-6 rounded-2xl border border-white/10"><span class="text-xs font-bold text-primary">' + exp.period + '</span><h3 class="text-lg font-bold text-white mt-1">' + exp.role + '</h3><p class="text-xs font-medium text-gray-400">' + exp.company + '</p><p class="text-sm text-gray-300 mt-2">' + exp.description + '</p></div></div>';
                }).join('');
            }

            // Render Testimonials
            var testContainer = document.getElementById("testimonials-container");
            if (testContainer) {
                testContainer.innerHTML = PORTFOLIO_DATA.testimonials.map(function(t) {
                    return '<div class="glass-card p-6 rounded-2xl space-y-4"><div class="text-yellow-400 space-x-1 text-sm"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div><p class="text-gray-300 text-sm italic">"' + t.text + '"</p><div class="pt-2 border-t border-white/10"><h4 class="text-white font-bold text-sm">' + t.name + '</h4><p class="text-gray-400 text-xs">' + t.role + '</p></div></div>';
                }).join('');
            }

            // TYPING ANIMATION
            var typedTextSpan = document.getElementById("typed-text");
            var roles = PORTFOLIO_DATA.roles;
            var roleIndex = 0;
            var charIndex = 0;

            function type() {
                if (charIndex < roles[roleIndex].length) {
                    typedTextSpan.textContent += roles[roleIndex].charAt(charIndex);
                    charIndex++;
                    setTimeout(type, 100);
                } else {
                    setTimeout(erase, 2000);
                }
            }

            function erase() {
                if (charIndex > 0) {
                    typedTextSpan.textContent = roles[roleIndex].substring(0, charIndex - 1);
                    charIndex--;
                    setTimeout(erase, 50);
                } else {
                    roleIndex = (roleIndex + 1) % roles.length;
                    setTimeout(type, 500);
                }
            }
            if(typedTextSpan) type();

            // MOBILE MENU TOGGLE
            var menuBtn = document.getElementById("menu-btn");
            var mobileMenu = document.getElementById("mobile-menu");
            if(menuBtn && mobileMenu) {
                menuBtn.addEventListener("click", function() {
                    mobileMenu.classList.toggle("hidden");
                });
            }

            // CONTACT FORM SUBMISSION
            var contactForm = document.getElementById("contact-form");
            var formStatus = document.getElementById("form-status");

            if(contactForm) {
                contactForm.addEventListener("submit", function(e) {
                    e.preventDefault();

                    var name = document.getElementById("form-name").value;
                    var phone = document.getElementById("form-phone").value;
                    var email = document.getElementById("form-email").value;
                    var message = document.getElementById("form-message").value;

                    formStatus.classList.remove("hidden", "bg-red-500/20", "text-red-400", "bg-green-500/20", "text-green-400");
                    formStatus.classList.add("bg-primary/20", "text-primary");
                    formStatus.innerText = "Sending message...";

                    var telegramMessage = " New Website Inquiry\n\n Name: " + name + "\n Phone: " + phone + "\n Email: " + email + "\n Message: " + message;

                    if (PORTFOLIO_DATA.telegramBotToken !== "YOUR_TELEGRAM_BOT_TOKEN") {
                        fetch("https://api.telegram.org/bot" + PORTFOLIO_DATA.telegramBotToken + "/sendMessage", {
                            method: "POST",
                            headers: { "Content-Type": "application/json" },
                            body: JSON.stringify({
                                chat_id: PORTFOLIO_DATA.telegramChatId,
                                text: telegramMessage
                            })
                        }).then(function() {
                            formStatus.classList.remove("bg-primary/20", "text-primary");
                            formStatus.classList.add("bg-green-500/20", "text-green-400");
                            formStatus.innerText = "✓ Success! Your message has been sent successfully.";
                            contactForm.reset();
                        }).catch(function() {
                            formStatus.classList.remove("bg-primary/20", "text-primary");
                            formStatus.classList.add("bg-red-500/20", "text-red-400");
                            formStatus.innerText = "✕ Oops! Something went wrong. Please try again later.";
                        });
                    } else {
                        setTimeout(function() {
                            formStatus.classList.remove("bg-primary/20", "text-primary");
                            formStatus.classList.add("bg-green-500/20", "text-green-400");
                            formStatus.innerText = "✓ Success! Your message has been received.";
                            contactForm.reset();
                        }, 1000);
                    }
                });
            }

        });
    //]]>
    </script>
</body>
</html>
