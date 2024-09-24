### [tlrc](https://github.com/tldr-pages/tlrc)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/tlrc.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/tlrc/archive/main.zip) option and unzip them.

#### Activating theme

1. Select one of the 4 variants of tlrc configuration file:
  - `config.full.toml`: **Full** default tlrc configuration file with Dracula theme and **default** background (includes complete configuration)
  - `config.min.toml`: **Minimal** default tlrc configuration file with Dracula theme and **default** background (includes only theme configuration)
  - `config.with_bg.full.toml`: **Full** default tlrc configuration file with Dracula theme and **Dracula** background (includes complete configuration)
  - `config.with_bg.min.toml`: **Minimal** default tlrc configuration file with Dracula theme and **Dracula** background (includes only theme configuration)
2. Copy the configuration file to `~/.config/tlrc/config.toml`.
3. Boom! It's working ✨

If you want to enable the prefix bullet for examples using a vampire emoji, modify the following lines:

```toml
[output]
show_hyphens = true
example_prefix = "🧛🏻‍♂️ "
```
