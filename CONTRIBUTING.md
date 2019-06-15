# How to contribute to this open source project

## Did you find a bug?

You can check for existing bug reports, or submit a new report, in the
**[Issues](https://github.com/grantneufeld/BBLM-GDScript/issues)**
section of the GitHub repository.

When submitting a report, please be sure to include a **title and clear description**,
and as much relevant information as possible, to explain what is going wrong.

## Are you contributing code?

Please do not make changes on the `master` branch.

1. Make a new branch for your code modifactions/additions (patch).
If there is a relevant [Issue](https://github.com/grantneufeld/BBLM-GDScript/issues)
for the code you are contributing,
start the branch name with the issue number and a dash (e.g., `123-Fix-broken-thing`)

2. Open a new GitHub pull request with the patch.

3. Ensure the pull request description clearly describes what the purpose of the patch is.
Include the relevant issue number if applicable. E.g:
```
    Added the ability to shoot lasers from unicorn horns.
    Addresses issue #123.
```

### Are you providing a language translation?

Please make a separate version of the `GDScript.plist` file with the language code
(and country/region/dialect code, if applicable)
as an additional suffix before the `.plist` suffix.

For example, `GDScript.en-ca.plist` would be a Canadian English translation.
