# {{basename}}

{{description}}

## Want to try this stuff out?

```
$ npm install {{basename}}
```

1. At command line - replacing 'my-awesome-library' with your project name and 'your-name' with your person, team, or organization name.

  ```shell
  git init
  npm start
  git add -A
  git commit -m "chore(): initial commit"
  git tag -f v0.0.0
  git checkout -b develop
  ```

4. Create new repository on Github

5. At command line

  ```shell
  git remote add origin https://github.com/{{github}}.git
  git push origin --all
  git push origin --tags
  ```

6. On [Travis-CI](https://travis-ci.org)
  - Enable your new repository
  - In settings enable: `Build only if .travis.yml is present`

7. Back on Github
  - At your new repository choose Settings > Branches
  - Change default branch from master to develop and choose Update
  - Under protected branches select master branch
  - Check protect this branch
  - Check require status checks to pass before merging (including maintainers)
  - Save your changes
