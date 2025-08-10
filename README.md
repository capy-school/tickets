# Multilingual Linguistics Learning

A comprehensive, linguistics-focused learning hub covering 45 languages. This project emphasizes phonetics, morphology, syntax, semantics, pragmatics, orthography, and sociolinguistics—paired with practical learner materials (vocabulary decks, graded readers, dialogues, exercises, and assessments).

## Goals
- Provide parallel, consistently-structured learning tracks across 45 languages
- Emphasize linguistic insight (sound systems, grammar typology, scripts) to accelerate learning
- Offer scaffolded content from A0 to B2 with clear outcomes and assessments
- Enable community contributions for content, corrections, and translations

## Structure
- `content/` – core lessons, dialogues, vocabulary, exercises
- `linguistics/` – language profiles (phonology, morphology, syntax, semantics, pragmatics)
- `assets/` – audio, images, IPA charts, scripts, handwriting guides
- `tools/` – generation scripts, validation, QA checks
- `data/` – word lists, frequency data, lemma mappings, morphology paradigms
- `guides/` – contributor guides, style guides, language-specific notes

## Language Coverage (sample)
Arabic, Mandarin Chinese, English, Spanish, French, German, Portuguese, Russian, Japanese, Korean, Hindi, Bengali, Punjabi, Turkish, Vietnamese, Thai, Indonesian, Malay, Filipino, Swahili, Amharic, Yoruba, Hausa, Zulu, Xhosa, Afrikaans, Italian, Dutch, Polish, Czech, Slovak, Ukrainian, Romanian, Greek, Hebrew, Persian, Urdu, Tamil, Telugu, Kannada, Malayalam, Marathi, Gujarati, Nepali, Burmese, Khmer, Lao. Target: 45 total; expand via issues/PRs.

## Content Model
Each language track follows a uniform schema:
- Levels: `A0`, `A1`, `A2`, `B1`, `B2`
- Units: 8–12 per level, with learning objectives
- For each unit:
  - Lesson overview and outcomes
  - Dialogue(s) with translations and notes
  - Vocabulary list with POS, lemma, frequency band, example sentence
  - Grammar notes with typological pointers
  - Pronunciation notes with IPA, minimal pairs, prosody cues
  - Exercises (MCQ, cloze, production) with answer keys
  - Assessment (unit quiz)

## Linguistics Profiles
For each language in `linguistics/<lang>/profile.md`:
- Phonology: phoneme inventory, allophony, syllable structure, stress/tones, IPA
- Morphology: inflection, derivation, productivity, paradigm examples
- Syntax: word order, agreement, case, clause types, subordination
- Semantics & Pragmatics: polysemy, particles, implicature, politeness systems
- Orthography: script(s), grapheme-phoneme mapping, diacritics, romanization
- Sociolinguistics: registers, dialects, diglossia, code-switching

## Contribution
We welcome contributions for:
- New or improved lessons, exercises, and assessments
- Corrections to linguistics profiles
- Audio recordings and assets
- Translations of existing content into additional target languages

### How to Contribute
1. Fork the repository and create a branch: `feat/lang-xx-unit-01` or `fix/phonology-xx`
2. Follow the style guides in `guides/`
3. Validate content using `tools/validate` (see below)
4. Open a Pull Request describing scope, language, level, and unit numbers

### Content Style Guidelines (essentials)
- Use IPA for phonetic transcriptions; include minimal pairs when relevant
- Keep glossing consistent (e.g., Leipzig Glossing Rules for interlinear examples)
- Include difficulty tags and CEFR alignment
- Provide sources for claims in linguistics notes when non-obvious

## Tooling
- Validation: `tools/validate` checks schema, metadata completeness, and link integrity
- Linting: `tools/lint` checks formatting, IPA validity, and glossary consistency
- Build: `tools/build` compiles content to site/static formats

## Directory Conventions
- Language codes use ISO 639-1/2 where possible (e.g., `es`, `pt-BR`, `zh-Hans`)
- Use kebab-case for filenames; avoid spaces
- Keep media lightweight; prefer compressed audio (e.g., `opus`, `mp3` at 96–128 kbps)

## Roadmap
- Fill minimum viable tracks for 10 languages (A0–A2)
- Add B-level content and assessments
- Expand to full 45-language coverage
- Integrate TTS/ASR helpers for practice

## Licensing
Specify the license here (e.g., CC BY-SA 4.0 for content, MIT/Apache-2.0 for code). Include attribution requirements for assets where applicable.

## Acknowledgements
Thanks to linguists, teachers, and native speakers who contribute content and review.
