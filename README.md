# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags for character set and responsive viewport -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Page title displayed in browser tab -->
    <title>The Global Accountants</title>

    <!-- Basic styling -->
    <style>
        
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        body {
            line-height: 1.7;
            color: #380b1e;
        }
        
        /* Header styles */
        header {
            background: #245013;
            color: whitesmoke;
            padding: 1rem;
            text-align: left;
        }
        
        /* Navigation styles */
        nav {
            background: #34495e;
            padding: 0.5rem;
        }
        
        nav ul {
            display: flex;
            justify-content: right;
            list-style: none;
        }
        
        nav li {
            margin: 0 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        nav a:hover {
            text-decoration: underline;
        }
        
        /* Main content styles */
        main {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        /* Footer styles */
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <!-- Header section with page title -->
    <header>
        <h1>The Global Accountants</h1>
        <p>Professional Solutions for Your Financial Needs</p>
    </header>
    
    <!-- Navigation bar -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    
    <!-- Main content section -->
    <main>
        <h2>About The Global Accountants Limited</h2>
        <p>Global Accountants Limited <strong>is a modern accounting firm</strong> founded and led by <strong>CPA Camil Omukaga</strong>, offering comprehensive financial solutions for businesses and individuals. Specializing in tax strategy, compliance, and financial advisory, we combine technical expertise with innovative technology to deliver exceptional value.

           <h2><strong>Why Choose Us?</strong></h2>
           <li>CPA-Led Expertise: Personalized service from a certified professional</li>
            <li>Global Perspective: Tailored solutions for local and international clients</li>
                <li>Tech-Forward Approach: Cloud accounting and real-time financial insights</li>
                    <li>Startup-Friendly: Affordable packages for growing businesses</li>
                    <br>
            
           <strong>"We don't just crunch numbers—we build financial futures."</strong>
            <strong>Camil Omukaga,</strong> Founder </p>
            <br>
        
        <h3>Our Services</h3>
        
                <li>Tax Planning & Strategy</li>
                <li>Corporate/Personal Tax Filing (Local & International)</li>
                <li>Tax Compliance & Audit Support</li>
                <li>VAT/Excise Duty Advisory</li>
            </ul>
               
            </ul>
        </div>
        <br>
        
        <div class="service-category">
            <h3>Business Advisory</h3>
            <ul class="service-list">
                <li>Startup Financial Setup & Coaching</li>
                <li>Cash Flow Management</li>
                <li>Budgeting & Forecasting</li>
                <li>Business Process Optimization</li>
            </ul>
        </div>
        
        <br>
        <div class="service-category">
            <h3>Compliance & Regulatory</h3>
            <ul class="service-list">
                <li>Company Registration Support</li>
                <li>Annual Returns & Statutory Filing</li>
                <li>IFRS/GAAP Compliance</li>
                <li>Secretarial Services</li>
            </ul>
        </div>
      
        <br>
        <div class="service-category">
            <h3>Specialized Solutions</h3>
            <ul class="service-list">
                <li>Cross-Border Taxation Advisory</li>
                <li>Digital Accounting System Setup</li>
                <li>Financial Health Checks</li>
                <li>Exit Strategy Planning</li>
            </ul>
        </div>
        
        <br>
            <strong>Why Our Services Stand Out</strong>
            
            <ul>
             </ul>Every service benefits from Camil’s direct expertise</ul>
            </ul>Tech-Integrated: Real-time dashboards and automated workflows</ul>
        </ul>Scalable: From startup packages to enterprise solutions</ul>
        
          <br>
    <p><strong>"We align our services with your growth stage—no generic templates, only tailored financial strategies."</strong></p>
    </main>
    <br>
          
    <!-- Footer with contact information -->
    <footer>
        <p>Contact us: <a href="mailto:camilomukaga240@gmail.com" style="color: #3498db;">info@camilomukaga240@gmail.com</a> | Phone: 0768730217</p>
        <p>&copy; 2025 THe Global Accountants Limited. All rights reserved.</p>
        <p>Designed by <strong>Dev.Camil</strong></p>

    </footer>
</body>
</html>

# about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags for character set and responsive viewport -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Page title displayed in browser tab -->
    <title>The Global Accountants</title>

    <!-- Basic styling -->
    <style>
        
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        body {
            line-height: 1.7;
            color: #380b1e;
        }
        
        /* Header styles */
        header {
            background: #245013;
            color: whitesmoke;
            padding: 1rem;
            text-align: left;
        }
        
        /* Navigation styles */
        nav {
            background: #34495e;
            padding: 0.5rem;
        }
        
        nav ul {
            display: flex;
            justify-content: right;
            list-style: none;
        }
        
        nav li {
            margin: 0 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        nav a:hover {
            text-decoration: underline;
        }
        
        /* Main content styles */
        main {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        /* Footer styles */
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <!-- Header section with page title -->
    <header>
        <h1>The Global Accountants</h1>
        <p>Professional Solutions for Your Financial Needs</p>
    </header>
    
    <!-- Navigation bar -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    
    <!-- Main content section -->
    <main>
        <p>The Global Accountants Limited <strong>is a modern accounting firm</strong> founded and led by <strong>CPA Camil Omukaga</strong>, offering comprehensive financial solutions for businesses and individuals. Specializing in tax strategy, compliance, and financial advisory, we combine technical expertise with innovative technology to deliver exceptional value.

           <h2><strong>Why Choose Us?</strong></h2>
           <li>CPA-Led Expertise: Personalized service from a certified professional</li>
            <li>Global Perspective: Tailored solutions for local and international clients</li>
                <li>Tech-Forward Approach: Cloud accounting and real-time financial insights</li>
                    <li>Startup-Friendly: Affordable packages for growing businesses</li>
                    <br>
            
           <strong>"We don't just crunch numbers—we build financial futures."</strong>
            <strong>Camil Omukaga,</strong> Founder </p>
            <br>
        
        <h3>Our Services</h3>
        
                <li>Tax Planning & Strategy</li>
                <li>Corporate/Personal Tax Filing (Local & International)</li>
                <li>Tax Compliance & Audit Support</li>
                <li>VAT/Excise Duty Advisory</li>
            </ul>
               
            </ul>
        </div>
        <br>
        
        <div class="service-category">
            <h3>Business Advisory</h3>
            <ul class="service-list">
                <li>Startup Financial Setup & Coaching</li>
                <li>Cash Flow Management</li>
                <li>Budgeting & Forecasting</li>
                <li>Business Process Optimization</li>
            </ul>
        </div>
        
        <br>
        <div class="service-category">
            <h3>Compliance & Regulatory</h3>
            <ul class="service-list">
                <li>Company Registration Support</li>
                <li>Annual Returns & Statutory Filing</li>
                <li>IFRS/GAAP Compliance</li>
                <li>Secretarial Services</li>
            </ul>
        </div>
      
        <br>
        <div class="service-category">
            <h3>Specialized Solutions</h3>
            <ul class="service-list">
                <li>Cross-Border Taxation Advisory</li>
                <li>Digital Accounting System Setup</li>
                <li>Financial Health Checks</li>
                <li>Exit Strategy Planning</li>
            </ul>
        </div>
        
        <br>
            <strong>Why Our Services Stand Out</strong>
            
            <ul>
             </ul>Every service benefits from Camil’s direct expertise</ul>
            </ul>Tech-Integrated: Real-time dashboards and automated workflows</ul>
        </ul>Scalable: From startup packages to enterprise solutions</ul>
        
          <br>
    <p><strong>"We align our services with your growth stage—no generic templates, only tailored financial strategies."</strong></p>
    </main>
    <br>
          
    <!-- Footer with contact information -->
    <footer>
        <p>Contact us: <a href="mailto:camilomukaga240@gmail.com" style="color: #3498db;">info@camilomukaga240@gmail.com</a> | Phone: 0768730217</p>
        <p>&copy; 2025 THe Global Accountants Limited. All rights reserved.</p>
        <p>Designed by <strong>Dev.Camil</strong></p>

    </footer>
</body>
</html>

# services.html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="/style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services</title>
    <style>
        .hero {
            background: linear-gradient(rgba(83, 36, 54, 0.5), rgba(0, 0, 0, 0.5)), url('hero-image.jpg');
            background-size: cover;
            background-position: center;
            height: 40vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: rgb(30, 32, 136);
            padding: 0px;
        }
        
        .hero-content {
            max-width: 500px;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        
        .cta-button {
            display: inline-block;
            background: #ff6b6b;
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .cta-button:hover {
            background: #ff5252;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
</html>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        
        .nav-links a {
            margin-left: 30px;
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }
        
        /* Hero Section */
        .services-hero {
            background: linear-gradient(135deg, hwb(17 9% 51%) 0%, #1e40af 100%);
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        
        .services-hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        /* Services Grid */
        .services-grid {
            padding: 60px 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: #ffffff;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            font-size: 2.5rem;
            color: #eb2571;
            margin-bottom: 20px;
        }
        
        /* Footer */
        footer {
            background: #1e293b;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
        }
    </style>
</head>

<body>

    <!-- Hero Section -->
    <section class="services-hero">
        <div class="container">
            <h1>Our Professional Services</h1>
            <p>Delivering excellence through our specialized solutions</p>
        </div>
    </section>

    <!-- Services Grid -->
    <section class="container services-grid">
        <div class="service-card">
            <div class="service-icon">📊</div>
            <h3>Financial Consulting</h3>
            <p>Comprehensive financial analysis and strategic planning to grow your business.</p>
        </div>
        
        <div class="service-card">
            <div class="service-icon">💼</div>
            <h3>Tax Preparation</h3>
            <p>Expert tax filing services to maximize deductions and minimize liabilities.</p>
        </div>
        
        <div class="service-card">
            <div class="service-icon">📈</div>
            <h3>Investment Planning</h3>
            <p>Personalized investment strategies tailored to your financial goals.</p>
        </div>
        
        <div class="service-card">
            <div class="service-icon">🔍</div>
            <h3>Audit Services</h3>
            <p>Thorough financial audits to ensure compliance and identify opportunities.</p>
        </div>
        
        <div class="service-card">
            <div class="service-icon">💰</div>
            <h3>Wealth Management</h3>
            <p>Holistic approaches to preserve and grow your assets.</p>
        </div>
        
        <div class="service-card">
            <div class="service-icon">📑</div>
            <h3>Bookkeeping</h3>
            <p>Accurate record-keeping and financial reporting services.</p>
        </div>
    </section>



    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 The Global Accountants. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

# Contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
         body {
            background-color: #3338bb; /* Fallback */
        background-image:url(https://img.freepik.com/free-photo/top-view-blue-monday-concept-composition-with-telephone_23-2149139103.jpg)
    }

        /* Reuse global styles from previous pages */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.9;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #2563eb;
            text-decoration: none;
        }
        
        .nav-links a {
            margin-left: 30px;
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }
        
        /* Contact Hero */
        .contact-hero {
            background: linear-gradient(135deg, #1e40af 0%, #1e293b 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        /* Contact Layout */
        .contact-container {
            padding: 60px 0;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }
        
        .contact-info {
            padding-right: 30px;
        }
        
        .contact-info h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #2563eb;
        }
        
        .contact-method {
            display: flex;
            align-items: flex-start;
            margin-bottom: 30px;
        }
        
        .contact-icon {
            font-size: 1.5rem;
            color: #2563eb;
            margin-right: 20px;
            margin-top: 5px;
        }
        
        /* Contact Form */
        .contact-form {
            background: #fff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        .submit-btn {
            background: #2563eb;
            color: white;
            border: none;
            padding: 12px 30px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 500;
            transition: background 0.3s;
        }
        
        .submit-btn:hover {
            background: #1e40af;
        }
        
        /* Map Section */
        .map-section {
            padding: 40px 0;
            background: #f8fafc;
        }
        
        .map-container {
            height: 400px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .map-container iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        
        /* Footer */
        footer {
            background: #1e293b;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        @media (max-width: 768px) {
            .contact-container {
                grid-template-columns: 1fr;
            }
            
            .nav-links {
                display: none;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="contact-hero">
        <div class="container">
            <h1>Get In Touch</h1>
            <p>We'd love to hear from you! Reach out for inquiries or appointments.</p>
        </div>
    </section>

    <!-- Contact Content -->
    <section class="container contact-container">
        <div class="contact-info">
            <h2>Contact Information</h2>
            
            <div class="contact-method">
                <div class="contact-icon">📞</div>
                <div>
                    <h3>Phone</h3>
                    <p>+254 768 730217</p>
                    <p>Mon-Fri: 8:00 AM - 5:00 PM</p>
                </div>
            </div>
            
            <div class="contact-method">
                <div class="contact-icon">✉️</div>
                <div>
                    <h3>Email</h3>
                    <p>camilomukaga240@gmail.com</p>
                    <p>camilomukaga240@gmail.com</p>
                </div>
            </div>
            
            <div class="contact-method">
                <div class="contact-icon">🏢</div>
                <div>
                    <h3>Office</h3>
                    <p>123 Financial District</p>
                    <p>GPO, Nairobi</p>
                </div>
            </div>
        </div>
        
        <div class="contact-form">
            <h2 style="margin-bottom: 30px; color: #2563eb;">Send Us a Message</h2>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" class="form-control" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" class="form-control" required>
                </div>
                
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone" class="form-control">
                </div>
                
                <div class="form-group">
                    <label for="service">Service Interested In</label>
                    <select id="service" name="service" class="form-control">
                        <option value="">Select a service</option>
                        <option value="tax">Tax Preparation</option>
                        <option value="audit">Audit Services</option>
                        <option value="consulting">Financial Consulting</option>
                        <option value="other">Other</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea id="message" name="message" class="form-control" required></textarea>
                </div>
                
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>

<!-- Footer -->
<footer>
    <div class="container">
        <p>&copy; 2025 The Global Accountants. All rights reserved.</p>
    </div>
</footer>
</body>
</html>
   

