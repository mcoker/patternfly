---
id: 'Sidebar'
section: components
cssPrefix: pf-v6-c-sidebar
---

import './Sidebar.css'

## Examples
### Basic
```hbs
{{#> sidebar}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Default layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### With secondary background

```hbs
{{#> sidebar}}
  {{#> sidebar-panel sidebar-panel--modifier="pf-m-secondary"}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content sidebar-content--modifier="pf-m-secondary"}}
    {{#> content}}
      <p>Default layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Gutter
```hbs
{{#> sidebar sidebar--modifier="pf-m-gutter"}}
  {{#> sidebar-panel}}
    Sidebar panel. Adding some extra content so that the gap between the panel and content area is better illustrated in this example.
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Adds a gutter between the panel and content when in the split layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Stack
```hbs
{{#> sidebar sidebar--modifier="pf-m-stack"}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Forces a stacked layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Split
```hbs
{{#> sidebar sidebar--modifier="pf-m-split"}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Forces a split layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Panel right (HTML)
```hbs
{{#> sidebar}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Moves the panel to the right by placing the panel after the content in the HTML.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
{{/sidebar}}
```

### Panel right (modifier)
```hbs
{{#> sidebar sidebar--modifier="pf-m-panel-right"}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Moves the panel to the right via the modifier class <b>.pf-m-panel-right</b>&nbsp;on the sidebar component.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Sticky panel
```hbs
{{#> sidebar sidebar--attribute="tabindex=0"}}
  {{#> sidebar-panel sidebar-panel--modifier="pf-m-sticky"}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Forces the panel to be sticky to the top of the layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Static panel
```hbs
{{#> sidebar sidebar--attribute="tabindex=0"}}
  {{#> sidebar-panel sidebar-panel--modifier="pf-m-static"}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Forces the panel to be statically positioned (not sticky).</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Responsive panel width
```hbs
{{#> sidebar sidebar--attribute="tabindex=0"}}
  {{#> sidebar-panel sidebar-panel--modifier="pf-m-sticky pf-m-width-50 pf-m-width-33-on-lg pf-m-width-75-on-xl"}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Changes the panel with and can change responsively at different breakpoints.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Border
```hbs
{{#> sidebar sidebar--modifier="pf-m-gutter" sidebar--HasBorder=true}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Default layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Padding on panel
```hbs
{{#> sidebar}}
  {{#> sidebar-panel sidebar-panel--modifier="pf-m-padding"}}
    Sidebar panel, with padding
  {{/sidebar-panel}}
  {{#> sidebar-content}}
    {{#> content}}
      <p>Default layout.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

### Padding on content
```hbs
{{#> sidebar}}
  {{#> sidebar-panel}}
    Sidebar panel
  {{/sidebar-panel}}
  {{#> sidebar-content sidebar-content--modifier="pf-m-padding"}}
    {{#> content}}
      <p>Sidebar content, with padding</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus nulla id augue dictum commodo. Donec mollis arcu massa, sollicitudin venenatis est rutrum vitae. Integer pulvinar ligula at augue mollis, ac pulvinar arcu semper. Maecenas nisi lorem, malesuada ac lectus nec, porta pretium neque. Ut convallis libero sit amet metus mattis, vel facilisis lorem malesuada. Duis consectetur ante sit amet magna efficitur, a interdum leo vulputate.</p>
      <p>Praesent at odio nec sapien ultrices tincidunt in non mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Duis consectetur nisl quis facilisis faucibus. Sed eu bibendum risus. Suspendisse porta euismod tortor, at elementum odio suscipit sed. Cras eget ultrices urna, ac feugiat lectus. Integer a pharetra velit, in imperdiet mi. Phasellus vel hendrerit velit. Vestibulum ut augue vitae erat vulputate bibendum a ut magna.</p>
    {{/content}}
  {{/sidebar-content}}
{{/sidebar}}
```

## Documentation

### Usage
| Class | Applied to | Outcome |
| -- | -- | -- |
| `.pf-v6-c-sidebar` | `<div>` | Initiates the sidebar component. **Required** |
| `.pf-v6-c-sidebar__main` | `<div>` | Initiates the sidebar main element. **Required** |
| `.pf-v6-c-sidebar__panel` | `<div>` | Initiates the sidebar panel element. **Required** |
| `.pf-v6-c-sidebar__content` | `<div>` | Initiates the sidebar content element. **Required** |
| `.pf-m-border` | `.pf-v6-c-sidebar__main` | Modifies the sidebar component to add a border between the panel and content. |
| `.pf-m-padding` | `.pf-v6-c-sidebar__panel`, `.pf-v6-c-sidebar__content` | Modifies the sidebar component to add a padding to panel and/or content. |
| `.pf-m-gutter` | `.pf-v6-c-sidebar` | Modifies the sidebar component to add a gutter between the panel and content. |
| `.pf-m-stack` | `.pf-v6-c-sidebar` | Modifies the sidebar to stack the panel on top of the content. |
| `.pf-m-split` | `.pf-v6-c-sidebar` | Modifies the sidebar to position the panel and content side by side. |
| `.pf-m-panel-right` | `.pf-v6-c-sidebar` | Modifies the sidebar to place the panel to the right of the content. |
| `.pf-m-sticky` | `.pf-v6-c-sidebar__panel` | Modifies the panel to be sticky to the top of the layout. |
| `.pf-m-static` | `.pf-v6-c-sidebar__panel` | Modifies the panel to be positioned statically. |
| `.pf-m-width-{default, 25, 33, 50, 66, 75, 100}{-on-[breakpoint]}` | `.pf-v6-c-sidebar__panel` | Modifies the panel width at optional [breakpoint](/tokens/all-patternfly-tokens). **Note:** does not apply when the panel is stacked on top of the content. |
| `.pf-m-no-background` | `.pf-v6-c-sidebar`, `.pf-v6-c-sidebar__panel, .pf-v6-c-sidebar__content` | Modifies the element to have a transparent background. |
| `.pf-m-secondary` | `.pf-v6-c-sidebar__panel, .pf-v6-c-sidebar__content` | Modifies the element to have secondary styling. |
