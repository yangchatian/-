<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Literacy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
        .section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:disabled {
            background-color: #ccc;
            cursor: not-allowed;
        }
    </style>
</head>
<body>
    <header>
        <h1>Digital Literacy: Empowering the Future</h1>
    </header>
    <div class="container">
        <section class="section">
            <h2>Introduction to Digital Literacy</h2>
            <p>Digital literacy is the ability to use information and communication technologies to find, evaluate, create, and communicate information, requiring both cognitive and technical skills. In today's digital age, being digitally literate is essential for personal, academic, and professional success.</p>
        </section>
        <section class="section">
            <h2>Key Components of Digital Literacy</h2>
            <p>Digital literacy encompasses several key components:</p>
            <ul>
                <li><strong>Technical Skills:</strong> The ability to use digital devices, software, and applications.</li>
                <li><strong>Information Literacy:</strong> The skill to find, evaluate, and use information effectively.</li>
                <li><strong>Communication Skills:</strong> The ability to interact and collaborate with others using digital tools.</li>
                <li><strong>Media Literacy:</strong> Understanding how to critically analyze media content and create media products.</li>
                <li><strong>Online Safety and Ethics:</strong> Knowledge of how to protect oneself online and adhere to ethical standards.</li>
            </ul>
        </section>
        <section class="section">
            <h2>Importance of Digital Literacy</h2>
            <p>In an increasingly digital world, digital literacy is crucial for several reasons:</p>
            <ul>
                <li><strong>Employment Opportunities:</strong> Many jobs require proficiency in digital tools and platforms.</li>
                <li><strong>Education:</strong> Digital literacy enhances learning experiences and access to educational resources.</li>
                <li><strong>Social Inclusion:</strong> It enables individuals to participate in online communities and stay connected with others.</li>
                <li><strong>Critical Thinking:</strong> Digital literacy helps individuals critically evaluate online information and avoid misinformation.</li>
            </ul>
        </section>
        <section class="section">
            <h2>Challenges and Solutions</h2>
            <p>Despite its importance, many people face challenges in achieving digital literacy. Some of these challenges include:</p>
            <ul>
                <li><strong>Lack of Access to Technology:</strong> Not everyone has access to digital devices or reliable internet.</li>
                <li><strong>Education Gaps:</strong> Some individuals may not have the opportunity to learn digital skills.</li>
                <li><strong>Language Barriers:</strong> Digital content is often available in limited languages.</li>
            </ul>
            <p>To address these challenges, various solutions can be implemented:</p>
            <ul>
                <li><strong>Government Initiatives:</strong> Programs to provide affordable access to technology and internet services.</li>
                <li><strong>Community Support:</strong> Workshops and training sessions in local communities.</li>
                <li><strong>Online Resources:</strong> Free educational materials and courses available online.</li>
            </ul>
        </section>
        <section class="section">
            <h2>Conclusion</h2>
            <p>Digital literacy is a vital skill in the 21st century. It empowers individuals to navigate the digital world safely, efficiently, and effectively. By promoting digital literacy, we can create a more inclusive and informed society.</p>
        </section>
        <section class="section">
            <h2>Feedback Form</h2>
            <form id="feedbackForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required autocomplete="off"><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required autocomplete="off"><br><br>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea><br><br>
                <button type="submit" id="submitBtn">Submit</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Digital Literacy Initiative</p>
    </footer>
    <script>
        document.getElementById('feedbackForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const submitBtn = document.getElementById('submitBtn');
            submitBtn.disabled = true; // Disable the button after submission
            alert('Thank you for your feedback!');
        });
    </script>
</body>
</html>
