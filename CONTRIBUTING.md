# Contributing to LeGambiArt Lola Marketplace

Want to share your tool with the community? Awesome! We welcome
contributions from creative professionals building practical AI
workflows.

## How to Contribute

It's simple:

1. **Fork this repository**
2. **Add your module** to `lola.yml`
3. **Document it** in `docs/catalog.md`
4. **Send us a pull request**

That's it!

## What to Add

### In lola.yml

```yaml
- name: "your-module-name"
  description: "Brief, clear description of what it does"
  version: "1.0.0"
  repository: "https://github.com/username/your-module"
  tags:
    - "relevant-category"
    - "all"
```

### In docs/catalog.md

Add a section under the appropriate category with:

- Module name and link to repository
- Clear description of what it does
- Key features (bulleted list)
- Use cases (practical examples)
- Installation command
- Quick usage example

## Guidelines

- Keep descriptions clear and honest
- Focus on practical value, not marketing speak
- Test your module before submitting
- Make sure it follows [Lola module structure][lola-docs]

## Questions?

Open an issue and we'll help you out.

[lola-docs]: https://github.com/RedHatProductSecurity/lola
