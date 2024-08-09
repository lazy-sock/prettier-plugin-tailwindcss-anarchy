Website: https://prettier-plugin-tailwindcss-anarchy.netlify.app/

This Prettier plugin is a modification to pretier-plugin-tailwindcss. It sorts the tailwind classes randomly and not according to a specific order.

# Installation

First, install prettier and the prettier-tailwindcss-anarchy-plugin:

```bash
npm install -D prettier prettier-plugin-tailwindcss-anarchy
```

Then create a file named .prettierrc and add the following code:

```jsx
{
    "plugins": ["prettier-plugin-tailwindcss-anarchy"]
}
```

- The installation can vary depending on your framework or setup.

For more information, refer to [prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss), as only the sorting has been changed.