Demonstration of the pain that is mismatching `allowSyntheticDefaultImports` setting between TS projects.

After `npm i` in both projects, `npm run build` in foo, then use `npm link ../foo` inside `bar` to get the dep correctly set up. Finally try `npm run build` in bar - it will generate errors.