Rationale for the Supernova Horizon License

Proposed license: Supernova Horizon License
Version: 0.1.0
Status: Public proposal; not approved by the Open Source Initiative (OSI).

1. Purpose

The Supernova Horizon License is a proposed permissive software license intended to explore several questions concerning software licensing in modern development environments.

These include the preservation of existing security-fix information, the boundary between software and separately licensed AI-related materials, and the clarity of redistribution and legal terms.

The purpose of this document is to explain the motivation behind the proposal, the intended behavior of its clauses, and the evidence needed to determine whether a new license is justified.

The project does not assume that every issue identified below requires a new license. Existing licenses may already address some concerns adequately.

2. Why Consider Another License?

Established licenses such as MIT, Apache-2.0, BSD licenses, GPL-3.0, and MPL-2.0 serve different purposes and have established adoption histories.

A new license should not exist merely to provide another name for substantially identical permissions.

The Supernova Horizon License therefore needs to demonstrate a specific, practical distinction from existing licenses. Its initial investigation focuses on two candidate areas:

1. The treatment of existing security-fix information when covered software is redistributed.
2. The distinction between software and separately licensed AI-related components and materials.

Other provisions, including patent permissions, attribution, termination, and warranty disclaimers, are included for completeness but are not claimed to be original innovations.

3. Design Goals

3.1. Permissive use and redistribution

The proposal permits users to use, modify, distribute, sublicense, and commercially exploit covered software.

It does not require distributors to publish modifications or license their own modifications under the same license.

This choice is intended to support broad adoption, including integration into proprietary products.

The trade-off is that the license cannot guarantee that improvements made by downstream distributors will be shared publicly.

3.2. Security-fix information

The proposal includes a clause addressing security metadata that is already supplied with a covered Work.

Its intended effect is to preserve relevant information such as security advisory identifiers and fix references when the Work is redistributed, subject to defined exceptions.

The proposal does not require a distributor to discover vulnerabilities, create advisories, provide security fixes, or maintain the Work.

The question requiring further investigation is whether this limited preservation requirement provides meaningful value beyond existing notice and documentation obligations, and whether distributors can comply with it reliably.

The wording must also avoid requiring the preservation of misleading, obsolete, or irrelevant information.

3.3. AI-related materials

Modern software projects may distribute code alongside models, model weights, datasets, evaluation materials, and generated content.

The proposal aims to make clear that placing software code under a license does not automatically place every associated material under that license.

Separate components remain subject to their applicable terms. A material is covered by this license only where the relevant rights holder has validly granted the necessary rights.

The proposal does not claim ownership of AI-generated output merely because it was produced using licensed software.

This clause is intended to clarify scope rather than to determine whether a particular model, dataset, or output is legally protected.

3.4. Copyright and patent permissions

The proposal includes express copyright permissions and a contributor patent grant.

These provisions are intended to make the permissions understandable to users and distributors. They are not presented as unique features; comparable mechanisms already exist in established licenses.

The patent provisions require careful comparison with existing drafting, particularly the scope of the grant and the consequences of patent litigation.

3.5. Attribution and provenance

The proposal requires applicable existing notices to be retained when covered material is redistributed.

It also encourages accurate identification of modifications without requiring distributors to make unverifiable claims about a Work's origin.

The intent is to preserve relevant information while allowing legitimate modifications and redistribution.

3.6. Termination and reinstatement

The proposal provides for termination following material non-compliance and reinstatement after certain violations are cured.

The intended goal is to make compliance consequences more predictable. The exact timing and operation of reinstatement should be reviewed against established license practice and applicable law.

3.7. Warranty and liability

The proposal includes warranty and liability disclaimers subject to applicable law.

These provisions are intended to communicate that contributors are not generally promising that the Work will be secure, maintained, error-free, or fit for a particular purpose.

Their enforceability may vary by jurisdiction.

4. Candidate Problem Areas

The project's initial investigation considers the following areas:

1. Preservation of existing security-fix metadata during redistribution.
2. Clear boundaries for AI models, datasets, and associated materials.
3. Attribution and notice retention across modifications and binary redistribution.
4. Third-party dependency and license boundaries.
5. Patent permissions and termination.
6. Source-material and build-information boundaries.
7. Contribution authority and AI-related warranty expectations.
8. Clearer treatment of warranty, liability, and compliance.

These are candidate problem areas, not findings that existing licenses are deficient. Each must be compared with existing licenses and real distribution scenarios.

5. Comparison with Existing Licenses

A serious assessment must compare this proposal with at least the following:

- MIT License: A short permissive license with copyright notice and warranty disclaimer provisions.
- Apache License 2.0: A permissive license with express patent provisions and detailed conditions concerning notices and redistribution.
- BSD licenses: Established permissive alternatives with different notice requirements.
- GNU GPL version 3: A copyleft license with conditions governing redistribution and source availability in specified circumstances.
- Mozilla Public License 2.0: A file-level copyleft license.
- Relevant AI-focused licensing proposals: These may help inform how software licenses distinguish code from models, datasets, and other AI materials.

The project must identify precisely which proposed clauses add a meaningful benefit and which merely reproduce existing solutions.

No claim of novelty, superiority, or compatibility should be made without adequate analysis.

6. Open Source Definition Considerations

The proposal is intended to permit broad use, modification, and redistribution. However, its compliance with the Open Source Definition has not been determined.

In particular, the project needs to examine whether the security-metadata condition is sufficiently clear, practical, and consistent with the requirements for an open-source license.

The project also needs to review its restrictions, patent terms, termination provisions, and scope definitions against OSI's current criteria.

OSI approval is a separate decision made through its review process and cannot be assumed.

7. Questions for Reviewers

The project welcomes feedback on the following questions:

1. Does the security-metadata provision address a real problem that existing licenses do not adequately address?
2. Is the preservation obligation objectively understandable and practical for distributors?
3. Could the provision discourage redistribution or create uncertainty about compliance?
4. Are the definitions of Work, Security Metadata, and AI Material sufficiently precise?
5. Are the patent grant and patent-litigation termination provisions clear and appropriately scoped?
6. Are the termination and reinstatement provisions workable?
7. Does the license create unnecessary duplication compared with Apache-2.0 or another established license?
8. Is there a compelling reason to create a new license instead of recommending an existing one?

Concrete examples and suggested wording are especially useful.

8. Planned Development

The proposed development process is:

1. Publish the text and supporting rationale.
2. Compare its clauses against established licenses.
3. Test the wording against representative software, binary distributions, third-party dependencies, and AI-related projects.
4. Obtain independent legal and community feedback.
5. Revise the text to address ambiguity and unnecessary obligations.
6. Determine whether the remaining differences justify a new license.
7. Consider submitting a complete proposal for OSI review if appropriate.

9. Conclusion

The Supernova Horizon License is an attempt to investigate whether a permissive license can provide clearer treatment of existing security-fix information and the boundaries of separately licensed AI-related materials while preserving broad software freedom.

Its value will depend on whether these provisions solve a demonstrable problem better than existing licenses, without introducing disproportionate compliance burdens or legal uncertainty.

The project welcomes evidence-based criticism and revision. The objective is not simply to create another license, but to determine whether a new license is genuinely useful.

---

Supernova Horizon License — Version 0.1.0
