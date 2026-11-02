# Source SBOM

**Initial source snapshot, not a release report.** Source commit `b77cd90d77c50ba62ad321cf0ebc2ad9deb75a17` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/libgsm `b77cd90d77c50ba62ad321cf0ebc2ad9deb75a17`

- sbom:role: source-root
- sbom:git-commit: b77cd90d77c50ba62ad321cf0ebc2ad9deb75a17
- sbom:git-tree: 9db1842081c221e96038dfc9e8738dbfe5b5cd39
- sbom:source-repository: https://github.com/wave-owl/libgsm
- sbom:release-tags: []

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/libgsm | b77cd90d77c50ba62ad321cf0ebc2ad9deb75a17 | source-root | unresolved |
| Conditional source requirements declared by Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Standalone C GSM codec; Makefile | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
