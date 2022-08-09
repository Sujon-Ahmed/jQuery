<img src="JQuery-Logo.svg.png">

In this repository i will practice jQuery Basics, Events, Effects, HTML, Traversing, Ajax etc.

## Table of Contents

- [Introduction](#introduction)
- [Google CDN](#google-cdn)
- [Syntax](#basic-syntax)
- [Advance Selectors](#advance-selectors)

## What is jQuery?

jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

The jQuery library contains the following features:

<ul>
    <li>HTML/DOM manipulation</li>
    <li>CSS manipulation</li>
    <li>HTML event methods</li>
    <li>Effects and animations</li>
    <li>AJAX</li>
    <li>Utilities</li>
</ul>

### Google CDN
<code>https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js</code>

### Basic Syntax

<pre>
<code>
    $(document).ready(function(){

        // jQuery methods go here...

    });
</code>
</pre>

### Advance Selectors

<table>
    <thead>
        <tr>
            <th>SL</th>
            <th>Selector</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>$("*")</td>
            <td>"*" is a universal operator</td>
        </tr>
        <tr>
            <td>2</td>
            <td>$("ul li")</td>
            <td>Here ul is parent and li is child </td>
        </tr>
        <tr>
            <td>3</td>
            <td>$(".abc, .xyz")</td>
            <td>Multiple Classes</td>
        </tr>
        <tr>
            <td>4</td>
            <td>$("h1, div, p")</td>
            <td>Multiple Tags</td>
        </tr>
        <tr>
            <td>5</td>
            <td>$("p:first")</td>
            <td>Page first p element</td>
        </tr>
        <tr>
            <td>6</td>
            <td>$("p:last")</td>
            <td>Page last p element</td>
        </tr>
    </tbody>
</table>


