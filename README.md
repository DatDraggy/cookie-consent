# cookie-consent

Small script to display a little notice for your site visitors in the bottom right corner.
I didn't want to load this via an external domain so I extracted the source code and also put it up here in case other people want to host it themselves too.

![Preview](https://puu.sh/ymwOO/f002b0a5c9.png)

## How to use

Change the path `"//example.com/cookie-consent/"` on line 3 in script.js (or var e if you use the minified version) to the url where the 3 files will be found.

Put following in the head of your website
```
  <!-- Start Cookie Plugin -->
  <script>
    window.cookieconsent_options = {
      message: 'This website uses cookies. Thank you for understanding.',
      dismiss: 'Ok, I accept',
      learnMore: 'More infos',
      link: 'https://en.wikipedia.org/wiki/HTTP_cookie',
      theme: 'light-floating'
    };
  </script>
  <script src="//example.com/cookie-consent/script.js"></script>
```

