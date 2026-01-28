## FontSpector report

fontspector version: 1.4.0






## Check results




<details><summary>[15] fonts/ttf/GeistPixel-Circle.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current                | Expected                       |
|----------------------------|------------------------|--------------------------------|
| Family Name                | Geist Pixel Circle     | Geist Pixel Circle             |
| Subfamily Name             | Regular                | Regular                        |
| Full Name                  | **Geist Pixel Circle** | **Geist Pixel Circle Regular** |
| Postscript Name            | **GeistPixel-Circle**  | **GeistPixelCircle-Regular**   |
| Typographic Family Name    | **Geist Pixel**        | **N/A**                        |
| Typographic Subfamily Name | **Circle**             | **N/A**                        | [code: bad-names]
  
  


- ⚠️ **WARN** Regular missing from full name [code: lacks-regular]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- 🔥 **FAIL** Please specify which languages and scripts this font supports. [code: missing-slng-tag]
  
  

  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* C (U+0043): found 88, expected one of: {5, 1, 2}
* Cacute (U+0106): found 97, expected one of: {3, 2, 6}
* Ccaron (U+010C): found 102, expected one of: {6, 2, 3}
* Cdotaccent (U+010A): found 94, expected one of: {2, 6, 3}
* uni018F (U+018F): found 118, expected one of: {2, 1}
* uni1E20 (U+1E20): found 123, expected one of: {3, 2, 4}
* I (U+0049): found 38, expected one of: {1, 2, 3}
* Iacute (U+00CD): found 47, expected one of: {2, 3, 4}
* Idotaccent (U+0130): found 44, expected one of: {3, 2, 6}
* Igrave (U+00CC): found 47, expected one of: {2, 3, 4}
* Imacron (U+012A): found 54, expected one of: {2, 6, 3}
* Itilde (U+0128): found 52, expected one of: {2, 6, 3}
* J (U+004A): found 59, expected one of: {3, 1, 2}
* S (U+0053): found 96, expected one of: {2, 5, 1}
* Sacute (U+015A): found 105, expected one of: {3, 2, 6}
* U (U+0055): found 86, expected one of: {5, 1, 2}
* Uacute (U+00DA): found 95, expected one of: {3, 2, 6}
* Ugrave (U+00D9): found 95, expected one of: {3, 6, 2}
* Uhungarumlaut (U+0170): found 104, expected one of: {3, 7, 4}
* Umacron (U+016A): found 102, expected one of: {3, 2, 6}
* Utilde (U+0168): found 100, expected one of: {6, 2, 3}
* V (U+0056): found 72, expected one of: {1, 2, 5}
* Zacute (U+0179): found 105, expected one of: {4, 6, 2}
* Zdotaccent (U+017B): found 102, expected one of: {4, 2, 6}
* uniA78B (U+A78B): found 20, expected one of: {1}
* uni013B.loclMAH (unencoded): found 66, expected one of: {4, 2, 8}
* uni0145.loclMAH (unencoded): found 115, expected one of: {2, 3}
* c (U+0063): found 66, expected one of: {3, 1, 5}
* cacute (U+0107): found 75, expected one of: {6, 2, 3}
* ccaron (U+010D): found 80, expected one of: {3, 6, 2}
* ccedilla (U+00E7): found 83, expected one of: {1, 2, 6}
* cdotaccent (U+010B): found 72, expected one of: {6, 2, 3}
* e (U+0065): found 85, expected one of: {5, 1, 2}
* eacute (U+00E9): found 94, expected one of: {3, 2, 6}
* ecaron (U+011B): found 99, expected one of: {2, 6, 3}
* ecircumflex (U+00EA): found 99, expected one of: {3, 2, 6}
* edieresis (U+00EB): found 97, expected one of: {3, 7, 4}
* edotaccent (U+0117): found 91, expected one of: {6, 3, 2}
* egrave (U+00E8): found 94, expected one of: {2, 3, 6}
* emacron (U+0113): found 101, expected one of: {2, 3, 6}
* uni1EBD (U+1EBD): found 99, expected one of: {6, 3, 2}
* uni0259 (U+0259): found 85, expected one of: {1, 2}
* dotlessi (U+0131): found 46, expected one of: {2, 1}
* iacute (U+00ED): found 55, expected one of: {3, 2, 6}
* icircumflex (U+00EE): found 60, expected one of: {2, 3, 6}
* idieresis (U+00EF): found 58, expected one of: {4, 3, 7}
* i.loclTRK (unencoded): found 52, expected one of: {3, 2}
* igrave (U+00EC): found 55, expected one of: {2, 6, 3}
* imacron (U+012B): found 62, expected one of: {6, 2}
* itilde (U+0129): found 60, expected one of: {2, 3, 6}
* uni0237 (U+0237): found 45, expected one of: {2, 3, 1}
* l (U+006C): found 53, expected one of: {6, 2, 1}
* lacute (U+013A): found 62, expected one of: {6, 3, 2}
* lcaron (U+013E): found 66, expected one of: {2, 3, 6}
* uni013C (U+013C): found 61, expected one of: {2, 3, 6}
* n (U+006E): found 66, expected one of: {1, 2, 5}
* nacute (U+0144): found 75, expected one of: {3, 6, 2}
* ntilde (U+00F1): found 80, expected one of: {6, 2, 3}
* ocircumflex (U+00F4): found 86, expected one of: {3, 7, 4}
* odieresis (U+00F6): found 84, expected one of: {8, 4, 5}
* ohungarumlaut (U+0151): found 90, expected one of: {4, 8, 5}
* omacron (U+014D): found 88, expected one of: {3, 7, 2}
* otilde (U+00F5): found 86, expected one of: {3, 4, 7}
* r (U+0072): found 50, expected one of: {1, 3, 2}
* racute (U+0155): found 59, expected one of: {2, 3, 6}
* rcaron (U+0159): found 64, expected one of: {6, 2, 3}
* s (U+0073): found 72, expected one of: {3, 1, 2}
* sacute (U+015B): found 81, expected one of: {3, 6, 2}
* germandbls (U+00DF): found 93, expected one of: {5, 1, 2}
* t (U+0074): found 51, expected one of: {2, 1, 3}
* tcaron (U+0165): found 64, expected one of: {2, 3, 6}
* u (U+0075): found 64, expected one of: {2, 5, 1}
* uacute (U+00FA): found 73, expected one of: {3, 2, 6}
* ucircumflex (U+00FB): found 78, expected one of: {6, 2, 3}
* udieresis (U+00FC): found 76, expected one of: {4, 3, 7}
* ugrave (U+00F9): found 73, expected one of: {6, 2, 3}
* uhungarumlaut (U+0171): found 82, expected one of: {4, 7, 3}
* umacron (U+016B): found 80, expected one of: {6, 2, 3}
* uring (U+016F): found 80, expected one of: {3, 7, 4}
* utilde (U+0169): found 78, expected one of: {6, 2, 3}
* v (U+0076): found 54, expected one of: {2, 5, 1}
* yacute (U+00FD): found 78, expected one of: {3, 2, 6}
* ygrave (U+1EF3): found 78, expected one of: {3, 6, 2}
* uni1EF9 (U+1EF9): found 83, expected one of: {6, 3, 2}
* z (U+007A): found 73, expected one of: {3, 1, 2}
* uniA78C (U+A78C): found 14, expected one of: {1}
* aacute.ss02 (unencoded): found 87, expected one of: {3, 2, 4}
* abreve.ss02 (unencoded): found 90, expected one of: {2, 3}
* acircumflex.ss02 (unencoded): found 92, expected one of: {4, 3, 2}
* adieresis.ss02 (unencoded): found 90, expected one of: {3, 4, 5}
* agrave.ss02 (unencoded): found 87, expected one of: {2, 3, 4}
* amacron.ss02 (unencoded): found 94, expected one of: {3, 2, 4}
* aogonek.ss02 (unencoded): found 93, expected one of: {3, 2, 4}
* aring.ss02 (unencoded): found 94, expected one of: {5, 3, 4}
* atilde.ss02 (unencoded): found 92, expected one of: {3, 2, 4}
* l.ss03 (unencoded): found 47, expected one of: {3, 1, 2}
* lacute.ss03 (unencoded): found 56, expected one of: {3, 4, 2}
* lcaron.ss03 (unencoded): found 60, expected one of: {4, 3, 2}
* uni013C.ss03 (unencoded): found 55, expected one of: {2, 3}
* Lambda (U+039B): found 74, expected one of: {1, 3}
* uni03A9 (U+03A9): found 106, expected one of: {3, 1}
* lambda (U+03BB): found 70, expected one of: {2, 1}
* uni03BC (U+03BC): found 77, expected one of: {1, 3, 2}
* pi (U+03C0): found 79, expected one of: {1, 3}
* one (U+0031): found 60, expected one of: {5, 1, 2}
* two (U+0032): found 90, expected one of: {5, 1, 2}
* three (U+0033): found 83, expected one of: {1, 5, 2}
* five (U+0035): found 89, expected one of: {5, 2, 1}
* six (U+0036): found 100, expected one of: {5, 2, 1}
* seven (U+0037): found 64, expected one of: {1, 2, 5}
* nine (U+0039): found 100, expected one of: {5, 1, 2}
* four.dnom (unencoded): found 39, expected one of: {3, 2, 1}
* three.numr (unencoded): found 36, expected one of: {1, 3, 2}
* fraction (U+2044): found 38, expected one of: {1}
* onehalf (U+00BD): found 98, expected one of: {3, 4, 5}
* uni00B9 (U+00B9): found 22, expected one of: {1, 2}
* uni00B2 (U+00B2): found 38, expected one of: {1, 2}
* uni00B3 (U+00B3): found 36, expected one of: {1, 2}
* period (U+002E): found 9, expected one of: {5, 1}
* comma (U+002C): found 15, expected one of: {1, 2}
* colon (U+003A): found 18, expected one of: {6, 2}
* semicolon (U+003B): found 24, expected one of: {6, 2}
* ellipsis (U+2026): found 27, expected one of: {3, 7}
* exclam (U+0021): found 32, expected one of: {2, 6}
* exclamdown (U+00A1): found 32, expected one of: {6, 2}
* question (U+003F): found 57, expected one of: {3, 2, 6}
* questiondown (U+00BF): found 57, expected one of: {6, 3, 2}
* periodcentered (U+00B7): found 9, expected one of: {1, 5}
* bullet (U+2022): found 32, expected one of: {1, 5}
* numbersign (U+0023): found 106, expected one of: {2, 6, 4}
* slash (U+002F): found 48, expected one of: {5, 1}
* backslash (U+005C): found 48, expected one of: {5, 1}
* hyphen (U+002D): found 16, expected one of: {1}
* endash (U+2013): found 22, expected one of: {1}
* emdash (U+2014): found 32, expected one of: {1}
* underscore (U+005F): found 24, expected one of: {1}
* uni301C (U+301C): found 40, expected one of: {1}
* parenleft (U+0028): found 50, expected one of: {1, 5}
* parenright (U+0029): found 50, expected one of: {5, 1}
* braceleft (U+007B): found 60, expected one of: {1, 5, 2}
* braceright (U+007D): found 60, expected one of: {1, 5, 2}
* bracketleft (U+005B): found 62, expected one of: {5, 1, 3}
* bracketright (U+005D): found 62, expected one of: {5, 1, 3}
* quotesinglbase (U+201A): found 12, expected one of: {2, 1}
* quotedblbase (U+201E): found 24, expected one of: {2, 6}
* quotedblleft (U+201C): found 24, expected one of: {6, 2}
* quotedblright (U+201D): found 24, expected one of: {2, 6}
* quoteleft (U+2018): found 12, expected one of: {1, 2}
* quoteright (U+2019): found 12, expected one of: {2, 1}
* guillemotleft (U+00AB): found 60, expected one of: {2, 6}
* guillemotright (U+00BB): found 60, expected one of: {2, 6}
* guilsinglleft (U+2039): found 30, expected one of: {5, 1}
* guilsinglright (U+203A): found 30, expected one of: {5, 1}
* quotedbl (U+0022): found 28, expected one of: {6, 2}
* quotesingle (U+0027): found 14, expected one of: {1, 5}
* florin (U+0192): found 66, expected one of: {2, 1}
* section (U+00A7): found 111, expected one of: {6, 4, 2}
* uni2117 (U+2117): found 55, expected one of: {3, 4}
* degree (U+00B0): found 40, expected one of: {2, 6}
* minute (U+2032): found 12, expected one of: {1, 5}
* second (U+2033): found 24, expected one of: {6, 2}
* bar (U+007C): found 46, expected one of: {1}
* brokenbar (U+00A6): found 36, expected one of: {2}
* dagger (U+2020): found 54, expected one of: {2, 4, 1}
* uni2120 (U+2120): found 55, expected one of: {3, 2}
* cent (U+00A2): found 98, expected one of: {1, 3, 2}
* currency (U+00A4): found 88, expected one of: {6, 2}
* plus (U+002B): found 44, expected one of: {1, 2}
* minus (U+2212): found 22, expected one of: {1}
* multiply (U+00D7): found 57, expected one of: {1, 2}
* divide (U+00F7): found 36, expected one of: {3, 7}
* equal (U+003D): found 48, expected one of: {6, 2}
* notequal (U+2260): found 72, expected one of: {1, 3, 7}
* greater (U+003E): found 46, expected one of: {2, 1}
* less (U+003C): found 46, expected one of: {1, 2}
* greaterequal (U+2265): found 70, expected one of: {2, 6, 3}
* lessequal (U+2264): found 70, expected one of: {6, 3, 2}
* plusminus (U+00B1): found 68, expected one of: {2, 3, 1}
* approxequal (U+2248): found 66, expected one of: {2, 6}
* asciitilde (U+007E): found 33, expected one of: {1, 5}
* logicalnot (U+00AC): found 30, expected one of: {2, 1}
* asciicircum (U+005E): found 30, expected one of: {1, 2}
* infinity (U+221E): found 84, expected one of: {1, 2, 3}
* integral (U+222B): found 52, expected one of: {1, 5}
* uni2206 (U+2206): found 98, expected one of: {3, 2}
* product (U+220F): found 114, expected one of: {3, 5, 1}
* summation (U+2211): found 82, expected one of: {1, 2}
* radical (U+221A): found 77, expected one of: {1, 2}
* uni00B5 (U+00B5): found 78, expected one of: {2, 3, 1}
* partialdiff (U+2202): found 82, expected one of: {1, 2}
* arrowup (U+2191): found 76, expected one of: {2, 1}
* uni2197 (U+2197): found 75, expected one of: {1, 2}
* arrowright (U+2192): found 76, expected one of: {1, 2}
* uni2198 (U+2198): found 75, expected one of: {2, 1}
* arrowdown (U+2193): found 76, expected one of: {2, 1}
* uni2199 (U+2199): found 75, expected one of: {2, 1}
* arrowleft (U+2190): found 76, expected one of: {2, 1}
* uni2196 (U+2196): found 75, expected one of: {2, 1}
* arrowboth (U+2194): found 92, expected one of: {3, 1, 2}
* arrowupdn (U+2195): found 92, expected one of: {1, 3, 2}
* uni21E4 (U+21E4): found 64, expected one of: {3, 1, 2}
* uni21E5 (U+21E5): found 64, expected one of: {3, 1, 2}
* uni21A9 (U+21A9): found 83, expected one of: {2, 1}
* uni21AA (U+21AA): found 83, expected one of: {1, 2}
* uni21B0 (U+21B0): found 62, expected one of: {3, 1, 2}
* uni21B1 (U+21B1): found 62, expected one of: {2, 3, 1}
* uni21B4 (U+21B4): found 62, expected one of: {2, 3, 1}
* carriagereturn (U+21B5): found 62, expected one of: {1, 2, 3}
* uni21E7 (U+21E7): found 114, expected one of: {2}
* lozenge (U+25CA): found 72, expected one of: {2}
* uni0308 (U+0308): found 12, expected one of: {2}
* uni0307 (U+0307): found 6, expected one of: {1}
* gravecomb (U+0300): found 9, expected one of: {1}
* acutecomb (U+0301): found 9, expected one of: {1}
* uni030B (U+030B): found 18, expected one of: {2}
* uni030C.alt (unencoded): found 13, expected one of: {3, 1}
* uni0302 (U+0302): found 14, expected one of: {1}
* uni030C (U+030C): found 14, expected one of: {1}
* uni0306 (U+0306): found 12, expected one of: {1}
* uni030A (U+030A): found 16, expected one of: {2}
* tildecomb (U+0303): found 14, expected one of: {1}
* uni0304 (U+0304): found 16, expected one of: {1}
* uni0312 (U+0312): found 8, expected one of: {1}
* uni0326 (U+0326): found 8, expected one of: {1}
* uni0326.loclMAH (unencoded): found 8, expected one of: {1, 0, 2}
* uni0327 (U+0327): found 17, expected one of: {1}
* uni0328 (U+0328): found 15, expected one of: {1}
* dieresis (U+00A8): found 12, expected one of: {2}
* dotaccent (U+02D9): found 6, expected one of: {1}
* grave (U+0060): found 9, expected one of: {1}
* acute (U+00B4): found 9, expected one of: {1}
* hungarumlaut (U+02DD): found 18, expected one of: {2}
* circumflex (U+02C6): found 14, expected one of: {1, 5}
* caron (U+02C7): found 14, expected one of: {1, 5}
* breve (U+02D8): found 12, expected one of: {1}
* ring (U+02DA): found 16, expected one of: {2, 6}
* tilde (U+02DC): found 14, expected one of: {1}
* macron (U+00AF): found 16, expected one of: {1}
* cedilla (U+00B8): found 17, expected one of: {5, 1}
* ogonek (U+02DB): found 15, expected one of: {1}
* uni02BB (U+02BB): found 8, expected one of: {1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 532 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=494: multiply, minus, logicalnot
width=570: approxequal
width=608: greaterequal, notequal, lessequal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* vercelLogo [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̂
* į̄
* į̌
* į́
* į̃
* į̀The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̦̊
* į̦̈
* į̦̂
* į̦̄
* į̦̌
* į̦̒
* į̦́
* į̦̃
* į̦̆
* į̦̋
* į̦̇
* į̦̀
* į̧̊
* į̧̈
* į̧̂
* į̧̄
* į̧̌
* į̧̒
* į̧́
* į̧̃
* į̧̆
* į̧̋
* į̧̇
* į̧̀
* į̨̊
* į̨̈
* į̨̂
* į̨̄
* į̨̌
* į̨̒
* į̨́
* į̨̃
* į̨̆
* į̨̋
* į̨̇
* į̨̀
* į̊
* į̈
* į̒
* į̆
* į̋
* į̇ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - eogonek (U+0119): X=399,Y=1 (should be at baseline 0?)
* - eogonek (U+0119): X=399,Y=1 (should be at baseline 0?)
* - eogonek (U+0119): X=399,Y=1 (should be at baseline 0?)
* - ohungarumlaut (U+0151): X=437,Y=723 (should be at cap-height 722?)
* - ohungarumlaut (U+0151): X=399,Y=723 (should be at cap-height 722?)
* - ohungarumlaut (U+0151): X=475,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=437,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=399,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=475,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=361,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=323,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=399,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=361,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=323,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=399,Y=723 (should be at cap-height 722?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* Aogonek (U+0104): Quad(QuadBez { p0: (551.0, 0.0), p1: (532.0, 0.0), p2: (532.0, 19.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Quad(QuadBez { p0: (532.0, 19.0), p1: (532.0, 38.0), p2: (551.0, 38.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Quad(QuadBez { p0: (551.0, 38.0), p1: (570.0, 38.0), p2: (570.0, 19.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Quad(QuadBez { p0: (570.0, 19.0), p1: (570.0, 0.0), p2: (551.0, 0.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Quad(QuadBez { p0: (513.0, 0.0), p1: (494.0, 0.0), p2: (494.0, 19.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Quad(QuadBez { p0: (494.0, 19.0), p1: (494.0, 38.0), p2: (513.0, 38.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Quad(QuadBez { p0: (513.0, 38.0), p1: (532.0, 38.0), p2: (532.0, 19.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Quad(QuadBez { p0: (532.0, 19.0), p1: (532.0, 0.0), p2: (513.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Quad(QuadBez { p0: (133.0, 0.0), p1: (114.0, 0.0), p2: (114.0, 19.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Quad(QuadBez { p0: (114.0, 19.0), p1: (114.0, 38.0), p2: (133.0, 38.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Quad(QuadBez { p0: (133.0, 38.0), p1: (152.0, 38.0), p2: (152.0, 19.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Quad(QuadBez { p0: (152.0, 19.0), p1: (152.0, 0.0), p2: (133.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Quad(QuadBez { p0: (323.0, 0.0), p1: (304.0, 0.0), p2: (304.0, 19.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Quad(QuadBez { p0: (304.0, 19.0), p1: (304.0, 38.0), p2: (323.0, 38.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Quad(QuadBez { p0: (323.0, 38.0), p1: (342.0, 38.0), p2: (342.0, 19.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Quad(QuadBez { p0: (342.0, 19.0), p1: (342.0, 0.0), p2: (323.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Quad(QuadBez { p0: (513.0, 0.0), p1: (494.0, 0.0), p2: (494.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Quad(QuadBez { p0: (494.0, 19.0), p1: (494.0, 38.0), p2: (513.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Quad(QuadBez { p0: (513.0, 38.0), p1: (532.0, 38.0), p2: (532.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Quad(QuadBez { p0: (532.0, 19.0), p1: (532.0, 0.0), p2: (513.0, 0.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Quad(QuadBez { p0: (323.0, 0.0), p1: (304.0, 0.0), p2: (304.0, 19.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Quad(QuadBez { p0: (304.0, 19.0), p1: (304.0, 38.0), p2: (323.0, 38.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Quad(QuadBez { p0: (323.0, 38.0), p1: (342.0, 38.0), p2: (342.0, 19.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Quad(QuadBez { p0: (342.0, 19.0), p1: (342.0, 0.0), p2: (323.0, 0.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Quad(QuadBez { p0: (437.0, 0.0), p1: (418.0, 0.0), p2: (418.0, 19.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Quad(QuadBez { p0: (418.0, 19.0), p1: (418.0, 38.0), p2: (437.0, 38.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Quad(QuadBez { p0: (437.0, 38.0), p1: (456.0, 38.0), p2: (456.0, 19.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Quad(QuadBez { p0: (456.0, 19.0), p1: (456.0, 0.0), p2: (437.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Quad(QuadBez { p0: (475.0, 0.0), p1: (456.0, 0.0), p2: (456.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Quad(QuadBez { p0: (456.0, 19.0), p1: (456.0, 38.0), p2: (475.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Quad(QuadBez { p0: (475.0, 38.0), p1: (494.0, 38.0), p2: (494.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Quad(QuadBez { p0: (494.0, 19.0), p1: (494.0, 0.0), p2: (475.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Quad(QuadBez { p0: (475.0, 0.0), p1: (456.0, 0.0), p2: (456.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Quad(QuadBez { p0: (456.0, 19.0), p1: (456.0, 38.0), p2: (475.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Quad(QuadBez { p0: (475.0, 38.0), p1: (494.0, 38.0), p2: (494.0, 19.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Quad(QuadBez { p0: (494.0, 19.0), p1: (494.0, 0.0), p2: (475.0, 0.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'VRCL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[15] fonts/ttf/GeistPixel-Triangle.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current                  | Expected                         |
|----------------------------|--------------------------|----------------------------------|
| Family Name                | Geist Pixel Triangle     | Geist Pixel Triangle             |
| Subfamily Name             | Regular                  | Regular                          |
| Full Name                  | **Geist Pixel Triangle** | **Geist Pixel Triangle Regular** |
| Postscript Name            | **GeistPixel-Triangle**  | **GeistPixelTriangle-Regular**   |
| Typographic Family Name    | **Geist Pixel**          | **N/A**                          |
| Typographic Subfamily Name | **Triangle**             | **N/A**                          | [code: bad-names]
  
  


- ⚠️ **WARN** Regular missing from full name [code: lacks-regular]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- 🔥 **FAIL** Please specify which languages and scripts this font supports. [code: missing-slng-tag]
  
  

  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* C (U+0043): found 88, expected one of: {5, 1, 2}
* Cacute (U+0106): found 97, expected one of: {3, 2, 6}
* Ccaron (U+010C): found 102, expected one of: {6, 2, 3}
* Cdotaccent (U+010A): found 94, expected one of: {2, 6, 3}
* uni018F (U+018F): found 118, expected one of: {2, 1}
* uni1E20 (U+1E20): found 123, expected one of: {3, 2, 4}
* I (U+0049): found 38, expected one of: {1, 2, 3}
* Iacute (U+00CD): found 47, expected one of: {2, 3, 4}
* Idotaccent (U+0130): found 44, expected one of: {3, 2, 6}
* Igrave (U+00CC): found 47, expected one of: {2, 3, 4}
* Imacron (U+012A): found 54, expected one of: {2, 6, 3}
* Itilde (U+0128): found 52, expected one of: {2, 6, 3}
* J (U+004A): found 59, expected one of: {3, 1, 2}
* S (U+0053): found 96, expected one of: {2, 5, 1}
* Sacute (U+015A): found 105, expected one of: {3, 2, 6}
* U (U+0055): found 86, expected one of: {5, 1, 2}
* Uacute (U+00DA): found 95, expected one of: {3, 2, 6}
* Ugrave (U+00D9): found 95, expected one of: {3, 6, 2}
* Uhungarumlaut (U+0170): found 104, expected one of: {3, 7, 4}
* Umacron (U+016A): found 102, expected one of: {3, 2, 6}
* Utilde (U+0168): found 100, expected one of: {6, 2, 3}
* V (U+0056): found 72, expected one of: {1, 2, 5}
* Zacute (U+0179): found 105, expected one of: {4, 6, 2}
* Zdotaccent (U+017B): found 102, expected one of: {4, 2, 6}
* uniA78B (U+A78B): found 20, expected one of: {1}
* uni013B.loclMAH (unencoded): found 66, expected one of: {4, 2, 8}
* uni0145.loclMAH (unencoded): found 115, expected one of: {2, 3}
* c (U+0063): found 66, expected one of: {3, 1, 5}
* cacute (U+0107): found 75, expected one of: {6, 2, 3}
* ccaron (U+010D): found 80, expected one of: {3, 6, 2}
* ccedilla (U+00E7): found 83, expected one of: {1, 2, 6}
* cdotaccent (U+010B): found 72, expected one of: {6, 2, 3}
* e (U+0065): found 85, expected one of: {5, 1, 2}
* eacute (U+00E9): found 94, expected one of: {3, 2, 6}
* ecaron (U+011B): found 99, expected one of: {2, 6, 3}
* ecircumflex (U+00EA): found 99, expected one of: {3, 2, 6}
* edieresis (U+00EB): found 97, expected one of: {3, 7, 4}
* edotaccent (U+0117): found 91, expected one of: {6, 3, 2}
* egrave (U+00E8): found 94, expected one of: {2, 3, 6}
* emacron (U+0113): found 101, expected one of: {2, 3, 6}
* uni1EBD (U+1EBD): found 99, expected one of: {6, 3, 2}
* uni0259 (U+0259): found 85, expected one of: {1, 2}
* dotlessi (U+0131): found 46, expected one of: {2, 1}
* iacute (U+00ED): found 55, expected one of: {3, 2, 6}
* icircumflex (U+00EE): found 60, expected one of: {2, 3, 6}
* idieresis (U+00EF): found 58, expected one of: {4, 3, 7}
* i.loclTRK (unencoded): found 52, expected one of: {3, 2}
* igrave (U+00EC): found 55, expected one of: {2, 6, 3}
* imacron (U+012B): found 62, expected one of: {6, 2}
* itilde (U+0129): found 60, expected one of: {2, 3, 6}
* uni0237 (U+0237): found 45, expected one of: {2, 3, 1}
* l (U+006C): found 53, expected one of: {6, 2, 1}
* lacute (U+013A): found 62, expected one of: {6, 3, 2}
* lcaron (U+013E): found 66, expected one of: {2, 3, 6}
* uni013C (U+013C): found 61, expected one of: {2, 3, 6}
* n (U+006E): found 66, expected one of: {1, 2, 5}
* nacute (U+0144): found 75, expected one of: {3, 6, 2}
* ntilde (U+00F1): found 80, expected one of: {6, 2, 3}
* ocircumflex (U+00F4): found 86, expected one of: {3, 7, 4}
* odieresis (U+00F6): found 84, expected one of: {8, 4, 5}
* ohungarumlaut (U+0151): found 90, expected one of: {4, 8, 5}
* omacron (U+014D): found 88, expected one of: {3, 7, 2}
* otilde (U+00F5): found 86, expected one of: {3, 4, 7}
* r (U+0072): found 50, expected one of: {1, 3, 2}
* racute (U+0155): found 59, expected one of: {2, 3, 6}
* rcaron (U+0159): found 64, expected one of: {6, 2, 3}
* s (U+0073): found 72, expected one of: {3, 1, 2}
* sacute (U+015B): found 81, expected one of: {3, 6, 2}
* germandbls (U+00DF): found 93, expected one of: {5, 1, 2}
* t (U+0074): found 51, expected one of: {2, 1, 3}
* tcaron (U+0165): found 64, expected one of: {2, 3, 6}
* u (U+0075): found 64, expected one of: {2, 5, 1}
* uacute (U+00FA): found 73, expected one of: {3, 2, 6}
* ucircumflex (U+00FB): found 78, expected one of: {6, 2, 3}
* udieresis (U+00FC): found 76, expected one of: {4, 3, 7}
* ugrave (U+00F9): found 73, expected one of: {6, 2, 3}
* uhungarumlaut (U+0171): found 82, expected one of: {4, 7, 3}
* umacron (U+016B): found 80, expected one of: {6, 2, 3}
* uring (U+016F): found 80, expected one of: {3, 7, 4}
* utilde (U+0169): found 78, expected one of: {6, 2, 3}
* v (U+0076): found 54, expected one of: {2, 5, 1}
* yacute (U+00FD): found 78, expected one of: {3, 2, 6}
* ygrave (U+1EF3): found 78, expected one of: {3, 6, 2}
* uni1EF9 (U+1EF9): found 83, expected one of: {6, 3, 2}
* z (U+007A): found 73, expected one of: {3, 1, 2}
* uniA78C (U+A78C): found 14, expected one of: {1}
* aacute.ss02 (unencoded): found 87, expected one of: {3, 2, 4}
* abreve.ss02 (unencoded): found 90, expected one of: {2, 3}
* acircumflex.ss02 (unencoded): found 92, expected one of: {4, 3, 2}
* adieresis.ss02 (unencoded): found 90, expected one of: {3, 4, 5}
* agrave.ss02 (unencoded): found 87, expected one of: {2, 3, 4}
* amacron.ss02 (unencoded): found 94, expected one of: {3, 2, 4}
* aogonek.ss02 (unencoded): found 93, expected one of: {3, 2, 4}
* aring.ss02 (unencoded): found 94, expected one of: {5, 3, 4}
* atilde.ss02 (unencoded): found 92, expected one of: {3, 2, 4}
* l.ss03 (unencoded): found 47, expected one of: {3, 1, 2}
* lacute.ss03 (unencoded): found 56, expected one of: {3, 4, 2}
* lcaron.ss03 (unencoded): found 60, expected one of: {4, 3, 2}
* uni013C.ss03 (unencoded): found 55, expected one of: {2, 3}
* Lambda (U+039B): found 74, expected one of: {1, 3}
* uni03A9 (U+03A9): found 106, expected one of: {3, 1}
* lambda (U+03BB): found 70, expected one of: {2, 1}
* uni03BC (U+03BC): found 77, expected one of: {1, 3, 2}
* pi (U+03C0): found 79, expected one of: {1, 3}
* one (U+0031): found 60, expected one of: {5, 1, 2}
* two (U+0032): found 90, expected one of: {5, 1, 2}
* three (U+0033): found 83, expected one of: {1, 5, 2}
* five (U+0035): found 89, expected one of: {5, 2, 1}
* six (U+0036): found 100, expected one of: {5, 2, 1}
* seven (U+0037): found 64, expected one of: {1, 2, 5}
* nine (U+0039): found 100, expected one of: {5, 1, 2}
* four.dnom (unencoded): found 39, expected one of: {3, 2, 1}
* three.numr (unencoded): found 36, expected one of: {1, 3, 2}
* fraction (U+2044): found 38, expected one of: {1}
* onehalf (U+00BD): found 98, expected one of: {3, 4, 5}
* uni00B9 (U+00B9): found 22, expected one of: {1, 2}
* uni00B2 (U+00B2): found 38, expected one of: {1, 2}
* uni00B3 (U+00B3): found 36, expected one of: {1, 2}
* period (U+002E): found 9, expected one of: {5, 1}
* comma (U+002C): found 15, expected one of: {1, 2}
* colon (U+003A): found 18, expected one of: {6, 2}
* semicolon (U+003B): found 24, expected one of: {6, 2}
* ellipsis (U+2026): found 27, expected one of: {3, 7}
* exclam (U+0021): found 32, expected one of: {2, 6}
* exclamdown (U+00A1): found 32, expected one of: {6, 2}
* question (U+003F): found 57, expected one of: {3, 2, 6}
* questiondown (U+00BF): found 57, expected one of: {6, 3, 2}
* periodcentered (U+00B7): found 9, expected one of: {1, 5}
* bullet (U+2022): found 32, expected one of: {1, 5}
* numbersign (U+0023): found 106, expected one of: {2, 6, 4}
* slash (U+002F): found 48, expected one of: {5, 1}
* backslash (U+005C): found 48, expected one of: {5, 1}
* hyphen (U+002D): found 16, expected one of: {1}
* endash (U+2013): found 22, expected one of: {1}
* emdash (U+2014): found 32, expected one of: {1}
* underscore (U+005F): found 24, expected one of: {1}
* uni301C (U+301C): found 40, expected one of: {1}
* parenleft (U+0028): found 50, expected one of: {1, 5}
* parenright (U+0029): found 50, expected one of: {5, 1}
* braceleft (U+007B): found 60, expected one of: {1, 5, 2}
* braceright (U+007D): found 60, expected one of: {1, 5, 2}
* bracketleft (U+005B): found 62, expected one of: {5, 1, 3}
* bracketright (U+005D): found 62, expected one of: {5, 1, 3}
* quotesinglbase (U+201A): found 12, expected one of: {2, 1}
* quotedblbase (U+201E): found 24, expected one of: {2, 6}
* quotedblleft (U+201C): found 24, expected one of: {6, 2}
* quotedblright (U+201D): found 24, expected one of: {2, 6}
* quoteleft (U+2018): found 12, expected one of: {1, 2}
* quoteright (U+2019): found 12, expected one of: {2, 1}
* guillemotleft (U+00AB): found 60, expected one of: {2, 6}
* guillemotright (U+00BB): found 60, expected one of: {2, 6}
* guilsinglleft (U+2039): found 30, expected one of: {5, 1}
* guilsinglright (U+203A): found 30, expected one of: {5, 1}
* quotedbl (U+0022): found 28, expected one of: {6, 2}
* quotesingle (U+0027): found 14, expected one of: {1, 5}
* florin (U+0192): found 66, expected one of: {2, 1}
* section (U+00A7): found 111, expected one of: {6, 4, 2}
* uni2117 (U+2117): found 55, expected one of: {3, 4}
* degree (U+00B0): found 40, expected one of: {2, 6}
* minute (U+2032): found 12, expected one of: {1, 5}
* second (U+2033): found 24, expected one of: {6, 2}
* bar (U+007C): found 46, expected one of: {1}
* brokenbar (U+00A6): found 36, expected one of: {2}
* dagger (U+2020): found 54, expected one of: {2, 4, 1}
* uni2120 (U+2120): found 55, expected one of: {3, 2}
* cent (U+00A2): found 98, expected one of: {1, 3, 2}
* currency (U+00A4): found 88, expected one of: {6, 2}
* plus (U+002B): found 44, expected one of: {1, 2}
* minus (U+2212): found 22, expected one of: {1}
* multiply (U+00D7): found 57, expected one of: {1, 2}
* divide (U+00F7): found 36, expected one of: {3, 7}
* equal (U+003D): found 48, expected one of: {6, 2}
* notequal (U+2260): found 72, expected one of: {1, 3, 7}
* greater (U+003E): found 46, expected one of: {2, 1}
* less (U+003C): found 46, expected one of: {1, 2}
* greaterequal (U+2265): found 70, expected one of: {2, 6, 3}
* lessequal (U+2264): found 70, expected one of: {6, 3, 2}
* plusminus (U+00B1): found 68, expected one of: {2, 3, 1}
* approxequal (U+2248): found 66, expected one of: {2, 6}
* asciitilde (U+007E): found 33, expected one of: {1, 5}
* logicalnot (U+00AC): found 30, expected one of: {2, 1}
* asciicircum (U+005E): found 30, expected one of: {1, 2}
* infinity (U+221E): found 84, expected one of: {1, 2, 3}
* integral (U+222B): found 52, expected one of: {1, 5}
* uni2206 (U+2206): found 98, expected one of: {3, 2}
* product (U+220F): found 114, expected one of: {3, 5, 1}
* summation (U+2211): found 82, expected one of: {1, 2}
* radical (U+221A): found 77, expected one of: {1, 2}
* uni00B5 (U+00B5): found 78, expected one of: {2, 3, 1}
* partialdiff (U+2202): found 82, expected one of: {1, 2}
* arrowup (U+2191): found 76, expected one of: {2, 1}
* uni2197 (U+2197): found 75, expected one of: {1, 2}
* arrowright (U+2192): found 76, expected one of: {1, 2}
* uni2198 (U+2198): found 75, expected one of: {2, 1}
* arrowdown (U+2193): found 76, expected one of: {2, 1}
* uni2199 (U+2199): found 75, expected one of: {2, 1}
* arrowleft (U+2190): found 76, expected one of: {2, 1}
* uni2196 (U+2196): found 75, expected one of: {2, 1}
* arrowboth (U+2194): found 92, expected one of: {3, 1, 2}
* arrowupdn (U+2195): found 92, expected one of: {1, 3, 2}
* uni21E4 (U+21E4): found 64, expected one of: {3, 1, 2}
* uni21E5 (U+21E5): found 64, expected one of: {3, 1, 2}
* uni21A9 (U+21A9): found 83, expected one of: {2, 1}
* uni21AA (U+21AA): found 83, expected one of: {1, 2}
* uni21B0 (U+21B0): found 62, expected one of: {3, 1, 2}
* uni21B1 (U+21B1): found 62, expected one of: {2, 3, 1}
* uni21B4 (U+21B4): found 62, expected one of: {2, 3, 1}
* carriagereturn (U+21B5): found 62, expected one of: {1, 2, 3}
* uni21E7 (U+21E7): found 114, expected one of: {2}
* lozenge (U+25CA): found 72, expected one of: {2}
* uni0308 (U+0308): found 12, expected one of: {2}
* uni0307 (U+0307): found 6, expected one of: {1}
* gravecomb (U+0300): found 9, expected one of: {1}
* acutecomb (U+0301): found 9, expected one of: {1}
* uni030B (U+030B): found 18, expected one of: {2}
* uni030C.alt (unencoded): found 13, expected one of: {3, 1}
* uni0302 (U+0302): found 14, expected one of: {1}
* uni030C (U+030C): found 14, expected one of: {1}
* uni0306 (U+0306): found 12, expected one of: {1}
* uni030A (U+030A): found 16, expected one of: {2}
* tildecomb (U+0303): found 14, expected one of: {1}
* uni0304 (U+0304): found 16, expected one of: {1}
* uni0312 (U+0312): found 8, expected one of: {1}
* uni0326 (U+0326): found 8, expected one of: {1}
* uni0326.loclMAH (unencoded): found 8, expected one of: {1, 0, 2}
* uni0327 (U+0327): found 17, expected one of: {1}
* uni0328 (U+0328): found 15, expected one of: {1}
* dieresis (U+00A8): found 12, expected one of: {2}
* dotaccent (U+02D9): found 6, expected one of: {1}
* grave (U+0060): found 9, expected one of: {1}
* acute (U+00B4): found 9, expected one of: {1}
* hungarumlaut (U+02DD): found 18, expected one of: {2}
* circumflex (U+02C6): found 14, expected one of: {1, 5}
* caron (U+02C7): found 14, expected one of: {1, 5}
* breve (U+02D8): found 12, expected one of: {1}
* ring (U+02DA): found 16, expected one of: {2, 6}
* tilde (U+02DC): found 14, expected one of: {1}
* macron (U+00AF): found 16, expected one of: {1}
* cedilla (U+00B8): found 17, expected one of: {5, 1}
* ogonek (U+02DB): found 15, expected one of: {1}
* uni02BB (U+02BB): found 8, expected one of: {1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 532 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=494: multiply, logicalnot, minus
width=570: approxequal
width=608: notequal, greaterequal, lessequal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* vercelLogo [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̃
* į́
* į̂
* į̀
* į̄
* į̌The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̨̃
* į̨́
* į̨̊
* į̨̇
* į̨̂
* į̨̈
* į̨̀
* į̨̄
* į̨̌
* į̨̆
* į̨̒
* į̨̋
* į̧̃
* į̧́
* į̧̊
* į̧̇
* į̧̂
* į̧̈
* į̧̀
* į̧̄
* į̧̌
* į̧̆
* į̧̒
* į̧̋
* į̦̃
* į̦́
* į̦̊
* į̦̇
* į̦̂
* į̦̈
* į̦̀
* į̦̄
* į̦̌
* į̦̆
* į̦̒
* į̦̋
* į̊
* į̇
* į̈
* į̆
* į̒
* į̋ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - eogonek (U+0119): X=418,Y=1 (should be at baseline 0?)
* - eogonek (U+0119): X=380,Y=1 (should be at baseline 0?)
* - eogonek (U+0119): X=399,Y=1 (should be at baseline 0?)
* - ohungarumlaut (U+0151): X=437,Y=723 (should be at cap-height 722?)
* - ohungarumlaut (U+0151): X=399,Y=723 (should be at cap-height 722?)
* - ohungarumlaut (U+0151): X=475,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=437,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=399,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=475,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=361,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=323,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=399,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=361,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=323,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=399,Y=723 (should be at cap-height 722?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* Aogonek (U+0104): Line(Line { p0: (551.0, 38.0), p1: (570.0, 0.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (570.0, 0.0), p1: (532.0, 0.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (532.0, 0.0), p1: (551.0, 38.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (513.0, 38.0), p1: (532.0, 0.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (532.0, 0.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (494.0, 0.0), p1: (513.0, 38.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (133.0, 38.0), p1: (152.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (152.0, 0.0), p1: (114.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (114.0, 0.0), p1: (133.0, 38.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (323.0, 38.0), p1: (342.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (342.0, 0.0), p1: (304.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (304.0, 0.0), p1: (323.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (513.0, 38.0), p1: (532.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (532.0, 0.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (494.0, 0.0), p1: (513.0, 38.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (323.0, 38.0), p1: (342.0, 0.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (342.0, 0.0), p1: (304.0, 0.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (304.0, 0.0), p1: (323.0, 38.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (437.0, 38.0), p1: (456.0, 0.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (456.0, 0.0), p1: (418.0, 0.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (418.0, 0.0), p1: (437.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (475.0, 38.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (494.0, 0.0), p1: (456.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (456.0, 0.0), p1: (475.0, 38.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (475.0, 38.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (494.0, 0.0), p1: (456.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (456.0, 0.0), p1: (475.0, 38.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'VRCL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/ttf/GeistPixel-Line.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tifinagh, coptic, hebrew, malayalam, duployan, todhri, tai-le, old-permic, canadian-aboriginal, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: greek, math, elbasan
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2120 SERVICE MARK: try adding math
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/ttf/GeistPixel-Square.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tifinagh, coptic, hebrew, malayalam, duployan, todhri, tai-le, old-permic, canadian-aboriginal, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: greek, math, elbasan
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2120 SERVICE MARK: try adding math
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/ttf/GeistPixel-Grid.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tifinagh, coptic, hebrew, malayalam, duployan, todhri, tai-le, old-permic, canadian-aboriginal, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: greek, math, elbasan
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2120 SERVICE MARK: try adding math
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/ttf/GeistPixel-Circle.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tifinagh, coptic, hebrew, malayalam, duployan, todhri, tai-le, old-permic, canadian-aboriginal, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: greek, math, elbasan
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2120 SERVICE MARK: try adding math
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/ttf/GeistPixel-Triangle.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tifinagh, coptic, hebrew, malayalam, duployan, todhri, tai-le, old-permic, canadian-aboriginal, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: greek, math, elbasan
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2120 SERVICE MARK: try adding math
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>


<details><summary>[15] fonts/ttf/GeistPixel-Line.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current              | Expected                     |
|----------------------------|----------------------|------------------------------|
| Family Name                | Geist Pixel Line     | Geist Pixel Line             |
| Subfamily Name             | Regular              | Regular                      |
| Full Name                  | **Geist Pixel Line** | **Geist Pixel Line Regular** |
| Postscript Name            | **GeistPixel-Line**  | **GeistPixelLine-Regular**   |
| Typographic Family Name    | **Geist Pixel**      | **N/A**                      |
| Typographic Subfamily Name | **Line**             | **N/A**                      | [code: bad-names]
  
  


- ⚠️ **WARN** Regular missing from full name [code: lacks-regular]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- 🔥 **FAIL** Please specify which languages and scripts this font supports. [code: missing-slng-tag]
  
  

  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* C (U+0043): found 29, expected one of: {5, 1, 2}
* Cacute (U+0106): found 32, expected one of: {3, 2, 6}
* Ccaron (U+010C): found 35, expected one of: {6, 2, 3}
* Cdotaccent (U+010A): found 32, expected one of: {2, 6, 3}
* uni018F (U+018F): found 30, expected one of: {2, 1}
* uni1E20 (U+1E20): found 34, expected one of: {3, 2, 4}
* I (U+0049): found 19, expected one of: {1, 2, 3}
* Iacute (U+00CD): found 22, expected one of: {2, 3, 4}
* Idotaccent (U+0130): found 22, expected one of: {3, 2, 6}
* Igrave (U+00CC): found 22, expected one of: {2, 3, 4}
* Imacron (U+012A): found 21, expected one of: {2, 6, 3}
* Itilde (U+0128): found 26, expected one of: {2, 6, 3}
* J (U+004A): found 23, expected one of: {3, 1, 2}
* S (U+0053): found 27, expected one of: {2, 5, 1}
* Sacute (U+015A): found 30, expected one of: {3, 2, 6}
* U (U+0055): found 36, expected one of: {5, 1, 2}
* Uacute (U+00DA): found 39, expected one of: {3, 2, 6}
* Ugrave (U+00D9): found 39, expected one of: {3, 6, 2}
* Uhungarumlaut (U+0170): found 42, expected one of: {3, 7, 4}
* Umacron (U+016A): found 38, expected one of: {3, 2, 6}
* Utilde (U+0168): found 43, expected one of: {6, 2, 3}
* V (U+0056): found 34, expected one of: {1, 2, 5}
* Zacute (U+0179): found 22, expected one of: {4, 6, 2}
* Zdotaccent (U+017B): found 22, expected one of: {4, 2, 6}
* uniA78B (U+A78B): found 10, expected one of: {1}
* uni013B.loclMAH (unencoded): found 24, expected one of: {4, 2, 8}
* uni0145.loclMAH (unencoded): found 55, expected one of: {2, 3}
* c (U+0063): found 20, expected one of: {3, 1, 5}
* cacute (U+0107): found 23, expected one of: {6, 2, 3}
* ccaron (U+010D): found 26, expected one of: {3, 6, 2}
* ccedilla (U+00E7): found 27, expected one of: {1, 2, 6}
* cdotaccent (U+010B): found 23, expected one of: {6, 2, 3}
* e (U+0065): found 20, expected one of: {5, 1, 2}
* eacute (U+00E9): found 23, expected one of: {3, 2, 6}
* ecaron (U+011B): found 26, expected one of: {2, 6, 3}
* ecircumflex (U+00EA): found 26, expected one of: {3, 2, 6}
* edieresis (U+00EB): found 26, expected one of: {3, 7, 4}
* edotaccent (U+0117): found 23, expected one of: {6, 3, 2}
* egrave (U+00E8): found 23, expected one of: {2, 3, 6}
* emacron (U+0113): found 22, expected one of: {2, 3, 6}
* uni1EBD (U+1EBD): found 27, expected one of: {6, 3, 2}
* uni0259 (U+0259): found 20, expected one of: {1, 2}
* dotlessi (U+0131): found 14, expected one of: {2, 1}
* iacute (U+00ED): found 17, expected one of: {3, 2, 6}
* icircumflex (U+00EE): found 20, expected one of: {2, 3, 6}
* idieresis (U+00EF): found 20, expected one of: {4, 3, 7}
* i.loclTRK (unencoded): found 17, expected one of: {3, 2}
* igrave (U+00EC): found 17, expected one of: {2, 6, 3}
* imacron (U+012B): found 16, expected one of: {6, 2}
* itilde (U+0129): found 21, expected one of: {2, 3, 6}
* uni0237 (U+0237): found 18, expected one of: {2, 3, 1}
* l (U+006C): found 19, expected one of: {6, 2, 1}
* lacute (U+013A): found 22, expected one of: {6, 3, 2}
* lcaron (U+013E): found 26, expected one of: {2, 3, 6}
* uni013C (U+013C): found 24, expected one of: {2, 3, 6}
* n (U+006E): found 28, expected one of: {1, 2, 5}
* nacute (U+0144): found 31, expected one of: {3, 6, 2}
* ntilde (U+00F1): found 35, expected one of: {6, 2, 3}
* ocircumflex (U+00F4): found 30, expected one of: {3, 7, 4}
* odieresis (U+00F6): found 30, expected one of: {8, 4, 5}
* ohungarumlaut (U+0151): found 30, expected one of: {4, 8, 5}
* omacron (U+014D): found 26, expected one of: {3, 7, 2}
* otilde (U+00F5): found 31, expected one of: {3, 4, 7}
* r (U+0072): found 16, expected one of: {1, 3, 2}
* racute (U+0155): found 19, expected one of: {2, 3, 6}
* rcaron (U+0159): found 22, expected one of: {6, 2, 3}
* s (U+0073): found 18, expected one of: {3, 1, 2}
* sacute (U+015B): found 21, expected one of: {3, 6, 2}
* germandbls (U+00DF): found 36, expected one of: {5, 1, 2}
* t (U+0074): found 17, expected one of: {2, 1, 3}
* tcaron (U+0165): found 24, expected one of: {2, 3, 6}
* u (U+0075): found 28, expected one of: {2, 5, 1}
* uacute (U+00FA): found 31, expected one of: {3, 2, 6}
* ucircumflex (U+00FB): found 34, expected one of: {6, 2, 3}
* udieresis (U+00FC): found 34, expected one of: {4, 3, 7}
* ugrave (U+00F9): found 31, expected one of: {6, 2, 3}
* uhungarumlaut (U+0171): found 34, expected one of: {4, 7, 3}
* umacron (U+016B): found 30, expected one of: {6, 2, 3}
* uring (U+016F): found 36, expected one of: {3, 7, 4}
* utilde (U+0169): found 35, expected one of: {6, 2, 3}
* v (U+0076): found 26, expected one of: {2, 5, 1}
* yacute (U+00FD): found 33, expected one of: {3, 2, 6}
* ygrave (U+1EF3): found 33, expected one of: {3, 6, 2}
* uni1EF9 (U+1EF9): found 37, expected one of: {6, 3, 2}
* z (U+007A): found 14, expected one of: {3, 1, 2}
* uniA78C (U+A78C): found 7, expected one of: {1}
* aacute.ss02 (unencoded): found 31, expected one of: {3, 2, 4}
* abreve.ss02 (unencoded): found 32, expected one of: {2, 3}
* acircumflex.ss02 (unencoded): found 34, expected one of: {4, 3, 2}
* adieresis.ss02 (unencoded): found 34, expected one of: {3, 4, 5}
* agrave.ss02 (unencoded): found 31, expected one of: {2, 3, 4}
* amacron.ss02 (unencoded): found 30, expected one of: {3, 2, 4}
* aogonek.ss02 (unencoded): found 36, expected one of: {3, 2, 4}
* aring.ss02 (unencoded): found 36, expected one of: {5, 3, 4}
* atilde.ss02 (unencoded): found 35, expected one of: {3, 2, 4}
* l.ss03 (unencoded): found 19, expected one of: {3, 1, 2}
* lacute.ss03 (unencoded): found 22, expected one of: {3, 4, 2}
* lcaron.ss03 (unencoded): found 26, expected one of: {4, 3, 2}
* uni013C.ss03 (unencoded): found 24, expected one of: {2, 3}
* Lambda (U+039B): found 36, expected one of: {1, 3}
* uni03A9 (U+03A9): found 36, expected one of: {3, 1}
* lambda (U+03BB): found 30, expected one of: {2, 1}
* uni03BC (U+03BC): found 33, expected one of: {1, 3, 2}
* pi (U+03C0): found 26, expected one of: {1, 3}
* one (U+0031): found 19, expected one of: {5, 1, 2}
* two (U+0032): found 23, expected one of: {5, 1, 2}
* three (U+0033): found 25, expected one of: {1, 5, 2}
* five (U+0035): found 26, expected one of: {5, 2, 1}
* six (U+0036): found 32, expected one of: {5, 2, 1}
* seven (U+0037): found 19, expected one of: {1, 2, 5}
* nine (U+0039): found 32, expected one of: {5, 1, 2}
* four.dnom (unencoded): found 12, expected one of: {3, 2, 1}
* three.numr (unencoded): found 11, expected one of: {1, 3, 2}
* fraction (U+2044): found 19, expected one of: {1}
* onehalf (U+00BD): found 38, expected one of: {3, 4, 5}
* uni00B9 (U+00B9): found 9, expected one of: {1, 2}
* uni00B2 (U+00B2): found 10, expected one of: {1, 2}
* uni00B3 (U+00B3): found 11, expected one of: {1, 2}
* period (U+002E): found 3, expected one of: {5, 1}
* comma (U+002C): found 7, expected one of: {1, 2}
* semicolon (U+003B): found 10, expected one of: {6, 2}
* ellipsis (U+2026): found 9, expected one of: {3, 7}
* exclam (U+0021): found 16, expected one of: {2, 6}
* exclamdown (U+00A1): found 16, expected one of: {6, 2}
* question (U+003F): found 21, expected one of: {3, 2, 6}
* questiondown (U+00BF): found 21, expected one of: {6, 3, 2}
* periodcentered (U+00B7): found 3, expected one of: {1, 5}
* bullet (U+2022): found 6, expected one of: {1, 5}
* numbersign (U+0023): found 34, expected one of: {2, 6, 4}
* slash (U+002F): found 24, expected one of: {5, 1}
* backslash (U+005C): found 24, expected one of: {5, 1}
* hyphen (U+002D): found 2, expected one of: {1}
* endash (U+2013): found 2, expected one of: {1}
* emdash (U+2014): found 2, expected one of: {1}
* underscore (U+005F): found 2, expected one of: {1}
* uni301C (U+301C): found 9, expected one of: {1}
* parenleft (U+0028): found 23, expected one of: {1, 5}
* parenright (U+0029): found 23, expected one of: {5, 1}
* braceleft (U+007B): found 23, expected one of: {1, 5, 2}
* braceright (U+007D): found 23, expected one of: {1, 5, 2}
* bracketleft (U+005B): found 23, expected one of: {5, 1, 3}
* bracketright (U+005D): found 23, expected one of: {5, 1, 3}
* quotesinglbase (U+201A): found 6, expected one of: {2, 1}
* quotedblbase (U+201E): found 12, expected one of: {2, 6}
* quotedblleft (U+201C): found 12, expected one of: {6, 2}
* quotedblright (U+201D): found 12, expected one of: {2, 6}
* quoteleft (U+2018): found 6, expected one of: {1, 2}
* quoteright (U+2019): found 6, expected one of: {2, 1}
* guillemotleft (U+00AB): found 22, expected one of: {2, 6}
* guillemotright (U+00BB): found 22, expected one of: {2, 6}
* guilsinglleft (U+2039): found 11, expected one of: {5, 1}
* guilsinglright (U+203A): found 11, expected one of: {5, 1}
* quotedbl (U+0022): found 14, expected one of: {6, 2}
* quotesingle (U+0027): found 7, expected one of: {1, 5}
* florin (U+0192): found 19, expected one of: {2, 1}
* section (U+00A7): found 28, expected one of: {6, 4, 2}
* uni2117 (U+2117): found 37, expected one of: {3, 4}
* degree (U+00B0): found 12, expected one of: {2, 6}
* minute (U+2032): found 6, expected one of: {1, 5}
* second (U+2033): found 12, expected one of: {6, 2}
* bar (U+007C): found 23, expected one of: {1}
* brokenbar (U+00A6): found 18, expected one of: {2}
* dagger (U+2020): found 19, expected one of: {2, 4, 1}
* uni2120 (U+2120): found 41, expected one of: {3, 2}
* cent (U+00A2): found 36, expected one of: {1, 3, 2}
* currency (U+00A4): found 26, expected one of: {6, 2}
* plus (U+002B): found 12, expected one of: {1, 2}
* minus (U+2212): found 2, expected one of: {1}
* multiply (U+00D7): found 19, expected one of: {1, 2}
* divide (U+00F7): found 8, expected one of: {3, 7}
* equal (U+003D): found 4, expected one of: {6, 2}
* notequal (U+2260): found 16, expected one of: {1, 3, 7}
* greater (U+003E): found 13, expected one of: {2, 1}
* less (U+003C): found 13, expected one of: {1, 2}
* greaterequal (U+2265): found 11, expected one of: {2, 6, 3}
* lessequal (U+2264): found 11, expected one of: {6, 3, 2}
* plusminus (U+00B1): found 14, expected one of: {2, 3, 1}
* approxequal (U+2248): found 22, expected one of: {2, 6}
* asciitilde (U+007E): found 11, expected one of: {1, 5}
* logicalnot (U+00AC): found 6, expected one of: {2, 1}
* asciicircum (U+005E): found 14, expected one of: {1, 2}
* infinity (U+221E): found 30, expected one of: {1, 2, 3}
* integral (U+222B): found 23, expected one of: {1, 5}
* uni2206 (U+2206): found 34, expected one of: {3, 2}
* product (U+220F): found 44, expected one of: {3, 5, 1}
* summation (U+2211): found 19, expected one of: {1, 2}
* radical (U+221A): found 33, expected one of: {1, 2}
* uni00B5 (U+00B5): found 33, expected one of: {2, 3, 1}
* partialdiff (U+2202): found 29, expected one of: {1, 2}
* arrowup (U+2191): found 28, expected one of: {2, 1}
* uni2197 (U+2197): found 21, expected one of: {1, 2}
* arrowright (U+2192): found 16, expected one of: {1, 2}
* uni2198 (U+2198): found 21, expected one of: {2, 1}
* arrowdown (U+2193): found 28, expected one of: {2, 1}
* uni2199 (U+2199): found 21, expected one of: {2, 1}
* arrowleft (U+2190): found 16, expected one of: {2, 1}
* uni2196 (U+2196): found 21, expected one of: {2, 1}
* arrowboth (U+2194): found 22, expected one of: {3, 1, 2}
* arrowupdn (U+2195): found 30, expected one of: {1, 3, 2}
* uni21E4 (U+21E4): found 20, expected one of: {3, 1, 2}
* uni21E5 (U+21E5): found 20, expected one of: {3, 1, 2}
* uni21A9 (U+21A9): found 19, expected one of: {2, 1}
* uni21AA (U+21AA): found 19, expected one of: {1, 2}
* uni21B0 (U+21B0): found 19, expected one of: {3, 1, 2}
* uni21B1 (U+21B1): found 19, expected one of: {2, 3, 1}
* uni21B4 (U+21B4): found 14, expected one of: {2, 3, 1}
* carriagereturn (U+21B5): found 19, expected one of: {1, 2, 3}
* uni21E7 (U+21E7): found 33, expected one of: {2}
* lozenge (U+25CA): found 30, expected one of: {2}
* uni0308 (U+0308): found 6, expected one of: {2}
* uni0307 (U+0307): found 3, expected one of: {1}
* gravecomb (U+0300): found 3, expected one of: {1}
* acutecomb (U+0301): found 3, expected one of: {1}
* uni030B (U+030B): found 6, expected one of: {2}
* uni030C.alt (unencoded): found 7, expected one of: {3, 1}
* uni0302 (U+0302): found 6, expected one of: {1}
* uni030C (U+030C): found 6, expected one of: {1}
* uni0306 (U+0306): found 4, expected one of: {1}
* uni030A (U+030A): found 8, expected one of: {2}
* tildecomb (U+0303): found 7, expected one of: {1}
* uni0304 (U+0304): found 2, expected one of: {1}
* uni0312 (U+0312): found 5, expected one of: {1}
* uni0326 (U+0326): found 5, expected one of: {1}
* uni0326.loclMAH (unencoded): found 5, expected one of: {1, 0, 2}
* uni0327 (U+0327): found 7, expected one of: {1}
* uni0328 (U+0328): found 8, expected one of: {1}
* dieresis (U+00A8): found 6, expected one of: {2}
* dotaccent (U+02D9): found 3, expected one of: {1}
* grave (U+0060): found 3, expected one of: {1}
* acute (U+00B4): found 3, expected one of: {1}
* hungarumlaut (U+02DD): found 6, expected one of: {2}
* circumflex (U+02C6): found 6, expected one of: {1, 5}
* caron (U+02C7): found 6, expected one of: {1, 5}
* breve (U+02D8): found 4, expected one of: {1}
* ring (U+02DA): found 8, expected one of: {2, 6}
* tilde (U+02DC): found 7, expected one of: {1}
* macron (U+00AF): found 2, expected one of: {1}
* cedilla (U+00B8): found 7, expected one of: {5, 1}
* ogonek (U+02DB): found 8, expected one of: {1}
* uni02BB (U+02BB): found 5, expected one of: {1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 532 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=608: greaterequal, lessequal, notequal
width=494: multiply, minus, logicalnot
width=570: approxequal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* vercelLogo [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̌
* į̃
* į́
* į̄
* į̀
* į̂The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̨̇
* į̨̌
* į̨̈
* į̨̃
* į̨̒
* į̨́
* į̨̄
* į̨̆
* į̨̋
* į̨̀
* į̨̊
* į̨̂
* į̦̇
* į̦̌
* į̦̈
* į̦̃
* į̦̒
* į̦́
* į̦̄
* į̦̆
* į̦̋
* į̦̀
* į̦̊
* į̦̂
* į̧̇
* į̧̌
* į̧̈
* į̧̃
* į̧̒
* į̧́
* į̧̄
* į̧̆
* į̧̋
* į̧̀
* į̧̊
* į̧̂
* į̇
* į̈
* į̒
* į̆
* į̋
* į̊ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - eogonek (U+0119): X=380,Y=1 (should be at baseline 0?)
* - eogonek (U+0119): X=418,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* Aogonek (U+0104): Line(Line { p0: (570.0, 19.0), p1: (570.0, 0.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (532.0, 19.0), p1: (532.0, 0.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (152.0, 19.0), p1: (152.0, 0.0) }) has the same coordinates as a previous segment.
* Uogonek (U+0172): Line(Line { p0: (456.0, 0.0), p1: (456.0, 19.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (342.0, 19.0), p1: (342.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (532.0, 19.0), p1: (532.0, 0.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (342.0, 19.0), p1: (342.0, 0.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (456.0, 19.0), p1: (456.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (494.0, 19.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (494.0, 19.0), p1: (494.0, 0.0) }) has the same coordinates as a previous segment.
* fi (U+FB01): Line(Line { p0: (342.0, 494.0), p1: (342.0, 513.0) }) has the same coordinates as a previous segment.
* fi (U+FB01): Line(Line { p0: (342.0, 456.0), p1: (342.0, 475.0) }) has the same coordinates as a previous segment.
* fl (U+FB02): Line(Line { p0: (342.0, 684.0), p1: (342.0, 703.0) }) has the same coordinates as a previous segment.
* fl (U+FB02): Line(Line { p0: (342.0, 646.0), p1: (342.0, 665.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'VRCL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[14] fonts/ttf/GeistPixel-Grid.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current              | Expected                     |
|----------------------------|----------------------|------------------------------|
| Family Name                | Geist Pixel Grid     | Geist Pixel Grid             |
| Subfamily Name             | Regular              | Regular                      |
| Full Name                  | **Geist Pixel Grid** | **Geist Pixel Grid Regular** |
| Postscript Name            | **GeistPixel-Grid**  | **GeistPixelGrid-Regular**   |
| Typographic Family Name    | **Geist Pixel**      | **N/A**                      |
| Typographic Subfamily Name | **Grid**             | **N/A**                      | [code: bad-names]
  
  


- ⚠️ **WARN** Regular missing from full name [code: lacks-regular]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- 🔥 **FAIL** Please specify which languages and scripts this font supports. [code: missing-slng-tag]
  
  

  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* C (U+0043): found 88, expected one of: {5, 1, 2}
* Cacute (U+0106): found 97, expected one of: {3, 2, 6}
* Ccaron (U+010C): found 102, expected one of: {6, 2, 3}
* Cdotaccent (U+010A): found 94, expected one of: {2, 6, 3}
* uni018F (U+018F): found 118, expected one of: {2, 1}
* uni1E20 (U+1E20): found 123, expected one of: {3, 2, 4}
* I (U+0049): found 38, expected one of: {1, 2, 3}
* Iacute (U+00CD): found 47, expected one of: {2, 3, 4}
* Idotaccent (U+0130): found 44, expected one of: {3, 2, 6}
* Igrave (U+00CC): found 47, expected one of: {2, 3, 4}
* Imacron (U+012A): found 54, expected one of: {2, 6, 3}
* Itilde (U+0128): found 52, expected one of: {2, 6, 3}
* J (U+004A): found 59, expected one of: {3, 1, 2}
* S (U+0053): found 96, expected one of: {2, 5, 1}
* Sacute (U+015A): found 105, expected one of: {3, 2, 6}
* U (U+0055): found 86, expected one of: {5, 1, 2}
* Uacute (U+00DA): found 95, expected one of: {3, 2, 6}
* Ugrave (U+00D9): found 95, expected one of: {3, 6, 2}
* Uhungarumlaut (U+0170): found 104, expected one of: {3, 7, 4}
* Umacron (U+016A): found 102, expected one of: {3, 2, 6}
* Utilde (U+0168): found 100, expected one of: {6, 2, 3}
* V (U+0056): found 72, expected one of: {1, 2, 5}
* Zacute (U+0179): found 105, expected one of: {4, 6, 2}
* Zdotaccent (U+017B): found 102, expected one of: {4, 2, 6}
* uniA78B (U+A78B): found 20, expected one of: {1}
* uni013B.loclMAH (unencoded): found 66, expected one of: {4, 2, 8}
* uni0145.loclMAH (unencoded): found 115, expected one of: {2, 3}
* c (U+0063): found 66, expected one of: {3, 1, 5}
* cacute (U+0107): found 75, expected one of: {6, 2, 3}
* ccaron (U+010D): found 80, expected one of: {3, 6, 2}
* ccedilla (U+00E7): found 83, expected one of: {1, 2, 6}
* cdotaccent (U+010B): found 72, expected one of: {6, 2, 3}
* e (U+0065): found 85, expected one of: {5, 1, 2}
* eacute (U+00E9): found 94, expected one of: {3, 2, 6}
* ecaron (U+011B): found 99, expected one of: {2, 6, 3}
* ecircumflex (U+00EA): found 99, expected one of: {3, 2, 6}
* edieresis (U+00EB): found 97, expected one of: {3, 7, 4}
* edotaccent (U+0117): found 91, expected one of: {6, 3, 2}
* egrave (U+00E8): found 94, expected one of: {2, 3, 6}
* emacron (U+0113): found 101, expected one of: {2, 3, 6}
* uni1EBD (U+1EBD): found 99, expected one of: {6, 3, 2}
* uni0259 (U+0259): found 85, expected one of: {1, 2}
* dotlessi (U+0131): found 46, expected one of: {2, 1}
* iacute (U+00ED): found 55, expected one of: {3, 2, 6}
* icircumflex (U+00EE): found 60, expected one of: {2, 3, 6}
* idieresis (U+00EF): found 58, expected one of: {4, 3, 7}
* i.loclTRK (unencoded): found 52, expected one of: {3, 2}
* igrave (U+00EC): found 55, expected one of: {2, 6, 3}
* imacron (U+012B): found 62, expected one of: {6, 2}
* itilde (U+0129): found 60, expected one of: {2, 3, 6}
* uni0237 (U+0237): found 45, expected one of: {2, 3, 1}
* l (U+006C): found 53, expected one of: {6, 2, 1}
* lacute (U+013A): found 62, expected one of: {6, 3, 2}
* lcaron (U+013E): found 66, expected one of: {2, 3, 6}
* uni013C (U+013C): found 61, expected one of: {2, 3, 6}
* n (U+006E): found 66, expected one of: {1, 2, 5}
* nacute (U+0144): found 75, expected one of: {3, 6, 2}
* ntilde (U+00F1): found 80, expected one of: {6, 2, 3}
* ocircumflex (U+00F4): found 86, expected one of: {3, 7, 4}
* odieresis (U+00F6): found 84, expected one of: {8, 4, 5}
* ohungarumlaut (U+0151): found 90, expected one of: {4, 8, 5}
* omacron (U+014D): found 88, expected one of: {3, 7, 2}
* otilde (U+00F5): found 86, expected one of: {3, 4, 7}
* r (U+0072): found 50, expected one of: {1, 3, 2}
* racute (U+0155): found 59, expected one of: {2, 3, 6}
* rcaron (U+0159): found 64, expected one of: {6, 2, 3}
* s (U+0073): found 72, expected one of: {3, 1, 2}
* sacute (U+015B): found 81, expected one of: {3, 6, 2}
* germandbls (U+00DF): found 93, expected one of: {5, 1, 2}
* t (U+0074): found 51, expected one of: {2, 1, 3}
* tcaron (U+0165): found 64, expected one of: {2, 3, 6}
* u (U+0075): found 64, expected one of: {2, 5, 1}
* uacute (U+00FA): found 73, expected one of: {3, 2, 6}
* ucircumflex (U+00FB): found 78, expected one of: {6, 2, 3}
* udieresis (U+00FC): found 76, expected one of: {4, 3, 7}
* ugrave (U+00F9): found 73, expected one of: {6, 2, 3}
* uhungarumlaut (U+0171): found 82, expected one of: {4, 7, 3}
* umacron (U+016B): found 80, expected one of: {6, 2, 3}
* uring (U+016F): found 80, expected one of: {3, 7, 4}
* utilde (U+0169): found 78, expected one of: {6, 2, 3}
* v (U+0076): found 54, expected one of: {2, 5, 1}
* yacute (U+00FD): found 78, expected one of: {3, 2, 6}
* ygrave (U+1EF3): found 78, expected one of: {3, 6, 2}
* uni1EF9 (U+1EF9): found 83, expected one of: {6, 3, 2}
* z (U+007A): found 73, expected one of: {3, 1, 2}
* uniA78C (U+A78C): found 14, expected one of: {1}
* aacute.ss02 (unencoded): found 87, expected one of: {3, 2, 4}
* abreve.ss02 (unencoded): found 90, expected one of: {2, 3}
* acircumflex.ss02 (unencoded): found 92, expected one of: {4, 3, 2}
* adieresis.ss02 (unencoded): found 90, expected one of: {3, 4, 5}
* agrave.ss02 (unencoded): found 87, expected one of: {2, 3, 4}
* amacron.ss02 (unencoded): found 94, expected one of: {3, 2, 4}
* aogonek.ss02 (unencoded): found 93, expected one of: {3, 2, 4}
* aring.ss02 (unencoded): found 94, expected one of: {5, 3, 4}
* atilde.ss02 (unencoded): found 92, expected one of: {3, 2, 4}
* l.ss03 (unencoded): found 47, expected one of: {3, 1, 2}
* lacute.ss03 (unencoded): found 56, expected one of: {3, 4, 2}
* lcaron.ss03 (unencoded): found 60, expected one of: {4, 3, 2}
* uni013C.ss03 (unencoded): found 55, expected one of: {2, 3}
* Lambda (U+039B): found 74, expected one of: {1, 3}
* uni03A9 (U+03A9): found 106, expected one of: {3, 1}
* lambda (U+03BB): found 70, expected one of: {2, 1}
* uni03BC (U+03BC): found 77, expected one of: {1, 3, 2}
* pi (U+03C0): found 79, expected one of: {1, 3}
* one (U+0031): found 60, expected one of: {5, 1, 2}
* two (U+0032): found 90, expected one of: {5, 1, 2}
* three (U+0033): found 83, expected one of: {1, 5, 2}
* five (U+0035): found 89, expected one of: {5, 2, 1}
* six (U+0036): found 100, expected one of: {5, 2, 1}
* seven (U+0037): found 64, expected one of: {1, 2, 5}
* nine (U+0039): found 100, expected one of: {5, 1, 2}
* four.dnom (unencoded): found 39, expected one of: {3, 2, 1}
* three.numr (unencoded): found 36, expected one of: {1, 3, 2}
* fraction (U+2044): found 38, expected one of: {1}
* onehalf (U+00BD): found 98, expected one of: {3, 4, 5}
* uni00B9 (U+00B9): found 22, expected one of: {1, 2}
* uni00B2 (U+00B2): found 38, expected one of: {1, 2}
* uni00B3 (U+00B3): found 36, expected one of: {1, 2}
* period (U+002E): found 9, expected one of: {5, 1}
* comma (U+002C): found 15, expected one of: {1, 2}
* colon (U+003A): found 18, expected one of: {6, 2}
* semicolon (U+003B): found 24, expected one of: {6, 2}
* ellipsis (U+2026): found 27, expected one of: {3, 7}
* exclam (U+0021): found 32, expected one of: {2, 6}
* exclamdown (U+00A1): found 32, expected one of: {6, 2}
* question (U+003F): found 57, expected one of: {3, 2, 6}
* questiondown (U+00BF): found 57, expected one of: {6, 3, 2}
* periodcentered (U+00B7): found 9, expected one of: {1, 5}
* bullet (U+2022): found 32, expected one of: {1, 5}
* numbersign (U+0023): found 106, expected one of: {2, 6, 4}
* slash (U+002F): found 48, expected one of: {5, 1}
* backslash (U+005C): found 48, expected one of: {5, 1}
* hyphen (U+002D): found 16, expected one of: {1}
* endash (U+2013): found 22, expected one of: {1}
* emdash (U+2014): found 32, expected one of: {1}
* underscore (U+005F): found 24, expected one of: {1}
* uni301C (U+301C): found 40, expected one of: {1}
* parenleft (U+0028): found 50, expected one of: {1, 5}
* parenright (U+0029): found 50, expected one of: {5, 1}
* braceleft (U+007B): found 60, expected one of: {1, 5, 2}
* braceright (U+007D): found 60, expected one of: {1, 5, 2}
* bracketleft (U+005B): found 62, expected one of: {5, 1, 3}
* bracketright (U+005D): found 62, expected one of: {5, 1, 3}
* quotesinglbase (U+201A): found 12, expected one of: {2, 1}
* quotedblbase (U+201E): found 24, expected one of: {2, 6}
* quotedblleft (U+201C): found 24, expected one of: {6, 2}
* quotedblright (U+201D): found 24, expected one of: {2, 6}
* quoteleft (U+2018): found 12, expected one of: {1, 2}
* quoteright (U+2019): found 12, expected one of: {2, 1}
* guillemotleft (U+00AB): found 60, expected one of: {2, 6}
* guillemotright (U+00BB): found 60, expected one of: {2, 6}
* guilsinglleft (U+2039): found 30, expected one of: {5, 1}
* guilsinglright (U+203A): found 30, expected one of: {5, 1}
* quotedbl (U+0022): found 28, expected one of: {6, 2}
* quotesingle (U+0027): found 14, expected one of: {1, 5}
* florin (U+0192): found 66, expected one of: {2, 1}
* section (U+00A7): found 111, expected one of: {6, 4, 2}
* uni2117 (U+2117): found 55, expected one of: {3, 4}
* degree (U+00B0): found 40, expected one of: {2, 6}
* minute (U+2032): found 12, expected one of: {1, 5}
* second (U+2033): found 24, expected one of: {6, 2}
* bar (U+007C): found 46, expected one of: {1}
* brokenbar (U+00A6): found 36, expected one of: {2}
* dagger (U+2020): found 54, expected one of: {2, 4, 1}
* uni2120 (U+2120): found 55, expected one of: {3, 2}
* cent (U+00A2): found 98, expected one of: {1, 3, 2}
* currency (U+00A4): found 88, expected one of: {6, 2}
* plus (U+002B): found 44, expected one of: {1, 2}
* minus (U+2212): found 22, expected one of: {1}
* multiply (U+00D7): found 57, expected one of: {1, 2}
* divide (U+00F7): found 36, expected one of: {3, 7}
* equal (U+003D): found 48, expected one of: {6, 2}
* notequal (U+2260): found 72, expected one of: {1, 3, 7}
* greater (U+003E): found 46, expected one of: {2, 1}
* less (U+003C): found 46, expected one of: {1, 2}
* greaterequal (U+2265): found 70, expected one of: {2, 6, 3}
* lessequal (U+2264): found 70, expected one of: {6, 3, 2}
* plusminus (U+00B1): found 68, expected one of: {2, 3, 1}
* approxequal (U+2248): found 66, expected one of: {2, 6}
* asciitilde (U+007E): found 33, expected one of: {1, 5}
* logicalnot (U+00AC): found 30, expected one of: {2, 1}
* asciicircum (U+005E): found 30, expected one of: {1, 2}
* infinity (U+221E): found 84, expected one of: {1, 2, 3}
* integral (U+222B): found 52, expected one of: {1, 5}
* uni2206 (U+2206): found 98, expected one of: {3, 2}
* product (U+220F): found 114, expected one of: {3, 5, 1}
* summation (U+2211): found 82, expected one of: {1, 2}
* radical (U+221A): found 77, expected one of: {1, 2}
* uni00B5 (U+00B5): found 78, expected one of: {2, 3, 1}
* partialdiff (U+2202): found 82, expected one of: {1, 2}
* arrowup (U+2191): found 76, expected one of: {2, 1}
* uni2197 (U+2197): found 75, expected one of: {1, 2}
* arrowright (U+2192): found 76, expected one of: {1, 2}
* uni2198 (U+2198): found 75, expected one of: {2, 1}
* arrowdown (U+2193): found 76, expected one of: {2, 1}
* uni2199 (U+2199): found 75, expected one of: {2, 1}
* arrowleft (U+2190): found 76, expected one of: {2, 1}
* uni2196 (U+2196): found 75, expected one of: {2, 1}
* arrowboth (U+2194): found 92, expected one of: {3, 1, 2}
* arrowupdn (U+2195): found 92, expected one of: {1, 3, 2}
* uni21E4 (U+21E4): found 64, expected one of: {3, 1, 2}
* uni21E5 (U+21E5): found 64, expected one of: {3, 1, 2}
* uni21A9 (U+21A9): found 83, expected one of: {2, 1}
* uni21AA (U+21AA): found 83, expected one of: {1, 2}
* uni21B0 (U+21B0): found 62, expected one of: {3, 1, 2}
* uni21B1 (U+21B1): found 62, expected one of: {2, 3, 1}
* uni21B4 (U+21B4): found 62, expected one of: {2, 3, 1}
* carriagereturn (U+21B5): found 62, expected one of: {1, 2, 3}
* uni21E7 (U+21E7): found 114, expected one of: {2}
* lozenge (U+25CA): found 72, expected one of: {2}
* uni0308 (U+0308): found 12, expected one of: {2}
* uni0307 (U+0307): found 6, expected one of: {1}
* gravecomb (U+0300): found 9, expected one of: {1}
* acutecomb (U+0301): found 9, expected one of: {1}
* uni030B (U+030B): found 18, expected one of: {2}
* uni030C.alt (unencoded): found 13, expected one of: {3, 1}
* uni0302 (U+0302): found 14, expected one of: {1}
* uni030C (U+030C): found 14, expected one of: {1}
* uni0306 (U+0306): found 12, expected one of: {1}
* uni030A (U+030A): found 16, expected one of: {2}
* tildecomb (U+0303): found 14, expected one of: {1}
* uni0304 (U+0304): found 16, expected one of: {1}
* uni0312 (U+0312): found 8, expected one of: {1}
* uni0326 (U+0326): found 8, expected one of: {1}
* uni0326.loclMAH (unencoded): found 8, expected one of: {1, 0, 2}
* uni0327 (U+0327): found 17, expected one of: {1}
* uni0328 (U+0328): found 15, expected one of: {1}
* dieresis (U+00A8): found 12, expected one of: {2}
* dotaccent (U+02D9): found 6, expected one of: {1}
* grave (U+0060): found 9, expected one of: {1}
* acute (U+00B4): found 9, expected one of: {1}
* hungarumlaut (U+02DD): found 18, expected one of: {2}
* circumflex (U+02C6): found 14, expected one of: {1, 5}
* caron (U+02C7): found 14, expected one of: {1, 5}
* breve (U+02D8): found 12, expected one of: {1}
* ring (U+02DA): found 16, expected one of: {2, 6}
* tilde (U+02DC): found 14, expected one of: {1}
* macron (U+00AF): found 16, expected one of: {1}
* cedilla (U+00B8): found 17, expected one of: {5, 1}
* ogonek (U+02DB): found 15, expected one of: {1}
* uni02BB (U+02BB): found 8, expected one of: {1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 532 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=608: lessequal, notequal, greaterequal
width=494: minus, multiply, logicalnot
width=570: approxequal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* vercelLogo [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̀
* į̌
* į́
* į̃
* į̂
* į̄The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̨̒
* į̨̇
* į̨̀
* į̨̌
* į̨́
* į̨̆
* į̨̈
* į̨̋
* į̨̃
* į̨̂
* į̨̊
* į̨̄
* į̦̒
* į̦̇
* į̦̀
* į̦̌
* į̦́
* į̦̆
* į̦̈
* į̦̋
* į̦̃
* į̦̂
* į̦̊
* į̦̄
* į̧̒
* į̧̇
* į̧̀
* į̧̌
* į̧́
* į̧̆
* į̧̈
* į̧̋
* į̧̃
* į̧̂
* į̧̊
* į̧̄
* į̒
* į̇
* į̆
* į̈
* į̋
* į̊ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* Aogonek (U+0104): Line(Line { p0: (536.0, 4.0), p1: (536.0, 34.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (536.0, 34.0), p1: (566.0, 34.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (566.0, 34.0), p1: (566.0, 4.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (566.0, 4.0), p1: (536.0, 4.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (498.0, 4.0), p1: (498.0, 34.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (498.0, 34.0), p1: (528.0, 34.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (528.0, 34.0), p1: (528.0, 4.0) }) has the same coordinates as a previous segment.
* Eogonek (U+0118): Line(Line { p0: (528.0, 4.0), p1: (498.0, 4.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (118.0, 4.0), p1: (118.0, 34.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (118.0, 34.0), p1: (148.0, 34.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (148.0, 34.0), p1: (148.0, 4.0) }) has the same coordinates as a previous segment.
* Iogonek (U+012E): Line(Line { p0: (148.0, 4.0), p1: (118.0, 4.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (308.0, 4.0), p1: (308.0, 34.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (308.0, 34.0), p1: (338.0, 34.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (338.0, 34.0), p1: (338.0, 4.0) }) has the same coordinates as a previous segment.
* Iogonek.ss05: Line(Line { p0: (338.0, 4.0), p1: (308.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (498.0, 4.0), p1: (498.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (498.0, 34.0), p1: (528.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (528.0, 34.0), p1: (528.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek (U+0105): Line(Line { p0: (528.0, 4.0), p1: (498.0, 4.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (308.0, 4.0), p1: (308.0, 34.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (308.0, 34.0), p1: (338.0, 34.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (338.0, 34.0), p1: (338.0, 4.0) }) has the same coordinates as a previous segment.
* iogonek (U+012F): Line(Line { p0: (338.0, 4.0), p1: (308.0, 4.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (422.0, 4.0), p1: (422.0, 34.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (422.0, 34.0), p1: (452.0, 34.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (452.0, 34.0), p1: (452.0, 4.0) }) has the same coordinates as a previous segment.
* uogonek (U+0173): Line(Line { p0: (452.0, 4.0), p1: (422.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (460.0, 4.0), p1: (460.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (460.0, 34.0), p1: (490.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (490.0, 34.0), p1: (490.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek.ss01: Line(Line { p0: (490.0, 4.0), p1: (460.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (460.0, 4.0), p1: (460.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (460.0, 34.0), p1: (490.0, 34.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (490.0, 34.0), p1: (490.0, 4.0) }) has the same coordinates as a previous segment.
* aogonek.ss02: Line(Line { p0: (490.0, 4.0), p1: (460.0, 4.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'VRCL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] fonts/ttf/GeistPixel-Square.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current                | Expected                       |
|----------------------------|------------------------|--------------------------------|
| Family Name                | Geist Pixel Square     | Geist Pixel Square             |
| Subfamily Name             | Regular                | Regular                        |
| Full Name                  | **Geist Pixel Square** | **Geist Pixel Square Regular** |
| Postscript Name            | **GeistPixel-Square**  | **GeistPixelSquare-Regular**   |
| Typographic Family Name    | **Geist Pixel**        | **N/A**                        |
| Typographic Subfamily Name | **Square**             | **N/A**                        | [code: bad-names]
  
  


- ⚠️ **WARN** Regular missing from full name [code: lacks-regular]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- 🔥 **FAIL** Please specify which languages and scripts this font supports. [code: missing-slng-tag]
  
  

  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* Itilde (U+0128): found 4, expected one of: {2, 6, 3}
* Utilde (U+0168): found 4, expected one of: {6, 2, 3}
* uni013B.loclMAH (unencoded): found 3, expected one of: {4, 2, 8}
* uni0145.loclMAH (unencoded): found 4, expected one of: {2, 3}
* ccedilla (U+00E7): found 3, expected one of: {1, 2, 6}
* uni1EBD (U+1EBD): found 5, expected one of: {6, 3, 2}
* itilde (U+0129): found 4, expected one of: {2, 3, 6}
* ntilde (U+00F1): found 5, expected one of: {6, 2, 3}
* otilde (U+00F5): found 5, expected one of: {3, 4, 7}
* germandbls (U+00DF): found 3, expected one of: {5, 1, 2}
* utilde (U+0169): found 5, expected one of: {6, 2, 3}
* uni1EF9 (U+1EF9): found 4, expected one of: {6, 3, 2}
* aogonek.ss02 (unencoded): found 5, expected one of: {3, 2, 4}
* atilde.ss02 (unencoded): found 5, expected one of: {3, 2, 4}
* uni00B3 (U+00B3): found 3, expected one of: {1, 2}
* semicolon (U+003B): found 3, expected one of: {6, 2}
* quotedblbase (U+201E): found 4, expected one of: {2, 6}
* quotedblleft (U+201C): found 4, expected one of: {6, 2}
* quotedblright (U+201D): found 4, expected one of: {2, 6}
* uni2117 (U+2117): found 18, expected one of: {3, 4}
* uni2120 (U+2120): found 16, expected one of: {3, 2}
* tildecomb (U+0303): found 3, expected one of: {1}
* uni0312 (U+0312): found 2, expected one of: {1}
* uni0326 (U+0326): found 2, expected one of: {1}
* uni0327 (U+0327): found 2, expected one of: {1}
* uni0328 (U+0328): found 3, expected one of: {1}
* tilde (U+02DC): found 3, expected one of: {1}
* cedilla (U+00B8): found 2, expected one of: {5, 1}
* ogonek (U+02DB): found 3, expected one of: {1}
* uni02BB (U+02BB): found 2, expected one of: {1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 532 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=570: approxequal
width=494: logicalnot, multiply, minus
width=608: lessequal, notequal, greaterequal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* vercelLogo [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̀
* į̂
* į̌
* į́
* į̃
* į̄The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̧̆
* į̧̀
* į̧̊
* į̧̈
* į̧̂
* į̧̋
* į̧̌
* į̧́
* į̧̇
* į̧̃
* į̧̄
* į̧̒
* į̦̆
* į̦̀
* į̦̊
* į̦̈
* į̦̂
* į̦̋
* į̦̌
* į̦́
* į̦̇
* į̦̃
* į̦̄
* į̦̒
* į̨̆
* į̨̀
* į̨̊
* į̨̈
* į̨̂
* į̨̋
* į̨̌
* į̨́
* į̨̇
* į̨̃
* į̨̄
* į̨̒
* į̆
* į̊
* į̈
* į̋
* į̇
* į̒ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - ohungarumlaut (U+0151): X=380,Y=723 (should be at cap-height 722?)
* - ohungarumlaut (U+0151): X=494,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=380,Y=723 (should be at cap-height 722?)
* - uhungarumlaut (U+0171): X=494,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=304,Y=723 (should be at cap-height 722?)
* - uni030B (U+030B): X=418,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=304,Y=723 (should be at cap-height 722?)
* - hungarumlaut (U+02DD): X=418,Y=723 (should be at cap-height 722?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* fi (U+FB01): Line(Line { p0: (342.0, 456.0), p1: (342.0, 532.0) }) has the same coordinates as a previous segment.
* fl (U+FB02): Line(Line { p0: (342.0, 646.0), p1: (342.0, 722.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* ae (U+00E6) contains a short segment Line(Line { p0: (76.0, 228.0), p1: (114.0, 228.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (114.0, 228.0), p1: (114.0, 266.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 266.0), p1: (190.0, 304.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 304.0), p1: (380.0, 342.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 342.0), p1: (418.0, 342.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (418.0, 418.0), p1: (380.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 418.0), p1: (380.0, 456.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 456.0), p1: (190.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 418.0), p1: (152.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (152.0, 418.0), p1: (152.0, 380.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (76.0, 456.0), p1: (114.0, 456.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (114.0, 456.0), p1: (114.0, 494.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 494.0), p1: (190.0, 532.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 532.0), p1: (380.0, 494.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (456.0, 418.0), p1: (494.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (798.0, 380.0), p1: (760.0, 380.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 380.0), p1: (760.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 418.0), p1: (722.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (722.0, 418.0), p1: (722.0, 456.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (570.0, 456.0), p1: (570.0, 418.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (494.0, 494.0), p1: (532.0, 494.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (532.0, 494.0), p1: (532.0, 532.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 532.0), p1: (760.0, 494.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 494.0), p1: (798.0, 494.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (798.0, 494.0), p1: (798.0, 456.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (798.0, 456.0), p1: (836.0, 456.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (836.0, 380.0), p1: (874.0, 380.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (494.0, 152.0), p1: (532.0, 152.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (532.0, 152.0), p1: (532.0, 114.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (532.0, 114.0), p1: (570.0, 114.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (570.0, 114.0), p1: (570.0, 76.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 76.0), p1: (760.0, 114.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 114.0), p1: (798.0, 114.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (798.0, 114.0), p1: (798.0, 152.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (874.0, 76.0), p1: (836.0, 76.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (836.0, 76.0), p1: (836.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (760.0, 38.0), p1: (760.0, 0.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (532.0, 0.0), p1: (532.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (532.0, 38.0), p1: (494.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (494.0, 38.0), p1: (494.0, 76.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (418.0, 266.0), p1: (380.0, 266.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 266.0), p1: (380.0, 228.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 228.0), p1: (190.0, 190.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (190.0, 190.0), p1: (152.0, 190.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (418.0, 76.0), p1: (418.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (418.0, 38.0), p1: (380.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (380.0, 38.0), p1: (380.0, 0.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (152.0, 0.0), p1: (152.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (152.0, 38.0), p1: (114.0, 38.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (114.0, 38.0), p1: (114.0, 76.0) })
* ae (U+00E6) contains a short segment Line(Line { p0: (114.0, 76.0), p1: (76.0, 76.0) }) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'VRCL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 10 | 75 | 27 | 410 | 245 | 
| 1% | 10% | 4% | 55% | 33% | 



