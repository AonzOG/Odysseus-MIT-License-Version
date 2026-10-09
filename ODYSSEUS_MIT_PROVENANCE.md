# Odysseus — Original MIT source provenance and license history

**Purpose:** Record the exact historical upstream source revision reproduced in the public repository [AonzOG/Odysseus-MIT-License-Version](https://github.com/AonzOG/Odysseus-MIT-License-Version), together with the later upstream license change. This is an evidence record, not a claim to authorship, not a new license grant, and not a legal opinion.

**Evidence reviewed:** 9 October 2026 (Fiji time; UTC+12).

## Original upstream MIT revision (source of this repository)

| Identifier | Verified value |
| --- | --- |
| Original repository | `https://github.com/odysseus-dev/odysseus` |
| Historical upstream branch | `main` |
| **Original MIT commit SHA (Git commit)** | **`6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997`** |
| **Original Git tree SHA (complete tracked source)** | **`d7d1143ee58beaf6889d22ec70bbf6edbc41163a`** |
| Original `LICENSE` Git blob SHA | `7087e2d598700ecb40f09a0fbf3f12952fcf641e` |
| Git commit time | 2026-06-09 01:31:43 UTC / **9 June 2026 1:31:43 PM Fiji time** |
| Project license recorded in `LICENSE` | **MIT License** |
| Project license stated in `README.md` | `MIT -- see [LICENSE](LICENSE) and [ACKNOWLEDGMENTS.md](ACKNOWLEDGMENTS.md).` |
| Number of tracked source files in the tree | 1,005 |

Authoritative upstream historical URLs:

- [Original MIT source commit](https://github.com/odysseus-dev/odysseus/commit/6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997)
- [Browse exact upstream MIT source snapshot](https://github.com/odysseus-dev/odysseus/tree/6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997)
- [Original MIT LICENSE at the pinned commit](https://github.com/odysseus-dev/odysseus/blob/6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997/LICENSE)
- [Original README at the pinned commit](https://github.com/odysseus-dev/odysseus/blob/6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997/README.md)
- [Original acknowledgments at the pinned commit](https://github.com/odysseus-dev/odysseus/blob/6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997/ACKNOWLEDGMENTS.md)

## Later upstream change from MIT to AGPL

| Identifier | Verified value |
| --- | --- |
| License-change commit SHA | `23f0d64edb7cb9ee2a6d0a6fddd72e50b726baf6` |
| License-change commit title | `Change project license to AGPL-3.0-or-later` |
| License-change commit time | 2026-06-09 05:25:04 UTC / **9 June 2026 5:25:04 PM Fiji time** |
| **Immediate parent of license-change commit** | **`6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997`** |
| Files changed by that commit | `LICENSE` and `README.md` |
| Previous project license in the parent | MIT |
| Project license declared by the new commit | AGPL-3.0-or-later |

**Direct record of the MIT-to-AGPL transition:**
[View the upstream license-change commit and two-file diff](https://github.com/odysseus-dev/odysseus/commit/23f0d64edb7cb9ee2a6d0a6fddd72e50b726baf6).

The upstream record shows that this project's MIT-licensed `main` source revision **predated** the AGPL change. The snapshot reproduced here is the historical MIT commit, not a later AGPL commit with its `LICENSE` file overwritten.

## Preservation in AonzOG/Odysseus-MIT-License-Version

| Identifier | Verified value |
| --- | --- |
| Public preservation repository | `https://github.com/AonzOG/Odysseus-MIT-License-Version` |
| **Repository commit publishing the identical historical source tree** | **`9791bbdce7a207eca18abda0f4fe1102f7a2ec93`** |
| **Git tree SHA of the preservation commit** | **`d7d1143ee58beaf6889d22ec70bbf6edbc41163a`** |
| Original upstream Git tree SHA | `d7d1143ee58beaf6889d22ec70bbf6edbc41163a` |
| Original `LICENSE` Git blob SHA | `7087e2d598700ecb40f09a0fbf3f12952fcf641e` |
| Preservation repository `LICENSE` blob SHA | `7087e2d598700ecb40f09a0fbf3f12952fcf641e` |

[View the preservation commit on GitHub](https://github.com/AonzOG/Odysseus-MIT-License-Version/commit/9791bbdce7a207eca18abda0f4fe1102f7a2ec93).

**Verification result:** The historical source revision and the preservation commit have **identical Git tree IDs**. This demonstrates that their entire tracked file trees, including Git object content and file modes, matched when that preservation commit was created. The original `LICENSE` file is unchanged. This is more comprehensive than comparing only two filenames or license statements.

**Important:** Adding this documentation file to the repository changes the **new** `main` tree SHA, as expected. The preservation commit linked above retains the exact original source tree SHA and remains the correct immutable comparison reference. Do not replace or amend that preservation commit.

### Reproduce the source comparison locally with Git

```sh
# Run from a local clone of AonzOG/Odysseus-MIT-License-Version.
git remote add original-odysseus https://github.com/odysseus-dev/odysseus.git
git fetch original-odysseus 6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997

git rev-parse 9791bbdce7a207eca18abda0f4fe1102f7a2ec93^{tree}
git rev-parse FETCH_HEAD^{tree}
# Both commands should print d7d1143ee58beaf6889d22ec70bbf6edbc41163a.

git diff --exit-code 9791bbdce7a207eca18abda0f4fe1102f7a2ec93 FETCH_HEAD
# No output and exit code 0 mean identical tracked source trees.
```

If `original-odysseus` is already configured as a remote, skip the `git remote add` step.

## Licensing scope and historical context

The original repository's MIT grant expressly permitted copying, modifying, publishing, and redistributing the software, provided the copyright and permission notice remained in copies or substantial portions. The original MIT notice and the project's acknowledgments are preserved with this historical source. See the [standard MIT License wording at the Open Source Initiative](https://opensource.org/license/mit).

A later upstream license change generally does not retroactively revoke rights already granted under MIT to a prior legitimately licensed version. This preservation therefore documents **continued use of an earlier MIT source revision**, not a claim that the later AGPL versions are MIT-licensed. New code taken from later AGPL revisions must be evaluated separately and should not be assumed to carry the original MIT grant. Embedded third-party materials may also have their own licensing obligations; consult the project's `licenses/` directory and acknowledgments.

Git SHAs and these links are technical evidence of repository history, not legal immunity or proof that every contributor had authority to license every component. If there is a formal copyright complaint, retain independent backups of the historical source and commit records and obtain advice from a qualified intellectual-property lawyer in the applicable jurisdiction.

## Separate later historical MIT revision on `dev` (not this repository's source)

A distinct, later MIT-licensed revision existed on upstream `dev` at `bdbe69946f66305a8b4d1577eeaf1f4e398f6660`, immediately before the `dev` relicensing commit `52ae2004220c3b67f9e98507647c0351db71f950`. That `dev` revision is **not** the content of this preservation repository: the repository's verified tree matches the earlier `main` SHA `6ed1c19bc965b455a1e9e60abc1b35e1bfdeb997`. Do not conflate the two revisions.

---
This file is supplementary provenance documentation. It does **not** alter the historical MIT license, original copyright statements, source files, or attribution.
