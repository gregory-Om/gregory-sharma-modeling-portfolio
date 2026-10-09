---
layout: profile
title: Gregory Sharma - Contact
permalink: /contact/
---

<style>
.contact-page { box-sizing: border-box; max-width: 1000px; margin: 0 auto; padding: 20px 40px 30px; min-height: calc(100vh - 75px); min-height: calc(100dvh - 75px); }
.contact-page .profile-hero { margin-bottom: 28px; text-align: center; }
.contact-page .profile-heading { font-size: clamp(2rem, 4vw, 3.5rem); margin-bottom: 10px; }
.contact-page .profile-rule { margin: 0 auto; }
.contact-card { box-sizing: border-box; display: grid; grid-template-columns: 170px 1fr 36px; align-items: baseline; padding: 22px 4px; border-bottom: 1px solid var(--color-body-text); color: var(--color-body-text); text-decoration: none; text-align: left; transition: transform 0.25s ease, color 0.25s ease, border-color 0.25s ease; }
.contact-card:last-child { border-bottom: none; }
a.contact-card::after { content: "\2197"; justify-self: end; font-size: 1.4rem; opacity: 0; transform: translateX(-8px); transition: opacity 0.25s ease, transform 0.25s ease; }
.contact-card:hover { transform: translateY(-6px); border-bottom-color: var(--color-link-hover); color: var(--color-link-hover); }
a.contact-card:hover::after { opacity: 1; transform: translateX(0); }
.contact-card-label { line-height: 1.1; font-size: clamp(1.05rem, 1.7vw, 1.4rem); font-weight: 700; letter-spacing: 0.12em; text-transform: uppercase; }
.contact-card-value { font-size: clamp(1.3rem, 2.5vw, 2rem); line-height: 1.1; overflow-wrap: anywhere; }
@media (max-width: 768px) {
.contact-page { padding: 12px 16px 20px; }
.contact-card { grid-template-columns: 1fr; row-gap: 6px; padding: 16px 2px; }
.contact-card-label { font-size: 0.95rem; }
.contact-card-value { font-size: 1.15rem; }
a.contact-card::after { display: none; }
}
</style>

<div class="contact-page">

<div class="profile-hero">
<p class="profile-eyebrow">Get in Touch</p>
<h1 class="profile-heading">Contact</h1>
<div class="profile-rule"></div>
</div>

<div class="contact-grid">

<a href="mailto:sharma.gregory@gmail.com" class="contact-card">
<span class="contact-card-label">Email</span>
<span class="contact-card-value">sharma.gregory@gmail.com</span>
</a>

<a href="tel:+15183098489" class="contact-card">
<span class="contact-card-label">Phone</span>
<span class="contact-card-value">+1 (518) 309-8489</span>
</a>

<a href="https://www.instagram.com/gregorythesharma" class="contact-card" target="_blank" rel="noopener">
<span class="contact-card-label">Instagram</span>
<span class="contact-card-value">@gregorythesharma</span>
</a>

<div class="contact-card">
<span class="contact-card-label">Based In</span>
<span class="contact-card-value">San Francisco, CA</span>
</div>

<div class="contact-card">
<span class="contact-card-label">Available</span>
<span class="contact-card-value">Los Angeles · New York · San Francisco · Travel-Flexible</span>
</div>

</div>
</div>