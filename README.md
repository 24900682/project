# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

HOME.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
        }
        .navbar {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .btn-primary {
            background: linear-gradient(45deg, #ff6f61, #ff9472);
            border: none;
        }
        .btn-primary:hover {
            background: linear-gradient(45deg, #ff9472, #ff6f61);
        }
        header {
            background: linear-gradient(135deg, #6a11cb, #a008b1);
            color: #000000;
            padding: 80px 0;
            text-align: center;
        }
        header h1 {
            font-weight: 700;
            margin-bottom: 20px;
        }
        header p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        section {
            padding: 60px 0;
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }
        .card-img-top {
            border-bottom: 3px solid #ff6f61;
        }
        footer {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        footer p {
            margin: 0;
        }
        footer a {
            color: #ff9472;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .section-separator {
            background: linear-gradient(135deg, #ff6f61, #ff9472);
            height: 10px;
            width: 100%;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#showcase">Showcase</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contactus.html">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary text-white px-4" href="signup.html">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <header>
        <div class="container">
            <h1>Unleash Your Creativity Globally</h1>
            <p class="lead">Join a premier platform where designers connect, innovate, and inspire growth.</p>
            <a href="#showcase" class="btn btn-light btn-lg">Start</a>
        </div>
    </header>
    <div class="section-separator"></div>
    <section id="features">
        <div class="container">
            <h2 class="text-center fw-bold mb-4">Features</h2>
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">For Creators</h5>
                            <p class="card-text">Turn your creativity into opportunities. Display your unique work, attract global clients, and grow your reputation with a standout Showcase.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">For Visionaries</h5>
                            <p class="card-text">Explore a curated collection of groundbreaking designs. Fuel your imagination with fresh concepts and cutting-edge trends shared by design leaders worldwide.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">For Brands</h5>
                            <p class="card-text">Collaborate with talented designers to craft your vision. Discover skilled creatives who can shape the identity and future of your brand.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <div class="section-separator"></div>
    <section id="portfolio" class="bg-light">
        <div class="container">
            <h2 class="text-center fw-bold mb-4">Showcase</h2>
            <p class="text-center mb-4">Explore some of the works shared by the Webpage.</p>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="c:\PRIVATE\Web Application Development\PROJECT\3-naruto-shippuden-sitting-set-action-figure-pvc-anime-figures-original-imagfdfy5sgfxqyn.jpg" class="card-img-top" alt="Retrospective Branding Design">
                        <div class="card-body">
                            <h5 class="card-title">Anime Collectibles Hub</h5>
                            <p class="card-text">
                                Anime serves as a thriving business model, generating substantial revenue through licensing, merchandise, and streaming platforms. Its global popularity offers brands opportunities for collaborations, marketing, and storytelling, making it a powerful medium for engaging diverse audiences and driving innovation.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="c:\PRIVATE\Web Application Development\PROJECT\pngtree-3d-rendering-of-pottery-object-image_13531694.png" class="card-img-top" alt="Home Swap Platform UI Elements">
                        <div class="card-body">
                            <h5 class="card-title">Timeless Clay Creations</h5>
                            <p class="card-text">
                                Pottery combines craftsmanship and creativity, offering timeless ceramic pieces that enhance living spaces. From functional dinnerware to decorative art, pottery businesses cater to customers seeking unique, handcrafted items that reflect artistry, quality, and a connection to tradition and style.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="c:\PRIVATE\Web Application Development\PROJECT\airpods-4-anc-select-202409_FV1_FMT_WHH.jpeg" class="card-img-top" alt="Jewelry Website Design">
                        <div class="card-body">
                            <h5 class="card-title">Revolutionary Wireless Earbuds</h5>
                            <p class="card-text">AirPods offer seamless wireless audio for enhanced productivity, with features like active noise cancellation, long battery life, and integration with Apple devices. Perfect for professionals seeking clear communication, immersive sound, and convenience during meetings, calls, and travel.</p>
                        </div>
                    </div>
                </div>
                <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Side-by-Side Cards</title>
    <style>
        /* Styling the container and cards */
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        .card {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }

        .card-img-top {
            width: 80%; /* Adjust image size */
            height: auto; /* Maintain aspect ratio */
            display: block;
            margin: auto; /* Center the image */
        }

        .row.d-flex {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .col-md-6 {
            flex: 0 0 48%; /* Each card takes 48% of the row for spacing */
        }

        .card-body {
            padding: 15px;
        }

        h5 {
            font-size: 1.25rem;
            margin-bottom: 10px;
        }

        p {
            font-size: 0.9rem;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <section>
        <div class="container">
            <div class="row d-flex">
                <!-- First Card -->
                <div class="col-md-6 mb-4">
                    <div class="card">
                        <img src="c:\PRIVATE\Web Application Development\PROJECT\DALL·E 2024-12-29 17.20.43 - A beautifully arranged display of artisanal pottery for a business catalog. The scene features a variety of handmade pottery items, including ceramic .webp" class="card-img-top" alt="Artisanal Pottery">
                        <div class="card-body">
                            <h5 class="card-title">Elegant Sleep Solutions</h5>
                            <p class="card-text">Innovative bed designs enhance comfort, style, and functionality, catering to diverse customer preferences. With options ranging from luxury to minimalist styles, businesses can offer versatile solutions for hotels, interiors, and home decor, promoting relaxation and aesthetic appeal in any setting.</p>
                        </div>
                    </div>
                </div>
                <!-- Second Card -->
                <div class="col-md-6 mb-4">
                    <div class="card">
                        <img src="c:\PRIVATE\Web Application Development\PROJECT\DALL·E 2024-12-29 17.19.35 - A collection of stylish and functional mobile backcases displayed on a clean, professional background. The backcases should vary in design, showcasing.webp" class="card-img-top" alt="Mobile Backcases">
                        <div class="card-body">
                            <h5 class="card-title">Stylish Mobile Protection</h5>
                            <p class="card-text">Mobile backcases offer essential protection against damage while enhancing the device's appearance. With a variety of materials, designs, and customization options, businesses can cater to diverse customer needs, providing both functionality and style for smartphones across different markets.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</body>
</html>
```
Signup.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Arial', sans-serif;
        }
        .container {
            max-width: 500px;
        }
        .form-container {
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
            background-color: #ffffff;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .form-container:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        h2 {
            font-weight: bold;
            color: #333;
        }
        .btn-primary {
            background: linear-gradient(90deg, #667eea, #764ba2);
            border: none;
            transition: background 0.3s;
        }
        .btn-primary:hover {
            background: linear-gradient(90deg, #764ba2, #667eea);
        }
        a {
            color: #764ba2;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        a:hover {
            color: #667eea;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="form-container">
            <h2 class="text-center mb-4">Create an Account</h2>
            <form action="#" method="POST">
                <div class="mb-3">
                    <label for="fullName" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="fullName" name="fullName" placeholder="Enter your full name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" name="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" name="password" placeholder="Create a strong password" required>
                </div>
                <div class="mb-3">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" name="confirmPassword" placeholder="Re-enter your password" required>
                </div>
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="terms" required>
                    <label class="form-check-label" for="terms">I agree to the <a href="#">terms and conditions</a></label>
                </div>
                <button type="submit" class="btn btn-primary w-100">Sign Up</button>
            </form>
            <p class="text-center mt-3">Already have an account? <a href="login.html">Login here</a></p>
        </div>
    </div>
</body>
</html>
```
Contact.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        .contact-container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .contact-header {
            text-align: center;
            margin-bottom: 20px;
        }

        .contact-header h1 {
            font-size: 1.8rem;
            color: #444;
        }

        .contact-header p {
            color: #666;
            margin-top: 8px;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            font-weight: bold;
            margin-bottom: 5px;
        }

        input, textarea, button {
            font-size: 1rem;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            outline: none;
        }

        input:focus, textarea:focus {
            border-color: #007bff;
            box-shadow: 0 0 4px rgba(0, 123, 255, 0.4);
        }

        textarea {
            resize: none;
            height: 100px;
        }

        button {
            background-color: #007bff;
            color: #fff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #0056b3;
        }

        .footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9rem;
            color: #777;
        }

        .footer a {
            text-decoration: none;
            color: #007bff;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="contact-container">
        <div class="contact-header">
            <h1>Contact Us</h1>
            <p>We'd love to hear from you. Whether you have a question, feedback, or suggestion, feel free to reach out using the form below.</p>
        </div>
        <form action="#" method="POST">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required>

            <label for="subject">Subject</label>
            <input type="text" id="subject" name="subject" placeholder="Enter the subject" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" placeholder="Type your message here..." required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>
    <div class="footer">
        &copy; 2024 Sahith <Main></Main>. All rights reserved.
    </div>
</body>
</html>

```
# OUTPUT:
![Screenshot 2024-12-29 173518](https://github.com/user-attachments/assets/3bd3bc3f-fb2d-404e-b5d4-c1e3aacdb630)
![Screenshot 2024-12-29 173638](https://github.com/user-attachments/assets/6662655c-2e02-4bc0-888d-b88b22df3a88)
![Screenshot 2024-12-29 173701](https://github.com/user-attachments/assets/46f96888-0e04-4c5c-8586-228acb155eac)
![Screenshot 2024-12-29 173721](https://github.com/user-attachments/assets/66aead4e-f661-42f1-b639-bc0b3687e087)
![Screenshot 2024-12-29 174630](https://github.com/user-attachments/assets/54f4482a-6e90-4a44-b7ad-69874f214ea6)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
