# Udemy Testing Library 강의 수강 기록

## Color Button Porject

- `testing-library`와 `jest`를 활용하여 Unit Test의 기초를 학습한다.

### Review

- Test interactivity using `fireEvent`
- jest-dom assertions:
  - `toBeEnabled()`
  - `toBeDisabled()`
  - `toBeChecked()`
- `getByRole` option `{ name: }`
- Jest `describe` to gropu tests
- Unit testing functions

## ESLint and Prettier

- ESLint: Linter
- Perttier: Formater

### ESLint

- Install

```bash
npm install eslint-plugin-testing-library eslint-plugin-jest-dom
```

- Remove `eslintConfig` from `packge.json`
- Create `.eslintrc.json` and add standard config
