

# New languages

The assignment pages are set up to support multiple languages. The core of the
collection is assignments in Norwegian, where some are originally written in
Norwegian, others are translated from English. The collection can be extended to
include any language, by doing the following steps.

## Kodeklubben/oppgaver

There is a filter for given criteria. The filter follows the language being
used, and must be translated to the given language. Create a new
[filtertags](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/translation_en.yml)-file
with translations. In [[Den gode oppgaven|Den-gode-oppgaven]] (Norwegian) you
will find explanations for how the tags are being used. Give your file the name
`translation_en.yml`, where `en` is changed for the [ISO 639-1
code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the given
language.

Add the same language code in the file
[keys.yml](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/keys.yml),
so that the user may filter the assignments available in each language.

## CodeClub-viewer

The graphical user interface (GUI) must be translated, so that the user can use
the website in the correct language. You have to start by creating a _fork_ from
[CodeClub-viewer](https://github.com/kodeklubben/codeclub-viewer/) in the same
way you created one for the [[assignment repository|Komme-i-gang-med-Git]]
(Norwegian).

Now translate [the file for the
GUI](https://github.com/kodeklubben/codeclub-viewer/blob/master/src/constants/captions_en.js)
to the correct language. Save the file as `captions_en.js`, where `en` is
changed for the given ISO 639-1 code.

Finally you must upload a flag (in svg format) to symbolise the language in
[this
folder](https://github.com/kodeklubben/codeclub-viewer/tree/master/src/assets/graphics),
with the file name `flag_en.svg`. Again change `en` to the correct ISO 639-1
code. Make sure that the image file is licenced for use on the website.

## Summary

To start a new language, you have to do the following:

- Translate
  [filtertags](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/translation_en.yml).

- Add language to
  [keys](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/keys.yml).

- Translate
  [captions](https://github.com/kodeklubben/codeclub-viewer/blob/master/src/constants/captions_en.js).

- Upload flag
  [here](https://github.com/kodeklubben/codeclub-viewer/tree/master/src/assets/graphics).
