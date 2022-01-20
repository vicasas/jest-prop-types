# Contributing to jest-prop-types

If you're reading this, you're awesome! Thank you for helping us make this project great. Here are a few guidelines that will help you along the way.

## Code of Conduct

We have adopted the [Contributor Covenant](https://www.contributor-covenant.org/) as its Code of Conduct, and we expect project participants to adhere to it.
Please read [the full text](/CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## Your first Pull Request

Working on your first Pull Request? You can learn how from this free video series:

[How to Contribute to an Open Source Project on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

If you decide to fix an issue, please be sure to check the comment thread in case somebody is already working on a fix. If nobody is working on it at the moment, please leave a comment stating that you have started to work on it so other people don't accidentally duplicate your effort.

If somebody claims an issue but doesn't follow up for more than a week, it's fine to take it over but you should still leave a comment. If there has been no activity on the issue for 7 to 14 days, it is safe to assume that nobody is working on it.

## Sending a Pull Request

jest-prop-types is a community project, so Pull Requests are always welcome, but, before working on a large change, it is best to open an issue first to discuss it with the maintainers.

When in doubt, keep your Pull Requests small. To give a Pull Request the best chance of getting accepted, don't bundle more than one feature or bug fix per Pull Request. It's often best to create two smaller Pull Requests than one big one.

The step by step

1. Fork the repository

2. Clone the fork to your local machine and add upstream remote:

```sh
git clone https://github.com/<your username>/jest-prop-types.git
cd jest-prop-types
git remote add upstream https://github.com/vicasas/jest-prop-types.git
```

3. Synchronize your local `main` branch with the upstream one:

```sh
git checkout main
git pull upstream main
```

4. Install the dependencies with npm:

```sh
npm install
```

5. Create a new topic branch:

```sh
git checkout -b my-topic-branch
```

6. Make changes, commit and push to your fork:

```sh
git push -u origin HEAD
```

7. Go to [the repository](https://github.com/vicasas/jest-prop-types) and make a Pull Request.

The core team is monitoring for Pull Requests. We will review your Pull Request and either merge it, request changes to it, or close it with an explanation.

## Coding style

We are using Prettier to format and Eslint to write better code, following the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript). Make sure your code adheres to the style rules before submitting a pull request.

We are using husky and lint-staged for a better development experience, every time I commit the linter tasks will run automatically. But you can also run the following commands manually on the console:

`npm run prettier:fix`: For formatting corrections.

`npm run eslint:fix`: For code fixes.

## License

By contributing your code to the [jest-prop-types](https://github.com/vicasas/jest-prop-types) GitHub repository, you agree to license your contribution under the [MIT license](/LICENSE).
