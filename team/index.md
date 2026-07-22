---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
  sort="order"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
  sort="order"
%}

## PhD Students
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
  sort="order"
%}

## Master's Students
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ms"
  sort="order"
%}

## Undergraduate Students
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
  sort="order"
%}

{% include section.html %}

## Alumni
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
  sort="order"
%}
{:.center}

{%
  include figure.html
  image="images/team/group.jpg"
  caption="Our team in the field"
  link="team"
  width="500px"
%}

{% include section.html %}

## Funding

Our work is made possible by funding from the following organizations.
{:.center}

{::nomarkdown}
<div style="display:flex;flex-wrap:wrap;justify-content:center;align-items:stretch;gap:30px;margin:40px 0;">
  <a href="https://www.nsf.gov/" data-tooltip="U.S. National Science Foundation" style="display:flex;align-items:center;justify-content:center;width:230px;height:140px;padding:24px;background:#ffffff;border-radius:14px;box-shadow:0 3px 12px rgba(0,0,0,0.15);">
    <img src="{{ 'images/funding/nsf.png' | relative_url }}" alt="U.S. National Science Foundation" style="max-width:100%;max-height:100%;object-fit:contain;" />
  </a>
  <a href="https://kingcounty.gov/" data-tooltip="King County, Washington" style="display:flex;align-items:center;justify-content:center;width:230px;height:140px;padding:24px;background:#14432a;border-radius:14px;box-shadow:0 3px 12px rgba(0,0,0,0.15);">
    <img src="{{ 'images/funding/king-county.svg' | relative_url }}" alt="King County, Washington" style="max-width:100%;max-height:100%;object-fit:contain;" />
  </a>
</div>
{:/}
