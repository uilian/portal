# Portal

##Tutorial application done by following [this post][1] from José Valim (@josevalim).

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add portal to your list of dependencies in `mix.exs`:

        def deps do
          [{:portal, "~> 0.0.1"}]
        end

  2. Ensure portal is started before your application:

        def application do
          [applications: [:portal]]
        end


[1]: https://howistart.org/posts/elixir/1 "Portal"