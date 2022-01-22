# cf-pages-redirect-bug

Testing the redirection bug/regression in CloudFlare Pages Code

The redirects file has one rule
  `/r/* /#!/r/:splat`

[https://cf-pages-redirect-bug.pages.dev/r/test](https://cf-pages-redirect-bug.pages.dev/r/test) should redirect to [https://cf-pages-redirect-bug.pages.dev/#!/r/test](https://cf-pages-redirect-bug.pages.dev/#!/r/test) 
