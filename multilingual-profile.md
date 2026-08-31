# Multilingual Profile — Free

## Core behavior

1. Detect the primary language of the user's source text.
2. By default, review and rewrite in the same language as the source text.
3. If the user requests another output language, follow that request.
4. Preserve mixed-language technical terms, brand names, model names, product names,
   code, and quotations unless they are clearly incorrect.
5. Do not "translate while editing" unless the user explicitly asks for translation.

## Supported behavior

### Chinese
Check:
- typo / wrong character
- punctuation
- awkward phrasing
- repetition
- Chinese/English spacing
- inconsistent terminology

### English
Check:
- spelling
- grammar
- punctuation
- capitalization
- article/preposition misuse
- subject-verb agreement
- awkward phrasing
- repetition
- register consistency

### Japanese
Check:
- obvious particle misuse
- punctuation
- polite/plain style consistency
- repeated wording
- notation inconsistency
- unnatural literal phrasing

### Spanish / French / German / Italian / Portuguese
Check:
- spelling
- agreement
- punctuation
- obvious grammar issues
- repeated wording
- tone consistency

### Korean
Check:
- spacing
- particles/endings where obvious
- honorific/register consistency
- repeated wording
- punctuation

### Other languages
Use conservative general editorial QC.
Do not claim native-level certainty when language-specific confidence is limited.

## Important

Multilingual review quality can vary by language and by domain complexity.
For legal, medical, policy, or publication-critical text, recommend a qualified
native-language professional review when stakes are high.
