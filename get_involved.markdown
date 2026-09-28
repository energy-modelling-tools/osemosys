---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /contact/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive">
    <div class="text-center mb-5">
      <h2 class="alt-h2 mb-4">Get Involved</h2>
    </div>

    <!-- Section 1: Community Engagement -->
    <div class="involvement-section mb-5">
      <h3 class="section-title text-center mb-4">💬 Join Our Community</h3>
      
      <!-- Discourse Link at the start -->
      {% include forum_cta.html %}

      <!-- CMS:section id=get_involved_join_our_community -->
      <p class="text-center lead mb-4">
        Join other OSeMOSYS practitioners by becoming part of our Discourse community—a dedicated online space for collaboration, learning, and sharing.
      </p>
      <!-- /CMS:section -->

      <!-- Centered platform benefits -->
      <div class="text-center mb-4">
        <h4 class="platform-benefits-title">This platform allows members to:</h4>
      </div>

      <div class="benefits-container">
        <div class="benefit-card text-center">
          {% octicon tools height:40 class:"fill-blue mb-3" aria-label:tools %}
          <h5>Troubleshoot Models</h5>
          <!-- CMS:section id=get_involved_troubleshoot_models -->
          <p class="text-gray">Share challenges, seek advice, and collaborate with other users to overcome technical hurdles in your OSeMOSYS applications.</p>
          <!-- /CMS:section -->
        </div>
        <div class="benefit-card text-center">
          {% octicon checklist height:40 class:"fill-blue mb-3" aria-label:checklist %}
          <h5>Share Publications</h5>
          <!-- CMS:section id=get_involved_share_publications -->
          <p class="text-gray">Showcase your research, explore the work of others, and contribute to the expanding body of knowledge on integrated systems modeling.</p>
          <!-- /CMS:section -->
        </div>
        <div class="benefit-card text-center">
          <img src="/assets/img/sparkles.svg" height="40" class="mb-3" alt="Events">
          <h5>Stay Updated on Events</h5>
          <!-- CMS:section id=get_involved_stay_updated_on_events -->
          <p class="text-gray">Be the first to know about upcoming capacity-building workshops, webinars, and networking opportunities.</p>
          <!-- /CMS:section -->
        </div>
      </div>
    </div>

    <!-- Section 2: Technical Contributions -->
    <div class="involvement-section">
      <h3 class="section-title text-center mb-4">🛠️ Contribute to Development</h3>
      
      <div class="github-container">
        <div class="unified-github-card text-center">
          <a href="https://github.com/OSeMOSYS" target="_blank" class="github-link">
            <svg height="80" viewBox="0 0 16 16" version="1.1" width="80" aria-hidden="true" class="mb-3">
              <path fill-rule="evenodd" fill="#0366d6" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 
              6.53 5.47 7.59.4.07.55-.17.55-.38 
              0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52
              -.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 
              2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 
              0-.87.31-1.59.82-2.15-.08-.2-.36-1.01.08-2.11 
              0 0 .67-.21 2.2.82.64-.18 1.32-.27 
              2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 
              2.2-.82.44 1.1.16 1.91.08 2.11.51.56.82 
              1.27.82 2.15 0 3.07-1.87 3.75-3.65 
              3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 
              2.2 0 .21.15.46.55.38A8.013 8.013 
              0 0016 8c0-4.42-3.58-8-8-8z"></path>
            </svg>
            <h4 class="text-primary mt-2 mb-4">Contribute to OSeMOSYS on GitHub</h4>
          </a>
          
          <div class="contribution-section text-left">
            <h5>Contribute to This Website</h5>
            <!-- CMS:section id=get_involved_contribute_to_this_website -->
            <p>
              Want to share your OSeMOSYS-related work, training, or resources? We welcome external contributions to this site!
            </p>
            <!-- /CMS:section -->
            <h6>How to contribute:</h6>
            <!-- CMS:section id=get_involved_how_to_contribute -->
            <ul class="contribution-steps">
              <li>Fork the repository: <a href="https://github.com/OSeMOSYS" target="_blank">github.com/OSeMOSYS</a></li>
              <li>Edit or add content (e.g. publications, capacity building activities)</li>
              <li>Submit a pull request</li>
              <li>A site administrator will review and approve if appropriate</li>
            </ul>
            <!-- /CMS:section -->
            <!-- CMS:section id=get_involved_how_to_contribute_2 -->
            <p class="text-muted">
              This website exists to grow a self-sustaining OSeMOSYS community—open to all. Let's make sure your work is visible and contributes to the global ecosystem!
            </p>
            <!-- /CMS:section -->
          </div>
        </div>
      </div>
    </div>

    <!-- Section 3: Project Registry -->
    <div class="involvement-section mt-5" id="project-registry">
      <h3 class="section-title text-center mb-4">OSeMOSYS Project Registry</h3>

      <div class="text-center mb-5">
        <!-- CMS:section id=registry_intro -->
        <p class="lead">
          See who is running OSeMOSYS-based projects, where, and on what — and register your own.
          This registry exists to promote collaboration across institutions and support the ongoing
          development of OSeMOSYS, by making it easy for teams working on similar problems to find
          each other instead of duplicating work.
        </p>
        <!-- /CMS:section -->

        <a href="https://github.com/energy-modelling-tools/osemosys/issues/new?template=register-project.yml"
           target="_blank" class="btn btn-primary btn-large mt-3">
          Register your project
        </a>
        <p class="text-muted mt-2" style="font-size: 0.85rem;">
          Takes about 5 minutes · opens a short form on GitHub · read the
          <a href="#registry-privacy">Privacy Notice</a> first
        </p>
      </div>

      <h4 class="text-center mb-4">📋 Current registry entries</h4>

      {% if site.data.registry and site.data.registry.size > 0 %}
      <div class="table-responsive">
        <table class="registry-table">
          <thead>
            <tr>
              <th>Project</th>
              <th>Institution(s)</th>
              <th>Country / Region</th>
              <th>Scope</th>
              <th>Status</th>
              <th>Tags</th>
              <th>Contact</th>
            </tr>
          </thead>
          <tbody>
            {% for entry in site.data.registry %}
            <tr>
              <td>
                {% if entry.linked_outputs %}
                <a href="{% if entry.linked_outputs contains '://' %}{{ entry.linked_outputs }}{% else %}https://{{ entry.linked_outputs }}{% endif %}" target="_blank">{{ entry.project_name }}</a>
                {% else %}
                {{ entry.project_name }}
                {% endif %}
              </td>
              <td>{{ entry.institutions }}</td>
              <td>{{ entry.country_region }}</td>
              <td>{{ entry.scope }}</td>
              <td><span class="status-badge status-{{ entry.status | downcase }}">{{ entry.status }}</span></td>
              <td>
                {% for tag in entry.tags %}<span class="tag-pill">{{ tag }}</span>{% endfor %}
              </td>
              <td>{% if entry.contact_email %}<a href="mailto:{{ entry.contact_email }}">{{ entry.contact_name }}</a>{% else %}{{ entry.contact_name }}{% endif %}</td>
            </tr>
            {% endfor %}
          </tbody>
        </table>
      </div>
      <p class="text-muted mt-3" style="font-size: 0.8rem;">
        Something out of date, or want an entry corrected or removed? See the
        <a href="#registry-privacy">Privacy Notice</a> for how.
      </p>
      {% else %}
      <p class="text-center text-muted">No entries yet — be the first to register your project above.</p>
      {% endif %}

      <div class="registry-privacy mt-5" id="registry-privacy">
        <h4 class="registry-privacy-title mb-4">Privacy Notice — OSeMOSYS Project Registry</h4>

        <p>This registry is a public, community-maintained directory of OSeMOSYS energy-modelling projects. This notice explains what personal data it collects and how it's handled.</p>

        <h5 class="mt-4">Purpose of this registry</h5>
        <p>The registry exists to make it possible to see, at any time, who is running OSeMOSYS-based projects and where — so that institutions working on similar problems can find each other, share experience, and avoid duplicating work that's already been done elsewhere. In doing so, it aims to promote collaboration across institutions and to support the ongoing development of OSeMOSYS itself, by giving the community and its funders a clearer, collective picture of how the tool is actually being used. This notice is about the personal data (contact name and email) that supports that purpose — not about the project-level data, which isn't personal data.</p>

        <h5 class="mt-4">What we collect</h5>
        <p>For each registry entry, we collect a <strong>contact name and email address</strong>, plus project-level information (institution, country/region, scope, status, dates, tags, funders, and linked outputs) that is not personal data. We do not ask for phone numbers, personal addresses, or any other personal identifiers.</p>

        <h5 class="mt-4">Why we collect it</h5>
        <p>The contact name and email let other researchers and institutions reach out about a listed project — that's the entire purpose of the registry. We do not use this contact information for anything else unless you separately opt in (see "Newsletter" below).</p>

        <h5 class="mt-4">Who can see it</h5>
        <p>Everything submitted through the registration form is published <strong>publicly</strong> — in this GitHub repository and on this page — visible to anyone, including outside the OSeMOSYS community.</p>

        <h5 class="mt-4">Newsletter</h5>
        <p>Registry entries are not automatically added to the quarterly digest or any mailing list. That requires a separate, explicit opt-in checkbox on the submission form.</p>

        <h5 class="mt-4">How long we keep it</h5>
        <p>Entries are reviewed roughly once a year (the "re-confirmation" cycle). An entry that isn't reconfirmed after two cycles is archived, and the contact's name and email are removed or redacted at that point. You don't need to wait for that cycle — see "Your rights" below.</p>

        <h5 class="mt-4">Your rights</h5>
        <p>If you are the contact listed on an entry (or you listed someone else and they've changed their mind), you can at any time:</p>
        <ul>
          <li><strong>Correct</strong> the entry — e.g., update the contact email or project status.</li>
          <li><strong>Remove</strong> the entry, or just the contact details, from the public registry.</li>
          <li><strong>Ask what's stored</strong> about you in the registry.</li>
        </ul>
        <p>To do any of these, open a GitHub issue tagged <code>privacy-request</code> in the
          <a href="https://github.com/energy-modelling-tools/osemosys" target="_blank">registry repository</a>,
          or email the registry curator at <strong>[curator-email@example.org]</strong>. Requests are handled by
          the current registry curator and we aim to action them within 5 business days.</p>

        <h5 class="mt-4">Where this is hosted</h5>
        <p>Entries are stored in the registry's GitHub repository. GitHub, Inc. is based in the United States; if you are in the EU/UK, this means your data is transferred outside the EU/UK, which GitHub's own data protection terms and Standard Contractual Clauses are intended to cover. Contact the registry curator if you'd like more detail on this.</p>

        <h5 class="mt-4">Submitting someone else's details</h5>
        <p>If you are registering a project on behalf of a colleague and listing them (not yourself) as the contact, please make sure they know their name and email will be published publicly before you submit — the submission form asks you to confirm this.</p>

        <hr class="my-4">
        <p class="text-muted" style="font-size: 0.85rem;"><em>This notice covers the registry only. It doesn't replace or override your own institution's data protection policies.</em></p>
      </div>
    </div>

  </div>
</section>

<style>
/* Enhanced Get Involved Page Styling */
.involvement-section {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.involvement-section:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.section-title {
  color: #0366d6;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e1e4e8;
}

.platform-benefits-title {
  color: #24292e;
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 2rem;
}

.benefits-container {
  display: flex;
  justify-content: center;
  align-items: stretch;
  gap: 2rem;
  flex-wrap: wrap;
  margin: 0 auto;
  max-width: 900px;
}

.benefit-card {
  background: #f8f9fa;
  padding: 2rem 1rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  flex: 1;
  min-width: 250px;
  max-width: 280px;
}

.benefit-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.benefit-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.github-container {
  display: flex;
  justify-content: center;
  margin: 0 auto;
  max-width: 600px;
}

.unified-github-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  border-left: 4px solid #0366d6;
  width: 100%;
}

.unified-github-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.contribution-section {
  margin-top: 2rem;
  padding-top: 2rem;
  border-top: 1px solid #e1e4e8;
}

.github-link {
  text-decoration: none;
  transition: all 0.3s ease;
  display: inline-block;
}

.github-link:hover {
  transform: scale(1.05);
  text-decoration: none;
}

.github-link svg {
  transition: all 0.3s ease;
}

.github-link:hover svg {
  transform: scale(1.1);
}

.unified-github-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.unified-github-card h6 {
  color: #0366d6;
  font-weight: 600;
  margin-top: 1rem;
  margin-bottom: 0.5rem;
}

.contribution-steps {
  list-style: none;
  padding-left: 0;
}

.contribution-steps li {
  padding: 0.5rem 0;
  padding-left: 1.5rem;
  position: relative;
}

.contribution-steps li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0366d6;
  font-weight: bold;
}

