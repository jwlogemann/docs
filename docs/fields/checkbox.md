---
title: Checkbox
---
Checkbox
=========

Simple checkbox input.

### Basic Configuration:

```
        showteaser:
            type: checkbox
```

### Example usage in templates:

```
{% if record.showteaser %}
    <p>Teaser here ...</p>
{% endif %}
```

### Options:

The field has one option to change the appearance of the field:

* `variant` set to `inline` to show the label next to the field instead of
  above it.
