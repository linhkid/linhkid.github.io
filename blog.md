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

.post-embed {
    background: white;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.2s;
}

.post-embed:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.substack-post-embed p[lang="en"] {
    font-size: 1.1em;
    font-weight: 600;
    margin-bottom: 10px;
    color: #333;
}

.substack-post-embed p:not([lang="en"]) {
    color: #666;
    margin-bottom: 15px;
}

.substack-post-embed a[data-post-link] {
    display: inline-block;
    padding: 8px 16px;
    background: #631919;
    color: white;
    text-decoration: none;
    border-radius: 4px;
}

.substack-post-embed a[data-post-link]:hover {
    background: #7d3f3f;
}

@media (max-width: 768px) {
    .blog-grid {
        grid-template-columns: 1fr;
    }
}
</style>

<div class="blog-container">
    <div class="blog-grid">
        <!-- DeepSeek-R1 Post -->
        <div class="post-embed">
            <div class="substack-post-embed">
                <p lang="en">DeepSeek-R1: A New Era in Deep Thinking (including Mathematical reasoning) Through Reinforcement Learning</p>
                <a data-post-link href="https://neuropurrfectai.substack.com/p/deepseek-r1-a-new-era-in-deep-thinking">Read on Substack</a>
            </div>
        </div>

        <!-- August 1-10 Papers -->
        <div class="post-embed">
            <div class="substack-post-embed">
                <p lang="en">In-depth Papers Highlight 1st - 10th August</p>
                <p>KV-Cache Management is the way to optimize LLM, and better AI alignment with self-improving alignment with LLM-as-a-Meta-Judge... is two of our favorite publications this week.</p>
                <a data-post-link href="https://neuropurrfectai.substack.com/p/in-depth-papers-highlight-1st-10th">Read on Substack</a>
            </div>
        </div>

        <!-- July 22-31 Papers -->
        <div class="post-embed">
            <div class="substack-post-embed">
                <p lang="en">In-depth Papers Highlight 22nd - 31st July</p>
                <p>July ends on a high-note with the comparison between RAG and long-context LLMs and guess what? RAG is not always better. ML-Mamba & Graph-Structured Speculative Decoding are also one of the highlights</p>
                <a data-post-link href="https://neuropurrfectai.substack.com/p/in-depth-papers-highlight-22nd-31st">Read on Substack</a>
            </div>
        </div>

        <!-- July 8-21 Papers -->
        <div class="post-embed">
            <div class="substack-post-embed">
                <p lang="en">In-depth Papers Highlight 8th - 21st July</p>
                <p>A Survey on LLM's efficient inference methods, accuracy is NOT all you need, and also how to detect hallucination in order to combat them... are the theme of these highlights.</p>
                <a data-post-link href="https://neuropurrfectai.substack.com/p/in-depth-papers-highlight-8th-21th">Read on Substack</a>
            </div>
        </div>

        <!-- WWDC 2024 Post -->
        <div class="post-embed">
            <div class="substack-post-embed">
                <p lang="en">From WWDC 2024, Apple Intelligence to the race of Open-Source model</p>
                <p>Corenet is the keyword.</p>
                <a data-post-link href="https://neuropurrfectai.substack.com/p/from-wwdc-2024-apple-intelligence">Read on Substack</a>
            </div>
        </div>
    </div>
</div>

<!-- Single script include for all posts -->
<script async src="https://substack.com/embedjs/embed.js" charset="utf-8"></script>