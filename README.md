# LeGambiArt Lola Marketplace

> A curated collection of daily driver tools for creative
> AI-assisted development

## What is This?

Think of this as your corner shop for quality dev tools. The Lola
package manager lets you install modules (think: specialized AI
assistants and workflows), and this marketplace is where we share the
good stuff with you. No fluff, no filler - just tools we'd recommend
to a friend over coffee.

## Prerequisites

You'll need Lola installed on your machine. If you don't have it yet,
head over to the [official Lola repository][lola-repo] and follow
their installation guide. It's straightforward - promise.

## Quick Start

### 1. Add Our Marketplace

Tell Lola where to find our collection:

```bash
lola market add legambiart \
  https://raw.githubusercontent.com/LeGambiArt/lola-market/main/lola.yml
```

### 2. Browse What's Available

Take a peek at what we've got:

```bash
lola mod search
```

list all modules with

```bash
lola mod search all
```

Or if you want the full details, check out our
[Module Catalog](docs/catalog.md).

### 3. Install Something Cool

Found a module you like? Grab it:

```bash
lola mod install lola-manager
```

That's it! The module is now ready to use. No configuration headaches,
no dependency hell - just install and go.

## Documentation

- **[Module Catalog](docs/catalog.md)** - Detailed information about
  each module, including features, use cases, and installation
  instructions
- **[Contributing Guide](CONTRIBUTING.md)** - Want to share your own
  tool? We'd love to see it!

Each module comes with its own documentation and examples. Check the
[catalog](docs/catalog.md) for module-specific usage details.

## Contributing

Fork this repo, add your module to `lola.yml` and `docs/catalog.md`,
and send us a pull request. Check out our
[Contributing Guide](CONTRIBUTING.md) for the quick rundown.

We're building a community of creative professionals who care about
craft and sharing knowledge. Your contribution helps make everyone's
work better.

## Resources

- **[Lola Package Manager][lola-repo]** - The foundation that makes
  this all possible
- **[Official Lola Market][official-market]** - RedHat's curated
  collection of enterprise-grade modules
- **[Module Catalog](docs/catalog.md)** - Browse our complete
  collection with detailed information

---

**Built by LeGambiArt**

[lola-repo]: https://github.com/RedHatProductSecurity/lola
[lola-manager]: https://github.com/mrbrandao/lola-manager
[legambiart-gh]: https://github.com/LeGambiArt
[lola-market-repo]: https://github.com/LeGambiArt/lola-market
