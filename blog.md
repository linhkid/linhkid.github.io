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

/* Additional styles to ensure iframe visibility */
.substack-post-embed iframe {
    width: 100% !important;
    min-height: 400px !important;
    margin: 0 !important;
}

@media (max-width: 768px) {
    .blog-grid {
        grid-template-columns: 1fr;
    }
}
</style>

<div class="blog-container">
    <div class="blog-grid">
        <!-- Use the full iframe embed code from Substack for each post -->
        <iframe src="https://neuropurrfectai.substack.com/embed/p/deepseek-r1-a-new-era-in-deep-thinking" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-1st-10th" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-22nd-31st" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/in-depth-papers-highlight-8th-21th" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>

        <iframe src="https://neuropurrfectai.substack.com/embed/p/from-wwdc-2024-apple-intelligence" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>
    </div>
</div>