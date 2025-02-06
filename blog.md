---
layout: page
title: Blog
---

<style>
.blog-container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px;
}

.blog-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
}

/* Increased height for full preview visibility */
.substack-embed {
    width: 100% !important;
    height: 600px !important; /* Increased from 320px to 600px */
    border: 1px solid #EEE;
    background: white;
    margin-bottom: 20px;
}

@media (max-width: 768px) {
    .blog-grid {
        grid-template-columns: 1fr;
    }
}
</style>

<div class="blog-container">
    <div class="blog-grid">
        <iframe src="https://neuropurrfectai.substack.com/embed/p/deepseek-r1-a-new-era-in-deep-thinking" class="substack-embed" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-1st-10th" class="substack-embed" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-22nd-31st" class="substack-embed" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-8th-21th" class="substack-embed" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/from-wwdc-2024-apple-intelligence" class="substack-embed" frameborder="0" scrolling="no"></iframe>
    </div>
</div>