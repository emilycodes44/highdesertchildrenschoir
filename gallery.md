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
                <img src="{{ '/assets/images/gallery-1.jpg' | relative_url }}" alt="Annual Spring Concert">
                <div class="photo-overlay">
                    <h3>Annual Spring Concert 2024</h3>
                    <p>Our annual spring showcase featuring performances by all age groups</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="concerts">
                <img src="{{ '/assets/images/gallery-2.jpg' | relative_url }}" alt="Holiday Concert">
                <div class="photo-overlay">
                    <h3>Holiday Concert 2023</h3>
                    <p>A magical evening of festive music and celebration</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="rehearsals">
                <img src="{{ '/assets/images/gallery-3.jpg' | relative_url }}" alt="Weekly Rehearsal">
                <div class="photo-overlay">
                    <h3>Weekly Rehearsal</h3>
                    <p>Students working hard during their regular Saturday rehearsal</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/gallery-4.jpg' | relative_url }}" alt="Community Festival">
                <div class="photo-overlay">
                    <h3>Community Festival</h3>
                    <p>Performing at the annual High Desert Community Festival</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="awards">
                <img src="{{ '/assets/images/gallery-5.jpg' | relative_url }}" alt="Awards Ceremony">
                <div class="photo-overlay">
                    <h3>Awards & Recognition</h3>
                    <p>Celebrating our achievements at the end-of-season ceremony</p>
                </div>
            </div>
            
            <div class="photo-item" data-category="events">
                <img src="{{ '/assets/images/gallery-6.jpg' | relative_url }}" alt="Group Photo">
                <div class="photo-overlay">
                    <h3>Choir Family</h3>
                    <p>The entire choir family together for our annual group photo</p>
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
