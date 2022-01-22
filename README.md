# cf-pages-redirect-bug

Testing the redirection bug/regression in CloudFlare Pages Code

The redirects file has two rules
  `/r/* /#!/r/:splat`
  `/t/* /test#/t/:splat`

[https://cf-pages-redirect-bug.pages.dev/r/redirected](https://cf-pages-redirect-bug.pages.dev/r/redirected) should be redirect to [https://cf-pages-redirect-bug.pages.dev/#/r/redirected](https://cf-pages-redirect-bug.pages.dev/#/r/redirected) 
