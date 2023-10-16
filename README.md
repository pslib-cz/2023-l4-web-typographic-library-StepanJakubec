[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** *Štěpán Jakubec*

## Description
Verse.css is a typography library for enhancing your HTML projects – and the best part? It's absolutely free! Elevate your web design by seamlessly integrating this resource into your code. All you need to do is download the file and connect it via a stylesheet reference. The CSS is fully responsive and works on every browser. Enjoy the magic of Verse.css!

## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-StepanJakubec/)** site for preview.

## Signpost
1. [Implementation](#Implementation)
2. [Font](#Font)
3. [Colors](#Colors)
4. [Headings](#Headings)
5. [Text](#Text)
6. [Photos](#Photos)
7. [Button](#Button)
8. [Lists](#Lists)
9. [Tables](#Tables)

## Implementation
1) Download verse.css
2) Put it into folder with your html
3) Link verse.css with your html

## Font
Verse.css is using linked google font, which can be simply changed to yours.
```html
@import url('https://fonts.googleapis.com/css2?family=Bitter:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

body{
    font-family: 'Kanit', sans-serif;
}
```
## Colors
The predefined colors can be changed by `:root` selector.
```html
:root {
    --white: #fff;
    --blue: rgb(69, 63, 256);
    --gray: #484848;
}
```
## Headings
You can use headings from `<h1>` to `<h6>`.

## Text
A standart paragraph is defined by `<p>` tag. There are also:
* `<b>` for bold text
* `<u>` for underlined text
* `<s>` for striked text
* `<mark>` for highlighted text
* `<i>` for italic text
* `<small>` for small text

## Photos
To use image template, modify your wrapper as `<figure class="galerry__block>`
```html
<figure class="gallery__block">
            <a href="./docs/Images/09-Eureka-Rolando-Cyril-AquaSixio-Digital-Art-in-a-Universe-between-Surreal-and-Fantasy-www-designstack-co.jpg">
                <img src="./docs/Images/09-Eureka-Rolando-Cyril-AquaSixio-Digital-Art-in-a-Universe-between-Surreal-and-Fantasy-www-designstack-co.jpg" alt="Man sitting in a universe">
                <figcaption class="gallery__caption">Single Image</figcaption>
            </a>
        </figure>
}
```
To create gallery use `<div class="gallery">`

## Button
To add button, add `class="button"` to `<a>` tag

## Lists
* Ordered list
```html
<ol>
    <li>RB Leipzig</li>
    <li>Real Madrid</li>
    <li>Liverpool</li>
        <ol>
            <li>Liverpool U18</li>
            <li>Liverpool U17</li>
        </ol>
</ol>
```
* Unordered list
```html
<ul>
    <li>Facebook</li>
    <li>Tik Tok</li>
    <li>Instagram</li>
        <ul>
            <li>Instagram reels</li>
            <li>Instagram stories</li>
            <li>Instagram posts</li>
        </ul>
</ul>
```

## Tables
You can use predefined table with standart `<table>` tag.
Use predefined table for your beggining
```html
<table>
              <thead>
                  <tr>
                  <th>Player</th>
                  <th>Age</th>
                  <th>Team</th>
                  <th>Nationality</th>
                  <th>Goals</th>
                </tr>
              </thead>
              <tbody>
                  <tr>
                    <td>Cristiano Ronaldo</td>
                    <td>38</td>
                    <td>Al Nassr</td>
                    <td>Portugal</td>
                    <td>800+</td>
                  </tr>
                  <tr>
                    <td>Lionel Messi</td>
                    <td>36</td>
                    <td>Inter Miami</td>
                    <td>Argentina</td>
                    <td>800+</td>
                  </tr>
                  <tr>
                    <td>Erling Haaland</td>
                    <td>23</td>
                    <td>Manchester City</td>
                    <td>Norway</td>
                    <td>200+</td>
                  </tr>
              </tbody>
          </table>
```



