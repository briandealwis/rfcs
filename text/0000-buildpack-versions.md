# Meta
[meta]: #meta
- Name: Buildpack Versions
- Start Date: 2020-01-29
- CNB Pull Request:
- CNB Issue:
- Supersedes: N/A

# Summary
[summary]: #summary

There's conversation on whether the buildpacks project wants to enforce a specific format for buildpack versions. This RFC explains that buildpack authors can use any pattern (ie. semantic versioning) when deciding how to create versions for buildpacks.

# Motivation
[motivation]: #motivation

There aren't specific guidelines in the buildpack documentation for buildpack authors that explain how versioning works for buildpacks. It should be explicitly stated that the API supports any version format.

Buildpack authors are enabled to use any versioning that increments versions with each release.

# What it is
[what-it-is]: #what-it-is

This provides a high level overview of the feature.

- Define any new terminology.
- Define the target persona: buildpack author, buildpack user, platform operator, platform implementor, and/or project contributor.
- Explaining the feature largely in terms of examples.
- If applicable, provide sample error messages, deprecation warnings, or migration guidance.
- If applicable, describe the differences between teaching this to existing users and new users.

# How it Works
[how-it-works]: #how-it-works

This is the technical portion of the RFC, where you explain the design in sufficient detail.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

This decision could cause issues with buildpack API in the future if a specific format or type is needed.

# Alternatives
[alternatives]: #alternatives

- What other designs have been considered?
- Why is this proposal the best?
- What is the impact of not doing this?

# Prior Art
[prior-art]: #prior-art

Discuss prior art, both the good and bad.

# Unresolved Questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to be resolved before this gets merged?
- What parts of the design do you expect to be resolved through implementation of the feature?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?
