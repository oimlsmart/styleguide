# OIML SMART writing style guide

This guide defines the writing conventions for all public-facing content produced under the OIML SMART program. It applies to README files, documentation pages, FAQ entries, landing pages, code comments that readers see, and any prose published under the program. The guide itself is written in the register it requires.

## Purpose and scope

CNML is the digital certificate format developed under the OIML SMART program to succeed the PDF-based OIML-CS certificate of conformity. The format was produced by analyzing every existing published OIML-CS Type Approval certificate and digitizing the resulting model in a manner compatible with OIML SMART and the relevant OIML R-Recommendations. The implementation is developed by Ribose, and the threshold-cryptography substrate is provided by Confium. Beyond those two attributions, the writing names no other organizations.

The writing audience is the OIML SMART community: Issuing Authorities, BIML and CIML staff, OIML member-state delegates, the OIML-CS technical community, and the metrology public. The writing is technical and institutional, not promotional or journalistic.

## Required register

The register is academic, professional, and substantive. Sentences are complete, with subject and verb. Paragraphs run three to six sentences. Sections open with a topic sentence, develop the point, and cite the relevant specification or standard by number where applicable.

The reader should learn what the system does and how it works. Excitement about the work is conveyed through substantive description of the architecture, not through superlatives or emphasis.

## Prohibited writing patterns

### Em-dashes

Em-dashes are not used. Sentence separation uses periods. Parenthetical material uses commas or parentheses. A clause that would naturally take an em-dash is either promoted to its own sentence or enclosed in parentheses.

### Paired clever sentences

The construction in which one sentence sets up a phrase and the next sentence echoes it for rhetorical effect is prohibited. Examples of the prohibited pattern include the form in which the first sentence introduces a phrase and the second sentence reuses that phrase, and the form in which a negation prelude sets up the actual claim. The same prohibition covers rhetorical echo constructions more generally.

### Hedges and intensifiers

The following words are avoided: essentially, literally, simply, exactly, just, obviously, naturally, of course, clearly, definitely, certainly, very, really, quite, rather. Where one of these words appears, the sentence is usually stronger without it.

### Rhetorical questions

Prose states its points directly. Sections do not open with questions. The FAQ section is the only place where question form is appropriate, and even there the questions are factual user queries, not stylized rhetorical setups.

### Conversational asides

Phrases such as worth noting, importantly, crucially, by the way, the kicker is, the trick is, what is interesting is, the key insight is, and the bottom line are not used. If a point matters, the sentence that makes the point is the sentence that matters.

### Marketing superlatives

Words such as revolutionary, game-changing, next-generation, world-class, cutting-edge, industry-leading, best-in-class, and seamless are not used. The architecture is described on its merits, and the reader is trusted to evaluate it.

### Telegraphic fragments

Bulleted lists may use either complete sentences or noun-phrase items, but the surrounding prose uses full sentences. A list item that begins with a verb must be a complete imperative or declarative sentence. The pattern of single-word or fragment bullets is reserved for true enumerations of names or terms.

## Content rules

### Origin story

Every introductory treatment of CNML states the origin plainly. CNML was developed under the OIML SMART program. The work consisted of analyzing every existing published OIML-CS Type Approval certificate and digitizing the resulting model in a manner compatible with OIML SMART and the relevant OIML R-Recommendations. The PDF-based OIML-CS certificate of conformity is the predecessor format that CNML succeeds.

### Relationship to DCC

CNML and the PTB Digital Calibration Certificate are complementary formats operating at different tiers of the metrology infrastructure. CNML operates at the type-approval tier under OIML-CS. DCC operates at the calibration tier under ISO/IEC 17025. The two are never described as equivalents and CNML is never called the OIML equivalent of DCC. A measuring instrument in legal use typically holds both a CNML type approval and periodic DCC calibrations.

### Organizations

The only organizations named in the writing are OIML SMART, the OIML institutional bodies (BIML, CIML, the International Conference), and the OIML-CS Issuing Authorities discussed collectively. Ribose is named only in a developed-by attribution. Confium is named only as the threshold-cryptography substrate. Specific Issuing Authorities, specific test laboratories, and specific manufacturers are not named as participants, pilots, or partners. Factual references to real OIML-registered IAs in the existing DoMC framework are acceptable in narrow technical context, but proposal documents, adoption documents, and pilot descriptions use generic selection-criteria language.

### Out-of-scope topics

The writing does not discuss finance, financial auditors, legal standing, liability frameworks, insurance, procurement, customs, environmental impact, geopolitical navigation, or comparative positioning against other frameworks such as eIDAS, FPKI, ISO 17025, WebTrust, or ETSI. These topics are outside the OIML SMART scope of CNML.

### Money

No dollar amounts, cost figures, total-cost-of-ownership models, bounty payouts, insurance figures, or liability caps appear anywhere in the writing. Hardware may be described by capability, certification level, and vendor name, but not by price.

### NIST and other evaluation programs

