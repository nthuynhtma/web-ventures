npm install tailwindcss @tailwindcss/vite

import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'
export default defineConfig({
plugins: [
tailwindcss(),
],
})

npm install -D babel-plugin-react-compiler@latest

install eslint extension help compiler immediately detect error syntax

https://github.com/tailwindlabs/prettier-plugin-tailwindcss

.prettierrc.json

{
  "plugins": ["prettier-plugin-tailwindcss"]
}
