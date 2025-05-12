---
title: "About"
draft: false
---
<div class="page-title-container">
    <h1 class="page-title">Unser Team</h1>
    <p class="page-subtitle">Alles ist gut, solange du wild bist.</p>
  </div>

<section class="team-container">
    <div class="team-grid">
      <div class="team-card">
        <div class="card-image">
          <img src="https://placehold.co/400.webp?text=600%20x%20600\nwebp" alt="Jane Doe">
        </div>
        <div class="card-content">
          <h2 class="member-name">Jane Doe</h2>
          <h3 class="member-role">Lead Developer</h3>
          <p class="member-description">
            Jane leads our development team with over 10 years of experience in web technologies. She specializes in
            frontend architecture and performance optimization.
          </p>
          <a href="mailto:jane@example.com" class="member-email">
            jane@example.com
          </a>
        </div>
      </div>
      <div class="team-card">
        <div class="card-image">
          <img src="https://placehold.co/400.webp?text=600%20x%20600\nwebp" alt="John Smith">
        </div>
        <div class="card-content">
          <h2 class="member-name">John Smith</h2>
          <h3 class="member-role">UX Designer</h3>
          <p class="member-description">
            John brings creative solutions to our design challenges with his background in user experience and
            interaction design. He focuses on creating intuitive interfaces.
          </p>
          <a href="mailto:john@example.com" class="member-email">
            john@example.com
          </a>
        </div>
      </div>
    </div>
  </section>







# Bootstrap Components

<div class="container py-5">
    <div class="accordion custom-accordion" id="modernAccordion">
        <!-- Accordion Item 1 -->
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        What is Bootstrap 5.3?
                    </button>
            </h2>
            <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#modernAccordion">
                <div class="accordion-body">
                    Bootstrap 5.3 is the latest version of the popular front-end framework, offering enhanced features,
                    improved performance, and modern design capabilities for web development.
                </div>
            </div>
        </div>
        <!-- Accordion Item 2 -->
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        What are the key features?
                    </button>
            </h2>
            <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#modernAccordion">
                <div class="accordion-body">
                    Key features include responsive grid system, updated components, custom properties, enhanced
                    utilities, and improved JavaScript plugins for creating modern web interfaces.
                </div>
            </div>
        </div>
        <!-- Accordion Item 3 -->
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                        How to customize styles?
                    </button>
            </h2>
            <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#modernAccordion">
                <div class="accordion-body">
                    You can customize Bootstrap styles using CSS variables, custom classes, and the built-in Sass
                    variables system to create unique and branded designs.
                </div>
            </div>
        </div>
    </div>
</div>