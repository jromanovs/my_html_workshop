# my_html_workshop

HTML workshop workbook: one page, `index.html`, built step by step.

Open the page in the browser:

<https://htmlpreview.github.io/?https://github.com/jromanovs/my_html_workshop/blob/main/index.html>

## Steps

1. Simple form: text fields `fname` and `lname` with default values and
   a submit button. The form is sent to `https://httpbin.org/get`. Sent
   to a script that does not exist, such as `/action_page.php`, it
   shows a 404 page.
2. City field `cname` with the default value `Riga`.
3. GET and POST samples:
   - a link with three parameters in the URL;
   - a search link with the parameter `q`;
   - a form with `method="get"`;
   - a form with `method="post"`.
4. GitHub API: five GET requests for one user — all info, followers,
   events, repos, gists. One form with five buttons: the first uses the
   `action` of the form, the others set their own address with
   `formaction`. The username is part of the address, and a form can
   only add fields after `?`, so the name is written in the addresses.
   Without signing in the API answers 60 requests an hour.

The samples send data to <https://httpbin.org>, which returns what it
received: GET parameters appear in the URL, POST data in the request
body.
