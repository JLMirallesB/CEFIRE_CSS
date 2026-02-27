# CSS CEFIRE — Quick Reference
## Callout Boxes
Eight colors: `b-gray` `b-green` `b-red` `b-blue` `b-orange` `b-purple` `b-pink` `b-cefire`
**Static box with title:**
<b-blue>
<b-title>Example Title</b-title>
Box content with **Markdown** support.
</b-blue>
```html
<b-blue>
<b-title>Title</b-title>
Content here.
</b-blue>
```
**Collapsible box with title:**
<div><b-cefire>
<details>
<summary><b-title>🔥 Click to expand</b-title></summary>
Content in **Markdown** inside a collapsible.
</details></b-cefire></div>
```html
<div><b-cefire>
<details>
<summary><b-title>🔥 Section title</b-title></summary>

Content in **Markdown** here...
</details></b-cefire></div>
```
**Plain collapsible (no title strip):**
<div><b-blue><details><summary><b>📘 Example</b></summary>
Content here...
</details></b-blue></div>
```html
<div><b-blue><details><summary><b>📘 Title</b></summary>
Content here...
</details></b-blue></div>
```
## Progress Bars
<div class="pbar-label"><span>Reading progress</span><span>70%</span></div>
<div class="pbar"><div class="pfill pfill-blue" style="width:70%"></div></div>
```html
<div class="pbar-label"><span>Label</span><span>70%</span></div>
<div class="pbar"><div class="pfill pfill-blue" style="width:70%"></div></div>
```
Colors: `pfill-blue` `pfill-green` `pfill-orange` `pfill-red` `pfill-purple`
## Stat Boxes
<stat-box><stat-num>42</stat-num><stat-label>Units</stat-label></stat-box>
<stat-box><stat-num>98%</stat-num><stat-label>Pass rate</stat-label></stat-box>
```html
<stat-box><stat-num>42</stat-num><stat-label>Units</stat-label></stat-box>
```
## Badges
<badge-green>Done</badge-green>  <badge-orange>In progress</badge-orange>  <badge-red>Pending</badge-red>  <badge-blue>Info</badge-blue>  <badge-purple>Review</badge-purple>
```html
<badge-green>Done</badge-green>  <badge-orange>In progress</badge-orange>  <badge-red>Pending</badge-red>
```
Colors: `badge-green` `badge-red` `badge-blue` `badge-orange` `badge-gray` `badge-purple` `badge-pink` `badge-cefire`
## Numbered Steps
<steps>
<step>First action</step>
<step>Second action</step>
<step>Third action</step>
</steps>
```html
<steps>
<step>First action</step>
<step>Second action</step>
<step>Third action</step>
</steps>
```
## Section Divider
<sec-label>Example Section</sec-label>
```html
<sec-label>Section title</sec-label>
```
## Level Indicator
Difficulty: <nivel-2></nivel-2> &nbsp; Advanced: <nivel-4></nivel-4> &nbsp; Expert: <nivel-5></nivel-5>
```html
Difficulty: <nivel-3></nivel-3>
```
Scale: `nivel-1` → `nivel-5`
## Author Citation
<cite-author>Author Name, Work Title</cite-author>
```html
<cite-author>Author Name, Work Title</cite-author>
```
## Definition List
Term one
: Definition of term one
Term two
: Definition of term two
```markdown
Term
: Definition of the term
Another term
: Its definition
```
## Table of Contents
```
[[toc]]
```
Headings auto-numbered: h2 → `1.`  h3 → `1.1.`  h4 → `1.1.1.` up to h6.
