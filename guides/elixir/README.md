# Elixir

## Rules

1. Avoid macros.
2. Prefer pattern matching and guards in function definitions over conditionals
in the function body.

### Aliases and Imports

1. Order the dependencies of a module as: `use`, `import`, `alias`.
2. Put an empty line between each type of dependency.
3. Sort the dependencies in each section alphabetically.

## Formatter

Elixir ships with a code formatter that is capable of automatically formatting
our codebase according to a consistent style.

```
mix format
```

Use it on all elixir code projects. For Phoenix Projects, use the plugin
[Phoenix.LiveView.HTMLFormatter][liveview-html-formatter].

Learn more about configuring [Mix.Tasks.Format][mix-format-task]
[here][mix-format].

[mix-format-task]: https://hexdocs.pm/mix/Mix.Tasks.Format.html
[mix-format]: https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html#automatic-code-formatting
[liveview-html-formatter]: https://hexdocs.pm/phoenix_live_view/Phoenix.LiveView.HTMLFormatter.html
