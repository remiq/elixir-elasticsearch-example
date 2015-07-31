Crawler
=======

Elixir/ElasticSearch experiment.

## Usage

Start ElasticSearch

    $ docker-compose up -d

Run Elixir's REPL in run container

    $ docker-compose run --rm crawler bash

Get dependencies and compile

    crawler$ mix do deps.get, compile

Execute feeding script

    crawler$ mix run 1_feed.exs

Interact 

    crawler$ iex -S mix
    crawler iex> ???


