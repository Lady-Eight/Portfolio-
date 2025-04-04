# Portfolio-
My cv as a portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Judith W. Mwangi | Environmental & Biosystems Engineer</title>
    <style>
        :root {
            --primary: #2E8B57; /* Sage green */
            --secondary: #FFD700; /* Gold */
            --accent: #8B4513; /* Earth brown */
            --light: #F5F5F5;
            --dark: #333;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            margin: 0;
            padding: 0;
            background-color: var(--light);
        }
        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('');
            color: white;
            text-align: center;
            padding: 4rem 1rem;
            background-size: cover;
            background-position: center;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 0 2rem;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        .tagline {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 1.5rem;
        }
        .btn {
            display: inline-block;
            background: var(--secondary);
            color: var(--dark);
            padding: 0.5rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        .btn:hover {
            background: var(--primary);
            color: white;
        }
        section {
            padding: 3rem 0;
        }
        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            color: var(--primary);
            position: relative;
        }
        .section-title:after {
            content: "";
            display: block;
            width: 80px;
            height: 3px;
            background: var(--secondary);
            margin: 0.5rem auto;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 1.5rem;
            margin-bottom: 2rem;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-5px);
        }
        .project-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        .project-content {
            padding: 1rem;
        }
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .skill {
            background: var(--primary);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        .social-links {
            margin: 1rem 0;
        }
        .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 1.2rem;
        }
        @media (max-width: 768px) {
            .project-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Judith W. Mwangi</h1>
            <p class="tagline">Environmental & Biosystems Engineer | Sustainable Solutions Innovator | Women in STEM Advocate</p>
            <a href="#contact" class="btn">Get In Touch</a>
        </div>
    </header>
    <section id="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="card">
                <p>I am a passionate Biosystems Engineer with expertise in sustainable development, renewable energy integration, and community empowerment. My work focuses on bridging engineering excellence with social impact, particularly in Kenya's arid and semi-arid lands (ASAL).</p>
                <p>As the CEO and Founder of The ASAL's Women Initiative, I empower women through technology-driven solutions that address food security, water scarcity, and climate resilience. My approach combines technical innovation with grassroots engagement to create scalable, sustainable change.</p>
            </div>
        </div>
    </section>
    <section id="projects">
        <div class="container">
            <h2 class="section-title">Featured Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <div class="project-img" style="background-image: url('');"></div>
                    <div class="project-content">
                        <h3>Solar-Powered Combined Planter</h3>
                        <p>Designed and implemented an innovative solar-powered machine for potato farmers in Nyandarua County that combines planting, tilling, and spraying functions. Reduced labor costs by 40% and increased yields by 25%.</p>
                        <p><strong>Technologies:</strong> AutoCAD, IoT sensors, Solar PV systems</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-img" style="background-image: url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                    <div class="project-content">
                        <h3>ASAL Women's Water Initiative</h3>
                        <p>Implemented water pan systems in Tuum, Samburu County to address water scarcity. Trained 150+ women on maintenance and sustainable water use, increasing household water access by 60%.</p>
                        <p><strong>Technologies:</strong> GIS mapping, Community-led design</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-img" style="background-image: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                    <div class="project-content">
                        <h3>Plastic Waste to Farm Tools</h3>
                        <p>Developed a plastic shredder and extruder system that converts waste plastic into durable farm tools. Implemented in Kipushi, DRC through workshops with local women's groups.</p>
                        <p><strong>Technologies:</strong> Recycling systems, Product design</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="skills">
        <div class="container">
            <h2 class="section-title">Technical Skills</h2>
            <div class="skills-container">
                <span class="skill">Sustainable Agriculture</span>
                <span class="skill">Renewable Energy Systems</span>
                <span class="skill">AutoCAD</span>
                <span class="skill">GIS Technology</span>
                <span class="skill">IoT Sensors</span>
                <span class="skill">Project Management</span>
                <span class="skill">Data Analysis</span>
                <span class="skill">Community Engagement</span>
                <span class="skill">Swahili & Kikuyu</span>
            </div>
        </div>
    </section>
<section id="education">
        <div class="container">
            <h2 class="section-title">Education & Certifications</h2>
            <div class="card">
                <h3>University of Nairobi</h3>
                <p><strong>MSc Civil Engineering</strong> (Ongoing) - Focus on Sustainable Infrastructure</p>
                <p><strong>BSc Environmental and Biosystems Engineering</strong> - Second Class (Upper Division)</p>
                
<h3 style="margin-top: 1.5rem;">Certifications</h3>
                <ul>
                    <li>Graduate Engineer - Engineers Board of Kenya (EBK)</li>
                    <li>UN CC:Learn - Climate Change Policy</li>
                    <li>Google Agri-Tech Professional Certificate</li>
                    <li>Member - Kenya Society of Environmental, Biological and Agricultural Engineers (KeSEBAE)</li>
                    <li>Advanced data analysis and modelling</li>
                    <li>Proficient in AutoCAD and engineering design software</li>
                    <li>Strong understanding of sustainable development principles</li>
                    <li>Expertise in water resource management and conservation techniques</li>
                    <li>Skilled in environmental impact assessments</li>
                    <li>Experienced in project management and coordination</li>
                    <li>Competent in quality control and risk management processes</li>
                    <li>Proficient in survey techniques and GIS technology</li>
                    <li>Skilled in drafting technical reports and research papers</li>
                    <li>Knowledgeable in renewable energy systems and environmental restoration techniques</li> 
                </ul>
            </div>
        </div>
    </section>
    <section id="experience">
        <div class="container">
            <h2 class="section-title">Professional Experience</h2>
            <div class="card">
                <h3>CEO & Founder - The ASAL's Women Initiative</h3>
                <p><em>2023 - Present</em></p>
                <ul>
                    <li>Develop and implement sustainable livelihood programs for women in arid regions</li>
                    <li>Train communities on renewable energy solutions and climate-smart agriculture</li>
                    <li>Design and deploy appropriate technologies for water conservation and food security</li>
                </ul>
                <h3>Contract Management Specialist - Ministry of Agriculture and Livestock Development</h3>
                <p><em>July 2024 - Present</em></p>
                <ul>
                  <li>Oversee contractor performance for government-funded agricultural and water projects</li>
                  <li>Ensure technical compliance with engineering drawings and specifications</li>
                  <li>Conduct field inspections and facilitate capacity building of local communities</li>
                </ul>  
                <h3>Community Facilitator – Nawiri Program (Tuum, Samburu County)</h3>
                <p><em>2024</em></p>
                <ul>
                  <li>Trained women and youth in water harvesting and small-scale irrigation techniques</li>
                  <li>Designed and implemented pasture plot and hay storage systems</li>
                  <li>Promoted sustainable land use through indigenous knowledge and local participation</li>
                </ul>     
                <h3 style="margin-top: 1.5rem;">Research Assistant - University of Nairobi Enterprises and Services (UNES)</h3>
                <p><em>2023 - 2024</em></p>
                <ul>
                    <li>Conducted research for the Kenya Small Electric Vehicle Project in collaboration with WRI</li>
                    <li>Analyzed data and contributed to policy recommendations on sustainable transportation</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="achievements">
        <div class="container">
            <h2 class="section-title">Honors & Awards</h2>
            <div class="card">
                <div class="timeline">
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2024</div>
                        <h3 class="timeline-title">UN SDSN Fellow</h3>
                        <p class="timeline-subtitle">United Nations Sustainable Development Solutions Network</p>
                        <p>Selected among top young leaders implementing SDG solutions in Africa</p>
                    </div>
<div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2023</div>
                        <h3 class="timeline-title">KECTIL Program Fellow</h3>
                        <p class="timeline-subtitle">The Knowledge for Children Trust International Leadership Program</p>
                        <p>Recognized for leadership in youth empowerment and sustainable development</p>
                    </div>
               <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2022</div>
                        <h3 class="timeline-title">PLP Scholar</h3>
                        <p class="timeline-subtitle">Pastoralist Leadership Program</p>
                        <p>Awarded for innovative solutions in arid lands development</p>
                    </div>
                </div>
            </div>
        </div>
    </section> 
    <section id="publications">
        <div class="container">
            <h2 class="section-title">Research & Publications</h2>
            <div class="card">
                <div class="project-grid">
                    <!-- Publication 1 -->
                    <div class="project-card">
                        <div class="project-img" style="background-image: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                        <div class="project-content">
                            <h3>Ecomarsh+</h3>
                            <p><strong>Current Research Project</strong></p>
                            <p>Integration of Advanced Wastewater Treatment for Eutrophication Management in Kenya</p>
                            <p><strong>Focus:</strong> Sustainable water solutions for agricultural runoff</p>
                        </div>
                    </div>
                <!-- Publication 2 -->
                    <div class="project-card">
                        <div class="project-img" style="background-image: url('https://images.unsplash.com/photo-1581093450023-4b1d3c6c1c3f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                        <div class="project-content">
                            <h3>KeSEBAE Conference 2024</h3>
                            <p><strong>University of Nairobi Towers</strong></p>
                            <p>Presented on "Solar-Powered Solutions for Smallholder Farmers"</p>
                            <p><strong>Keynote:</strong> Bridging engineering innovation with community needs</p>
                        </div>
                    </div>
                  <!-- Publication 3 -->
                    <div class="project-card">
                        <div class="project-img" style="background-image: url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                        <div class="project-content">
                            <h3>Design Proposals</h3>
                            <p><strong>Academic Projects</strong></p>
                            <ul>
                                <li>Hand-Driven Pesticide Sprayer for Narok</li>
                                <li>Plastic Shredder for Construction Tiles</li>
                                <li>Multipurpose Farming Machine</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
   <section id="testimonials">
        <div class="container">
            <h2 class="section-title">Endorsements</h2>
            <div class="project-grid">
                <div class="card">
                    <blockquote>
                        "Judith's solar-powered planter design revolutionized potato farming in our county. Her ability to combine technical expertise with community needs is exceptional."
                        <footer>- <strong>County Agricultural Officer</strong>, Nyandarua</footer>
                    </blockquote>
                </div>
                <div class="card">
                    <blockquote>
                        "As her supervisor at UNES, I was impressed by Judith's rigorous research methods and ability to translate data into actionable policy recommendations."
                        <footer>- <strong>Research Coordinator</strong>, University of Nairobi</footer>
                    </blockquote>
                </div>
                <div class="card">
                    <blockquote>
                        "The ASAL Women Initiative has transformed lives in our community. Judith's leadership has given women access to technologies we never thought possible."
                        <footer>- <strong>Community Leader</strong>, Samburu</footer>
                    </blockquote>
                </div>
            </div>
        </div>
    </section>
  <section id="volunteer">
        <div class="container">
            <h2 class="section-title">Community Engagement</h2>
            <div class="card">
                <div class="timeline">
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2023-Present</div>
                        <h3 class="timeline-title">Member</h3>
                        <p class="timeline-subtitle">Kenya Society of Environmental, Biological and Agricultural Engineers (KeSEBAE)</p>
                        <p>Participate in technical committees and mentorship programs</p>
                    </div>
               <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2022-Present</div>
                        <h3 class="timeline-title">Technical Trainer</h3>
                        <p class="timeline-subtitle">4-H Kenya STEM Program</p>
                        <p>Teach secondary school students about renewable energy applications</p>
                    </div>
                <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2021-Present</div>
                        <h3 class="timeline-title">Founder</h3>
                        <p class="timeline-subtitle">Women in AgriTech Network</p>
                        <p>Monthly meetups connecting 150+ female professionals in agricultural technology</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
 <section id="languages">
        <div class="container">
            <h2 class="section-title">Language Proficiency</h2>
            <div class="card">
                <div class="skills-container" style="justify-content: space-around;">
                    <div style="text-align: center;">
                        <h3 style="color: var(--primary);">English</h3>
                        <div style="width: 120px; height: 120px; margin: 0 auto; position: relative;">
                            <svg viewBox="0 0 36 36" style="transform: rotate(-90deg);">
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="#eee" stroke-width="3" />
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="var(--secondary)" stroke-width="3" 
                                    stroke-dasharray="95, 100" />
                            </svg>
                            <span style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); 
                                        font-weight: bold; color: var(--dark);">C2</span>
                        </div>
                        <p>Proficient (K.C.S.E)</p>
                    </div>
                <div style="text-align: center;">
                        <h3 style="color: var(--primary);">Swahili</h3>
                        <div style="width: 120px; height: 120px; margin: 0 auto; position: relative;">
                            <svg viewBox="0 0 36 36" style="transform: rotate(-90deg);">
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="#eee" stroke-width="3" />
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="var(--secondary)" stroke-width="3" 
                                    stroke-dasharray="100, 100" />
                            </svg>
                            <span style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); 
                                        font-weight: bold; color: var(--dark);">Native</span>
                        </div>
                        <p>Mother tongue</p>
                    </div>
                 <div style="text-align: center;">
                        <h3 style="color: var(--primary);">German</h3>
                        <div style="width: 120px; height: 120px; margin: 0 auto; position: relative;">
                            <svg viewBox="0 0 36 36" style="transform: rotate(-90deg);">
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="#eee" stroke-width="3" />
                                <path d="M18 2.0845
                                    a 15.9155 15.9155 0 0 1 0 31.831
                                    a 15.9155 15.9155 0 0 1 0 -31.831"
                                    fill="none" stroke="var(--secondary)" stroke-width="3" 
                                    stroke-dasharray="60, 100" />
                            </svg>
                            <span style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); 
                                        font-weight: bold; color: var(--dark);">B1</span>
                        </div>
                        <p>Intermediate (Learned in DRC)</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
  <section id="professional-development">
        <div class="container">
            <h2 class="section-title">Professional Development</h2>
            <div class="card">
                <div class="project-grid" style="grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));">
                    <div class="professional-dev-card">
                        <h3><i class="fas fa-certificate" style="color: var(--accent);"></i> Certifications</h3>
                        <ul>
                            <li>Graduate Engineer (EBK)</li>
                            <li>AutoCAD Advanced</li>
                            <li>Google Analytics</li>
                            <li>UN CC:Learn Climate Policy</li>
                            <li>Driving License Class B</li>
                        </ul>
                    </div>
                 <div class="professional-dev-card">
                        <h3><i class="fas fa-users" style="color: var(--accent);"></i> Memberships</h3>
                        <ul>
                            <li>Engineers Board of Kenya</li>
                            <li>Institution of Engineers of Kenya</li>
                            <li>KeSEBAE (K22026)</li>
                            <li>ASABE (1062719)</li>
                        </ul>
                    </div>
                   <div class="professional-dev-card">
                        <h3><i class="fas fa-graduation-cap" style="color: var(--accent);"></i> Training</h3>
                        <ul>
                            <li>Clerk of Works Certification</li>
                            <li>Gender M&E (Global Health)</li>
                            <li>Youth Engagement (Univ. Minnesota)</li>
                            <li>Front-End Development</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
  <section id="media">
        <div class="container">
            <h2 class="section-title">Media & Presentations</h2>
            <div class="card">
                <div class="timeline">
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">Nov 2024</div>
                        <h3 class="timeline-title">KeSEBAE Annual Conference</h3>
                        <p class="timeline-subtitle">University of Nairobi Towers</p>
                        <p>Keynote speaker on "Solar-Powered Solutions for Smallholder Farmers"</p>
                    </div>
               <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">Aug 2023</div>
                        <h3 class="timeline-title">KeSEBAE Webinar</h3>
                        <p>"How Western Systems Maintain Smallholders' Poverty"</p>
                    </div>
                  <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-date">2023</div>
                        <h3 class="timeline-title">Seminar on Agroforestry</h3>
                        <p class="timeline-subtitle">KeSEBAE, Nairobi</p>
                        <p>Panelist on "Engineering Solutions for Arid Lands"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
   <section id="cta">
        <div class="container">
            <div class="card" style="background: linear-gradient(rgba(46, 139, 87, 0.9), rgba(46, 139, 87, 0.9)), 
                                    url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
                                    color: white; background-size: cover; text-align: center; padding: 3rem;">
                <h2 style="margin-bottom: 1.5rem;">Ready to Collaborate on Sustainable Solutions?</h2>
                <p style="font-size: 1.2rem; margin-bottom: 2rem;">I'm available for consulting, research partnerships, and speaking engagements on agricultural technology and women empowerment in STEM.</p>
                <div>
                    <a href="#contact" class="btn" style="background: white; color: var(--primary); margin-right: 1rem;">Contact Me</a>
                    <a href="path/to/your-cv.pdf" class="btn" style="background: transparent; border: 2px solid white;">Download CV</a>
                </div>
            </div>
        </div>
    </section>
  <footer>
        <div class="container">
            <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
                <div style="margin-bottom: 1rem;">
                    <h3 style="color: white; margin-bottom: 0.5rem;">Judith W. Mwangi</h3>
                    <p style="color: #ccc;">Agricultural & Biosystems Engineer</p>
                </div>
               <div class="social-links" style="margin-bottom: 1rem;">
                    <a href="https://www.linkedin.com/in/jmwangi01" target="_blank" title="LinkedIn">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="#" target="_blank" title="Twitter">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="#" target="_blank" title="ResearchGate">
                        <i class="fab fa-researchgate"></i>
                    </a>
                    <a href="#" target="_blank" title="GitHub">
                        <i class="fab fa-github"></i>
                    </a>
                </div>
            </div>
          <div style="border-top: 1px solid #555; margin: 1.5rem 0; padding-top: 1.5rem; 
                        display: flex; justify-content: space-between; flex-wrap: wrap;">
                <p style="color: #aaa; margin-bottom: 0.5rem;">&copy; 2024 Judith W. Mwangi. All rights reserved.</p>
                <p style="color: #aaa; margin-bottom: 0.5rem;">
                    <a href="#" style="color: #aaa; text-decoration: none;">Privacy Policy</a> | 
                    <a href="#" style="color: #aaa; text-decoration: none;">Terms of Use</a>
                </p>
            </div>
        </div>
    </footer>
  <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
   <style>
        /* Additional Styles */
        .professional-dev-card {
            background: white;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .professional-dev-card:hover {
            transform: translateY(-5px);
        }
        .professional-dev-card h3 {
            color: var(--primary);
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        .professional-dev-card ul {
            padding-left: 1.2rem;
        }
        .professional-dev-card li {
            margin-bottom: 0.5rem;
        }
        #languages .skills-container {
            align-items: flex-start;
        }
        #languages h3 {
            margin-top: 0;
        }
        .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 1.3rem;
            transition: color 0.3s ease;
        }
        .social-links a:hover {
            color: var(--accent);
        }
        @media (max-width: 768px) {
            #languages .skills-container {
                flex-direction: column;
                align-items: center;
            }
            #languages .skills-container > div {
                margin-bottom: 2rem;
            }
        }
    </style>
  <!-- Script for smooth scrolling -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
  <section id="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="card" style="text-align: center;">
                <p>Let's collaborate on sustainable engineering solutions!</p>
                <p>Email: <a href="mailto:mwangji8dy@gmail.com">mwangji8dy@gmail.com</a></p>
                <p>Phone: +254 700 724 917</p>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/jmwangi01" target="_blank">LinkedIn</a>
                    <a href="#" target="_blank">Twitter</a>
                    <a href="#" target="_blank">ResearchGate</a>
                </div>
            </div>
        </div>
    </section>
 <footer>
        <div class="container">
            <p>&copy; 2025 Judith W. Mwangi. All rights reserved.</p>
            <p>Passionate about engineering solutions that empower communities and protect our planet.</p>
        </div>
    </footer>
</body>
</html>
