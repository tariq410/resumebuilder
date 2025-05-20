<!DOCTYPE html>
<html lang="en" itemscope itemtype="https://schema.org/WebApplication">
<head>
    <!-- SEO Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Create professional resumes instantly with our free online resume builder. Download in PDF format with perfect formatting and templates. Get hired faster!">
    <meta name="keywords" content="resume builder, CV creator, online resume, job application, career tools">
    <meta name="author" content="ResumePro">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://yourdomain.com/resume-builder">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:title" content="Professional Resume Builder | Create Perfect CV Online">
    <meta property="og:description" content="Free online resume builder with instant download. Create professional resumes in minutes with our easy-to-use templates.">
    
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Professional Resume Builder | Create Perfect CV Online">
    <meta name="twitter:description" content="Free online resume builder with instant download. Create professional resumes in minutes with our easy-to-use templates.">

    <!-- Schema.org structured data -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebApplication",
        "name": "ResumePro Builder",
        "applicationCategory": "Career",
        "operatingSystem": "Web",
        "aggregateRating": {
            "@type": "AggregateRating",
            "ratingValue": "4.8",
            "reviewCount": "1500"
        }
    }
    </script>

    <title>Professional Resume Builder | Create Perfect CV Online - ResumePro</title>
    
    <!-- Styles -->
    <style>
        /* Base Styles */
        * { box-sizing: border-box; margin: 0; padding: 0 }
        body { font-family: 'Segoe UI', system-ui; line-height: 1.6; color: #333; background: #f5f5f5; transition: background 0.3s, color 0.3s }

        /* Dark Mode */
        body.dark-mode { background: #1a1a1a; color: #fff }
        body.dark-mode .builder-form,
        body.dark-mode .resume-preview { background: #2d2d2d; box-shadow: 0 2px 15px rgba(0,0,0,0.3) }
        body.dark-mode label { background: #2d2d2d }
        body.dark-mode input,
        body.dark-mode textarea { background: #333; border-color: #444; color: #fff }

        /* Layout */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            display: grid;
            grid-template-columns: 3fr 1fr;
            gap: 30px;
        }

        /* Form Styles */
        .builder-form { background: #fff; padding: 30px; border-radius: 10px; box-shadow: 0 2px 15px rgba(0,0,0,0.1); transition: all 0.3s }
        .form-group { position: relative; margin-bottom: 2rem; transition: all 0.3s }
        label { display: block; margin-bottom: 8px; font-weight: 600; position: absolute; left: 15px; top: 50%; transform: translateY(-50%); background: white; padding: 0 5px; transition: all 0.3s; pointer-events: none; color: #666 }
        input, textarea, select { width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 5px; font-size: 16px; transition: all 0.3s }
        input:focus, textarea:focus, select:focus { border-color: #2196F3 !important; box-shadow: 0 0 8px rgba(33,150,243,0.3); outline: none }
        
        /* Floating Labels */
        input:focus + label,
        input:not(:placeholder-shown) + label,
        textarea:focus + label,
        textarea:not(:placeholder-shown) + label { top: -10px; left: 10px; font-size: 0.8em; color: #2196F3 }

        /* Preview Section */
        .resume-preview { background: #fff; padding: 30px; min-height: 100vh; box-shadow: 0 2px 15px rgba(0,0,0,0.1); transition: all 0.3s; cursor: pointer }
        .resume-preview:hover { transform: scale(1.02) }

        /* Ads Section */
        .ad-unit { margin: 20px 0; text-align: center }

        /* Progress Bar */
        .progress-bar { height: 4px; background: #eee; margin-bottom: 2rem; position: relative }
        .progress-fill { height: 100%; background: #2196F3; width: 0; transition: width 0.5s ease }

        /* Star Rating */
        .rating-stars { display: flex; gap: 10px; margin-bottom: 1rem }
        .star { cursor: pointer; font-size: 24px; color: #ddd; transition: all 0.2s }
        .star:hover, .star.active { color: #ffc107; transform: scale(1.2) }

        /* Dark Mode Toggle */
        .dark-mode-toggle { position: fixed; top: 20px; right: 20px; cursor: pointer; z-index: 1000; font-size: 24px }

        /* Download Button */
        .download-btn { background: #2196F3; color: white; padding: 15px 30px; border: none; border-radius: 5px; cursor: pointer; font-size: 18px; margin-top: 20px; position: relative; overflow: hidden; transition: all 0.4s }
        .download-btn:hover { transform: translateY(-2px); box-shadow: 0 5px 15px rgba(33,150,243,0.4) }
        .download-btn::after { content: ''; position: absolute; top: 50%; left: 50%; width: 0; height: 0; background: rgba(255,255,255,0.2); border-radius: 50%; transform: translate(-50%, -50%); transition: width 0.3s, height 0.3s }
        .download-btn:active::after { width: 200px; height: 200px }

        /* Animations */
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px) } to { opacity: 1; transform: translateY(0) } }
        .animated-section { animation: fadeIn 0.6s ease-out forwards; opacity: 0 }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container { grid-template-columns: 1fr }
            .sidebar { order: -1 }
        }
    </style>
    
    <!-- Google Adsense -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
</head>

<body>
    <!-- Dark Mode Toggle -->
    <div class="dark-mode-toggle" onclick="toggleDarkMode()">🌓</div>

    <header>
        <h1 class="animated-section">Professional Resume Builder</h1>
        <div class="ad-unit animated-section">
            <!-- Header Ad -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                data-ad-slot="XXXXXXXXXX"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
        </div>
    </header>

    <!-- Progress Bar -->
    <div class="progress-bar animated-section">
        <div class="progress-fill" id="progress"></div>
    </div>

    <main class="container">
        <section class="builder-form animated-section">
            <h2>Create Your Resume</h2>
            <form id="resumeForm">
                <div class="form-group">
                    <input type="text" id="fullName" required placeholder=" ">
                    <label>Full Name</label>
                </div>

                <div class="form-group">
                    <input type="email" id="email" required placeholder=" ">
                    <label>Email</label>
                </div>

                <div class="form-group">
                    <textarea id="summary" rows="4" placeholder=" "></textarea>
                    <label>Professional Summary</label>
                </div>

                <div class="form-group">
                    <textarea id="experience" rows="6" placeholder=" "></textarea>
                    <label>Work Experience</label>
                </div>

                <div class="form-group">
                    <textarea id="education" rows="4" placeholder=" "></textarea>
                    <label>Education</label>
                </div>

                <button type="button" onclick="generateResume()" class="download-btn">Download Resume</button>
            </form>
        </section>

        <aside class="sidebar">
            <div class="ad-unit animated-section">
                <ins class="adsbygoogle"
                    style="display:block"
                    data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                    data-ad-slot="XXXXXXXXXX"
                    data-ad-format="auto"
                    data-full-width-responsive="true"></ins>
                <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
            </div>

            <div class="feedback animated-section">
                <h3>Rate Your Experience</h3>
                <div class="rating-stars">
                    <div class="star" onclick="rate(1)">★</div>
                    <div class="star" onclick="rate(2)">★</div>
                    <div class="star" onclick="rate(3)">★</div>
                    <div class="star" onclick="rate(4)">★</div>
                    <div class="star" onclick="rate(5)">★</div>
                </div>
                <form id="feedbackForm">
                    <div class="form-group">
                        <textarea id="comments" rows="4" placeholder="Additional comments"></textarea>
                    </div>
                    <button type="submit">Submit Feedback</button>
                </form>
            </div>
        </aside>
    </main>

    <section class="resume-preview animated-section" id="resumePreview">
        <!-- Dynamic preview content -->
    </section>

    <script>
        // Dark Mode Toggle
        function toggleDarkMode() {
            document.body.classList.toggle('dark-mode');
            localStorage.setItem('darkMode', document.body.classList.contains('dark-mode'));
        }

        // Initialize Dark Mode
        if (localStorage.getItem('darkMode') === 'true') {
            document.body.classList.add('dark-mode');
        }

        // Star Rating System
        let currentRating = 0;
        function rate(value) {
            currentRating = value;
            document.querySelectorAll('.star').forEach((star, index) => {
                star.classList.toggle('active', index < value);
            });
        }

        // Progress Calculation
        function calculateProgress() {
            const fields = document.querySelectorAll('input, textarea');
            const filled = [...fields].filter(f => f.value.trim() !== '').length;
            const progress = (filled / fields.length) * 100;
            document.getElementById('progress').style.width = `${progress}%`;
        }

        // Real-time Preview Updates
        document.getElementById('resumeForm').addEventListener('input', function(e) {
            const field = e.target.id;
            const value = e.target.value;
            if(document.getElementById(`preview-${field}`)) {
                document.getElementById(`preview-${field}`).textContent = value;
            }
            calculateProgress();
        });

        // PDF Generation
        function generateResume() {
            const element = document.getElementById('resumePreview');
            html2pdf()
                .set({
                    margin: 10,
                    filename: 'resume.pdf',
                    image: { type: 'jpeg', quality: 0.98 },
                    html2canvas: { scale: 2 },
                    jsPDF: { unit: 'mm', format: 'a4', orientation: 'portrait' }
                })
                .from(element)
                .save();
            triggerConfetti();
        }

        // Feedback Handling
        document.getElementById('feedbackForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your feedback!');
        });

        // Confetti Animation
        function triggerConfetti() {
            // Requires canvas-confetti library
            if(typeof confetti === 'function') {
                confetti({
                    particleCount: 100,
                    spread: 70,
                    origin: { y: 0.6 }
                });
            }
        }

        // Initialize Animations
        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('.animated-section').forEach((section, index) => {
                setTimeout(() => {
                    section.style.opacity = 1;
                }, index * 200);
            });
        });
    </script>

    <!-- External Libraries -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
</body>
</html>
