# Erlang on Heroku

No real magic, fool it in to being an accepted app, and run it using R13B04 on the cedar stack.

Will need to ship built output.

## Known issues

Anything using distributed erlang won't work, the dist erlang system binds an additional TCP port
which heroku doesn't like.
