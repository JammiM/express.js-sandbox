# Index

## modules

### path

`import path from "path";`

`__dirname`
directory name of the current module

`path.sep`
shows the platform-specific path segment separator

`path.join(__dirname, 'subfolder', 'test.txt')`
Building paths relative to the current module

`path.resolve(\_\_dirname, 'content', 'subfolder', 'test.txt')`
absolute path

// ES Module (e.g., app.mjs or "type": "module" in package.json)

`import { fileURLToPath } from 'url';`

`import { dirname } from 'path';`

// Get the current module's URL

`const __filename = fileURLToPath(import.meta.url);`

`const __dirname = dirname(__filename);`

`console.log('ES Module file path:', __filename);`

`console.log('ES Module directory:', __dirname);`
