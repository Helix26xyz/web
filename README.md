# My Hugo Site

This is a sample Hugo site created to demonstrate the structure and functionality of a Hugo project.

## Project Structure

```
my-hugo-site
├── archetypes
│   └── default.md        # Template for new content types
├── content
│   └── _index.md        # Main content file for the homepage
├── layouts
│   ├── _default
│   │   ├── baseof.html   # Base template for all pages
│   │   ├── list.html     # Template for listing multiple items
│   │   └── single.html   # Template for displaying a single item
├── static
│   └── css
│       └── styles.css    # CSS styles for the site
├── config.toml           # Configuration file for the Hugo site
└── README.md             # Documentation for the project
```

## Getting Started

To set up and run this Hugo site, follow these steps:

1. **Install Hugo**: Make sure you have Hugo installed on your machine. You can download it from [Hugo's official website](https://gohugo.io/getting-started/installation/).

2. **Clone the Repository**: Clone this repository to your local machine.

   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:

   ```
   cd my-hugo-site
   ```

4. **Run the Hugo Server**: Start the Hugo server to view the site locally.

   ```
   hugo server
   ```

5. **Open Your Browser**: Go to `http://localhost:1313` to see your Hugo site in action.

## Customization

You can customize the site by modifying the following files:

- **Content**: Add new content in the `content` directory.
- **Layouts**: Change the layout by editing the files in the `layouts` directory.
- **Styles**: Update the styles in `static/css/styles.css`.
- **Configuration**: Adjust site settings in `config.toml`.

## License

This project is licensed under the MIT License.