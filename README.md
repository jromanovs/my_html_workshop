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
4. GitHub user info: a form with a username field. A form can only add
   its fields after `?`, and the username belongs in the path, so a
   short script builds `https://api.github.com/users/<username>` and
   opens it. Without signing in the API answers 60 requests an hour.

The samples send data to <https://httpbin.org>, which returns what it
received: GET parameters appear in the URL, POST data in the request
body.
