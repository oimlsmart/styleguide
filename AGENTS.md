# AGENTS.md

This file provides guidance to AI agents of any framework when working in this repository or in any repository that references the OIML SMART style guide. It applies to Claude Code, the OpenAI Agents SDK, Aider, Continue, Cursor, and any other agent framework that consumes a root-level `AGENTS.md`.

## Read the style guide

Before producing any written content for the OIML SMART program, read `WRITING_STYLE.md` in full. The guide is the authoritative source on register, prohibited patterns, content rules, vocabulary, and formatting.

## Binding rules

The following rules are enforced on every draft produced under the OIML SMART program.

The register is academic and professional. Sentences are complete with subject and verb. Paragraphs are three to six sentences. The present tense and active voice are preferred.

Em-dashes are not used. Sentence separation uses periods, commas, or parentheses.

Paired clever sentences, hedges, rhetorical questions, conversational asides, and marketing superlatives are not used. The full list of prohibited words and patterns appears in `WRITING_STYLE.md`.

No dollar amounts, cost figures, total-cost-of-ownership models, bounty payouts, insurance figures, or liability caps appear in the writing.

No named Issuing Authorities, test laboratories, or manufacturers appear as participants, pilots, or partners. The only organizations named are OIML SMART, the OIML institutional bodies (BIML, CIML), and the OIML-CS Issuing Authorities discussed collectively. Ribose appears only as the developer. Confium appears only as the threshold-cryptography substrate.

CNML is the digital certificate format developed under the OIML SMART program by analyzing every existing published OIML-CS Type Approval certificate and digitizing the resulting model compatibly with OIML SMART and the relevant OIML R-Recommendations.

CNML is not described as the OIML equivalent of the PTB Digital Calibration Certificate. CNML and DCC operate at different tiers of the metrology infrastructure and are complementary.

CNML is not associated with NIST or any other external evaluation program. NIST is mentioned only where the writing cites a real NIST standard.

The writing does not discuss finance, financial auditors, legal standing, liability frameworks, insurance, procurement, customs, environmental impact, geopolitical navigation, or comparative positioning against other frameworks.

Local filesystem paths do not appear in any committed file. Cross-repository references describe the upstream project by name.

## Self-review before completion

Before reporting a writing task as complete, the agent performs a self-review pass against `WRITING_STYLE.md`. The pass reads the draft aloud, marks any em-dash, paired sentence, hedge, conversational aside, or marketing superlative, and rewrites each marked sentence. The pass then verifies that no named organization, dollar amount, local path, or out-of-scope topic appears. The pass finally verifies that the origin story and the DCC relationship are correctly stated wherever they appear.

## When uncertain

If a draft contains a claim that cannot be verified against a published source, the claim is removed. If a draft makes the agent uncertain whether a pattern is permitted, the pattern is treated as prohibited. Vagueness is acceptable. Invented specifics are not.

## Scope of application

The guide applies to README files, documentation pages, FAQ entries, landing-page prose, code comments that readers see, and any other content published under the OIML SMART program. The guide does not apply to internal commit messages, code identifiers, or test fixtures.
