# Omnia Textual maintenance

Based on upstream Textual 0.5.0 (`01b51875a5406eefc95f52a058cb059e7bc94dc4`), under its unchanged MIT license.

Adopts the production-source first-pass parsing/styling/block-spacing correction proposed in upstream PR90 (`e7e269ff3f5ae21eae1ee5cfab4931dc15c278b3`), with synchronous table-cell spacing passed through the environment to the table label. The obsolete table-spacing preference/state path is removed. Public APIs, package dependencies, supported platforms, links, selection and image policy are unchanged.

Native consumer owner: Omnia-co/Frontend, native-ios-2, apps/ios. Qualification and exact compatibility limits are recorded by IOS-CHAT-FLOW-001 in the Context repository. Omnia pins an immutable commit; do not silently move that pin. This is a maintained correction, not a claim that upstream accepted the open PR.

Return to the upstream package once a released correction satisfies the same first/recreated-layout, Dynamic Type, replacement, selection and reader-continuity regressions. Rollback is the original upstream exact 0.5.0 declaration; retain its known first-layout limitation.
