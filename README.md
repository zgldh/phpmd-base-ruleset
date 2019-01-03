# phpmd-base-ruleset
PHPMD base ruleset

## Usage

1. `composer require zgldh/phpmd-base-ruleset`
2. `cp vendor/zgldh/phpmd-base-ruleset/ruleset.template.xml ./phpmd_ruleset.xml`
3. `vendor/bin/phpmd ./ xml phpmd_ruleset.xml --suffixes php --reportfile phpmd_report.xml`

You can integrate PHPMD into Jenkins or other CI/CD tools.
