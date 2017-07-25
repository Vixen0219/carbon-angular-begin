# Neutrino Seed

## Prerequisites

* [npm](https://www.npmjs.com/) (`brew install npm`)
* [git](https://git-scm.com/) (`brew install git`)

## NPM Setup

We use scoped packages from [npm-registry.whitewater.ibm.com](https://npm.whitewater.ibm.com/), so you will need access
to this registry.

You can get it by running the following command in the terminal and logging in with your IBM ID (use the part before @ for username):

```bash
npm login --registry=https://npm-registry.whitewater.ibm.com --scope=@peretz --auth-type=oauth
```

This will create/add to your `~/.npmrc` file the token required for access.

[More details](https://github.ibm.com/Whitewater/npm-enterprise#option-2-using-npm-enterprise-for-private-packages-only)

## Download and install

If you haven't already, [add an SSH key to your GHE account](https://github.ibm.com/settings/keys).

After you've set up your NPM, proceed to downloading and installing seed by pasting the following in the terminal

```bash
git clone git@github.ibm.com:peretz-next/neutrino-seed.git
cd neutrino-seed
npm install
```

If the installation doesn't go through, you may need to validate your whitewater session by visiting the link shown in the error.

## Development server
Run `ng serve` for a dev server. Navigate to [http://localhost:4200/](http://localhost:4200/). The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
