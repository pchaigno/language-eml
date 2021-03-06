### Contributing

> :bulb: Sublime Text users, check: https://github.com/mariozaizar/eml-tmLanguage

- Fork this repo.
- Create a new branch and commit the changes.
- Test manually and add specs. All new code requires tests to ensure against regressions
- Send Pull Request. Filling out the PR template is required. Any pull request that does not include enough information to be reviewed in a timely manner may be closed at the maintainers' discretion.
- Get a +1 from the core team.
- Get your changes merged.

## Build dependencies

```shell
npm install # Node package manager install
apm rebuild # Atom package manager rebuild
```

## Release new versions

```shell
apm publish patch # or minor, mayor
```

## Update Changelogs

```
bundle check || bundle install
github_changelog_generator
```
