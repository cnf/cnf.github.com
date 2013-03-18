---
layout: default
---
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <title>cnf.github.com by cnf</title>

    <link rel="stylesheet" href="stylesheets/styles.css">
    <link rel="stylesheet" href="stylesheets/pygment_trac.css">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    <!--[if lt IE 9]>
    <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
  </head>
  <body>
    <div class="wrapper">
<ul class="posts">
    {% for post in site.posts %}
    <li>
        <h3>
            <a href="{{ post.url }}">
                {{ post.title }}
            </a>
            <span class="post-date">
                {{ post.date | date_to_string }}
            </span>
        </h3>
    </li>
    {% endfor %}
</ul>
      <header>
        <h1>cnf.github.com</h1>
        <p>GitHub repos by cnf</p>


        <p class="view"><a href="https://github.com/cnf">View My GitHub Profile</a></p>

      </header>
      <section>
        <p>A list of my repos will appear here.</p>

<h1>Projects</h1>

<p>here</p>
      </section>
      <footer>
        <p><small>Hosted on GitHub Pages &mdash; Theme by <a href="https://github.com/orderedlist">orderedlist</a></small></p>
      </footer>
    </div>
    <script src="javascripts/scale.fix.js"></script>
              <script type="text/javascript">
            var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
            document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));
          </script>
          <script type="text/javascript">
            try {
              var pageTracker = _gat._getTracker("UA-426420-7");
            pageTracker._trackPageview();
            } catch(err) {}
          </script>

  </body>
</html>
