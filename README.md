# ExampleAngular20App

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.2.2.

```shell
ng new example-angular-20-app

✔ Which stylesheet format would you like to use? Sass (SCSS)     [ https://sass-lang.com/documentation/syntax#scss                ]
✔ Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? No
✔ Do you want to create a 'zoneless' application without zone.js? No
✔ Which AI tools do you want to configure with Angular best practices? https://angular.dev/ai/develop-with-ai None, Claude                 [ https://docs.anthropic.com/en/docs/claude-code/memory
     ], Cursor                 [ https://docs.cursor.com/en/context/rules                                              ], Gemini                 [ https://ai.google.dev/gemini-api/docs
           ], GitHub Copilot         [ https://code.visualstudio.com/docs/copilot/copilot-customization#_custom-instructions ], JetBrains AI Assistant [ https://www.jetbrains.com/help/junie/customize-guidelines.html
                 ], Windsurf               [ https://docs.windsurf.com/windsurf/cascade/memories#rules                             ]
CREATE example-angular-20-app/README.md (1482 bytes)
CREATE example-angular-20-app/.editorconfig (314 bytes)
CREATE example-angular-20-app/.gitignore (587 bytes)
CREATE example-angular-20-app/angular.json (2618 bytes)
CREATE example-angular-20-app/package.json (1145 bytes)
CREATE example-angular-20-app/tsconfig.json (992 bytes)
CREATE example-angular-20-app/tsconfig.app.json (429 bytes)
CREATE example-angular-20-app/tsconfig.spec.json (408 bytes)
CREATE example-angular-20-app/.vscode/extensions.json (130 bytes)
CREATE example-angular-20-app/.vscode/launch.json (470 bytes)
CREATE example-angular-20-app/.vscode/tasks.json (938 bytes)
CREATE example-angular-20-app/src/main.ts (222 bytes)
CREATE example-angular-20-app/src/index.html (305 bytes)
CREATE example-angular-20-app/src/styles.scss (80 bytes)
CREATE example-angular-20-app/src/app/app.scss (0 bytes)
CREATE example-angular-20-app/src/app/app.spec.ts (680 bytes)
CREATE example-angular-20-app/src/app/app.ts (305 bytes)
CREATE example-angular-20-app/src/app/app.html (20122 bytes)
CREATE example-angular-20-app/src/app/app.config.ts (400 bytes)
CREATE example-angular-20-app/src/app/app.routes.ts (77 bytes)
CREATE example-angular-20-app/public/favicon.ico (15086 bytes)
CREATE example-angular-20-app/.claude/CLAUDE.md (1936 bytes)
CREATE example-angular-20-app/.cursor/rules/cursor.mdc (1989 bytes)
CREATE example-angular-20-app/.gemini/GEMINI.md (1936 bytes)
CREATE example-angular-20-app/.github/copilot-instructions.md (1936 bytes)
CREATE example-angular-20-app/.junie/guidelines.md (1936 bytes)
CREATE example-angular-20-app/.windsurf/rules/guidelines.md (1936 bytes)
✔ Packages installed successfully.
    Successfully initialized git.

npm run ng -- add @angular/material@20

✔ Determining Package Manager
  › Using package manager: npm
✔ Loading package information from registry
✔ Confirming installation
✔ Installing package
✔ Select a pair of starter prebuilt color palettes for your Angular Material theme Azure/Blue         [Preview: https://material.angular.dev?theme=azure-blue]
UPDATE package.json (1212 bytes)
✔ Packages installed successfully.
UPDATE src/styles.scss (1328 bytes)
UPDATE src/index.html (505 bytes)

npm run ng -- add angular-eslint@20

✔ Determining Package Manager
  › Using package manager: npm
✔ Loading package information from registry
✔ Confirming installation
✔ Installing package

    All angular-eslint dependencies have been successfully installed 🎉

    Please see https://github.com/angular-eslint/angular-eslint for how to add ESLint configuration to your project.

    We detected that you have a single project in your workspace and no existing linter wired up, so we are configuring ESLint for you automatically.

    Please see https://github.com/angular-eslint/angular-eslint for more information.

CREATE eslint.config.js (969 bytes)
UPDATE package.json (1327 bytes)
UPDATE angular.json (2941 bytes)
✔ Packages installed successfully.
```

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