CNML is not associated with NIST. NIST is mentioned only where the writing cites a real NIST standard such as FIPS 203, FIPS 204, NIST SP 800-53, or the SHA-3 competition. References to NIST as auditor, evaluator, partner, submission target, or pilot participant are prohibited. The same rule applies to other national or international evaluation programs: CNML is described on its own properties, not positioned relative to external evaluations.

### Cryptographic history

Historical narratives about past PKI failures and historical narratives about specific cryptocurrency key-loss incidents are not used as motivation. The architecture is described on its own properties, not by contrast to past disasters.

### Local filesystem paths

References such as `~/src/` or `/Users/` or any local checkout path are prohibited. Cross-repository references describe the upstream project by name, for example the confium CNML-deployment specification or the OIML-CS certificates repository. Ruby code that consumes external data uses the published Ruby gem rather than a hardcoded path.

### Fabricated specifics

The writing does not invent dollar amounts, vendor partnerships, audit firms, submission timelines, evaluator relationships, or named pilot participants. Where a planning document requires a placeholder, it uses generic descriptors (the third-party audit firm, the pilot IA cohort, the post-pilot cost model) and explicitly marks the item as to be determined.

## Vocabulary conventions

### Standards and specifications

Standards are cited by their full identifier on first reference and by their short identifier thereafter. OIML R60 is the OIML Recommendation for load cells. ISO/IEC 17025 is the competence standard for testing and calibration laboratories. RFC 6962 is the IETF Certificate Transparency specification. FIPS 204 is the NIST standard for ML-DSA. WCAG 2.2 AA is the Web Content Accessibility Guidelines conformance level.

### Architectural terms

The Certificate Authority is the CA. The certificate signing request is the CSR. The certificate revocation list is the CRL. The Issuing Authority under OIML-CS is the IA. The International Bureau of Legal Metrology is the BIML. The International Committee of Legal Metrology is the CIML. Threshold cryptography terms such as FROST, BLS, ML-KEM, and ML-DSA are spelled out on first reference and abbreviated thereafter.

### Voice

The writing uses the present tense and the active voice. The form CNML provides X is preferred to the form CNML is designed to provide X or the form CNML will provide X. Future-tense constructions appear only when the writing genuinely describes work not yet implemented, and even then the writing states what the work is, not what it aims to be.

## Formatting

### Headings

Headings are sentence case. A level-one heading titles the page. Level-two headings divide the page into sections. Level-three headings appear only when a section has multiple named subsections. No heading is a question.

### Tables

Tables are used for structured comparisons of properties across systems or components. The first column names the property. Subsequent columns name the systems being compared. Cells contain noun phrases or short declarative sentences, not fragments.

### Code blocks

Code blocks identify their language. Inline code uses single backticks for filenames, identifiers, and short commands. Shell commands in code blocks use the bash fence.

### Diagrams

Diagrams are referenced from prose and described in the surrounding text. A diagram does not stand alone. The `alt` attribute on an embedded SVG states what the diagram shows in one sentence.

## Examples

### Opening sentence

Preferred. "CNML is the digital certificate format developed under the OIML SMART program to succeed the PDF-based OIML-CS certificate of conformity."

Avoided. "CNML is the OIML equivalent of PTB's DCC, a cryptographically signed XML format for type approvals." The avoided formulation positions CNML relative to another format and gets the relationship wrong. The preferred formulation states what CNML is and where it comes from.

### Paired sentences

Preferred. "PDF certificates are reproducible with consumer-grade image editing software. The widespread availability of generative image models has increased the realism of forged documents."

Avoided. "PDFs are forgeable. AI tools make it worse." The avoided formulation pairs two short sentences for rhetorical effect and reads as casual. The preferred formulation makes two substantive claims in two complete sentences.

### Em-dash replacement

Preferred. "No single party can forge a CNML certificate. Producing a valid signature requires collaboration among a configured quorum of independent signers."

Avoided. "The kicker is, no single party can forge a CNML certificate." The avoided formulation uses a conversational opener and an em-dash. The preferred formulation states the property and then explains the mechanism.

### Scope

A sentence of the form "for finance directors, CNML offers a 37 percent reduction in ten-year cost of ownership" is removed entirely. Cost of ownership is outside the OIML SMART scope of CNML and is not discussed.

## Editorial workflow

A draft is read aloud to detect em-dashes, paired sentences, and hedges. If a sentence sounds casual when spoken, it is rewritten. If a paragraph can be deleted without losing information, it is deleted. If a section makes claims about specific organizations, dollar amounts, or external programs, those claims are either sourced to a published reference or removed.

A second pass verifies that the origin story, the DCC relationship, and the scope rules are correctly stated. A third pass verifies that no prohibited pattern remains and that all standards citations are by their correct identifier.

## When in doubt

If a draft makes the writer uncertain whether a claim is real or invented, the claim is removed. Vagueness is acceptable. Invented specifics are not.
