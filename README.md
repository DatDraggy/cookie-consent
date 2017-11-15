# cookie-consent

Small script to display a small notice for your site visitors in the bottom right corner.

![Preview](https://puu.sh/ymwOO/f002b0a5c9.png)

## How to use

Change the path `"//example.com/cookie-consent/"` on line 3 in script.js (or var e if you use the minified version) to the url where the 3 files will be found.

Put following in the header of your website where the popup should be shown
```
  <!-- Start Cookie Plugin -->
  <script type="text/javascript">
    window.cookieconsent_options = {
      message: 'This website uses cookies. Thank you for understanding.',
      dismiss: 'Ok, I accept',
      learnMore: 'More infos',
      link: 'https://en.wikipedia.org/wiki/HTTP_cookie',
      theme: 'light-floating'
    };
  </script>
  <script src="//example.com/cookie-hinweis/script.js"></script>
```
