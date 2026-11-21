<!--
README template for lncodes repositories. Copy, then replace every <ANGLE-BRACKET> value and delete what doesn't apply.
Rules: plain Markdown headings (GitHub builds the "Outline" table of contents from them), alt text on every image,
absolute links to org files, and only badges for workflows that actually run.

Two layouts:
  A. Repository root (collection or single project): keep the logo, badge and "What's inside" table.
  B. A folder inside a collection: delete the logo and badge; keep the "Part of" line and the short footer.
-->

<p align="center"><a href="https://www.lncodes.com"><img src="https://raw.githubusercontent.com/lncodes/docs/main/assets/animations/lncodes-logo-animation.gif" alt="Last Night Codes logo" height="120"></a></p>

# <Project title>

[![CI](https://github.com/lncodes/<repo>/actions/workflows/ci.yml/badge.svg)](https://github.com/lncodes/<repo>/actions/workflows/ci.yml)

<!-- Layout B only: -->
> Part of [**<collection>**](../README.md) · targets **.NET 10**

<One or two sentences: what this shows or does, and why someone would use it.>

<!-- Demos: add a screenshot or GIF here. Libraries: show a short usage example under "Usage". -->

## Quick start

```bash
git clone https://github.com/lncodes/<repo>.git
cd <repo>/<folder>
dotnet run --project src     # console demo
dotnet test test             # unit tests
```

## What's inside

- [`src/<KeyFile>.cs`](src/<KeyFile>.cs): <what it contains>

## Usage

```csharp
// The smallest working example. Compile it before publishing.
```

## Learn more

Read the full explanation on the blog: [<Post title> – Last Night Codes](https://www.lncodes.com/<slug>)

---

Questions? Use [Discussions](https://github.com/lncodes/<repo>/discussions) · [Contributing](https://github.com/lncodes/.github/blob/main/CONTRIBUTING.md) · [MIT License](LICENSE)
