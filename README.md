<div align="center">
  <img height="80" alt="icon" src="https://github.com/vague-theme/vague/blob/main/assets/icon.png?raw=true" />
  <h1>Vague for Yazi</h1>
  <img alt="preview" src="preview.png" />
</div>

## Usage

Add the flavor.toml and tmtheme.xml files in ~/.config/yazi/flavors/vague.yazi/

The directory structure should be this:

```
~/.config/yazi/
├── flavors/
│   ├── vague.yazi/
└── theme.toml
```

To set it as your dark flavor, change the content of your `theme.toml` to:

```toml
[flavor]
dark = "vague"
```

Make sure your `theme.toml` doesn't contain anything other than `[flavor]`, unless you want to override certain styles of this flavor.

See the [Yazi flavor documentation](https://yazi-rs.github.io/docs/flavors/overview) for more details.

## Thanks to contributors

- [pgdkl](https://github.com/pgdkl)
