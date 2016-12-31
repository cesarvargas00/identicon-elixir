# Identicon

This is an [identicon](https://en.wikipedia.org/wiki/Identicon) implementation using Elixir.
to use it:
  1. `Identicon.main "billy"`
  2. Check billy.png in the same folder
  3. 🍺😎
  
  
## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `identicon` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:identicon, "~> 0.1.0"}]
    end
    ```

  2. Ensure `identicon` is started before your application:

    ```elixir
    def application do
      [applications: [:identicon]]
    end
    ```

