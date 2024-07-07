# 📖 **Welcome to Usher Labs Documentation Repository**

This is the home of the Usher Labs documentation repository!

This website is built using **[Docusaurus 3](https://docusaurus.io/)**, a static website generator.

## Get started

### Installation

```sh
$ pnpm i

```

### Local Development

```sh
$ pnpm start
```

This command starts a local development server and opens a browser window. Most changes are reflected live without having to restart the server.

## **Customization**

### Creating and organizing content

- Store content in the `docs` directory, supporting `.md` and `.mdx` files. [Learn more →](https://docusaurus.io/docs/create-doc)
- Configure each folder metadata accordingly, using `_category_.json` or `_category_.yml`. [Learn more →](https://docusaurus.io/docs/sidebar/autogenerated#category-item-metadata)
- Utilize frontmatter options for configuration and customization. **[See the API here →](https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-docs#markdown-front-matter)**
- Set a specific page as the main page [link] (if you do not intend to create a dedicated homepage. Otherwise, to create a homepage learn more here)
- Configure header navigation items in the `docusaurus.config.js` file. [Learn more →](https://docusaurus.io/docs/docs-multi-instance#docs-navbar-items)
- Create multiple sidebars by updating `sidebars.js` according to your docs folder structure. [Learn more →](https://docusaurus.io/docs/sidebar/multiple-sidebars)

**Example of a tree structure in the `docs` folder:**

```
docs
├── getting-started
│   ├── introduction.md
│   └── installation.md
└── guides
    ├── configuration.md
    └── customization.md

```

### Basic customization

- Change fonts following instructions at `tailwind.config.ts`
- Modify typography settings at `tailwind.config.ts`
- Update colors at `tailwind.config.ts`

### Advanced customization

- Apply component-specific styles at specific `module.css` files
- Use mdx and React. [Learn more →](https://docusaurus.io/docs/markdown-features/react)
- Swizzle built-in components or update our modifications at `src/theme/*` files. [Learn more about Swizzling →](https://docusaurus.io/docs/swizzling)
- Develop custom React pages at `src/pages`. [Learn more →](https://docusaurus.io/docs/creating-pages#add-a-react-page)

## Best practices

- When swizzling components, add comments to indicate where changes occurred
- Follow Docusaurus-specific best practices for versioning and customization. [Learn more →](https://docusaurus.io/docs/versioning#recommended-practices)

## Deployment

### Build

```sh
$ pnpm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

To deploy your documentation with Vercel, follow these steps:

1. Sign up for a **[Vercel account](https://vercel.com/signup)** if you don't have one.
2. Install the **[Vercel CLI](https://vercel.com/download)** by running `npm i -g vercel`.
3. Run `vercel login` in your terminal and log in using your Vercel account.
4. In your project directory, run `vercel` to initiate the deployment process. Follow the prompts to link your project to Vercel.
5. Once your project is linked, Vercel will deploy your documentation. After the deployment, you'll receive a URL to access your live documentation.

For subsequent deployments, run `vercel --prod` in your project directory to deploy your documentation to the production environment.

For more information on Vercel deployments, consult the **[official Vercel documentation](https://vercel.com/docs)**.

## Contributing to this documentation

1. **Report issues**: If you find any errors, inconsistencies, or areas that need improvement, please open an issue on the **[GitHub repository](https://github.com/usherlabs/logstore/issues)**. Provide a clear description of the issue and suggest a possible solution or improvement.
2. **Suggest enhancements**: If you have ideas for new sections, topics, or content that would be helpful to others, please share your suggestions by opening an issue on the **[GitHub repository](https://github.com/usherlabs/logstore/issues)**.
3. **Submit a pull request**: If you'd like to contribute directly by fixing an issue or adding new content, please fork the repository, make changes, and submit a pull request. Ensure your changes follow the documentation guidelines and best practices outlined in the README.
