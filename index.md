---
layout: default
ext-css:
  - /style.css
canonical_url: "https://www.apartmentdealsaustin.com"
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": ["LocalBusiness", "RealEstateAgent"],
  "name": "Apartment Deals Austin",
  "founder": { "@type": "Person", "name": "Taylor Boykin" },
  "telephone": "+19727547790",
  "email": "taylor@myapartmentfinders.com",
  "url": "https://www.apartmentdealsaustin.com",
  "priceRange": "Free",
  "description": "Licensed real estate agent and full-time apartment locator serving Austin TX. Free service — the property pays my fee when you sign.",
  "areaServed": [
    "Austin, TX", "Cedar Park, TX", "Leander, TX",
    "Round Rock, TX", "Pflugerville, TX", "Georgetown, TX",
    "Buda, TX", "Kyle, TX", "Taylor, TX"
  ]
}
</script>

<!-- STICKY NAV -->
<nav>
  <a href="/" class="nav-brand">Apartment Deals Austin</a>
  <ul class="nav-links">
    <li><a href="#deals">Deals</a></li>
    <li><a href="#calculator">Calculator</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="faq-blog.html">Blog</a></li>
  </ul>
  <a href="sms:9727547790" class="nav-cta">Text Me Now</a>
</nav>


<!-- ============================================================
     1. HERO
     ============================================================ -->
<header class="hero">
  <img src="photos/headshot.jpg" alt="Taylor Boykin, Austin Apartment Locator" class="profile-pic">
  <h1>Austin's Best Apartment Deals</h1>
  <p class="hero-sub">I find Austin renters the best move-in specials in the city — weeks free, waived fees, gift cards. Completely free to you.</p>
  <div class="hero-actions">
    <a href="sms:9727547790" class="btn btn-white">Text Me Now — It's Free</a>
    <a href="https://forms.gle/UaBbaEc6RfzK8iPS7" target="_blank" class="btn btn-ghost">Fill Out My Intake Form</a>
  </div>
</header>


<!-- ============================================================
     2. HOW IT WORKS
     ============================================================ -->
<section class="section" id="how-it-works">
  <div class="section-inner">
    <div class="section-header">
      <h2>How It Works</h2>
      <p>Three steps is all it takes. No fees, no catch — the property pays me when you sign.</p>
    </div>
    <div class="steps-grid">
      <div class="step">
        <div class="step-number">1</div>
        <h3>Tell me what you need</h3>
        <p>Text me your budget, move-in date, and the areas you're interested in. Takes about two minutes.</p>
      </div>
      <div class="step">
        <div class="step-number">2</div>
        <h3>I find the best deals</h3>
        <p>I dig through current specials across Austin — weeks free, waived deposits, gift cards — and hand-pick the best matches for you.</p>
      </div>
      <div class="step">
        <div class="step-number">3</div>
        <h3>You move in, you pay nothing</h3>
        <p>My service is 100% free to renters. The property pays my fee when you lease. You just get a great deal.</p>
      </div>
    </div>
  </div>
</section>


<!-- ============================================================
     3. CURRENT DEALS
     ============================================================ -->
<section class="section section-alt" id="deals">
  <div class="section-inner">
    <div class="section-header">
      <h2>Deals of the Week</h2>
      <p>These specials move fast. Text me to find out what's still available — or to see what else I'm working with right now.</p>
    </div>
    <div class="deals-grid">

      <div class="deal-card">
        <div class="deal-card-image">
          <img src="photos/apartments/central/central-austin-1.jpg" alt="Central Austin apartment">
        </div>
        <div class="deal-card-body">
          <div class="deal-card-area">Central Austin</div>
          <div class="deal-card-price">1 Bed &bull; $1,352/mo effective</div>
          <p class="deal-card-desc">Brand new build in one of Austin's most walkable neighborhoods. 8 weeks free + $500 gift card. Rooftop pools, gym, EV charging. Listed at $1,597 — effective rent after special is $1,352.</p>
          <a href="sms:9727547790" class="btn btn-primary btn-sm">Text Me About This</a>
        </div>
      </div>

      <div class="deal-card">
        <div class="deal-card-image">
          <img src="photos/apartments/east/east-austin-1.jpg" alt="East Austin apartment">
        </div>
        <div class="deal-card-body">
          <div class="deal-card-area">East Austin</div>
          <div class="deal-card-price">1 Bed &bull; $1,316/mo effective</div>
          <p class="deal-card-desc">Backs up to a greenbelt with miles of trails. 10 weeks free. 12 minutes to downtown. Great access to the best food, coffee, and nightlife East Austin has to offer. Listed at $1,630.</p>
          <a href="sms:9727547790" class="btn btn-primary btn-sm">Text Me About This</a>
        </div>
      </div>

      <div class="deal-card">
        <div class="deal-card-image">
          <img src="photos/apartments/south/south-austin-1.jpg" alt="South Austin apartment">
        </div>
        <div class="deal-card-body">
          <div class="deal-card-area">South Austin</div>
          <div class="deal-card-price">2 Bed / 2 Bath &bull; $1,620/mo effective</div>
          <p class="deal-card-desc">Brand new 2/2 in South Austin at a price that's hard to beat. 8 weeks free. Steps from a brand new H-E-B and all the South Austin classics. Listed at $1,920.</p>
          <a href="sms:9727547790" class="btn btn-primary btn-sm">Text Me About This</a>
        </div>
      </div>

    </div>
  </div>
