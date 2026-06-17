---
id: Avatar
section: components
cssPrefix: pf-v6-c-avatar
---

## Examples
### Default
Custom content such as an icon or svg element can be passed as children to the avatar. Similar to the with initials example, an avatar with children passed can be given a colorful background via the color property and should follow the same guildelines regarding the alt property as the with image example.
```hbs
{{> avatar--list}}
```

### With image
```hbs
{{> avatar avatar--IsImg=true}}
{{> avatar avatar--IsImg=true avatar--src="/assets/images/img_avatar-rhds.svg"}}
```

### Bordered
```hbs
{{> avatar avatar--IsImg=true avatar--IsBordered=true avatar--alt="Avatar image bordered"}}
{{> avatar avatar--IsImg=true avatar--IsBordered=true avatar--alt="Avatar image bordered" avatar--src="/assets/images/img_avatar-rhds.svg"}}
```

### Size variations
```hbs
{{#> l-flex l-flex--modifier="pf-m-wrap pf-m-align-items-center pf-m-gap-sm" avatar--IsRed=true avatar--IsSmall=true avatar-size-text="Small"}}
  {{> avatar--sizes}}
{{/l-flex}}
<br>
{{#> l-flex l-flex--modifier="pf-m-wrap pf-m-align-items-center pf-m-gap-sm" avatar--IsRed=true avatar--IsMedium=true avatar-size-text="Medium"}}
  {{> avatar--sizes}}
{{/l-flex}}
<br>
{{#> l-flex l-flex--modifier="pf-m-wrap pf-m-align-items-center pf-m-gap-sm" avatar--IsRed=true avatar--IsLarge=true avatar-size-text="Large"}}
  {{> avatar--sizes}}
{{/l-flex}}
<br>
{{#> l-flex l-flex--modifier="pf-m-wrap pf-m-align-items-center pf-m-gap-sm" avatar--IsRed=true avatar--IsXLarge=true avatar-size-text="Extra large"}}
  {{> avatar--sizes}}
{{/l-flex}}
```

### With initials
Use a color modifier with a user's initial to add visual interest when no image is available.
```hbs
{{> avatar--list avatar--initials="C" avatar-label-text="with initials"}}
```

### With icon
Use a color modifier with a user's initial to add visual interest when no image is available.
```hbs
{{> avatar--list avatar--icon="rh-ui-ai-chatbot" avatar-label-text="with chatbot icon"}}
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
| `.pf-m-bordered` | `.pf-v6-c-avatar` | Modifies an avatar to have a border. |
| `.pf-m-sm{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be small on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-md{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be medium on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). **Note:** This is the default size. |
| `.pf-m-lg{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be large on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-xl{-on-[breakpoint]}` | `.pf-v6-c-avatar` | Modifies an avatar to be extra large on an optional [breakpoint](/foundations-and-styles/design-tokens/all-design-tokens). |
| `.pf-m-colorful` | `.pf-v6-c-avatar` | Modifies an avatar to use colorful styling with a border. |
| `.pf-m-red` | `.pf-v6-c-avatar` |  Modifies avatar for red styling. |
| `.pf-m-orangered` | `.pf-v6-c-avatar` |  Modifies avatar for orangered styling. |
| `.pf-m-orange` | `.pf-v6-c-avatar` |  Modifies avatar for orange styling. |
| `.pf-m-yellow` | `.pf-v6-c-avatar` |  Modifies avatar for yellow styling. |
| `.pf-m-green` | `.pf-v6-c-avatar` |  Modifies avatar for green styling. |
| `.pf-m-teal` | `.pf-v6-c-avatar` |  Modifies avatar for teal styling. |
| `.pf-m-blue` | `.pf-v6-c-avatar` |  Modifies avatar for blue styling. |
| `.pf-m-purple` | `.pf-v6-c-avatar` |  Modifies avatar for purple styling. |
| `.pf-m-gray` | `.pf-v6-c-avatar` |  Modifies avatar for gray styling. |
