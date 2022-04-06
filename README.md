# webstack

A project to prototype web stacks:
runtimes + frameworks + databases + hosting platforms.

For each stack,
`SELECT 1` to a Postgres database
using a database driver (no ORM)
and return a JSON payload of `{ "status": "ok" }`.

Runtimes / frameworks:

* Crystal / [Kemal](https://kemalcr.com/)
* Deno / stdlib, [Oak](https://oakserver.github.io/oak/)
* Go / stdlib, [Gin](https://github.com/gin-gonic/gin)
* Node / [Express](https://expressjs.com/)
* Ruby / [Sinatra](http://sinatrarb.com/), X

Hosting platforms:

* [Deno Deploy](https://deno.com/deploy)
* [Heroku](https://heroku.com)
* [Netlify](https://netlify.com)
* [Railway](https://railway.app)
* [Render](https://render.com)
* [Vercel](https://vercel.com)

The dashboard at <https://webstack.checklyhq.com/>
shows real-time latencies from
Northern California, Montreal, Ireland, Stockholm, and Sydney.