</section>


<!-- ============================================================
     4. RENT CALCULATOR
     ============================================================ -->
<section class="section" id="calculator">
  <div class="section-inner">
    <div class="section-header">
      <h2>What's Your Effective Rent?</h2>
      <p>Move-in specials are quoted in weeks free — this calculator shows you what that means for your actual monthly payment.</p>
    </div>
    <div class="calculator-wrap">
      <div class="calculator-form">
        <form id="calculator-form">
          <div class="form-group">
            <label for="rent">Listed Monthly Rent ($)</label>
            <input type="number" id="rent" name="rent" placeholder="e.g. 1597" required>
          </div>
          <div class="form-group">
            <label for="lease">Lease Term (months)</label>
            <input type="number" id="lease" name="lease" placeholder="e.g. 12" required>
          </div>
          <div class="form-group">
            <label for="freeWeeks">Weeks Free</label>
            <input type="number" id="freeWeeks" name="freeWeeks" placeholder="e.g. 8" required>
          </div>
          <button type="submit" class="btn btn-primary">Calculate My Effective Rent</button>
        </form>
        <div id="result"></div>
      </div>
      <div class="calculator-cta">
        <p>Want deals like this? I'll find them for you.</p>
        <a href="sms:9727547790" class="btn btn-primary">Text Me Now</a>
      </div>
    </div>
  </div>
</section>

<script>
  document.getElementById('calculator-form').addEventListener('submit', function(e) {
    e.preventDefault();
    const rent = parseFloat(document.getElementById('rent').value);
    const lease = parseFloat(document.getElementById('lease').value);
    const freeWeeks = parseFloat(document.getElementById('freeWeeks').value);
    if (isNaN(rent) || isNaN(lease) || isNaN(freeWeeks) || lease <= 0) {
      document.getElementById('result').innerText = 'Please enter valid values.';
      return;
    }
    const totalFree = (rent / 4) * freeWeeks;
    const effectiveRent = ((rent * lease) - totalFree) / lease;
    document.getElementById('result').innerText = 'Effective monthly rent: $' + effectiveRent.toFixed(2);
  });
</script>


<!-- ============================================================
     5. WHY USE A LOCATOR
     ============================================================ -->
<section class="section section-alt" id="why">
  <div class="section-inner">
    <div class="section-header">
      <h2>Why Use a Locator?</h2>
      <p>Most renters don't know this service exists — and the ones who use it move faster and pay less.</p>
    </div>
    <div class="why-grid">
      <div class="why-item">
        <div class="why-icon">&#x1F4B0;</div>
        <h3>It's 100% free to you</h3>
        <p>The property pays my fee when you sign a lease. You get expert help finding the best deal — at zero cost.</p>
      </div>
      <div class="why-item">
        <div class="why-icon">&#x26A1;</div>
        <h3>Move faster</h3>
        <p>I already know which buildings have inventory, which ones are negotiating, and where the real specials are right now. No wasted tours.</p>
      </div>
      <div class="why-item">
        <div class="why-icon">&#x1F3D9;</div>
        <h3>Real local knowledge</h3>
        <p>I'm in Austin full time. I know which neighborhoods fit which lifestyles and which new builds are actually worth it.</p>
      </div>
      <div class="why-item">
        <div class="why-icon">&#x1F91D;</div>
        <h3>A real person, not an algorithm</h3>
        <p>I respond fast, I'm honest about what I see, and I'll tell you if a deal isn't right for you. That's not something a listing site does.</p>
      </div>
    </div>
  </div>
