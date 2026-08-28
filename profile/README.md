<div align="center">

<img src="https://raw.githubusercontent.com/inklayer-dev/inklayer-core/main/docs/public/logo.svg" alt="InkLayer" width="88" />

# InkLayer

### One PDF engine for every web framework.

Build custom PDF experiences with a framework-independent core engine, or use
ready-to-use viewer and annotator SDKs for React and Vue.

[Website](https://inklayer.dev/) ·
[Documentation](https://inklayer.dev/docs/) ·
[Core Documentation](https://core.inklayer.dev/) ·
[Core Demo](https://core.inklayer.dev/demo/)

</div>

---

## What is InkLayer?

InkLayer is an open-source PDF foundation for JavaScript and TypeScript
applications, centered on a framework-independent and extensible core engine.

InkLayer Core is designed to provide the shared document model, rendering,
interaction, extension, and output capabilities. Products can use Core directly
to create their own interface and workflow. React and Vue SDKs provide
ready-to-use viewer and annotator experiences for application developers.

The ecosystem supports two ways of working:

- **A framework-independent core engine** for teams that want to design their
  own interface, application state, extensions, persistence, output, and
  product workflow.
- **Ready-to-use framework SDKs** for React and Vue, with complete viewer and
  annotator components, toolbars, sidebars, comments, permissions, and review
  workflows.

InkLayer Core is the architectural direction for the ecosystem. The current
React and Vue packages are still independent implementations; they are planned
to converge on Core as their shared engine.

## Projects

### InkLayer Core

A headless, framework-independent, and extensible PDF engine for JavaScript and
TypeScript.

Core provides document behavior and public extension APIs without imposing a
finished toolbar, sidebar, or application shell. Viewing and annotation are
important built-in capabilities, but they are not the boundary of what can be
built on Core.

- PDF loading, rendering, search, zoom, navigation, thumbnails, and outlines
- Virtualized single, continuous, and facing-page layouts
- Text selection and 16 built-in annotation types
- Serializable annotations, authors, comments, references, and permissions
- Watermarks and PDF, print, secure raster, and Excel output
- Capability plugins for connecting application services
- Custom annotation types with their own data, behavior, rendering, and output
- Integration with React, Vue, Vanilla JavaScript, and other web frameworks

```bash
npm install @inklayer-dev/core
```

[Repository](https://github.com/inklayer-dev/inklayer-core) ·
[Getting Started](https://core.inklayer.dev/guide/getting-started) ·
[Documentation](https://core.inklayer.dev/) ·
[Live Demo](https://core.inklayer.dev/demo/) ·
[npm](https://www.npmjs.com/package/@inklayer-dev/core)

### InkLayer React

A ready-to-use PDF viewer and annotation SDK for React 18 and React 19
applications.

- Ready-to-use `PdfViewer` and `PdfAnnotator` components
- Highlights, freehand drawing, shapes, stamps, and signatures
- Comments, replies, annotation references, and cross-page navigation
- Owner-based permissions, administrator overrides, and read-only mode
- Persistable annotation data and PDF/Excel export
- Customizable toolbar and sidebar UI

```bash
npm install inklayer-react
```

[Repository](https://github.com/Laomai-codefee/inklayer-react) ·
[Documentation](https://inklayer.dev/docs/react/) ·
[Live Demo](https://laomai-codefee.github.io/inklayer-react/) ·
[npm](https://www.npmjs.com/package/inklayer-react)

### InkLayer Vue

A ready-to-use PDF viewer and annotation SDK for Vue 3 applications.

- Ready-to-use `PdfViewer` and `PdfAnnotator` components
- Thumbnails, document outline, zoom, search, and theming
- Highlights, freehand drawing, shapes, stamps, and signatures
- Comments, replies, annotation references, and cross-page navigation
- Owner-based permissions, administrator overrides, and read-only mode
- Persistable annotation data and PDF/Excel export
- Customizable toolbar and sidebar UI

```bash
npm install inklayer-vue
```

[Repository](https://github.com/Laomai-codefee/inklayer-vue) ·
[Documentation](https://inklayer.dev/docs/vue/) ·
[Live Demo](https://laomai-codefee.github.io/inklayer-vue/) ·
[npm](https://www.npmjs.com/package/inklayer-vue)

## Which package should I choose?

| If you need... | Start with... |
| --- | --- |
| A foundation for a new PDF product or capability | `@inklayer-dev/core` |
| Custom document behavior, extensions, or output workflows | `@inklayer-dev/core` |
| Framework-independent PDF APIs | `@inklayer-dev/core` |
| A complete PDF viewer or annotator for a React application | `inklayer-react` |
| A complete PDF viewer or annotator for a Vue 3 application | `inklayer-vue` |
| The fastest way to evaluate the complete annotation experience | A React or Vue starter |

## What you can build

- Document review and approval systems
- Collaborative PDF annotation tools
- Contract, report, and drawing review workflows
- Education and research applications
- Internal document platforms
- Custom PDF viewers embedded in existing products
- PDF processing and output pipelines
- Domain-specific document tools built with custom capabilities and annotation types

## Application responsibilities

InkLayer provides browser-side PDF and annotation capabilities. Your
application remains responsible for trusted identity, server-side
authorization, data storage, synchronization, and business workflow rules.

Client-side annotation permissions improve the user experience, but they must
not be treated as a security boundary. Backends should validate every
authoritative read and write operation independently.

## Community and support

InkLayer's core SDKs are released under the MIT License and can be used in
personal and commercial projects.

- Read the guides and API documentation at [inklayer.dev](https://inklayer.dev/)
- Report bugs through the relevant repository's GitHub Issues
- Share ideas and usage questions through GitHub Discussions

Commercial support is available for framework integration, annotation
persistence, identity and permission workflows, custom features, and ongoing
private maintenance.

Contact: [codefee@foxmail.com](mailto:codefee@foxmail.com?subject=InkLayer%20Project%20Inquiry)

## License

Each InkLayer project is distributed under the license included in its
repository. InkLayer Core, InkLayer React, and InkLayer Vue are currently
released under the MIT License.
