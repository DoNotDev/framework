# DoNotDev Framework

**The "Don't Reinvent the Wheel" Full-Stack Framework**

AI-First • Zero-Config • Type-Safe • Production-Ready • **Open source (MIT)**

---

## This repository

Public **community hub** for the DoNotDev framework:

- **Issues & bug reports** — report bugs, request features, and discuss improvements
- **Documentation pointers** — links to published packages and the project site (this repo does not mirror the full monorepo)

Framework packages are distributed on **npm** under the **MIT License**. See **[LICENSE.md](./LICENSE.md)** for the full license text.

---

## Quick start

```bash
# Install CLI globally
npm install -g @donotdev/cli

# Create a new project
dndev init my-project

# Navigate and install dependencies
cd my-project && bun install

# Start development server
dndev dev my-app
```

Use **Bun** or **Node.js 20+**. After scaffolding, open the project in your editor and follow the generated **AGENTS.md** for agent-oriented workflows.

---

## Documentation

- **Website:** [donotdev.com](https://donotdev.com)
- **FAQ:** [donotdev.com/faq](https://donotdev.com/faq)
- **npm scope:** [@donotdev on npm](https://www.npmjs.com/org/donotdev) — each package page includes usage and API notes

---

## Reporting issues

Found a bug? Have a feature request?

1. **Search existing issues** to avoid duplicates
2. **Open a new issue** with steps to reproduce (for bugs) or a clear use case (for features)

**Before reporting:** check the [FAQ](https://donotdev.com/faq) for common questions.

---

## Contributing

We welcome community input:

- **Issues** — bugs, ideas, and documentation gaps (this repo is the right place)
- **Code** — implementation is maintained in a private monorepo; fixes ship via published `@donotdev/*` releases. If you want to contribute code beyond issues, reach out via the website or an issue so we can coordinate

**Guides and examples** — improvements to public docs or examples may be proposed via issues (or PRs if this repo gains tracked doc sources).

---

## Package overview

| Area | Packages |
|------|----------|
| Foundation | `@donotdev/core` |
| Composition & routing | `@donotdev/ui` |
| UI primitives | `@donotdev/components` |
| Optional features | `@donotdev/features/*` (e.g. auth, billing) |
| Tooling | `@donotdev/cli` |
| Templates | `@donotdev/templates` (where published) |

For an authoritative list and architecture notes, see published **README** files on npm and [donotdev.com](https://donotdev.com).

---

## License

**MIT** — see [LICENSE.md](./LICENSE.md).

---

**Maintained by [AMBROISE PARK Consulting](https://ambroise-park.com)**
