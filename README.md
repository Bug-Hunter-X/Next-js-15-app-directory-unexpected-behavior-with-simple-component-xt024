# Next.js 15 App Directory Unexpected Behavior

This repository demonstrates an unexpected behavior in Next.js 15's App directory when using a simple component.

## Bug Description

When creating a simple component in the `app` directory (e.g. pages/index.js), Next.js throws an error related to React Strict Mode even when Strict Mode is not enabled. The error message might vary.

## Steps to Reproduce

1. Create a new Next.js 15 app.
2. Replace the contents of `app/page.js` with the provided code.
3. Run the development server (`npm run dev`).
4. Observe the error.

## Expected Behavior

The component should render without any error.

## Actual Behavior

Next.js throws an error.

## Solution

The solution often involves ensuring that the component structure and dependencies are correctly configured and align with Next.js 15 app router conventions.