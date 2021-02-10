# Tailwind CSS

## Tutorial

Code: https://github.com/iamshaunjp/tailwind-tutorial

[Video 1](https://www.youtube.com/watch?v=bxmDnn7lrnk&ab_channel=TheNetNinja)
- New package.json file `$npm init -y`
- Install tailwind package `$npm install tailwindcss`
- Create src/styles.css and add tailwind directives (see TW installation guide online)
- Add script to package.json for building the public css script
    `"npx tailwindcss-cli@latest build ./src/styles.css -o ./public/styles.css"`
- `$npm run build-css`

[Video 2](https://www.youtube.com/watch?v=3ZMUgga6SsY&ab_channel=TheNetNinja): HTML structure

[Video 3](https://www.youtube.com/watch?v=w0KZhi3DD-0&ab_channel=TheNetNinja): Fonts & colours
- See Tailwind docs for colour scheme and class names
- Colour eg: text-gray-600
- Weight eg: font-semibold
- Size eg: text-2xl

[Video 4](https://www.youtube.com/watch?v=1g4W2U-l350&ab_channel=TheNetNinja): Margin, Padding & Borders
- Padding eg: p-4, py-6
- Margin eg: mt-4, ml-4
- Border eg: border-8, border-t, border-l-4, border-gray-200
