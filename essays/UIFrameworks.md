---
layout: essay
type: essay
title: "UI Frameworks: Worth the Hype or Just Extra Baggage?"
# All dates must be YYYY-MM-DD format!
date: 2025-02-27
published: true
labels:
  - Bootstrap 5
  - UI Framework
  - HTML
  - CSS
---

<h3>Frameworks To The Help</h3>   
<img width="300px" class="rounded float-start pe-4" src="../img/essayUIFramework/UIFrameworks.png">  

UI Frameworks are not simple. In fact, they can be almost as complicated to learn as a new programming language. Given that, why bother to use something like Bootstrap 5? What does one get in return for the investment of time and frustration? Why not just use raw HTML and CSS? Are the software engineering benefits of UI frameworks?

For this assignment, create an engaging and informative essay about UI Frameworks. You might want to discuss some of the issues raised above, as well as your own personal experience with Bootstrap 5. Or perhaps you’ve also used another framework such as Semantic UI. In that case, it might be interesting to read your perspective on a comparison of the two.

This essay is tailor made to include an image of a web page built with a UI framework (or even a comparison of web pages built with and without a UI framework).

Feel free to go in another direction entirely, as long as you are discussing UI Frameworks, and as long as the result is interesting, informative, and insightful. Write for the world!


## The Struggle is Real

UI frameworks are not simple to manage and learn. Learning one can be like trying a completely new programming language.When I first looked at Bootstrap 5 in ICS 314 I though it was such a hussle to lookup the available classes that would do what I wanted to do instead of just writting the CSS file. I am pretty sure I am not alone and people have thought, *"Why bother?"*.

The question is, why developers use UI frameworks instead of just writing raw HTML and CSS? What’s the payoff. Are they really worth it? Let’s dive in.

## First, What’s a UI Framework?

According to Samantha Zhang in a [Medium](https://medium.com/5000-things/learning-from-lego-a-step-forward-in-modular-web-design-d8ff953f45a8) published article. A UI framework is a pre-built set of components, styles, and utilities that make web development faster and more consistent. It's like a LEGO set, instead of creating plastic bricks from scratch, you getalready made to just snap together.

<u>Some Popular UI frameworks</u>:
- **Bootstrap** – The OG framework used for ICS 314.
- **Tailwind CSS** – Styling is on steroids.
- **Semantic UI** – Readable class names, very nice defaults.

## The Payoff of Using UI Frameworks

1. **Speed & Efficiency**
Instead of writing CSS from scratch, you can use pre-styled components. A nice navigation bar with no need to enter an extensive *style.css* full of different fomatting.

2. **Teamwork Consistency**
When working as a team, UI frameworks ensure that everyone’s styling is the same. NO MORE DEBATING ON STYLE!

## My Experience with Bootstrap 5
<img width="100px" class="rounded float-start pe-4" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1200px-Bootstrap_logo.svg.png">  
I've used both Bootstrap 5 and it is fantastic for quick prototyping. The grid system is intuitive, and the documentation is very solid. Everytime I run into an error, forums and their documentation has been able to solve them. I do think it is a little more time consuming that writing your own style but when it comes to designing the navigation bar, footer, columns, it works wonders.   

If you like structure and efficiency, Bootstrap is a solid choice. I have personally never used any other frameworks, but I would love to try and see their differences.

## UI Frameworks in Action

Here's an example of a simple web page built with Bootstrap 5:

```html
<head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>
    <div class="container text-center mt-5">
        <h1 class="text-primary">Hello, UI Frameworks!</h1>
        <button class="btn btn-success">Click Me</button>
    </div>
</body>
</html>
```

Now, imagine writing all that styling manually. It would take **so long**!

## Conclusion

I believe the decision to use UI Frameworks or not despends on what you need for your project. If you care designing a prototype with a team then you most likely want to use one to be consistent. If you want more control over the design then you probably dont. Either way, learning a framework is a great skill to have since it saves time, improves consistency, and lets you focus on what really matters: **building good websites**.