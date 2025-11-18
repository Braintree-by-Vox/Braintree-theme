---
layout: default
title: Customization
---

# Customization Guide

Learn how to customize the Braintree Theme to match your project's needs.

## Configuration Options

### Basic Configuration

The theme can be customized through the `_config.yml` file:

```yaml
title: Your Site Title
description: Your site description
baseurl: "/your-base-url"
url: "https://your-domain.com"
```

### Theme Customization

#### Colors and Styling

You can customize the theme's appearance by:
- Modifying CSS variables
- Creating custom stylesheets
- Overriding default styles

#### Layout Changes

Customize the layout structure:
- Modify header and footer
- Adjust navigation menu
- Change page layouts

### Advanced Customization

#### Custom Pages

Create custom pages by adding new markdown files:

```markdown
---
layout: default
title: Your Custom Page
---

# Your Custom Content
```

#### Navigation Menu

Update the navigation in `_config.yml`:

```yaml
navigation:
  - title: Home
    url: /
  - title: Your Custom Page
    url: /custom-page
```

## Best Practices

1. **Keep it Simple**: Start with small changes
2. **Test Thoroughly**: Verify changes in different browsers
3. **Document Changes**: Keep track of customizations
4. **Version Control**: Use Git to manage changes

## Examples

### Example 1: Custom Color Scheme

Add your custom colors to maintain consistency across your site.

### Example 2: Custom Footer

Personalize the footer with your own information and links.

## Tips

- Back up your files before making major changes
- Test on different devices and screen sizes
- Keep accessibility in mind when customizing

[← Back to Installation](installation.md) | [Next: Contributing →](contributing.md)