</section>


<!-- ============================================================
     6. ABOUT TAYLOR
     ============================================================ -->
<section class="section" id="about">
  <div class="section-inner">
    <div class="about-inner">
      <img src="photos/headshot.jpg" alt="Taylor Boykin, Austin Apartment Locator" class="about-photo">
      <div class="about-text">
        <h2>About Me</h2>
        <p>I'm Taylor — a licensed real estate agent based in Austin, TX. I work exclusively as an apartment locator, which means my full-time focus is knowing where the best deals are in this city and matching renters with them fast.</p>
        <p>I cover Austin and the surrounding areas: Cedar Park, Leander, Round Rock, and Pflugerville. I respond quickly, I'm straight with you about what I see, and I genuinely enjoy helping people find a great place to live.</p>
        <p>The service is completely free to you. Text me and let's get started.</p>
        <a href="sms:9727547790" class="btn btn-primary">Text Taylor &mdash; (972) 754-7790</a>
      </div>
    </div>
  </div>
</section>


<!-- ============================================================
     7. TESTIMONIALS
     ============================================================ -->
<section class="section section-alt" id="testimonials">
  <div class="section-inner">
    <div class="section-header">
      <h2>What Clients Say</h2>
    </div>
    <!-- TODO: Replace placeholder quotes with real client testimonials -->
    <div class="testimonials-grid">
      <div class="testimonial-card">
        <p class="testimonial-quote">"Taylor found me a place with 6 weeks free that I never would have found on my own. Saved me over $1,000 and the whole process took less than a week."</p>
        <p class="testimonial-author">— Austin renter, East Austin</p>
      </div>
      <div class="testimonial-card">
        <p class="testimonial-quote">"I was completely overwhelmed searching on my own. Taylor narrowed it down to three options that actually fit my budget and lifestyle. Moved in two weeks later."</p>
        <p class="testimonial-author">— Austin renter, South Austin</p>
      </div>
      <div class="testimonial-card">
        <p class="testimonial-quote">"Didn't know this was a free service until a friend told me. Wish I had found Taylor two apartments ago. 10/10 would recommend to anyone moving to Austin."</p>
        <p class="testimonial-author">— Austin renter, Cedar Park</p>
      </div>
    </div>
    <div class="reviews-image-wrap">
      <img src="photos/reviews.png" alt="Google Reviews from past clients">
    </div>
  </div>
</section>


<!-- ============================================================
     8. FINAL CTA
     ============================================================ -->
<section class="final-cta" id="contact">
  <h2>Ready to find your place in Austin?</h2>
  <p>Text me now and I'll send you a curated list of the best deals available today — no forms, no waiting, no cost.</p>
  <div class="final-cta-actions">
    <a href="sms:9727547790" class="btn btn-white">Text Me Now &mdash; (972) 754-7790</a>
    <a href="https://forms.gle/UaBbaEc6RfzK8iPS7" target="_blank" class="btn btn-ghost">Fill Out the Intake Form</a>
  </div>
</section>


<!-- ============================================================
     9. FOOTER
     ============================================================ -->
<footer>
  <div class="footer-inner">
    <div class="footer-contact">
      <p><strong style="color:rgba(255,255,255,0.9)">Taylor Boykin</strong> &mdash; Austin Apartment Locator</p>
      <p>
        <a href="sms:9727547790">(972) 754-7790</a>
        &nbsp;&bull;&nbsp;
        <a href="mailto:taylor@myapartmentfinders.com">taylor@myapartmentfinders.com</a>
      </p>
    </div>
    <ul class="footer-nav">
      <li><a href="/">Home</a></li>
      <li><a href="#deals">Deals</a></li>
      <li><a href="#calculator">Calculator</a></li>
      <li><a href="faq-blog.html">Blog</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="footer-legal">
      <p>&copy; 2026 Apartment Deals Austin &mdash; Taylor Boykin, Licensed Real Estate Agent, Texas</p>
      <p>
        <a href="https://acrobat.adobe.com/id/urn%3Aaaid%3Asc%3AUS%3A22ee4d14-818b-4513-9cae-d4d11f140285/?x_api_client_id=acom_nav&filetype=application%2Fpdf"
           target="_blank"
           rel="noopener noreferrer">
          Texas Real Estate Commission Information About Brokerage Services
        </a>
      </p>
    </div>
  </div>
</footer>
