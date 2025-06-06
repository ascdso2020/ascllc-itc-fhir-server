## Description
Describe the changes in this PR.

## Related issues
Addresses [issue #].

## Testing
Describe how this change was tested.

## FHIR Team Checklist
- **Update the title** of the PR to be succinct and less than 65 characters
- **Add a milestone** to the PR for the sprint that it is merged (i.e. add S47)
- Tag the PR with the type of update: **Bug**, **Build**, **Dependencies**, **Enhancement**, **New-Feature** or **Documentation**
- Tag the PR with **Open source**, **Azure API for FHIR** (CosmosDB or common code) or **Azure Healthcare APIs** (SQL or common code) to specify where this change is intended to be released.
- Tag the PR with **Schema Version backward compatible** or **Schema Version backward incompatible** or **Schema Version unchanged** if this adds or updates Sql script which is/is not backward compatible with the code.
- When changing or adding behavior, if your code modifies the system design or changes design assumptions, please create and include an [ADR](https://github.com/microsoft/fhir-server/blob/main/docs/arch).
- [ ] CI is green before merge [![Build Status](https://microsofthealthoss.visualstudio.com/FhirServer/_apis/build/status/CI%20Build%20%26%20Deploy?branchName=main)](https://microsofthealthoss.visualstudio.com/FhirServer/_build/latest?definitionId=27&branchName=main) 
- Review [squash-merge requirements](https://github.com/microsoft/fhir-server/blob/main/SquashMergeRequirements.md)

### Semver Change ([docs](https://github.com/microsoft/fhir-server/blob/main/docs/Versioning.md))
Patch|Skip|Feature|Breaking (reason)
