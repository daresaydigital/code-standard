# Code standards

Guides and project templates that we use at Screen Interaction

## How do I use this?

Fork the correct branch for your project:
  * [General](https://github.com/screeninteraction/code-standard/tree/global)
  * [iOS](https://github.com/screeninteraction/code-standard/tree/ios)
  * [Android](https://github.com/screeninteraction/code-standard/tree/android)
  * [Web](https://github.com/screeninteraction/code-standard/tree/web)

In the template you will find gitignore and configuration files for the project.

## High level guidelines:

* Be consistent.
  * Use the same coding standard as the rest of the project.
  * Use a linter or similar tool when writing code.
* Always use [editorconfig](http://editorconfig.org).
  * Use the [global file](https://github.com/screeninteraction/code-standard/blob/global/.editorconfig) in all templates.
* Make sure you put a README.md file in the root of your project.
* Never commit more files to git than you need to.
  * Sanitize and improve your gitignore regulary.
* Never include 3PP libraries in a static context.
  * Use a package manager if possible.
* Don't violate a guideline without a good reason.
  * A reason is good when you can convince a teammate.
  * If a customer want a different standard, try to convince them not to, if that fails, use theirs.

## A note on the language:

* "Avoid" means don't do it unless you have good reason.
* "Don't" means there's never a good reason.
* "Prefer" indicates a better option and its alternative to watch out for.
* "Use" is a positive instruction.

## How to contribute
### To the global template
1. Fork the global branch.
2. Make your improvements.
5. Create a pull request.
3. Invite your colleagues to the discussion and ask about their opinion.
4. When consensus is reached, merge the pull request.
5. Merge the changes to the project branches.

### An existing template
1. Fork the branch and make your improvements.
2. Create a pull request.
3. Invite your colleagues to the discussion and ask about their opinion.
4. When consensus is reached, merge the pull request.

### A new template
1. Fork the global branch.
2. Name your new branch after your type of project.
3. Make your improvements.
4. Create an issue.
5. Invite your colleagues to the discussion and ask about their opinion about the new project template.
6. When consensus is reached, close the issue.

### Inspiration
* [GitHub git ignore](https://github.com/github/gitignore)
* [Thoughtbot style guide](https://github.com/thoughtbot/guides)
