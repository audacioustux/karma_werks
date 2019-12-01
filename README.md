# KarmaWerks

#### NOTE: This branch contains the quickly stitched version. This will stop existing once the clean branch is feature par with this.

KarmaWerks is a work-in-progress Project Management tool created with Elixir, Phoenix, LiveView, Stencil and Dgraph.

Setting up KarmaWerks:

* Install `dgraph`. [Detailed procedure is given here](https://docs.dgraph.io/get-started#step-1-install-dgraph).
* Install dependencies with `mix deps.get`
* Install Node.js dependencies with `cd assets && npm install`
* Start Phoenix endpoint along with interactive REPL with `iex -S mix phx.server`
* In the `REPL`, type `KarmaWerks.DB.Migrations.run` to setup the `dgraph` types.

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).
