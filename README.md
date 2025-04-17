# Modern Tailwind CSS Website

A simple, responsive website template built with HTML and Tailwind CSS.

## Features

- Responsive navigation with mobile menu
- Modern card-based layout
- Smooth hover animations
- Mobile-first design
- Clean and minimal UI
- Automated release notes generation

## Getting Started

1. Simply open the `index.html` file in your web browser to view the website.
2. The template uses Tailwind CSS via CDN, so you need an internet connection for the styles to work.

## Release Process

This repository includes an automated release notes generation system using GitHub Actions. When you create a new tag with the prefix 'v' (e.g., v1.0.0), it will automatically:

1. Generate release notes based on commit messages since the last tag
2. Create a new GitHub release with these notes
3. Attach the release to the tag

To create a new release:

```bash
git tag v1.0.0  # Replace with your version number
git push origin v1.0.0
```

The action will automatically create a release with all commit messages since the last tag.

## Customization

### Colors
- The template uses Tailwind's default color palette
- Modify color classes (e.g., `bg-gray-100`, `text-blue-500`) to change the color scheme

### Layout
- The main content uses a responsive grid system
- Cards adjust from 1 column on mobile to 3 columns on desktop
- Modify the grid classes in the HTML to change the layout

### Content
- Replace the text and emojis with your own content
- Add or remove cards as needed
- Customize the navigation links in the header

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- GitHub Actions for release automation

## License

Feel free to use this template for your personal or commercial projects. 