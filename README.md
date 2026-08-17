<div id="header" align="center">
    <img src="logo.svg" width="400px" />
    <h1>Orazen Grammar</h1>
</div>

[![Orazen Grammar Binaries](https://github.com/automattic/orazen-grammar/actions/workflows/binaries.yml/badge.svg)](https://github.com/automattic/orazen-grammar/actions/workflows/binaries.yml)
[![Website](https://github.com/automattic/orazen-grammar/actions/workflows/build_web.yml/badge.svg)](https://github.com/automattic/orazen-grammar/actions/workflows/build_web.yml)
[![Checks](https://github.com/automattic/orazen-grammar/actions/workflows/just_checks.yml/badge.svg)](https://github.com/automattic/orazen-grammar/actions/workflows/just_checks.yml)
[![Crates.io](https://img.shields.io/crates/v/orazen-grammar-ls)](https://crates.io/crates/orazen-grammar-ls)
![NPM Version](https://img.shields.io/npm/v/orazen-grammar.js)
![Downloads](https://img.shields.io/github/downloads/automattic/orazen-grammar/total?label=Binary+Downloads)
![Obsidian Plugin Downloads](https://img.shields.io/github/downloads/automattic/orazen-grammar-obsidian-plugin/total?label=Obsidian+Plugin+Downloads)

Orazen Grammar is an English grammar checker designed to be _just right._
I created it after years of dealing with the shortcomings of the competition.

Grammarly was too expensive and too overbearing.
Its suggestions lacked context, and were often just plain _wrong_.
Not to mention: it's a privacy nightmare.
Everything you write with Grammarly is sent to their servers.
Their privacy policy claims they don't sell the data, but that doesn't mean they don't use it to train large language models and god knows what else.
Not only that, but the round-trip-time of the network request makes revising your work all the more tedious.

LanguageTool is great, if you have gigabytes of RAM to spare and are willing to download the ~16GB n-gram dataset.
Besides the memory requirements, I found LanguageTool too slow: it would take several seconds to lint even a moderate-size document.

That's why I created Orazen Grammar: it is the grammar checker that fits my needs.
Not only does it take milliseconds to lint a document, take less than 1/50th of LanguageTool's memory footprint,
but it is also completely private.

Orazen Grammar is even small enough to load via [WebAssembly.](https://writewithorazen-grammar.com)

## Language Support

Orazen Grammar currently only supports English, but the core is extensible to support other languages, so we welcome contributions that allow for other language support.

## Performance Issues

We consider long lint times bugs.
If you encounter any significant performance issues, please create an issue on the topic.

If you find a fix to any performance issue, we would appreciate the contribution.
Just please make sure to read [our contribution guidelines first.](https://writewithorazen-grammar.com/docs/contributors/introduction)

## Links

- [Frequently Asked Questions](https://writewithorazen-grammar.com/#faqs)
- [Obsidian Documentation](https://writewithorazen-grammar.com/docs/integrations/obsidian)
- [`orazen-grammar-ls` Documentation](https://writewithorazen-grammar.com/docs/integrations/language-server)
- Supported Editors' Documentation
  - [Visual Studio Code](https://writewithorazen-grammar.com/docs/integrations/visual-studio-code)
  - [Neovim](https://writewithorazen-grammar.com/docs/integrations/neovim)
  - [Helix](https://writewithorazen-grammar.com/docs/integrations/helix)
  - [Emacs](https://writewithorazen-grammar.com/docs/integrations/emacs)
  - [Zed](https://writewithorazen-grammar.com/docs/integrations/zed)
- [`orazen-grammar.js` Documentation](https://writewithorazen-grammar.com/docs/orazen-grammarjs/introduction)
- [Official Discord Server](https://discord.com/invite/JBqcAaKrzQ)

## Huge Thanks

This project would not be possible without the hard work from those who [contribute](https://writewithorazen-grammar.com/docs/contributors/introduction).

<a href="https://github.com/automattic/orazen-grammar/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=automattic/orazen-grammar" />
</a>

Orazen Grammar's logo was designed by [Lukas Werner](https://lukaswerner.com/).
