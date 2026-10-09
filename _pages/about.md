---
permalink: /
title: "Take a seat"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Research / Soccer / [Lex Fridman](https://www.youtube.com/@lexfridman).

Hi, I'm Furkan. I'm a PhD student in Statistics at the **University of Toronto** and a researcher at the **[Vector Institute](https://vectorinstitute.ai/)**, co-supervised by [Dehan Kong](https://www.statistics.utoronto.ca/people/directories/all-faculty/dehan-kong) (Statistics) and [Zhijing Jin](https://zhijing-jin.com/) (Computer Science).

**In one sentence:** I build statistical and AI tools that answer *"what if?"* questions (what if this patient had gotten a different treatment, what if this policy had changed), and I check whether AI systems actually understand cause and effect or are just very confident guessers.

## What I work on, in plain English

<div class="areas">

<div class="area">
<h3>Statistics</h3>
<svg class="fig" viewBox="0 0 320 126" role="img" aria-label="Millions of simulated worlds train one model; your dataset goes in; a what-if answer comes out in seconds">
  <defs><marker id="a1" viewBox="0 0 8 8" refX="7" refY="4" markerWidth="7" markerHeight="7" orient="auto"><path d="M0,0 L8,4 L0,8 z"/></marker></defs>
  <rect class="box" x="4" y="10" width="96" height="44" rx="8"/><text x="52" y="28" text-anchor="middle">millions of</text><text x="52" y="43" text-anchor="middle">simulated worlds</text>
  <rect class="box hl" x="124" y="10" width="80" height="44" rx="8"/><text x="164" y="28" text-anchor="middle">one</text><text x="164" y="43" text-anchor="middle">trained model</text>
  <rect class="box" x="228" y="10" width="88" height="44" rx="8"/><text x="272" y="28" text-anchor="middle">what-if answer</text><text x="272" y="43" text-anchor="middle">in seconds</text>
  <rect class="box" x="124" y="84" width="80" height="34" rx="8"/><text x="164" y="105" text-anchor="middle">your dataset</text>
  <path class="arr" d="M100,32 H121" marker-end="url(#a1)"/><path class="arr" d="M204,32 H225" marker-end="url(#a1)"/><path class="arr" d="M164,84 V57" marker-end="url(#a1)"/>
  <text class="lbl" x="110" y="76" text-anchor="end">train once</text><text class="lbl" x="218" y="76">reuse forever</text>
</svg>
<p><b>The question.</b> Did the medicine make you better, or would you have gotten better anyway? Answering "what if" questions like this normally takes an expert weeks of careful modelling, for every new dataset.</p>
<p><b>What I do.</b> I train one model on millions of simulated worlds, so it learns to answer "what if?" for a brand-new dataset in seconds. Researchers call this a <i>causal foundation model</i>. I also build methods that recover the full shape of data that only arrives in bins ("50 people earn $100k–$120k…"), and prove when they're guaranteed to work.</p>
<p class="area-quip">Correlation is not causation. I'm teaching this to machines; plenty of humans are still taking the course.</p>
<a class="area-link" href="/publications/?topic=stats">Statistics papers →</a>
</div>

<div class="area">
<h3>Economics</h3>
<svg class="fig" viewBox="0 0 320 126" role="img" aria-label="A lender deposits into a smart contract, which lends to a borrower who posts collateral; if the collateral loses value the loan is liquidated">
  <defs><marker id="a2" viewBox="0 0 8 8" refX="7" refY="4" markerWidth="7" markerHeight="7" orient="auto"><path d="M0,0 L8,4 L0,8 z"/></marker></defs>
  <rect class="box" x="4" y="30" width="60" height="44" rx="8"/><text x="34" y="56" text-anchor="middle">lender</text>
  <rect class="box hl" x="115" y="30" width="90" height="44" rx="8"/><text x="160" y="48" text-anchor="middle">smart contract</text><text x="160" y="63" text-anchor="middle">(no bank)</text>
  <rect class="box" x="246" y="30" width="70" height="44" rx="8"/><text x="281" y="56" text-anchor="middle">borrower</text>
  <path class="arr" d="M64,42 H112" marker-end="url(#a2)"/><text class="lbl" x="89" y="24" text-anchor="middle">deposits</text>
  <path class="arr" d="M205,42 H243" marker-end="url(#a2)"/><text class="lbl" x="225" y="24" text-anchor="middle">loan</text>
  <path class="arr" d="M246,64 H208" marker-end="url(#a2)"/><text class="lbl" x="227" y="88" text-anchor="middle">collateral</text>
  <rect class="box note" x="60" y="96" width="200" height="24" rx="6"/><text class="lbl" x="160" y="112" text-anchor="middle">collateral drops in value → auto-liquidated</text>
</svg>
<p><b>The question.</b> What happens when you lend money to a stranger on the internet, with no bank in the middle? And what if AI agents ran the systems banks use to move billions to each other every day?</p>
<p><b>What I do.</b> At the Bank of Canada I studied decentralized-finance (DeFi) lending: what it earns, how much borrowing it piles up, and what happens when it all gets liquidated. I also built a simulated payment system where AI agents play fund managers, and watched how they strategize.</p>
<p class="area-quip">My most-read work (300,000+ views) is about lending money to strangers on the internet. I have made peace with this.</p>
<a class="area-link" href="/publications/?topic=econ">Economics papers →</a>
</div>

<div class="area">
<h3>Healthcare</h3>
<svg class="fig" viewBox="0 0 320 126" role="img" aria-label="Dense breast tissue both raises cancer risk and hides tumours on a mammogram; the model separates the two effects">
  <defs><marker id="a3" viewBox="0 0 8 8" refX="7" refY="4" markerWidth="7" markerHeight="7" orient="auto"><path d="M0,0 L8,4 L0,8 z"/></marker></defs>
  <rect class="box hl" x="4" y="38" width="104" height="44" rx="8"/><text x="56" y="56" text-anchor="middle">dense breast</text><text x="56" y="71" text-anchor="middle">tissue</text>
  <rect class="box" x="196" y="6" width="120" height="40" rx="8"/><text x="256" y="30" text-anchor="middle">higher cancer risk</text>
  <rect class="box" x="196" y="78" width="120" height="42" rx="8"/><text x="256" y="95" text-anchor="middle">tumour harder to see</text><text x="256" y="110" text-anchor="middle">on the mammogram</text>
  <path class="arr" d="M108,52 L193,28" marker-end="url(#a3)"/><text class="lbl" x="150" y="30" text-anchor="middle">raises</text>
  <path class="arr" d="M108,68 L193,96" marker-end="url(#a3)"/><text class="lbl" x="150" y="100" text-anchor="middle">hides</text>
  <text class="lbl" x="56" y="104" text-anchor="middle">my model tells</text><text class="lbl" x="56" y="116" text-anchor="middle">these two apart</text>
</svg>
<p><b>The question.</b> Dense breast tissue raises the risk of breast cancer, but it also makes tumours harder to spot on a mammogram. How do you tell those two effects apart?</p>
<p><b>What I do.</b> I build models that follow women's mammograms over 5–8 years and separate "this raises your risk" from "this hides the cancer". That work won the best student presentation award at the Statistical Society of Canada in 2026. I also do the statistics for clinical studies, from burnout among cancer doctors to how patients feel about AI in their care.</p>
<p class="area-quip">The place where a p-value stops being abstract.</p>
<a class="area-link" href="/publications/?topic=healthcare">Healthcare papers →</a>
</div>

<div class="area">
<h3>LLMs</h3>
<svg class="fig" viewBox="0 0 320 126" role="img" aria-label="A real scientific study is given to an LLM; its cause-and-effect answer is compared with the experts' answer">
  <defs><marker id="a4" viewBox="0 0 8 8" refX="7" refY="4" markerWidth="7" markerHeight="7" orient="auto"><path d="M0,0 L8,4 L0,8 z"/></marker></defs>
  <rect class="box" x="4" y="10" width="86" height="44" rx="8"/><text x="47" y="28" text-anchor="middle">real scientific</text><text x="47" y="43" text-anchor="middle">study</text>
  <rect class="box hl" x="116" y="10" width="62" height="44" rx="8"/><text x="147" y="36" text-anchor="middle">LLM</text>
  <rect class="box" x="204" y="10" width="112" height="44" rx="8"/><text x="260" y="28" text-anchor="middle">its cause-and-effect</text><text x="260" y="43" text-anchor="middle">answer</text>
  <rect class="box" x="204" y="86" width="112" height="34" rx="8"/><text x="260" y="107" text-anchor="middle">the experts' answer</text>
  <path class="arr" d="M90,32 H113" marker-end="url(#a4)"/><path class="arr" d="M178,32 H201" marker-end="url(#a4)"/>
  <path class="arr dash" d="M260,57 V83" marker-end="url(#a4)"/><text class="lbl" x="252" y="74" text-anchor="end">does it match?</text>
</svg>
<p><b>The question.</b> Do chatbots like ChatGPT actually understand cause and effect, or do they just sound like they do?</p>
<p><b>What I do.</b> I build tests that check whether LLMs can do the cause-and-effect analysis in real scientific studies (CauSciBench, ICML 2026). I also look inside these models to see where "culture" lives, and teach them to recognize the same causal story told in different words.</p>
<p class="area-quip">They're very confident. We're checking whether they should be.</p>
<a class="area-link" href="/publications/?topic=llms">LLM papers →</a>
</div>

</div>

## How I got here

<div class="path">
  <div><b>Ankara</b><span>Modelled years of mammograms as a research fellow at TÜBİTAK, Türkiye's national science council</span></div>
  <div><b>York University</b><span>BSc in Statistics, First Class with Distinction, and the binned-data method above</span></div>
  <div><b>Bank of Canada</b><span>DeFi lending, and AI agents running a pretend payment system</span></div>
  <div><b>UofT + Vector</b><span>PhD (2025–): models that answer "what if?"</span></div>
</div>

## Lately

<ul class="news">
  <li><span class="when">2026</span> Won an <b>NSERC Canada Graduate Research Scholarship</b>. The Government of Canada is now officially funding my curiosity.</li>
  <li><span class="when">Jun 2026</span> <b>Best Student Research Presentation</b>, Statistical Society of Canada (Biostatistics Section), for the mammogram work.</li>
  <li><span class="when">2026</span> <b>CauSciBench</b> is at <b>ICML 2026</b>. Can AI do the cause-and-effect analysis in real scientific papers? (Spoiler: read the paper.)</li>
  <li><span class="when">2026</span> The mammogram paper made it onto <a href="https://stream.interpress.com/temp/48a031d0-4b5b-446f-a091-4d113ea575d1.html">Turkish national news</a>. Both new preprints are on arXiv: <a href="https://arxiv.org/abs/2607.16793">mammograms</a> and <a href="https://arxiv.org/abs/2607.13182">binned data</a>.</li>
  <li><span class="when">Sep 2025</span> Started the PhD, and started teaching tutorials for <b>STA313</b> (Data Visualization, where I gently discourage pie charts) and <b>STA238</b>.</li>
</ul>

My ultimate goal in life is to be friends with a gorilla.

<img src="/images/gorilla.jpg" alt="A gorilla, future friend" style="width:150px;border-radius:6px;">

<style>
.areas { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 14px; margin: 0.8em 0 1.4em; }
.area { border: 1px solid rgba(127,127,127,.3); border-radius: 12px; padding: 14px 16px 12px; font-size: 0.85em; line-height: 1.5; display: flex; flex-direction: column; }
.area h3 { margin: 0 0 8px; font-size: 1.15em; }
.area p { margin: 0 0 0.6em; }
.fig { width: 100%; height: auto; margin: 2px 0 10px; }
.fig text { fill: currentColor; font-size: 11px; font-family: inherit; }
.fig .lbl { font-size: 10px; opacity: .7; }
.fig .box { fill: rgba(127,127,127,.06); stroke: currentColor; stroke-opacity: .4; stroke-width: 1.2; }
.fig .box.hl { fill: rgba(42,120,214,.12); stroke: #2a78d6; stroke-opacity: 1; stroke-width: 1.6; }
.fig .box.note { stroke-dasharray: 4 3; fill: none; }
.fig .arr { fill: none; stroke: currentColor; stroke-opacity: .6; stroke-width: 1.4; }
.fig .arr.dash { stroke-dasharray: 4 3; }
.fig marker path { fill: currentColor; fill-opacity: .6; }
.area-quip { font-style: italic; opacity: .75; border-left: 3px solid #2a78d6; padding-left: 8px; }
.area-link { margin-top: auto; font-weight: 600; font-size: 0.95em; text-decoration: none; }
.path { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 0; margin: 0.6em 0 1.2em; font-size: 0.8em; }
.path div { border-top: 3px solid #2a78d6; padding: 8px 12px 0 0; position: relative; }
.path div::before { content: ""; position: absolute; top: -8px; left: 0; width: 13px; height: 13px; border-radius: 50%; background: #2a78d6; }
.path b { display: block; margin-top: 4px; }
.path span { opacity: .75; }
.news { list-style: none; padding-left: 0; font-size: 0.85em; }
.news li { margin-bottom: 0.7em; padding-left: 5.2em; text-indent: -5.2em; }
.news .when { display: inline-block; width: 5em; text-indent: 0; opacity: .6; font-variant-numeric: tabular-nums; }
</style>
