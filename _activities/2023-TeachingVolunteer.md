---
title: "Stellar Corps, Young Sprout Association"
collection: activities
type: "Teaching Volunteer"
permalink: /activities/2023-TeachingVolunteer
excerpt: |
    <div style="text-align: justify; font-size: 16px; color: #666; margin: 5px 0 0 20px; margin-left: 0px;">
        <p>
            I joined Young Sprout Association of Henan University and served as vice captain of Stellar Corps (chapter for high school students). Our team brought together members from diverse discipline backgrounds, including medicine, chemistry, physics, education, business and statistics. We collaborated with <a href="http://www.lingqing.org/" style="text-decoration: none;">Lingqing Philanthropy Development Center</a> in Shanghai and co-launched a long-term volunteer project with Yuqing Middle School in Baini Town, Yuqing County, Guizhou Province. We spent most vacations (winter, summer and national vacations) on volunteer teaching activities, student mentoring, and course design. Our team created a series of engaging extracurricular programs that integrated academic concepts with real-world challenges, such as:
        </p>
        <ul style="padding-left: 30px;">
            <li>
                <strong>“Puzzle Tracker”</strong> – an interactive program introducing computer vision and image processing through puzzle-based games.
            </li>
            <li>
                <strong>“Hidden Gems in the Mountains”</strong> – a cultural exploration program combining local Miaoethnic herbal medicine rooted in Chinese cultural heritage.
            </li>
        </ul>
        <p>
            Hope these efforts can inspire students to decode STEM principles through gamified challenges; discover cultural wisdom within real-world contexts; develop critical thinking via cross-disciplinary exploration. Moverover, this is not merely a top-down transmission of knowledge, but a two-way learning bridge that fosters mutual growth between them and teaching volunteers across generations. The project has been sustained for over two years, and I truly hope it will continue to grow and benefit more people in the years to come.
        </p>
    </div>
venue: "Shanghai Lingqing Philanthropy Development Center and Yuqing Middle School, China"
start-date: 2023-01-01
end-date: 2024-12-01
---

<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>Gallery</title>
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <style>
            body {
                margin: 0;
                background: #fafafa;
                color: #333;
            }
            .gallery {
                display: grid;
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
                gap: 5px;
                padding: 5px;
                max-width: 1600px;
                margin: 0 auto;
            }
            .gallery img {
                width: 100%;
                height: auto;
                object-fit: cover;
                cursor: pointer;
                border-radius: 4px;
                transition: transform .3s, box-shadow .3s;
            }
            .gallery img:hover {
                transform: scale(1.03);
                box-shadow: 0 4px 12px rgba(0,0,0,0.2);
            }
            /* Lightbox */
            #lightbox {
                position: fixed; top: 0; left: 0;
                width: 100%; height: 100%;
                background: rgba(0,0,0,0.85);
                display: none; align-items: center; justify-content: center;
                z-index: 1000;
            }
            #lightbox img {
                max-width: 90%; max-height: 90%;
                border-radius: 4px;
            }
            #lightbox .close {
                position: absolute; top: 20px; right: 30px;
                font-size: 2rem; color: #fff; cursor: pointer;
            }
        </style>
    </head>
    <body>
        <hr style="border: none; border-top: 1px dashed #ccc; margin: 0 8px 1rem;" />
        <h3>Journey with my partners, my friends...</h3>

        <div class="gallery" id="gallery"></div>

        <!-- Lightbox Overlay -->
        <div id="lightbox">
            <span class="close">&times;</span>
            <img src="" alt="Full-size Image" />
        </div>

        <p style="font-size: 12px; margin: 5px 0 0 20px; margin-left: 0px; text-align: justify; margin-top: 10px;">
            Note: Participants were informed that photos would be publicly shared for project outreach, and no private data is disclosed.
        </p>

        <script>
            // ------------- Dynamic gallery generation -------------
            const gallery = document.getElementById('gallery');

            // If your files are sequentially named: photo1.jpg … photoN.jpg
            const TOTAL_IMAGES = 56;   // ← set this to however many you have
            for (let i = 1; i <= TOTAL_IMAGES; i++) {
                const img = document.createElement('img');
                img.src = `/images/TeachingVolunteer/IMG${i}.JPG`;
                img.alt = `IMG ${i}`;
                img.loading = 'lazy';
                gallery.appendChild(img);
            }
            // ------------- Lightbox logic -------------
            const lightbox = document.getElementById('lightbox');
            const lightboxImg = lightbox.querySelector('img');
            const closeBtn = lightbox.querySelector('.close');

            gallery.addEventListener('click', e => {
                if (e.target.tagName !== 'IMG') return;
                lightboxImg.src = e.target.src;
                lightbox.style.display = 'flex';
            });
            closeBtn.addEventListener('click', () => lightbox.style.display = 'none');
            lightbox.addEventListener('click', e => {
                if (e.target === lightbox) lightbox.style.display = 'none';
            });
            document.addEventListener('keydown', e => {
                if (e.key === 'Escape') lightbox.style.display = 'none';
            });
        </script>
    </body>
</html>
