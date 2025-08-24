## Getting Started

npx create-next-app@latest <project name>

    ✔ Would you like to use TypeScript? … Yes
	
    ✔ Would you like to use ESLint? … Yes
	
    ✔ Would you like to use Tailwind CSS? … Yes
	
    ✔ Would you like your code inside a `src/` directory? … No
	
    ✔ Would you like to use App Router? (recommended) … Yes
	
    ✔ Would you like to use Turbopack for next dev? … No
	
    ✔ Would you like to customize the import alias (@/* by default)? … No
	
<reference>
https://www.heropy.dev/p/n7JHmI

## VS Extension

ESLint: 코드 품질 확인 및 버그, 안티패턴(Anti-pattern)을 감지

Prettier - Code formatter: 코드 스타일 및 포맷팅 관리, 일관된 코드 스타일을 적용 가능

# npm i -D prettier eslint-config-prettier prettier-plugin-tailwindcss

/.prettierrc
{
  "semi": false,
  "singleQuote": true,
  "singleAttributePerLine": true,
  "bracketSameLine": true,
  "endOfLine": "lf",
  "trailingComma": "none",
  "arrowParens": "avoid",
  "plugins": ["prettier-plugin-tailwindcss"]
}

/.vscode/settings.json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
