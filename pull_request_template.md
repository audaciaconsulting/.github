### Version changed and CHANGELOG updated
- ✔ New version set in the project file(s) `.csproj` or `Directory.Build.props` and version documented in the CHANGELOG
- ❌ New version is required but not set, or set but not documented in the CHANGELOG
- ❎ No version change required

### Code ready for review
- ✔ Code compiles, all tests pass, no debug/console statements or commented out code left in
- ❌ Build/tests fail or commented out code/debug statements left in
- ❎ No code changes (e.g. just a documentation change)

### Unit tests added/updated
- ✔ Tests added/updated for all new and modified code
- ❌ New or modified code not covered by tests
- ❎ No code changed

### README or other documentation updated
- ✔ Documentation updated to reflect the changes made
- ❌ Documentation needed but not written
- ❎ Changes do not require documentation

### Dependency licenses
- ✔ Licenses of new/upgraded dependencies checked, with no copyleft dependencies introduced
- ❌ Licenses of new/upgraded dependencies have not been checked, or check with copyleft dependencies introduced
- ❎ No new/upgraded dependencies

### Work item linked
- ✔ The Azure DevOps work item has been linked to the PR
- ❌ The Azure DevOps work item has not been linked to the PR
- ❎ No work item exists and none is needed