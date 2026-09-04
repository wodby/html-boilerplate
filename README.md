# HTML boilerplate

A dependency-free static HTML starter for [Wodby](https://wodby.com).

## Local development

Serve the `public` directory with any static web server. For example:

```sh
python3 -m http.server --directory public 8000
```

Open <http://localhost:8000>.

## Deployment

The included Wodby CI pipeline publishes the contents of `public` without a build step. This boilerplate is used by the [Nginx service](https://github.com/wodby/service-nginx) and [HTML stack](https://github.com/wodby/stack-html).