.contribution-steps a {
  color: #0366d6;
  text-decoration: none;
}

.contribution-steps a:hover {
  text-decoration: underline;
}

/* Project Registry */
.registry-note {
  font-size: 0.85rem;
}

.table-responsive {
  overflow-x: auto;
}

.registry-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.9rem;
}

.registry-table th,
.registry-table td {
  padding: 0.6rem 0.75rem;
  border-bottom: 1px solid #e1e4e8;
  text-align: left;
  vertical-align: top;
}

.registry-table th {
  background: #f6f8fa;
  color: #24292e;
  font-weight: 600;
}

.status-badge {
  display: inline-block;
  padding: 0.15rem 0.6rem;
  border-radius: 999px;
  font-size: 0.75rem;
  font-weight: 600;
  white-space: nowrap;
}

.status-active { background: #dafbe1; color: #1a7f37; }
.status-completed { background: #eaeef2; color: #57606a; }
.status-planned { background: #ddf4ff; color: #0969da; }

.tag-pill {
  display: inline-block;
  background: #f1f8ff;
  color: #0366d6;
  border-radius: 999px;
  padding: 0.1rem 0.5rem;
  font-size: 0.75rem;
  margin: 0 0.2rem 0.2rem 0;
}

.registry-privacy {
  border-top: 1px solid #e1e4e8;
  padding-top: 1.5rem;
  font-size: 0.9rem;
}

.registry-privacy-title {
  color: #0366d6;
  font-weight: 600;
  margin-bottom: 0.75rem;
}

.registry-privacy h5 {
  color: #24292e;
  font-weight: 600;
  font-size: 1rem;
  margin-top: 1.25rem;
  margin-bottom: 0.35rem;
}

.btn-primary {
  background-color: #0366d6;
  border-color: #0366d6;
  padding: 0.75rem 1.5rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.btn-primary:hover {
  background-color: #0256c7;
  border-color: #0256c7;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(3, 102, 214, 0.3);
}

/* Enhanced fade-in animations */
.fade-in-center {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeInUp 1.2s ease-out forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Responsive design */
@media (max-width: 768px) {
  .involvement-section {
    padding: 1.5rem;
  }
  
  .benefits-container, .github-container {
    flex-direction: column;
    gap: 1rem;
    max-width: 100%;
  }
  
  .benefit-card, .unified-github-card {
    padding: 1.5rem 1rem;
    min-width: auto;
    max-width: 100%;
    flex: none;
  }
  
  .contribution-section {
    margin-top: 1.5rem;
    padding-top: 1.5rem;
  }
  
  .section-title {
    font-size: 1.25rem;
  }
}
</style>