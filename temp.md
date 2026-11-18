
| | Grace | MIT | Spec Kit | Kiro | Tessl | OpenSpec |
|---|---|---|---|---|---|---|
| **Rough English in, spec out** | Yes: interview, then a sketch | Yes: agent skill | Yes | Yes | Yes | Yes |
| **Readable English after** | Generated summary and sketch | Purpose, Principle, prose | The spec itself | User stories | The spec itself | Proposal plus spec |
| **Spec output** | Numbered rules plus terms | Concept specs plus TypeScript | spec, plan, tasks | EARS requirements, design, tasks | `.spec.md` with test links | Proposal, design, tasks, change specs |
| **Visible dialect** | Full grammar, parsed into an IR | Partly: conditions are free prose | Template headings | EARS sentence forms | Light: frontmatter, test links | Requirement plus Scenario, SHALL/WHEN/THEN |
| **Formal tools** | Alloy 6, TLA+ (TLC), TLAPS | None in the repo; `check` is structural | None | None | None | None |
| **Proofs, published?** | Yes: 141 models hold, 1,783 planted faults caught, Money proved at every size by TLAPS, all in the public repo | No | No | No | Linked tests, no proofs | No; OccupySaaS tests against vendor SDKs |
| **Shared library** | 67 patterns | 16-concept catalog, "inspiration" | No | No | A registry? | No |
| **Spec stays the source after code** | Yes: rebuilt from patterns, no hand patches | Partly: shape check only | Not enforced? | Spec files synced, code unchecked? | Partly: linked tests | Partly: changes merge back into specs |
| **Says what's out** | Owned Non-goals, MUST NOT rules | No | Edge cases section | No | No | No |
| **Regulated shape** | Yes | No | No | No | No | No |
