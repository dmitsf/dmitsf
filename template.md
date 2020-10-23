Account age: **{{ ACCOUNT_AGE }}** years

Pushed **{{ COMMITS }}** commits

Opened **{{ ISSUES }}** issues

Submitted **{{ PULL_REQUESTS }}** pull requests

Received **{{ STARS }}** stars

Own **{{ REPOSITORIES }}** repositories

Contributed to **{{ REPOSITORIES_CONTRIBUTED_TO }}** public repositories

Top 8 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}

Top 4 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START:max=4 }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}


{{ ACCOUNT_AGE }}
Account age in years.

{{ ISSUES }}
Total number of opened issues across all repositories.

{{ PULL_REQUESTS }}
Total number of opened pull requests across all repositories.

{{ COMMITS }}
Total number of commits across all repositories. Includes commits in private repositories only if you allowed github to show your private contributions on your profile (check out this link for more info).

{{ GISTS }}
Total number of public gists.

{{ REPOSITORIES }}
Total number of repositories. Includes private repositories if the given personal access token has repo scope (see more here).

{{ REPOSITORIES_CONTRIBUTED_TO }}
Total number of repositories you contributed to.

{{ STARS }}
Total number of stars on all your gists and repositories.

Languages
A region that will be repeated for every language you use in your repositories.

{{ LANGUAGE_TEMPLATE_START }}
Special template string that signifies the start of the region.

{{ LANGUAGE_NAME }}
Name of the language.

{{ LANGUAGE_PERCENT }}
How often the language is used in your repositories (percentage wise).

{{ LANGUAGE_COLOR }}
Color of the language (in CSS color format ex: #0248AC).

{{ LANGUAGE_TEMPLATE_END }}
