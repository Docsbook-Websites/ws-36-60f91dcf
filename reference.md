```yaml
title: Slugify Command Reference for URL Optimization
description: Discover Slugify's commands to create SEO-friendly URLs for your web projects efficiently.
---

# Slugify Command Reference

Use the following commands and parameters to optimize your URLs with Slugify. This reference is organized by category for easy navigation.

## URL Generation Commands

| Parameter/Command       | Type          | Description                                        | Example                        |
|-------------------------|---------------|----------------------------------------------------|--------------------------------|
| `slugify`               | Command       | Converts a string into a URL-friendly slug.       | `slugify("Hello World!")`     |
| `--separator`           | Option        | Specifies a custom separator for slugs.            | `slugify("Hello World!", --separator="-")` |
| `--lowercase`           | Flag          | Converts the slug to lowercase.                     | `slugify("Hello World!", --lowercase)` |
| `--remove-special`      | Flag          | Removes special characters from the slug.          | `slugify("Hello@World!", --remove-special)` |
| `--max-length`          | Integer       | Limits the slug to a specified number of characters. | `slugify("Hello World!", --max-length=10)` |

## Integration Parameters

| Parameter/Command       | Type          | Description                                        | Example                        |
|-------------------------|---------------|----------------------------------------------------|--------------------------------|
| `--cms`                 | String        | Specifies the content management system for integration. | `slugify --cms="WordPress"`   |
| `--auto-generate`       | Flag          | Enables automatic slug generation for new posts.  | `slugify --auto-generate`     |
| `--update-existing`     | Flag          | Updates slugs for existing content in the CMS.    | `slugify --update-existing`    |

## Output Options

| Parameter/Command       | Type          | Description                                        | Example                        |
|-------------------------|---------------|----------------------------------------------------|--------------------------------|
| `--output-format`       | String        | Defines the output format for slugs (JSON, XML).  | `slugify --output-format="JSON"` |
| `--dry-run`             | Flag          | Simulates the command without making changes.      | `slugify --dry-run`           |

## Error Handling

| Parameter/Command       | Type          | Description                                        | Example                        |
|-------------------------|---------------|----------------------------------------------------|--------------------------------|
| `--verbose`             | Flag          | Provides detailed error messages during execution. | `slugify --verbose`           |
| `--log-file`            | String        | Specifies a file to log errors and warnings.      | `slugify --log-file="error.log"` |

## Usage Tips

- Combine options for customized slug generation.
- Use the `--dry-run` option to test commands before applying them.
- Integrate Slugify with your CMS to automate URL optimization.

For more information, visit the [Slugify documentation](https://slugify.com/docs).
```