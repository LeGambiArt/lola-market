# LeGambiArt Lola Marketplace Catalog

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated tools for creative professionals and AI-assisted development

This catalog showcases modules available in the LeGambiArt Lola
Marketplace. Each module has been tested in real-world projects and
selected for its practical value.

## Contents

- [Module Development](#module-development)
- [Future Modules](#future-modules)
- [Contributing](#contributing)

## Module Development

Tools for creating and managing Lola modules.

### lola-manager

**Repository:** [mrbrandao/lola-manager][lola-manager]
**Author:** LeGambiArt
**Version:** 0.1.0
**Tags:** module-builder, workflow, scaffolding

Build new Lola modules with interactive workflow guidance and
intelligent scaffolding. lola-manager streamlines the module creation
process by asking the right questions and generating well-structured
boilerplate code.

**Features:**

- Interactive module creation workflow
- Scaffolds complete module structure (skills, commands, agents)
- Generates frontmatter with proper YAML formatting
- Validates module structure against Lola specifications
- Supports both single-skill and multi-skill module patterns
- Creates example content to get you started quickly

**Use Cases:**

- Building custom AI assistants for your workflow
- Creating specialized skills for domain-specific tasks
- Packaging reusable workflows for team collaboration
- Experimenting with new AI-assisted development patterns

**Installation:**

```bash
lola mod install lola-manager
```

**Usage:**

```bash
# Start interactive module creation
/lola-manager create my-new-module

# Get help with module structure
/lola-manager help
```

## Future Modules

We're constantly building and refining new tools. Stay tuned for
modules focused on:

- Code review and quality analysis
- Documentation generation
- Testing automation
- Deployment workflows

Want to see a specific type of module? Open an issue and let us know
what would make your workflow better.

## Contributing

Have a module that others would find useful? We'd love to include it
in the marketplace.

**To add your module:**

1. Fork this repository
2. Add your module to `lola.yml`
3. Add documentation to this catalog
4. Send us a pull request

Keep your module description clear and honest. Focus on what it does
and why it's useful. Include installation instructions and a quick
usage example.

See [CONTRIBUTING.md][contributing] for more details.

---

**Questions?** Open an issue in the [repository][repo].

[lola-manager]: https://github.com/mrbrandao/lola-manager
[contributing]: ../CONTRIBUTING.md
[repo]: https://github.com/LeGambiArt/lola-market
