# BCI Project

The BCI Project is a broad range of open source game development tools, frameworks, and libraries, primarily for the Unreal Engine. The project is spread across multiple repositories and is organized in a way such that developers will have an easy time taking as little or as many libraries as they wish to consume.

## Development

The BCI Project is built working backwards from BCI's commercial games. As such, feature development will be constantly dog fooded by the games being supported. Features will only be shipped if there's been a proven use case with an actual game.

Additionally, development of BCI's commercial games integrate with the BCI Project like an external user. BCI commercial games do not use internal forks of these libraries. This way, the tools provided are constantly tested in house.

## Tenets

The BCI project adheres to 3 major principles:

### Live at Head

Due to the tremendous difficulty behind package management in general, let alone a project of this size, versioned releases will not be provided. Instead, developers should be able to take from mainline at any given time. Versioning, deprecation warnings, and stable interfaces should make it possible to support continual release and integration with external projects.

When new major versions of the Unreal Engine are released, however, then the current commits for each repo will be tagged. This will provide an unofficial release milestone.

### Missing Features are Bugs

All BCI Project code must provide customization, hooks, interfaces, and whatever else may be needed such that users will never need to modify the base code. Developers should be able to extend these tools without ever needing to modify the source code. If development is completely blocked and the feature cannot be made with the current state of the code provided, then it is a bug report, not a feature request.

### Shared Development Responsibility

The BCI Project is ultimately a solo effort, and it is a very ambitious one. As such, users must be willing to put in the work when submitting bugs, feature requests, etc. Any feature requests must provide a proof of concept, design, prototype, something other than a statement of a problem, or else it will most likely be ignored. This due to the nature of limited time and resources.
