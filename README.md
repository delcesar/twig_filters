# Twig_Filters

twig_filters is a module for Drupal 8 which provides custom Twig filters.

## Installation

1. In modules, create a directory named custom and copy twig_filters inside. (DrupalSite/modules/custom/twig_filters)
2. Install the module in Drupal

### TruncateHtml Filter

Truncate a HTML string without breaking tags. Useful for previews or on Teaser  

## Usage

```twig
{{ body|truncatehtml(200)|raw }}
```
