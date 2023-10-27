---
layout: post
---

## Intro

WILDS will and does have publicly available code in varying states of usability, development, and support. We think it's important to get code in users hands early and often to make sure we're solving users needs; given that situation, we want to clearly communicate that the software may not be stable yet. On the other extreme software may no longer be maintained, and we want to have a standard way to communicate about that as well.

Software maintainers often achieve this communication about the status of a piece of software using a simple badge at the top of the landing page for the software.

These badges are adapted from Repostatus.org.

## Repo Statuses

* <a name="concept"></a>__Concept__ – Not useable, no support, not open to feedback, unstable API.
* <a name="experimental"></a>__Experimental__ – Useable, some support, not open to feedback, unstable API.
* <a name="prototype"></a>__Prototype__ – Useable, some support, open to feedback, unstable API.
* <a name="stable"></a>__Stable__ – Useable, full support, open to feedback, stable API.
* <a name="deprecated"></a>__Deprecated__ – Useable as of a fixed, past date, no support, not open to feedback, stable API as of a fixed, past date.

## What It Looks Like

[![Project Status: Stable – Useable, full support, open to feedback, stable API.](/badges/stable.svg)](https://getwilds.github.io/badges/#stable)

This incorporates three components:

1. The image URL, which serves as the machine-readable status identifier. It points to a status-specific image hosted on `getwilds.org`.
2. Alt-text on the image (this can generally be viewed in a browser by mousing over the image) which begins with the canonical project status ("Project Status: <status name>") and can optionally be followed by a human-readable description of the status, provided by the project's maintainer(s). Such text might also be useful to appear after the badge.
3. The image is linked back to the particular status description at <https://getwilds.github.io/badges/>.

## Use a badge

Click any of the below buttons to copy to your clipboard the text for badges for the 5 badge types and for each of 3 markup types (<a class="btn btn-sm btn-info" role="button">Markdown</a>, Restructured text (<a class="btn btn-sm btn-primary" role="button">ReST</a>), or <a class="btn btn-sm btn-secondary" role="button">HTML</a>; i.e., if your README is a markdown file, get the Markdown version of the badge). 

**Concept** [![Project Status: Concept – Not useable, no support, not open to feedback, unstable API.](/badges/concept.svg)](https://getwilds.github.io/badges/#concept)

<div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
  <button type="button" class="btn btn-info" onclick="copysample('concept','md')">Markdown</button>
  <button type="button" class="btn btn-primary" onclick="copysample('concept','rst')">ReST</button>
  <button type="button" class="btn btn-secondary" onclick="copysample('concept','html')">HTML</button>
</div>

<br>

**Experimental** [![Project Status: Experimental – Useable, some support, not open to feedback, unstable API.](/badges/experimental.svg)](https://getwilds.github.io/badges/#experimental)

<div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
  <button type="button" class="btn btn-info" onclick="copysample('experimental','md')">Markdown</button>
  <button type="button" class="btn btn-primary" onclick="copysample('experimental','rst')">ReST</button>
  <button type="button" class="btn btn-secondary" onclick="copysample('experimental','html')">HTML</button>
</div>

<br>

**Prototype** [![Project Status: Prototype – Useable, some support, open to feedback, unstable API.](/badges/prototype.svg)](https://getwilds.github.io/badges/#prototype)

<div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
  <button type="button" class="btn btn-info" onclick="copysample('prototype','md')">Markdown</button>
  <button type="button" class="btn btn-primary" onclick="copysample('prototype','rst')">ReST</button>
  <button type="button" class="btn btn-secondary" onclick="copysample('prototype','html')">HTML</button>
</div>

<br>

**Stable** [![Project Status: Stable – Useable, full support, open to feedback, stable API.](/badges/stable.svg)](https://getwilds.github.io/badges/#stable)

<div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
  <button type="button" class="btn btn-info" onclick="copysample('stable','md')">Markdown</button>
  <button type="button" class="btn btn-primary" onclick="copysample('stable','rst')">ReST</button>
  <button type="button" class="btn btn-secondary" onclick="copysample('stable','html')">HTML</button>
</div>

<br>

**Deprecated** [![Project Status: Deprecated – Useable as of a fixed, past date, no support, not open to feedback, stable API as of a fixed, past date.](/badges/deprecated.svg)](https://getwilds.github.io/badges/#deprecated)

<div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
  <button type="button" class="btn btn-info" onclick="copysample('deprecated','md')">Markdown</button>
  <button type="button" class="btn btn-primary" onclick="copysample('deprecated','rst')">ReST</button>
  <button type="button" class="btn btn-secondary" onclick="copysample('deprecated','html')">HTML</button>
</div>

<div id="samplewrapper" style="display: none;"><h5 id="sampletitle"></h5><div id="samplecode"></div></div>

<br>


## References

These badges and content of this repository were adapted from the following sources:

- [repostatus.org](https://www.repostatus.org/) - License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
