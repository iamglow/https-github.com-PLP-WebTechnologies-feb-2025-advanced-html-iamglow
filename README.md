<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Webpage</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Multimedia Webpage</h1>
    </header>

    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#audio">Audio</a></li>
            <li><a href="#video">Video</a></li>
            <li><a href="#form">Registration Form</a></li>
            <li><a href="#image">Image</a></li>
            <li><a href="#table">Table</a></li>
            <li><a href="#list">List</a></li>
        </ul>
    </nav>

    <!-- Audio Section -->
    <section id="audio">
        <h2>Listen to This Audio</h2>
        <audio controls>
            <source src="audio-file.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </section>

    <!-- Video Section -->
    <section id="video">
        <h2>Watch This Video</h2>
        <video width="600" controls>
            <source src="video-file.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

    <!-- Registration Form Section -->
    <section id="form">
        <h2>Registration Form</h2>
        <form action="submit-form.php" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required placeholder="Enter your name">

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required placeholder="Enter your email">

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required placeholder="Enter your password" minlength="6">

            <label for="confirm-password">Confirm Password:</label>
            <input type="password" id="confirm-password" name="confirm-password" required placeholder="Confirm your password" minlength="6">

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>

            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Image Section -->
    <section id="image">
        <h2>Our Beautiful Image</h2>
        <img src="image.jpg" alt="Beautiful Scenery" width="600">
    </section>

    <!-- Table Section -->
    <section id="table">
        <h2>Product Table</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Product</th>
                    <th>Price</th>
                    <th>Quantity</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Apple</td>
                    <td>$1.00</td>
                    <td>10</td>
                </tr>
                <tr>
                    <td>Banana</td>
                    <td>$0.50</td>
                    <td>20</td>
                </tr>
                <tr>
                    <td>Orange</td>
                    <td>$1.20</td>
                    <td>15</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- List Section -->
    <section id="list">
        <h2>Top 3 Favorite Fruits</h2>
        <ul>
            <li>Apple</li>
            <li>Banana</li>
            <li>Orange</li>
        </ul>
    </section>

</body>
</html>
