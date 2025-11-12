---
layout: default
title: Photo Gallery
---

<section class="gallery-hero">
    <div class="container">
        <h1>Photo Gallery</h1>
        <p>Capturing our musical moments and memories</p>
    </div>
</section>

<section class="gallery-content">
    <div class="container">
        <div class="gallery-filters">
            <button class="filter-btn active" data-filter="all">All Photos</button>
            <button class="filter-btn" data-filter="concerts">Concerts</button>
            <button class="filter-btn" data-filter="rehearsals">Rehearsals</button>
            <button class="filter-btn" data-filter="events">Events</button>
            <button class="filter-btn" data-filter="awards">Awards</button>
        </div>
        
        <div class="photo-grid">
            <div class="photo-item" data-category="concerts">
                <img src="{{ '/assets/images/choir_group_photos/choir_recital.jpg' | relative_url }}" alt="Choir Recital">
                <div class="photo-overlay">
                    <h3>Choir Recital</h3>
                    <p>Beautiful performance showcasing our choir's musical talent</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/choir_group_photos/choir_hangout.jpg' | relative_url }}" alt="Choir Hangout">
                <div class="photo-overlay">
                    <h3>Choir Hangout</h3>
                    <p>Building friendships and community through music</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/choir_group_photos/20250920_133237.jpg' | relative_url }}" alt="Choir Activity">
                <div class="photo-overlay">
                    <h3>Choir Activity</h3>
                    <p>Fun activities and special moments with our choir</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/choir_group_photos/choir_group_photo.jpg' | relative_url }}" alt="Group Photo">
                <div class="photo-overlay">
                    <h3>Group Photo</h3>
                    <p>The entire choir family together for our group photo</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/choir_group_photos/donuts.jpg' | relative_url }}" alt="Choir Fun">
                <div class="photo-overlay">
                    <h3>Choir Fun</h3>
                    <p>Special treats and celebrations with our choir family</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/choir_group_photos/choir_tree climbing.jpg' | relative_url }}" alt="Outdoor Activity">
                <div class="photo-overlay">
                    <h3>Outdoor Activity</h3>
                    <p>Adventure and fun activities outside of rehearsals</p>
                </div>
            </div>
            
        </div>
        
        <div class="gallery-stats">
            <h2>Our Journey in Photos</h2>
            <div class="stats-grid">
                <div class="stat-item">
                    <h3>100+</h3>
                    <p>Students served annually</p>
                </div>
                <div class="stat-item">
                    <h3>15+</h3>
                    <p>Years of musical excellence</p>
                </div>
                <div class="stat-item">
                    <h3>50+</h3>
                    <p>Community performances each year</p>
                </div>
                <div class="stat-item">
                    <h3>200+</h3>
                    <p>Concerts performed</p>
                </div>
            </div>
        </div>
        
        <div class="video-section">
            <h2>Performance Videos</h2>
            <p>Watch highlights from our recent performances</p>
            <div class="video-grid">
                <div class="video-item">
                    <div class="video-placeholder">
                        <div class="play-button">▶</div>
                        <h3>Spring Concert 2024 Highlights</h3>
                        <p>Watch our annual spring showcase featuring all age groups</p>
                    </div>
                </div>
                
                <div class="video-item">
                    <div class="video-placeholder">
                        <div class="play-button">▶</div>
                        <h3>Holiday Concert 2023</h3>
                        <p>A magical evening of festive music and celebration</p>
                    </div>
                </div>
                
                <div class="video-item">
                    <div class="video-placeholder">
                        <div class="play-button">▶</div>
                        <h3>Behind the Scenes</h3>
                        <p>Go behind the scenes to see how we prepare for performances</p>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="gallery-cta">
            <h2>Want to See More?</h2>
            <p>Follow us on social media for the latest photos and videos from our rehearsals and performances.</p>
            <div class="social-links">
                <a href="#" class="social-link">Facebook</a>
                <a href="#" class="social-link">Instagram</a>
                <a href="#" class="social-link">YouTube</a>
            </div>
        </div>
    </div>
</section>
