---
layout: default
title: Contact Us
permalink: /contact/
---

<section class="contact-hero">
    <div class="container">
        <h1>Contact Us</h1>
        <p>Get in touch with the High Desert Children's Choir</p>
    </div>
</section>

<section class="contact-content">
    <div class="container">
        <div class="contact-grid">
            <div class="contact-info">
                <h2>Get In Touch</h2>
                <p>We'd love to hear from you! Whether you're interested in joining our choir, have questions about our programs, or want to book us for an event, we're here to help.</p>
                
                <div class="contact-methods">
                    <div class="contact-method">
                        <h3>📧 Email</h3>
                        <p><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
                        <p>For general inquiries and information</p>
                    </div>
                    
                    <div class="contact-method">
                        <h3>📞 Phone</h3>
                        <p><strong>(555) 123-4567</strong></p>
                        <p>Monday - Friday, 9:00 AM - 5:00 PM</p>
                    </div>
                    
                    <div class="contact-method">
                        <h3>📍 Location</h3>
                        <p><strong>High Desert Community Center</strong><br>
                        123 Music Lane<br>
                        High Desert, CA 92301</p>
                    </div>
                    
                    <div class="contact-method">
                        <h3>🕒 Rehearsal Times</h3>
                        <p><strong>Saturdays</strong><br>
                        10:00 AM - 12:00 PM<br>
                        September - May</p>
                    </div>
                </div>
                
                <div class="staff-info">
                    <h2>Meet Our Staff</h2>
                    <div class="staff-member">
                        <h3>Sarah Johnson - Director</h3>
                        <p>Sarah has been directing children's choirs for over 15 years. She holds a Master's degree in Music Education and specializes in vocal pedagogy for young singers.</p>
                        <p><strong>Email:</strong> sarah@highdesertchildrenschoir.org</p>
                    </div>
                    
                    <div class="staff-member">
                        <h3>Michael Chen - Assistant Director</h3>
                        <p>Michael brings his expertise in contemporary music and piano accompaniment to our choir. He has worked with youth ensembles throughout the region.</p>
                        <p><strong>Email:</strong> michael@highdesertchildrenschoir.org</p>
                    </div>
                </div>
            </div>
            
            <div class="contact-form-section">
                <h2>Send Us a Message</h2>
                <form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
                    <div class="form-group">
                        <label for="name">Name *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="email">Email *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="phone">Phone</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    
                    <div class="form-group">
                        <label for="subject">Subject *</label>
                        <select id="subject" name="subject" required>
                            <option value="">Select a topic</option>
                            <option value="joining">Interested in Joining</option>
                            <option value="audition">Audition Information</option>
                            <option value="booking">Event Booking</option>
                            <option value="volunteer">Volunteer Opportunities</option>
                            <option value="donation">Donations</option>
                            <option value="general">General Question</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="child-age">Child's Age (if applicable)</label>
                        <input type="number" id="child-age" name="child-age" min="6" max="17">
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Message *</label>
                        <textarea id="message" name="message" rows="5" required placeholder="Tell us more about your inquiry..."></textarea>
                    </div>
                    
                    <button type="submit" class="submit-btn">Send Message</button>
                </form>
                
                <div class="form-note">
                    <p><small>* Required fields. We typically respond within 24-48 hours.</small></p>
                </div>
            </div>
        </div>
        
        <div class="faq-section">
            <h2>Frequently Asked Questions</h2>
            <div class="faq-grid">
                <div class="faq-item">
                    <h3>What age groups do you accept?</h3>
                    <p>We welcome children ages 6-17 in our choir program.</p>
                </div>
                
                <div class="faq-item">
                    <h3>Do I need musical experience to join?</h3>
                    <p>No prior musical experience is required! We welcome all children who love to sing and want to learn.</p>
                </div>
                
                <div class="faq-item">
                    <h3>What are the costs involved?</h3>
                    <p>We offer competitive tuition rates and scholarship opportunities. Contact us for current pricing and financial assistance options.</p>
                </div>
                
                <div class="faq-item">
                    <h3>When can my child join?</h3>
                    <p>We accept new members at the beginning of each semester (September and January). Special arrangements can be made for mid-semester enrollment.</p>
                </div>
                
                <div class="faq-item">
                    <h3>What should my child wear to rehearsals?</h3>
                    <p>Comfortable, casual clothing is fine for rehearsals. Concert attire is provided closer to performance dates.</p>
                </div>
                
                <div class="faq-item">
                    <h3>How often do you perform?</h3>
                    <p>We typically have 2-3 major concerts per season, plus community performances and special events throughout the year.</p>
                </div>
            </div>
        </div>
    </div>
</section>
