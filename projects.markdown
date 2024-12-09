---
layout: page
title: Projects
permalink: /projects/
---

<div class="flex justify-center mt-4">
  <a href="/contact" class="bg-red-500 hover:bg-red-700 text-white text-2xl font-bold py-2 px-4 rounded-full my-4 inline-block">Contact Us</a>
</div>

<img src="/assets/Free-Estimate-Call-Today.png" alt="Free Estimate Call Today" class="w-[100px] mx-auto block mb-4" />


<div id="painting" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Painting</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.painting.images %}
        <img src="/assets/painting/{{ image }}" alt="painting" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div id="tiling" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Tiling</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.tiling.images %}
        <img src="/assets/tiling/{{ image }}" alt="tiling" width="100%" height="100%" class="rounded-2xl aspect-square" />
        {% endfor %}
    </div>
</div>

<div id="bathrooms" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Bathrooms</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.bathrooms.images %}
        <img src="/assets/bathroom/{{ image }}" alt="bathroom" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>

</div>

<div id="kitchens" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Kitchens</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.kitchen.images %}
        <img src="/assets/kitchen/{{ image }}" alt="kitchen" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div id="outdoor" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Outdoor Living</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.outdoor.images %}
        <img src="/assets/outdoor/{{ image }}" alt="outdoor-living" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div id="closets" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Closets and Stairs</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.closets.images %}
        <img src="/assets/closets/{{ image }}" alt="closet" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div id="decking" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Decking</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.deck.images %}
        <img src="/assets/deck/{{ image }}" alt="deck" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div id="fireplace" class="mb-4">
    <h2 class="text-xl font-bold mb-2 text-center bg-gray-300 rounded-2xl py-2 w-full">Fireplace</h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-1">
        {% for image in site.data.fireplace.images %}
        <img src="/assets/fireplace/{{ image }}" alt="fireplace" width="100%" height="100%" class="rounded-2xl aspect-square object-cover" />
        {% endfor %}
    </div>
</div>

<div class="flex justify-center mt-4">
  <a href="/contact" class="bg-red-500 hover:bg-red-700 text-white text-2xl font-bold py-2 px-4 rounded-full my-4 inline-block">Contact Us</a>
</div>

<img src="/assets/Free-Estimate-Call-Today.png" alt="Free Estimate Call Today" class="w-[100px] mx-auto block mb-4" />



