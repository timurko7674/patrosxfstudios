<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patrosxf Studios</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Patrosxf Studios</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#games">Games</a></li>
                <li><a href="#tos">TOS</a></li>
                <li><a href="#partnership">Partnership</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#help">Need Help?</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to Patrosxf Studios</h2>
            <p>Your one-stop destination for amazing games!</p>
            <!-- Add more content here -->
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Patrosxf Studios is a leading game development studio...</p>
            <!-- Add more content here -->
        </section>

        <section id="games">
            <h2>Our Games</h2>
            <ul>
                <li>Blocky Kingdom - <button onclick="downloadGame()">Download</button></li>
                <!-- Add more games here -->
            </ul>
        </section>

        <section id="tos">
            <h2>Terms of Service</h2>
            <h3>1. Acceptance of Terms</h3>
            <p>By accessing and using the services provided by Patrosxf Studios ("we," "our," "us"), you ("user," "client") agree to comply with and be bound by these Terms of Service ("TOS"). If you do not agree to these terms, you should not use our services.</p>

            <h3>2. Services Provided</h3>
            <p>Patrosxf Studios offers the following services:</p>
            <ul>
                <li>Uploading user-created games to our platform for a fee.</li>
                <li>Creating custom games for users based on their requirements for a fee.</li>
            </ul>

            <h3>3. User Responsibilities</h3>
            <p>Users agree to:</p>
            <ul>
                <li>Provide accurate and complete information when requesting services.</li>
                <li>Ensure that their content does not violate any laws or third-party rights.</li>
                <li>Use our services in compliance with all applicable laws and regulations.</li>
            </ul>

            <h3>4. Content Ownership and Rights</h3>
            <ul>
                <li>Users retain ownership of their submitted content.</li>
                <li>By submitting content to Patrosxf Studios, users grant us a non-exclusive, royalty-free, worldwide license to use, distribute, and display the content for the purpose of providing our services.</li>
                <li>Users affirm that they have the rights to the content they submit and that it does not infringe on any third-party rights.</li>
            </ul>

            <h3>5. Payment and Fees</h3>
            <ul>
                <li>Fees for our services will be communicated to users prior to service delivery.</li>
                <li>Payments must be made in full before services are rendered.</li>
                <li>All payments are non-refundable unless otherwise stated.</li>
            </ul>

            <h3>6. Confidentiality</h3>
            <ul>
                <li>Patrosxf Studios will maintain the confidentiality of any sensitive information provided by users, using it solely for the purpose of delivering the requested services.</li>
                <li>Users agree not to disclose any confidential information received from Patrosxf Studios to third parties.</li>
            </ul>

            <h3>7. Termination</h3>
            <ul>
                <li>Patrosxf Studios reserves the right to terminate or suspend access to our services at our discretion, without prior notice, for conduct that we believe violates these TOS or is harmful to other users of our services.</li>
                <li>Users may terminate their use of our services at any time by providing written notice to us.</li>
            </ul>

            <h3>8. Limitation of Liability</h3>
            <ul>
                <li>Patrosxf Studios is not liable for any direct, indirect, incidental, consequential, or punitive damages arising out of the use or inability to use our services.</li>
                <li>Our liability is limited to the amount paid by the user for the service in question.</li>
            </ul>

            <h3>9. Changes to Terms</h3>
            <ul>
                <li>Patrosxf Studios reserves the right to modify these TOS at any time. We will notify users of any changes by posting the new TOS on our website.</li>
                <li>Continued use of our services after changes to the TOS constitutes acceptance of the new terms.</li>
            </ul>

            <h3>10. Governing Law</h3>
            <p>These TOS are governed by and construed in accordance with the laws of [Your Jurisdiction], without regard to its conflict of law principles.</p>

            <h3>11. Contact Information</h3>
            <p>For any questions or concerns regarding these TOS, please contact us at:</p>
            <ul>
                <li>Email: contact.patrosxfstudios@gmail.com</li>
                <li>Discord: timurko767</li>
            </ul>
        </section>

        <section id="partnership">
            <h2>Partnership</h2>
            <p>Interested in partnering with us? <a href="google-form-link">Apply here</a>.</p>
            <!-- Add more content here -->
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: contact.patrosxfstudios@gmail.com</p>
            <p>Discord: timurko767</p>
            <!-- Add more content here -->
        </section>

        <section id="help">
            <h2>Need Help?</h2>
            <p>Check out our FAQ or contact support.</p>
            <!-- Add more content here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Patrosxf Studios. All rights reserved.</p>
    </footer>

    <script>
        function downloadGame() {
            // URLs for the game file and icon
            const gameUrl = 'https://drive.google.com/file/d/1Q2DWOovbTw0Idd1SxuGVz-VFFzvAYyT9/view?usp=drive_link';
            const iconUrl = 'https://drive.google.com/file/d/1FhUE9Pv3XOKjPiWt8j2m51QSIrP9mgZi/view?usp=drive_link';

            // Create invisible links to trigger download
            const gameLink = document.createElement('a');
            gameLink.href = gameUrl;
            gameLink.download = 'BlockyKingdom.zip';
            document.body.appendChild(gameLink);
            gameLink.click();
            document.body.removeChild(gameLink);

            const iconLink = document.createElement('a');
            iconLink.href = iconUrl;
            iconLink.download = 'BlockyIcon.ico';
            document.body.appendChild(iconLink);
            iconLink.click();
            document.body.removeChild(iconLink);

            // Provide instructions for creating a desktop shortcut
            alert('Download complete. Please follow the instructions below to create a desktop shortcut:\n\n1. Locate the downloaded files (BlockyKingdom.zip and BlockyIcon.ico).\n2. Extract the BlockyKingdom.zip file if necessary.\n3. Right-click on the extracted game file and select "Create Shortcut".\n4. Move the shortcut to your desktop.\n5. Right-click on the shortcut, select "Properties", and then "Change Icon".\n6. Browse to the location of BlockyIcon.ico and select it.\n7. Click "OK" to save the changes.');
        }
    </script>
</body>
</html>
