# Self-Skill-evaluation
I am trying to evaluate my skills based on the top 10 on-demand skills for 2025. (according to the World economic forum) Not just evaluate, but elevate. I will try to demonstrate how I am doing that and to show my quality of work to you. Cheers!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <!-- Add other meta tags, title, and CSS links as needed -->
</head>
<body>
    <div class="video-container">
        <iframe width="640" height="360" src="https://www.youtube.com/embed/BqVgJHvK5OQ" frameborder="0" allowfullscreen></iframe>
        <div class="nav-arrows">
            <span class="arrow left"><</span>
            <span class="arrow right">></span>
        </div>
    </div>
    <!-- Other content goes here -->

    <script>
        const video = document.querySelector('iframe');
        const leftArrow = document.querySelector('.left');
        const rightArrow = document.querySelector('.right');

        // Replace these video URLs with actual most-watched videos
        const videoUrls = [
            'https://www.youtube.com/embed/BqVgJHvK5OQ', // Baby Shark Dance
            'https://www.youtube.com/embed/kJQP7kiw5Fk', // Despacito
            // Add more video URLs as needed
        ];

        let currentVideoIndex = 0;

        leftArrow.addEventListener('click', () => {
            currentVideoIndex = (currentVideoIndex - 1 + videoUrls.length) % videoUrls.length;
            video.src = videoUrls[currentVideoIndex];
        });

        rightArrow.addEventListener('click', () => {
            currentVideoIndex = (currentVideoIndex + 1) % videoUrls.length;
            video.src = videoUrls[currentVideoIndex];
        });
    </script>
</body>
</html>


