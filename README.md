# VS Code React Bricks snippets (TypeScript)

This extensions add snippets to make developing with React Bricks easier. At the moment only TypeScript React (.tsx) is supported.

## What is React Bricks

React Bricks is a CMS with visual editing based on React components, for Next.js and Gatsby. It is both a React library to create your visually editable content blocks and a SaaS where the content is persisted.

See [https://reactbricks.com](https://reactbricks.com)

## Available snippets

|           Prefix | Method                                              |
| ---------------: | --------------------------------------------------- |
|         `brick→` | Scaffolds a new Brick. Use it in a new file.        |
|  `sideEditProp→` | Creates a new `sideEditProp`                        |
| `selectOptions→` | Creates `selectOptions` for a select `sideEditProp` |
|          `Text→` | Add a React Bricks `<Text>` component               |
|      `RichText→` | Add a React Bricks `<RichText>` component           |
|         `Image→` | Add a React Bricks `<Image>` component              |
|          `File→` | Add a React Bricks `<File>` component               |
|      `Repeater→` | Add a React Bricks `<Repeater>` component           |

## Requirements

In order to have working React Bricks' bricks, you need to have a React Bricks project set up.

You can easily create a project using the React Bricks CLI:  
`npx create-reactbricks-app`

## Release Notes

### 0.0.1

Initial release
