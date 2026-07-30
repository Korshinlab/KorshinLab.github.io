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
  padding:13px;
  border-radius:3px;
  background:linear-gradient(135deg,#a56d36 0%,#6a4120 30%,#7d4d26 55%,#442a11 100%);
  box-shadow:
    0 16px 38px rgba(0,0,0,.52),
    inset 4px 4px 5px rgba(255,255,255,.32),
    inset -5px -5px 9px rgba(0,0,0,.62),
    inset 0 0 0 1px rgba(0,0,0,.45);
  transition:transform .18s ease, box-shadow .18s ease;
}
.art-frame:hover{
  transform:translateY(-4px);
  box-shadow:0 24px 50px rgba(0,0,0,.58),inset 4px 4px 5px rgba(255,255,255,.32),inset -5px -5px 9px rgba(0,0,0,.62),inset 0 0 0 1px rgba(0,0,0,.45);
}
.art-frame .art-mat{
  display:block;
  padding:14px;
  background:#f4efe2;
  box-shadow:
    inset 3px 3px 7px rgba(0,0,0,.42),
    inset -1px -1px 3px rgba(255,255,255,.5);
}
.art-frame img{display:block;width:100%;height:auto;}
@media (max-width:520px){
  .art-wall{gap:30px;}
  .art-frame{padding:10px;}
  .art-frame .art-mat{padding:10px;}
}
</style>

<div class="art-wall">
  <figure class="art-frame"><span class="art-mat"><img src="{{ 'images/art/art1.jpg' | relative_url }}" alt="Artwork by Gregory Korshin" /></span></figure>
  <figure class="art-frame"><span class="art-mat"><img src="{{ 'images/art/art2.jpg' | relative_url }}" alt="Artwork by Gregory Korshin" /></span></figure>
</div>
{:/}
