* [template-package-template-package-fail-tests](https://github.com/dustuu/template-package-fail-tests) shows what happens when all repository variables and secrets are configured properly, but one or more Unit Tests are failing.
  * The `Build Release` workflow will fail because Unit Tests are present and configured to run by the user via repository variables, but failing:
  * ![image](https://github.com/vrchat-community/template-package/assets/101824882/ca7219c0-bbd4-41a9-84d8-556a9c1eaa89)
  * The `Build Repo Listing` workflow will fail as expected because there are no published releases.
  * Both badges will be broken because there are no releases:
    * [![VPM Package Version](https://img.shields.io/vpm/v/com.vrchat.demo-template?repository_url=https%3A%2F%2Fdustuu.github.io%2Ftemplate-package-fail-tests%2Findex.json)](https://dustuu.github.io/template-package-fail-tests)
    * [![Code Coverage](https://dustuu.github.io/template-package-fail-tests/coverage/badge_linecoverage.svg)](https://dustuu.github.io/template-package-fail-tests/coverage)
