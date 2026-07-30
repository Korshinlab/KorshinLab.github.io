---
title: Art
nav:
  order: 6
  tooltip: Artwork by Gregory Korshin
---

# <i class="fas fa-palette"></i>Art

Beyond the laboratory, our PI Gregory Korshin is an accomplished artist. A selection of his artwork is shown here.
{:.center}

{% include section.html %}

{::nomarkdown}
<style>
.art-wall{display:flex;flex-wrap:wrap;gap:44px;justify-content:center;align-items:flex-start;margin:34px 0;}
.art-frame{
  margin:0;
  flex:0 1 380px;
  max-width:430px;
  padding:20px;
  border-radius:4px;
  background:linear-gradient(135deg,#946230 0%,#5c3819 38%,#7c4c25 63%,#472b12 100%);
  box-shadow:
    0 20px 42px rgba(0,0,0,.44),
    inset 0 0 0 2px rgba(0,0,0,.38),
    inset 3px 3px 4px rgba(255,255,255,.16),
    inset -3px -3px 6px rgba(0,0,0,.45);
  transition:transform .18s ease, box-shadow .18s ease;
}
.art-frame:hover{
  transform:translateY(-4px);
  box-shadow:0 26px 52px rgba(0,0,0,.5),inset 0 0 0 2px rgba(0,0,0,.38),inset 3px 3px 4px rgba(255,255,255,.16),inset -3px -3px 6px rgba(0,0,0,.45);
}
.art-frame .art-mat{
  display:block;
  padding:18px;
  background:#f5f0e4;
  box-shadow:inset 0 0 11px rgba(0,0,0,.26);
}
.art-frame img{display:block;width:100%;height:auto;}
@media (max-width:520px){
  .art-wall{gap:30px;}
  .art-frame{padding:13px;}
  .art-frame .art-mat{padding:11px;}
}
</style>

<div class="art-wall">
  <figure class="art-frame"><span class="art-mat"><img src="{{ 'images/art/art1.jpg' | relative_url }}" alt="Artwork by Gregory Korshin" /></span></figure>
  <figure class="art-frame"><span class="art-mat"><img src="{{ 'images/art/art2.jpg' | relative_url }}" alt="Artwork by Gregory Korshin" /></span></figure>
</div>
{:/}
