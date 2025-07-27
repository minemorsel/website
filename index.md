---
layout: home
title: My Awesome Homepage
---

<div class="banner-container relative bg-gray-700 flex items-center justify-center rounded-b-lg shadow-lg">
    <!-- Banner Image -->
    <img src="{{ "/assets/images/banner.jpg" | relative_url }}"
         alt="Website Banner"
         class="banner-image">

    <!-- Logo Overlay -->
    <div class="logo-overlay">
        <img src="{{ "/assets/images/logo.jpg" | relative_url }}"
             alt="Company Logo"
             class="w-32 h-32 md:w-40 md:h-40 rounded-full border-4 border-white shadow-lg">
    </div>
</div>

<main class="container mx-auto my-8 p-6 bg-white rounded-lg shadow-md">
    <section class="text-center mb-8">
        <h2 class="text-4xl font-extrabold text-gray-900 mb-4">Welcome to My Homepage!</h2>
        <p class="text-lg text-gray-600 leading-relaxed max-w-3xl mx-auto">
            This is an example of a beautiful and responsive homepage. Customize this content to tell your story, showcase your
            projects, or share your thoughts.
        </p>
    </section>

    <!-- ... (rest of your content sections) ... -->
</main>