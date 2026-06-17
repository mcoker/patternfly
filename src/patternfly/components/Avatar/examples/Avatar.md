---
id: Avatar
section: components
cssPrefix: pf-v6-c-avatar
---

import './Avatar.css'

## Examples
### Basic usage
Avatars can be created using either an `<img>` element with an image source, or a `<div>` element with custom content.
```hbs
{{> avatar avatar--IsImg=true avatar--src="/assets/images/pf-logo-avatar.jpg" avatar--alt="Avatar image"}}
{{> avatar avatar--src="/assets/images/img_avatar-rhds.svg" avatar--arial-label="Avatar image"}}
```

### Color modifiers
Color modifiers add visual interest and automatically include a border. **Do not combine color modifiers with `.pf-m-bordered`** as color modifiers set their own borders.
```hbs
{{> avatar--colors avatar--initials="C" avatar-label-text="with initial C"}}
```

### With initials
Display a user's initials in the avatar.
```hbs
{{> avatar avatar--IsBordered=true avatar--initials="C" avatar--aria-label="Avatar with initial C"}}
{{> avatar--colors avatar--initials="C" avatar-label-text="with initial C"}}
```

### Bordered
Use `.pf-m-bordered` to add a border to non-colorful avatars. **This modifier does not work with color modifiers** since colors set their own borders.
```hbs
{{> avatar avatar--IsBordered=true avatar--IsColorful=true avatar--IsRed=true avatar--icon="rh-ui-ai-chatbot" avatar--aria-label="Bordered red avatar with chatbot icon"}}
```

### Size variations
Avatars support small, medium (default), large, and extra large sizes.
```hbs
{{#> wrapper avatar--IsColorful=true avatar--IsRed=true}}
  {{> avatar avatar--IsSmall=true avatar--initials="C" avatar--aria-label="Small red avatar with initial C"}}
  {{> avatar avatar--IsMedium=true avatar--initials="C" avatar--aria-label="Medium red avatar with initial C"}}
  {{> avatar avatar--IsLarge=true avatar--initials="C" avatar--aria-label="Large red avatar with initial C"}}
  {{> avatar avatar--IsXLarge=true avatar--initials="C" avatar--aria-label="Extra large red avatar with initial C"}}
{{/wrapper}}
```

## Documentation
### Overview
The avatar component provides a default SVG icon. If an image is used it should be 36px by 36px.

### Accessibility
| Attribute | Applied to | Outcome |
| -- | -- | -- |
| `alt` | `.pf-v6-c-avatar` | The alt attribute describes the appearance and function of the avatar image. **Required for image avatars** |
| `role="img"` | `.pf-v6-c-avatar` | Indicates the element represents an image. **Required for colorful avatars** |
| `aria-label` | `.pf-v6-c-avatar` | Provides an accessible name for the avatar. **Required for colorful avatars** |
| `aria-hidden="true"` | `.pf-v6-c-avatar__initials`, `<svg>` | Hides decorative content from screen readers when the container has `aria-label`. |

### Usage
| Class | Applied to | Outcome |
| -- | -- | -- |
| `.pf-v6-c-avatar` | `<img>`, `<div>` |  Initiates an avatar. **Required** |
| `.pf-v6-c-avatar__initials` | `<span>` | Contains the user's initials in a colorful avatar. |
| `.pf-m-bordered` | `.pf-v6-c-avatar` | Modifies an avatar to have a border. **Note:** Do not use with `.pf-m-colorful` as colorful avatars provide their own border. |
| `.pf-m-sm{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be small on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-md{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be medium on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). **Note:** This is the default size. |
| `.pf-m-lg{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be large on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-xl{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be extra large on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-colorful` | `.pf-v6-c-avatar` | Modifies an avatar to use colorful styling with a border. **Note:** Do not use with `.pf-m-bordered`. |
| `.pf-m-red` | `.pf-v6-c-avatar` |  Modifies avatar for red styling. |
| `.pf-m-orangered` | `.pf-v6-c-avatar` |  Modifies avatar for orangered styling. |
| `.pf-m-orange` | `.pf-v6-c-avatar` |  Modifies avatar for orange styling. |
| `.pf-m-yellow` | `.pf-v6-c-avatar` |  Modifies avatar for yellow styling. |
| `.pf-m-green` | `.pf-v6-c-avatar` |  Modifies avatar for green styling. |
| `.pf-m-teal` | `.pf-v6-c-avatar` |  Modifies avatar for teal styling. |
| `.pf-m-blue` | `.pf-v6-c-avatar` |  Modifies avatar for blue styling. |
| `.pf-m-purple` | `.pf-v6-c-avatar` |  Modifies avatar for purple styling. |
| `.pf-m-gray` | `.pf-v6-c-avatar` |  Modifies avatar for gray styling. |
