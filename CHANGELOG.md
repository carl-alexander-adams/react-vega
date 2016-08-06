# react-vega

## v2.0.0
- Rewrite using preferred method recommended by React. `Vega` component now extends `React.Component` and use `ref` as a function instead of string.
- Add check for props/data changes and only update when necessary.
- Refactor code for clarity
- Remove support for spec as a function
- Add static functions `isSameData`, `isSameSpec` and `listenerName` to `Vega` class.

## v1.1.1
- Fix bug to call `vis.update()` before setting new data

## v1.1.0
- Support function as data and add static `getSpec()`

## v1.0.1
- Avoid clearing data when that field is not set in the input.

## v1.0.0
- Change global export name to `ReactVega` instead of `reactVega`

## v0.1.2
- Fix bug with umd export when using global

## v0.1.1
- Fix bug with umd export when using global

## v0.1.0
- Add support for dynamic spec via `<Vega>` component.

## v0.0.2
- Fix external lib bug

## v0.0.1
- First release