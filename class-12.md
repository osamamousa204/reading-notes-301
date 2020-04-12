# EJS Partials

Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need 


As you can see from the screenshots above, the same navigation bar and footer appear in both the home and post view. This makes them perfect candidates for partials!
Let’s go ahead and create those partials. Under the views/partials/ directory create a file callednavbar.ejs which will contain only the HTML for the navigation bar at the top of the home and post pages:


`<div class="header clearfix">`
    `<nav>`
        `<ul class="nav nav-pills pull-right">`
            `<li role="presentation"><a href="/">Home</a></li>`
        `</ul>`
        `<h3 class="text-muted">Node.js Blog</h3>`
        `</nav>`
    `</div>`

and a file called footer.ejs in that same directory:


`<footer class="footer">`
`<p>© 90210 Lawyer Stuff.</p>`
`</footer>`

[Home Page](https://osamamousa204.github.io/reading-notes-301/)






























[Home Page](https://osamamousa204.github.io/reading-notes-301/)