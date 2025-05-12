# 35883

## Current behavior
Renovate bypasses renovate ruleset allowedVersions for hibernate-validator while doing a replacement + upgrade on dependency.

## Expected behavior
Renovate should make a replacement as the hibernate-validator has been relocate, but it should respect the allowedVersions <=6 packageRule for hibernate-validator.

## Workaround
none found

## Link to the Renovate issue or Discussion
renovatebot/renovate#35883
