# LeGambiArt Lola Marketplace

> Your curated collection of daily driver tools for creative
> AI-assisted development

Welcome to the LeGambiArt Lola Marketplace - where practical meets
playful, and your workflow gets a serious upgrade. We're not here to
flood you with a thousand half-baked tools. Instead, we handpick the
gems we actually use every day, the ones that make our creative work
flow like butter.

## What is This?

Think of this as your corner shop for quality dev tools. The Lola
package manager lets you install modules (think: specialized AI
assistants and workflows), and this marketplace is where we share the
good stuff with you. No fluff, no filler - just tools we'd recommend
to a friend over coffee.

Built on the same foundation as RedHat's official lola-market, but
with a LeGambiArt twist: we focus on tools for creative professionals
who work with AI, build interesting things, and don't want to waste
time wrestling with their toolchain.

## Prerequisites

You'll need Lola installed on your machine. If you don't have it yet,
head over to the [official Lola repository][lola-repo] and follow
their installation guide. It's straightforward - promise.

## Quick Start

Ready to dive in? Let's get you set up in three simple steps:

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

Or if you want the full details, check out our
[Module Catalog](docs/catalog.md).

### 3. Install Something Cool

Found a module you like? Grab it:

```bash
lola mod install lola-manager
```

That's it! The module is now ready to use. No configuration headaches,
no dependency hell - just install and go.

## Current Modules

We're starting focused with one rock-solid tool:

- **[lola-manager][lola-manager]** - Build new Lola modules with
  workflow guidance and scaffolding. Your launchpad for creating
  custom AI assistants.

More tools are coming as we refine and release them. Quality over
quantity, always.

## Documentation

- **[Module Catalog](docs/catalog.md)** - Detailed information about
  each module, including features, use cases, and installation
  instructions
- **[Contributing Guide](CONTRIBUTING.md)** - Want to share your own
  tool? We'd love to see it!

## Using the Modules

Once you've installed a module, using it is delightfully simple. Lola
integrates modules as skills you can invoke from your AI assistant.
For example, after installing `lola-manager`:

```bash
# Start a conversation with your AI assistant
lola chat

# Then use the module
/lola-manager create my-awesome-module
```

Each module comes with its own documentation and examples. Check the
[catalog](docs/catalog.md) for module-specific usage details.

## Contributing

Got a tool that makes your workflow sing? Something you use daily and
think others would love? We want to hear about it!

The process is dead simple: fork this repo, add your module to
`lola.yml` and `docs/catalog.md`, and send us a pull request. Check
out our [Contributing Guide](CONTRIBUTING.md) for the quick rundown.

We're building a community of creative professionals who care about
craft and sharing knowledge. Your contribution helps make everyone's
work better.

## Author & Community

**LeGambiArt** is all about creative experimentation at the
intersection of AI, art, and practical tooling. We believe in building
things that actually work, sharing what we learn, and having fun along
the way.

This marketplace is our way of giving back to the community. Every
tool here has been battle-tested in real projects, refined through
actual use, and shared with love.

Want to connect?
- **GitHub**: [LeGambiArt][legambiart-gh]
- **Repository**: [lola-market][lola-market-repo]

## Resources

- **[Lola Package Manager][lola-repo]** - The foundation that makes
  this all possible
- **[Official Lola Market][official-market]** - RedHat's curated
  collection of enterprise-grade modules
- **[Module Catalog](docs/catalog.md)** - Browse our complete
  collection with detailed information

---

**Built by LeGambiArt**

*Because your tools should be as creative as you are.*

[lola-repo]: https://github.com/RedHatProductSecurity/lola
[lola-manager]: https://github.com/mrbrandao/lola-manager
[legambiart-gh]: https://github.com/LeGambiArt
[lola-market-repo]: https://github.com/LeGambiArt/lola-market
[official-market]: https://github.com/RedHatProductSecurity/lola-market
