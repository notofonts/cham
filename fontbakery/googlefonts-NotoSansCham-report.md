## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansCham/googlefonts/ttf', 'fonts/NotoSansCham/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[9] NotoSansCham-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* pha_cham
	* five_cham
	* ai_cham
	* da_cham
	* raMedial_cham
	* ka_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* three (U+0033): X=35.0,Y=652.0 (should be at cap-height 653?)

	* question (U+003F): X=0.0,Y=655.0 (should be at cap-height 653?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* P (U+0050): X=527.5,Y=655.0 (should be at cap-height 653?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?) 

	* And 83 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] NotoSansCham-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* pha_cham
	* da_cham
	* ka_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt
	* a_cham
	* ppa_cham
	* eight_cham and 40 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=101.5,Y=631.5 (should be at cap-height 630?)

	* asterisk (U+002A): X=498.0,Y=631.0 (should be at cap-height 630?)

	* asterisk (U+002A): X=50.0,Y=631.0 (should be at cap-height 630?)

	* zero (U+0030): X=474.0,Y=628.0 (should be at cap-height 630?)

	* two (U+0032): X=491.5,Y=629.5 (should be at cap-height 630?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* I (U+0049): X=32.0,Y=628.0 (should be at cap-height 630?)

	* I (U+0049): X=357.0,Y=628.0 (should be at cap-height 630?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?) 

	* And 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<717.0,175.0>--<717.0,176.0>> -> L<<717.0,176.0>--<717.0,177.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] NotoSansCham-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* pha_cham
	* da_cham
	* ka_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt
	* a_cham
	* ppa_cham
	* ssFinal_cham and 44 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=528.0,Y=643.0 (should be at cap-height 641?)

	* comma (U+002C): X=57.5,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=57.5,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=535.5,Y=1.5 (should be at baseline 0?)

	* S (U+0053): X=142.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=298.0,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=405.0,Y=1.5 (should be at baseline 0?)

	* e (U+0065): X=441.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=341.0,Y=538.0 (should be at x-height 536?) 

	* And 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357 

	* And Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansCham-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=141.5,Y=1.5 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=72.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=141.5,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.5 (should be at baseline 0?)

	* three (U+0033): X=136.5,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=149.5,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=95.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=141.5,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.5 (should be at baseline 0?) 

	* And 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[7] NotoSansCham-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=469.0,Y=576.0 (should be at cap-height 575?)

	* ampersand (U+0026): X=130.0,Y=573.0 (should be at cap-height 575?)

	* ampersand (U+0026): X=186.0,Y=573.0 (should be at cap-height 575?)

	* ampersand (U+0026): X=412.0,Y=576.0 (should be at cap-height 575?)

	* five (U+0035): X=147.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=98.0,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=483.0,Y=573.5 (should be at cap-height 575?)

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=478.0,Y=2.0 (should be at baseline 0?) 

	* And 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[10] NotoSansCham-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt
	* ppa_cham
	* eight_cham
	* ja_cham
	* chha_cham
	* jha_cham
	* ngFinal_cham and 16 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<687.0,165.0>--<687.0,167.0>> -> L<<687.0,167.0>--<687.0,169.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* nhja_cham (U+AA12): B<<349.5,-51.5>-<362.0,-22.0>-<381.0,-6.0>>/B<<381.0,-6.0>-<352.0,-21.0>-<313.0,-21.0>> = 12.751031766142344 

	* And nhja_cham (U+AA12): B<<437.0,86.0>-<437.0,35.0>-<400.0,6.0>>/B<<400.0,6.0>-<418.0,14.0>-<443.0,17.5>> = 14.126283906397104 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] NotoSansCham-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/cham.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansCham/googlefonts/ttf/NotoSansCham-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/cham.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ꨫ ꨴꨆꨪꨖꨵꨳꨖꨶꨳꩆ꩗</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+594|iiSign_cham=0@-69,0+-125|space=1+260|raMedial_cham_pre=1+400|uni25CC=1+594|ka_cham=3+855|iSign_cham=3@-7,0+0|dha_cham=5+1047|laMedial_cham.narrow=5@51,2+0|yaMedial_cham=5+542|dha_cham=8+1047|waMedial_cham.narrow=8@-182,2+0|yaMedial_cham=8+542|nFinal_cham=11+1086|seven_cham=12+914</pre>



<pre>Got     : uni25CC=0+594|iiSign_cham=0@-69,0+135|raMedial_cham_pre=1+400|space=1+260|ka_cham=3+855|iSign_cham=3@-7,0+0|dha_cham=5+1047|laMedial_cham.narrow=5@51,2+0|yaMedial_cham=5+542|dha_cham=8+1047|waMedial_cham.narrow=8@-182,2+0|yaMedial_cham=8+542|nFinal_cham=11+1086|seven_cham=12+914</pre>



<pre>                                            ^^^^             ++++++++++++++++++++++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7422 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(0, 851)"/>
<path d="M61.0,820.0Q61.0,741.0 19.5,662.0Q-22.0,583.0 -99.0,508.0L-152.0,555.0Q-115.0,589.0 -103.5,609.0Q-92.0,629.0 -92.0,654.0Q-92.0,676.0 -108.5,689.0Q-125.0,702.0 -161.0,702.0L-196.0,702.0Q-268.0,702.0 -309.0,741.5Q-350.0,781.0 -350.0,844.0Q-350.0,924.0 -296.0,973.5Q-242.0,1023.0 -148.0,1023.0Q-88.0,1023.0 -41.0,998.0Q6.0,973.0 33.5,927.5Q61.0,882.0 61.0,820.0ZM-16.0,820.0Q-16.0,887.0 -53.0,923.5Q-90.0,960.0 -149.0,960.0Q-208.0,960.0 -242.0,929.5Q-276.0,899.0 -276.0,851.0Q-276.0,811.0 -251.0,787.0Q-226.0,763.0 -180.0,763.0L-137.0,763.0Q-53.0,763.0 -46.0,687.0Q-31.0,717.0 -23.5,752.0Q-16.0,787.0 -16.0,820.0ZM-146.0,811.0Q-167.0,811.0 -179.0,823.5Q-191.0,836.0 -191.0,856.0Q-191.0,902.0 -146.0,902.0Q-101.0,902.0 -101.0,856.0Q-101.0,836.0 -113.0,823.5Q-125.0,811.0 -146.0,811.0Z"  transform="translate(525, 851)"/>
<path d="M887.0,-334.0Q812.0,-284.0 757.0,-261.0Q702.0,-238.0 661.0,-238.0Q625.0,-238.0 599.0,-258.0Q573.0,-278.0 561.0,-313.0L499.0,-334.0Q424.0,-295.0 358.0,-230.5Q292.0,-166.0 241.5,-82.0Q191.0,2.0 162.5,102.0Q134.0,202.0 134.0,313.0Q134.0,607.0 353.0,840.0L197.0,840.0Q147.0,840.0 119.0,819.0Q91.0,798.0 91.0,768.0Q91.0,752.0 95.5,739.5Q100.0,727.0 110.0,710.0L45.0,671.0Q25.0,699.0 18.0,720.5Q11.0,742.0 11.0,769.0Q11.0,830.0 62.5,869.0Q114.0,908.0 196.0,908.0L427.0,908.0L459.0,850.0Q223.0,612.0 223.0,313.0Q223.0,216.0 246.0,128.0Q269.0,40.0 309.5,-35.0Q350.0,-110.0 402.5,-168.5Q455.0,-227.0 514.0,-265.0Q534.0,-218.0 572.0,-194.0Q610.0,-170.0 659.0,-170.0Q710.0,-170.0 778.0,-197.0Q846.0,-224.0 922.0,-276.0L887.0,-334.0Z"  transform="translate(729, 851)"/>
<path d=""  transform="translate(1129, 851)"/>
<path d="M802.0,417.0Q802.0,377.0 788.5,342.0Q775.0,307.0 743.0,274.0L680.0,320.0Q718.0,361.0 718.0,418.0Q718.0,468.0 689.0,496.5Q660.0,525.0 609.0,525.0Q558.0,525.0 524.0,489.0Q490.0,453.0 491.0,379.0L417.0,379.0Q419.0,453.0 386.5,489.0Q354.0,525.0 302.0,525.0Q252.0,525.0 222.5,496.0Q193.0,467.0 193.0,420.0Q193.0,382.0 208.5,343.0Q224.0,304.0 239.5,261.0Q255.0,218.0 255.0,168.0Q255.0,84.0 204.0,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 195.0,572.5Q236.0,594.0 289.0,594.0Q343.0,594.0 386.0,570.5Q429.0,547.0 454.0,503.0Q478.0,547.0 521.5,570.5Q565.0,594.0 620.0,594.0Q702.0,594.0 752.0,545.5Q802.0,497.0 802.0,417.0Z"  transform="translate(1389, 851)"/>
<path d="M61.0,821.0Q61.0,741.0 19.5,662.0Q-22.0,583.0 -99.0,508.0L-152.0,555.0Q-115.0,589.0 -103.5,609.0Q-92.0,629.0 -92.0,654.0Q-92.0,676.0 -108.5,689.0Q-125.0,702.0 -161.0,702.0L-196.0,702.0Q-269.0,702.0 -310.0,741.0Q-351.0,780.0 -351.0,844.0Q-351.0,897.0 -326.0,937.0Q-301.0,977.0 -255.0,1000.0Q-209.0,1023.0 -147.0,1023.0Q-88.0,1023.0 -41.0,998.0Q6.0,973.0 33.5,927.5Q61.0,882.0 61.0,821.0ZM-19.0,821.0Q-19.0,886.0 -55.5,922.0Q-92.0,958.0 -148.0,958.0Q-206.0,958.0 -239.0,927.5Q-272.0,897.0 -272.0,850.0Q-272.0,810.0 -248.5,787.5Q-225.0,765.0 -180.0,765.0L-137.0,765.0Q-57.0,765.0 -47.0,696.0Q-33.0,727.0 -26.0,759.5Q-19.0,792.0 -19.0,821.0Z"  transform="translate(2237, 851)"/>
<path d="M994.0,421.0Q994.0,381.0 978.5,343.5Q963.0,306.0 931.0,276.0L868.0,324.0Q887.0,344.0 898.5,368.5Q910.0,393.0 910.0,421.0Q910.0,470.0 881.0,497.5Q852.0,525.0 802.0,525.0Q752.0,525.0 724.5,498.5Q697.0,472.0 697.0,428.0Q697.0,404.0 703.5,381.5Q710.0,359.0 710.0,335.0Q710.0,294.0 694.0,268.0Q678.0,242.0 654.5,224.0Q631.0,206.0 607.0,191.0Q583.0,176.0 567.0,157.5Q551.0,139.0 551.0,111.0Q551.0,89.0 559.5,73.5Q568.0,58.0 586.0,37.0L564.0,-16.0Q551.0,-17.0 534.0,-17.0Q517.0,-17.0 499.0,-17.0Q435.0,-17.0 387.0,7.0Q339.0,31.0 313.0,73.0Q287.0,115.0 287.0,170.0Q287.0,205.0 297.0,235.5Q307.0,266.0 320.0,295.0Q333.0,324.0 343.0,353.0Q353.0,382.0 353.0,414.0Q353.0,464.0 325.5,494.5Q298.0,525.0 248.0,525.0Q198.0,525.0 167.5,497.5Q137.0,470.0 137.0,421.0Q137.0,393.0 148.5,368.0Q160.0,343.0 178.0,323.0L116.0,275.0Q85.0,306.0 69.0,343.5Q53.0,381.0 53.0,419.0Q53.0,499.0 107.0,546.5Q161.0,594.0 249.0,594.0Q333.0,594.0 386.0,546.5Q439.0,499.0 439.0,417.0Q439.0,380.0 429.0,348.0Q419.0,316.0 406.0,287.0Q393.0,258.0 383.0,229.0Q373.0,200.0 373.0,170.0Q373.0,118.0 403.0,85.0Q433.0,52.0 484.0,52.0L491.0,52.0Q478.0,69.0 473.0,85.0Q468.0,101.0 468.0,122.0Q468.0,158.0 484.0,181.0Q500.0,204.0 523.0,221.0Q546.0,238.0 569.0,254.0Q592.0,270.0 608.0,291.5Q624.0,313.0 624.0,346.0Q624.0,363.0 617.5,387.5Q611.0,412.0 611.0,439.0Q611.0,508.0 663.0,551.0Q715.0,594.0 803.0,594.0Q889.0,594.0 941.5,546.5Q994.0,499.0 994.0,421.0Z"  transform="translate(2244, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0Z"  transform="translate(3342, 853)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(3291, 851)"/>
<path d="M994.0,421.0Q994.0,381.0 978.5,343.5Q963.0,306.0 931.0,276.0L868.0,324.0Q887.0,344.0 898.5,368.5Q910.0,393.0 910.0,421.0Q910.0,470.0 881.0,497.5Q852.0,525.0 802.0,525.0Q752.0,525.0 724.5,498.5Q697.0,472.0 697.0,428.0Q697.0,404.0 703.5,381.5Q710.0,359.0 710.0,335.0Q710.0,294.0 694.0,268.0Q678.0,242.0 654.5,224.0Q631.0,206.0 607.0,191.0Q583.0,176.0 567.0,157.5Q551.0,139.0 551.0,111.0Q551.0,89.0 559.5,73.5Q568.0,58.0 586.0,37.0L564.0,-16.0Q551.0,-17.0 534.0,-17.0Q517.0,-17.0 499.0,-17.0Q435.0,-17.0 387.0,7.0Q339.0,31.0 313.0,73.0Q287.0,115.0 287.0,170.0Q287.0,205.0 297.0,235.5Q307.0,266.0 320.0,295.0Q333.0,324.0 343.0,353.0Q353.0,382.0 353.0,414.0Q353.0,464.0 325.5,494.5Q298.0,525.0 248.0,525.0Q198.0,525.0 167.5,497.5Q137.0,470.0 137.0,421.0Q137.0,393.0 148.5,368.0Q160.0,343.0 178.0,323.0L116.0,275.0Q85.0,306.0 69.0,343.5Q53.0,381.0 53.0,419.0Q53.0,499.0 107.0,546.5Q161.0,594.0 249.0,594.0Q333.0,594.0 386.0,546.5Q439.0,499.0 439.0,417.0Q439.0,380.0 429.0,348.0Q419.0,316.0 406.0,287.0Q393.0,258.0 383.0,229.0Q373.0,200.0 373.0,170.0Q373.0,118.0 403.0,85.0Q433.0,52.0 484.0,52.0L491.0,52.0Q478.0,69.0 473.0,85.0Q468.0,101.0 468.0,122.0Q468.0,158.0 484.0,181.0Q500.0,204.0 523.0,221.0Q546.0,238.0 569.0,254.0Q592.0,270.0 608.0,291.5Q624.0,313.0 624.0,346.0Q624.0,363.0 617.5,387.5Q611.0,412.0 611.0,439.0Q611.0,508.0 663.0,551.0Q715.0,594.0 803.0,594.0Q889.0,594.0 941.5,546.5Q994.0,499.0 994.0,421.0Z"  transform="translate(3833, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(4698, 853)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(4880, 851)"/>
<path d="M1033.0,327.0Q1033.0,242.0 1004.0,158.5Q975.0,75.0 922.0,3.0Q869.0,-69.0 796.0,-122.0L738.0,-66.0Q803.0,-19.0 850.0,44.0Q897.0,107.0 922.5,179.5Q948.0,252.0 948.0,328.0Q948.0,421.0 914.0,473.0Q880.0,525.0 818.0,525.0Q771.0,525.0 744.0,498.0Q717.0,471.0 717.0,424.0Q717.0,389.0 726.0,355.0Q735.0,321.0 743.5,285.0Q752.0,249.0 752.0,205.0Q752.0,135.0 713.5,76.5Q675.0,18.0 615.0,-17.0L574.0,15.0Q580.0,95.0 555.0,151.0Q530.0,207.0 486.0,234.0Q477.0,119.0 425.0,51.0Q373.0,-17.0 294.0,-17.0Q235.0,-17.0 195.5,20.5Q156.0,58.0 156.0,124.0Q156.0,182.0 187.0,227.0Q218.0,272.0 270.5,298.5Q323.0,325.0 388.0,325.0Q395.0,325.0 403.0,325.0Q396.0,424.0 355.5,474.5Q315.0,525.0 251.0,525.0Q201.0,525.0 172.0,499.0Q143.0,473.0 143.0,429.0Q143.0,404.0 152.0,383.0Q161.0,362.0 174.0,347.0L118.0,302.0Q93.0,325.0 77.0,359.0Q61.0,393.0 61.0,435.0Q61.0,504.0 111.0,549.0Q161.0,594.0 249.0,594.0Q352.0,594.0 416.5,520.0Q481.0,446.0 487.0,307.0Q551.0,282.0 590.0,226.5Q629.0,171.0 638.0,98.0Q653.0,120.0 661.5,146.5Q670.0,173.0 670.0,199.0Q670.0,236.0 660.5,271.5Q651.0,307.0 641.0,345.5Q631.0,384.0 631.0,426.0Q631.0,501.0 681.5,547.5Q732.0,594.0 817.0,594.0Q921.0,594.0 977.0,522.5Q1033.0,451.0 1033.0,327.0ZM239.0,127.0Q239.0,92.0 254.5,71.5Q270.0,51.0 296.0,51.0Q340.0,51.0 370.0,106.0Q400.0,161.0 403.0,258.0L399.0,258.0Q348.0,258.0 312.0,239.0Q276.0,220.0 257.5,190.5Q239.0,161.0 239.0,127.0Z"  transform="translate(5422, 851)"/>
<path d="M829.0,333.0Q829.0,250.0 811.5,185.5Q794.0,121.0 750.5,69.0Q707.0,17.0 629.0,-28.0Q569.0,-63.0 540.5,-91.5Q512.0,-120.0 503.0,-141.5Q494.0,-163.0 494.0,-177.0Q494.0,-196.0 506.0,-210.0Q518.0,-224.0 540.0,-224.0Q560.0,-224.0 576.0,-209.0Q592.0,-194.0 607.5,-172.0Q623.0,-150.0 641.5,-128.0Q660.0,-106.0 685.5,-91.0Q711.0,-76.0 748.0,-76.0Q792.0,-76.0 820.5,-104.0Q849.0,-132.0 849.0,-172.0Q849.0,-189.0 842.5,-211.5Q836.0,-234.0 822.0,-253.0L754.0,-222.0Q768.0,-202.0 768.0,-183.0Q768.0,-149.0 733.0,-149.0Q714.0,-149.0 699.0,-164.0Q684.0,-179.0 669.0,-201.5Q654.0,-224.0 635.5,-246.5Q617.0,-269.0 591.5,-284.0Q566.0,-299.0 529.0,-299.0Q480.0,-299.0 445.0,-266.5Q410.0,-234.0 410.0,-184.0Q410.0,-152.0 423.5,-120.5Q437.0,-89.0 472.5,-54.0Q508.0,-19.0 574.0,21.0Q635.0,58.0 672.0,98.5Q709.0,139.0 726.0,194.5Q743.0,250.0 743.0,331.0Q743.0,422.0 710.5,473.5Q678.0,525.0 611.0,525.0Q559.0,525.0 529.5,495.5Q500.0,466.0 500.0,418.0Q500.0,381.0 510.0,346.5Q520.0,312.0 530.0,275.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 445.0,272.5Q435.0,308.0 425.0,344.5Q415.0,381.0 415.0,424.0Q415.0,475.0 439.5,513.5Q464.0,552.0 508.0,573.0Q552.0,594.0 609.0,594.0Q717.0,594.0 773.0,523.0Q829.0,452.0 829.0,333.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0Z"  transform="translate(6508, 851)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7756 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(0, 851)"/>
<path d="M61.0,820.0Q61.0,741.0 19.5,662.0Q-22.0,583.0 -99.0,508.0L-152.0,555.0Q-115.0,589.0 -103.5,609.0Q-92.0,629.0 -92.0,654.0Q-92.0,676.0 -108.5,689.0Q-125.0,702.0 -161.0,702.0L-196.0,702.0Q-268.0,702.0 -309.0,741.5Q-350.0,781.0 -350.0,844.0Q-350.0,924.0 -296.0,973.5Q-242.0,1023.0 -148.0,1023.0Q-88.0,1023.0 -41.0,998.0Q6.0,973.0 33.5,927.5Q61.0,882.0 61.0,820.0ZM-16.0,820.0Q-16.0,887.0 -53.0,923.5Q-90.0,960.0 -149.0,960.0Q-208.0,960.0 -242.0,929.5Q-276.0,899.0 -276.0,851.0Q-276.0,811.0 -251.0,787.0Q-226.0,763.0 -180.0,763.0L-137.0,763.0Q-53.0,763.0 -46.0,687.0Q-31.0,717.0 -23.5,752.0Q-16.0,787.0 -16.0,820.0ZM-146.0,811.0Q-167.0,811.0 -179.0,823.5Q-191.0,836.0 -191.0,856.0Q-191.0,902.0 -146.0,902.0Q-101.0,902.0 -101.0,856.0Q-101.0,836.0 -113.0,823.5Q-125.0,811.0 -146.0,811.0Z"  transform="translate(525, 851)"/>
<path d=""  transform="translate(469, 851)"/>
<path d="M887.0,-334.0Q812.0,-284.0 757.0,-261.0Q702.0,-238.0 661.0,-238.0Q625.0,-238.0 599.0,-258.0Q573.0,-278.0 561.0,-313.0L499.0,-334.0Q424.0,-295.0 358.0,-230.5Q292.0,-166.0 241.5,-82.0Q191.0,2.0 162.5,102.0Q134.0,202.0 134.0,313.0Q134.0,607.0 353.0,840.0L197.0,840.0Q147.0,840.0 119.0,819.0Q91.0,798.0 91.0,768.0Q91.0,752.0 95.5,739.5Q100.0,727.0 110.0,710.0L45.0,671.0Q25.0,699.0 18.0,720.5Q11.0,742.0 11.0,769.0Q11.0,830.0 62.5,869.0Q114.0,908.0 196.0,908.0L427.0,908.0L459.0,850.0Q223.0,612.0 223.0,313.0Q223.0,216.0 246.0,128.0Q269.0,40.0 309.5,-35.0Q350.0,-110.0 402.5,-168.5Q455.0,-227.0 514.0,-265.0Q534.0,-218.0 572.0,-194.0Q610.0,-170.0 659.0,-170.0Q710.0,-170.0 778.0,-197.0Q846.0,-224.0 922.0,-276.0L887.0,-334.0Z"  transform="translate(729, 851)"/>
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(1129, 851)"/>
<path d="M802.0,417.0Q802.0,377.0 788.5,342.0Q775.0,307.0 743.0,274.0L680.0,320.0Q718.0,361.0 718.0,418.0Q718.0,468.0 689.0,496.5Q660.0,525.0 609.0,525.0Q558.0,525.0 524.0,489.0Q490.0,453.0 491.0,379.0L417.0,379.0Q419.0,453.0 386.5,489.0Q354.0,525.0 302.0,525.0Q252.0,525.0 222.5,496.0Q193.0,467.0 193.0,420.0Q193.0,382.0 208.5,343.0Q224.0,304.0 239.5,261.0Q255.0,218.0 255.0,168.0Q255.0,84.0 204.0,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 195.0,572.5Q236.0,594.0 289.0,594.0Q343.0,594.0 386.0,570.5Q429.0,547.0 454.0,503.0Q478.0,547.0 521.5,570.5Q565.0,594.0 620.0,594.0Q702.0,594.0 752.0,545.5Q802.0,497.0 802.0,417.0Z"  transform="translate(1723, 851)"/>
<path d="M61.0,821.0Q61.0,741.0 19.5,662.0Q-22.0,583.0 -99.0,508.0L-152.0,555.0Q-115.0,589.0 -103.5,609.0Q-92.0,629.0 -92.0,654.0Q-92.0,676.0 -108.5,689.0Q-125.0,702.0 -161.0,702.0L-196.0,702.0Q-269.0,702.0 -310.0,741.0Q-351.0,780.0 -351.0,844.0Q-351.0,897.0 -326.0,937.0Q-301.0,977.0 -255.0,1000.0Q-209.0,1023.0 -147.0,1023.0Q-88.0,1023.0 -41.0,998.0Q6.0,973.0 33.5,927.5Q61.0,882.0 61.0,821.0ZM-19.0,821.0Q-19.0,886.0 -55.5,922.0Q-92.0,958.0 -148.0,958.0Q-206.0,958.0 -239.0,927.5Q-272.0,897.0 -272.0,850.0Q-272.0,810.0 -248.5,787.5Q-225.0,765.0 -180.0,765.0L-137.0,765.0Q-57.0,765.0 -47.0,696.0Q-33.0,727.0 -26.0,759.5Q-19.0,792.0 -19.0,821.0Z"  transform="translate(2571, 851)"/>
<path d="M994.0,421.0Q994.0,381.0 978.5,343.5Q963.0,306.0 931.0,276.0L868.0,324.0Q887.0,344.0 898.5,368.5Q910.0,393.0 910.0,421.0Q910.0,470.0 881.0,497.5Q852.0,525.0 802.0,525.0Q752.0,525.0 724.5,498.5Q697.0,472.0 697.0,428.0Q697.0,404.0 703.5,381.5Q710.0,359.0 710.0,335.0Q710.0,294.0 694.0,268.0Q678.0,242.0 654.5,224.0Q631.0,206.0 607.0,191.0Q583.0,176.0 567.0,157.5Q551.0,139.0 551.0,111.0Q551.0,89.0 559.5,73.5Q568.0,58.0 586.0,37.0L564.0,-16.0Q551.0,-17.0 534.0,-17.0Q517.0,-17.0 499.0,-17.0Q435.0,-17.0 387.0,7.0Q339.0,31.0 313.0,73.0Q287.0,115.0 287.0,170.0Q287.0,205.0 297.0,235.5Q307.0,266.0 320.0,295.0Q333.0,324.0 343.0,353.0Q353.0,382.0 353.0,414.0Q353.0,464.0 325.5,494.5Q298.0,525.0 248.0,525.0Q198.0,525.0 167.5,497.5Q137.0,470.0 137.0,421.0Q137.0,393.0 148.5,368.0Q160.0,343.0 178.0,323.0L116.0,275.0Q85.0,306.0 69.0,343.5Q53.0,381.0 53.0,419.0Q53.0,499.0 107.0,546.5Q161.0,594.0 249.0,594.0Q333.0,594.0 386.0,546.5Q439.0,499.0 439.0,417.0Q439.0,380.0 429.0,348.0Q419.0,316.0 406.0,287.0Q393.0,258.0 383.0,229.0Q373.0,200.0 373.0,170.0Q373.0,118.0 403.0,85.0Q433.0,52.0 484.0,52.0L491.0,52.0Q478.0,69.0 473.0,85.0Q468.0,101.0 468.0,122.0Q468.0,158.0 484.0,181.0Q500.0,204.0 523.0,221.0Q546.0,238.0 569.0,254.0Q592.0,270.0 608.0,291.5Q624.0,313.0 624.0,346.0Q624.0,363.0 617.5,387.5Q611.0,412.0 611.0,439.0Q611.0,508.0 663.0,551.0Q715.0,594.0 803.0,594.0Q889.0,594.0 941.5,546.5Q994.0,499.0 994.0,421.0Z"  transform="translate(2578, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0Z"  transform="translate(3676, 853)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(3625, 851)"/>
<path d="M994.0,421.0Q994.0,381.0 978.5,343.5Q963.0,306.0 931.0,276.0L868.0,324.0Q887.0,344.0 898.5,368.5Q910.0,393.0 910.0,421.0Q910.0,470.0 881.0,497.5Q852.0,525.0 802.0,525.0Q752.0,525.0 724.5,498.5Q697.0,472.0 697.0,428.0Q697.0,404.0 703.5,381.5Q710.0,359.0 710.0,335.0Q710.0,294.0 694.0,268.0Q678.0,242.0 654.5,224.0Q631.0,206.0 607.0,191.0Q583.0,176.0 567.0,157.5Q551.0,139.0 551.0,111.0Q551.0,89.0 559.5,73.5Q568.0,58.0 586.0,37.0L564.0,-16.0Q551.0,-17.0 534.0,-17.0Q517.0,-17.0 499.0,-17.0Q435.0,-17.0 387.0,7.0Q339.0,31.0 313.0,73.0Q287.0,115.0 287.0,170.0Q287.0,205.0 297.0,235.5Q307.0,266.0 320.0,295.0Q333.0,324.0 343.0,353.0Q353.0,382.0 353.0,414.0Q353.0,464.0 325.5,494.5Q298.0,525.0 248.0,525.0Q198.0,525.0 167.5,497.5Q137.0,470.0 137.0,421.0Q137.0,393.0 148.5,368.0Q160.0,343.0 178.0,323.0L116.0,275.0Q85.0,306.0 69.0,343.5Q53.0,381.0 53.0,419.0Q53.0,499.0 107.0,546.5Q161.0,594.0 249.0,594.0Q333.0,594.0 386.0,546.5Q439.0,499.0 439.0,417.0Q439.0,380.0 429.0,348.0Q419.0,316.0 406.0,287.0Q393.0,258.0 383.0,229.0Q373.0,200.0 373.0,170.0Q373.0,118.0 403.0,85.0Q433.0,52.0 484.0,52.0L491.0,52.0Q478.0,69.0 473.0,85.0Q468.0,101.0 468.0,122.0Q468.0,158.0 484.0,181.0Q500.0,204.0 523.0,221.0Q546.0,238.0 569.0,254.0Q592.0,270.0 608.0,291.5Q624.0,313.0 624.0,346.0Q624.0,363.0 617.5,387.5Q611.0,412.0 611.0,439.0Q611.0,508.0 663.0,551.0Q715.0,594.0 803.0,594.0Q889.0,594.0 941.5,546.5Q994.0,499.0 994.0,421.0Z"  transform="translate(4167, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(5032, 853)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(5214, 851)"/>
<path d="M1033.0,327.0Q1033.0,242.0 1004.0,158.5Q975.0,75.0 922.0,3.0Q869.0,-69.0 796.0,-122.0L738.0,-66.0Q803.0,-19.0 850.0,44.0Q897.0,107.0 922.5,179.5Q948.0,252.0 948.0,328.0Q948.0,421.0 914.0,473.0Q880.0,525.0 818.0,525.0Q771.0,525.0 744.0,498.0Q717.0,471.0 717.0,424.0Q717.0,389.0 726.0,355.0Q735.0,321.0 743.5,285.0Q752.0,249.0 752.0,205.0Q752.0,135.0 713.5,76.5Q675.0,18.0 615.0,-17.0L574.0,15.0Q580.0,95.0 555.0,151.0Q530.0,207.0 486.0,234.0Q477.0,119.0 425.0,51.0Q373.0,-17.0 294.0,-17.0Q235.0,-17.0 195.5,20.5Q156.0,58.0 156.0,124.0Q156.0,182.0 187.0,227.0Q218.0,272.0 270.5,298.5Q323.0,325.0 388.0,325.0Q395.0,325.0 403.0,325.0Q396.0,424.0 355.5,474.5Q315.0,525.0 251.0,525.0Q201.0,525.0 172.0,499.0Q143.0,473.0 143.0,429.0Q143.0,404.0 152.0,383.0Q161.0,362.0 174.0,347.0L118.0,302.0Q93.0,325.0 77.0,359.0Q61.0,393.0 61.0,435.0Q61.0,504.0 111.0,549.0Q161.0,594.0 249.0,594.0Q352.0,594.0 416.5,520.0Q481.0,446.0 487.0,307.0Q551.0,282.0 590.0,226.5Q629.0,171.0 638.0,98.0Q653.0,120.0 661.5,146.5Q670.0,173.0 670.0,199.0Q670.0,236.0 660.5,271.5Q651.0,307.0 641.0,345.5Q631.0,384.0 631.0,426.0Q631.0,501.0 681.5,547.5Q732.0,594.0 817.0,594.0Q921.0,594.0 977.0,522.5Q1033.0,451.0 1033.0,327.0ZM239.0,127.0Q239.0,92.0 254.5,71.5Q270.0,51.0 296.0,51.0Q340.0,51.0 370.0,106.0Q400.0,161.0 403.0,258.0L399.0,258.0Q348.0,258.0 312.0,239.0Q276.0,220.0 257.5,190.5Q239.0,161.0 239.0,127.0Z"  transform="translate(5756, 851)"/>
<path d="M829.0,333.0Q829.0,250.0 811.5,185.5Q794.0,121.0 750.5,69.0Q707.0,17.0 629.0,-28.0Q569.0,-63.0 540.5,-91.5Q512.0,-120.0 503.0,-141.5Q494.0,-163.0 494.0,-177.0Q494.0,-196.0 506.0,-210.0Q518.0,-224.0 540.0,-224.0Q560.0,-224.0 576.0,-209.0Q592.0,-194.0 607.5,-172.0Q623.0,-150.0 641.5,-128.0Q660.0,-106.0 685.5,-91.0Q711.0,-76.0 748.0,-76.0Q792.0,-76.0 820.5,-104.0Q849.0,-132.0 849.0,-172.0Q849.0,-189.0 842.5,-211.5Q836.0,-234.0 822.0,-253.0L754.0,-222.0Q768.0,-202.0 768.0,-183.0Q768.0,-149.0 733.0,-149.0Q714.0,-149.0 699.0,-164.0Q684.0,-179.0 669.0,-201.5Q654.0,-224.0 635.5,-246.5Q617.0,-269.0 591.5,-284.0Q566.0,-299.0 529.0,-299.0Q480.0,-299.0 445.0,-266.5Q410.0,-234.0 410.0,-184.0Q410.0,-152.0 423.5,-120.5Q437.0,-89.0 472.5,-54.0Q508.0,-19.0 574.0,21.0Q635.0,58.0 672.0,98.5Q709.0,139.0 726.0,194.5Q743.0,250.0 743.0,331.0Q743.0,422.0 710.5,473.5Q678.0,525.0 611.0,525.0Q559.0,525.0 529.5,495.5Q500.0,466.0 500.0,418.0Q500.0,381.0 510.0,346.5Q520.0,312.0 530.0,275.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 445.0,272.5Q435.0,308.0 425.0,344.5Q415.0,381.0 415.0,424.0Q415.0,475.0 439.5,513.5Q464.0,552.0 508.0,573.0Q552.0,594.0 609.0,594.0Q717.0,594.0 773.0,523.0Q829.0,452.0 829.0,333.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0Z"  transform="translate(6842, 851)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ꩁꨏꨏꨶꨳ꩑,ꨶꨦꨶ</span> (Added by SIESTA)</li>


<pre>Expected: gFinal_cham=0+914|jha_cham=1+1407|jha_cham=2+1485|waMedial_cham.narrow=2@-113,-5+0|yaMedial_cham=2+542|one_cham=5+565|comma.cham=6+268|uni25CC=6+594|waMedial_cham=6@-183,-235+0|ssa_cham=8+1074|waMedial_cham.narrow=8@-66,0+0</pre>



<pre>Got     : gFinal_cham=0+914|jha_cham=1+1407|jha_cham=2+1485|waMedial_cham.narrow=2@-113,-5+0|yaMedial_cham=2+542|one_cham=5+565|comma.cham=6+268|waMedial_cham=6+0|ssa_cham=8+1074|waMedial_cham.narrow=8@-66,0+0</pre>



<pre>                                                                                                                                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6255 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M861.0,329.0Q861.0,245.0 833.5,163.5Q806.0,82.0 755.0,8.5Q704.0,-65.0 632.0,-124.0L572.0,-71.0Q634.0,-21.0 679.5,43.5Q725.0,108.0 750.0,181.0Q775.0,254.0 775.0,328.0Q775.0,422.0 738.0,473.5Q701.0,525.0 633.0,525.0Q578.0,525.0 542.5,488.0Q507.0,451.0 508.0,377.0L434.0,377.0Q436.0,448.0 402.0,486.5Q368.0,525.0 312.0,525.0Q244.0,525.0 205.0,467.5Q166.0,410.0 166.0,309.0Q166.0,237.0 182.0,183.0Q198.0,129.0 226.0,95.0Q242.0,135.0 273.0,158.5Q304.0,182.0 347.0,182.0Q395.0,182.0 426.0,155.0Q457.0,128.0 457.0,82.0Q457.0,38.0 425.5,9.5Q394.0,-19.0 339.0,-19.0Q265.0,-19.0 206.0,20.5Q147.0,60.0 113.5,133.5Q80.0,207.0 80.0,308.0Q80.0,441.0 140.5,517.5Q201.0,594.0 305.0,594.0Q362.0,594.0 405.0,569.5Q448.0,545.0 471.0,501.0Q496.0,545.0 540.0,569.5Q584.0,594.0 642.0,594.0Q746.0,594.0 803.5,523.0Q861.0,452.0 861.0,329.0ZM346.0,131.0Q314.0,131.0 294.0,109.5Q274.0,88.0 267.0,57.0Q302.0,35.0 344.0,35.0Q370.0,35.0 385.0,48.0Q400.0,61.0 400.0,83.0Q400.0,108.0 384.5,119.5Q369.0,131.0 346.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M820.0,421.0Q820.0,391.0 811.5,364.0Q803.0,337.0 791.0,312.0Q812.0,317.0 835.0,317.0Q906.0,317.0 950.5,275.5Q995.0,234.0 995.0,163.0Q995.0,131.0 986.5,102.5Q978.0,74.0 969.0,54.0Q1021.0,66.0 1048.5,102.0Q1076.0,138.0 1076.0,196.0Q1076.0,237.0 1066.0,272.5Q1056.0,308.0 1046.0,344.5Q1036.0,381.0 1036.0,424.0Q1036.0,501.0 1090.5,547.5Q1145.0,594.0 1233.0,594.0Q1323.0,594.0 1377.5,544.5Q1432.0,495.0 1432.0,415.0Q1432.0,376.0 1417.5,338.0Q1403.0,300.0 1372.0,272.0L1310.0,320.0Q1327.0,338.0 1337.0,363.5Q1347.0,389.0 1347.0,417.0Q1347.0,467.0 1317.5,496.0Q1288.0,525.0 1234.0,525.0Q1181.0,525.0 1151.0,495.5Q1121.0,466.0 1121.0,418.0Q1121.0,381.0 1131.0,346.5Q1141.0,312.0 1151.0,275.0Q1161.0,238.0 1161.0,191.0Q1161.0,97.0 1099.0,40.0Q1037.0,-17.0 925.0,-17.0Q849.0,-17.0 792.5,6.0Q736.0,29.0 705.0,69.0Q674.0,109.0 674.0,161.0L674.0,161.0L674.0,163.0L674.0,165.0Q674.0,175.0 675.0,185.0Q679.0,229.0 693.5,266.5Q708.0,304.0 721.0,339.5Q734.0,375.0 734.0,412.0Q734.0,462.0 704.0,493.5Q674.0,525.0 619.0,525.0Q563.0,525.0 530.0,495.5Q497.0,466.0 497.0,417.0Q497.0,382.0 508.0,348.0Q519.0,314.0 529.5,276.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 444.5,272.5Q434.0,308.0 423.0,344.5Q412.0,381.0 412.0,424.0Q412.0,474.0 437.5,512.5Q463.0,551.0 508.5,572.5Q554.0,594.0 615.0,594.0Q707.0,594.0 763.5,547.0Q820.0,500.0 820.0,421.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0ZM753.0,166.0Q753.0,116.0 793.0,84.0Q833.0,52.0 900.0,48.0Q909.0,69.0 916.5,98.0Q924.0,127.0 924.0,152.0Q924.0,199.0 901.0,225.0Q878.0,251.0 838.0,251.0Q798.0,251.0 775.5,227.5Q753.0,204.0 753.0,166.0Z"  transform="translate(914, 851)"/>
<path d="M820.0,421.0Q820.0,391.0 811.5,364.0Q803.0,337.0 791.0,312.0Q812.0,317.0 835.0,317.0Q906.0,317.0 950.5,275.5Q995.0,234.0 995.0,163.0Q995.0,131.0 986.5,102.5Q978.0,74.0 969.0,54.0Q1021.0,66.0 1048.5,102.0Q1076.0,138.0 1076.0,196.0Q1076.0,237.0 1066.0,272.5Q1056.0,308.0 1046.0,344.5Q1036.0,381.0 1036.0,424.0Q1036.0,501.0 1090.5,547.5Q1145.0,594.0 1233.0,594.0Q1323.0,594.0 1377.5,544.5Q1432.0,495.0 1432.0,415.0Q1432.0,376.0 1417.5,338.0Q1403.0,300.0 1372.0,272.0L1310.0,320.0Q1327.0,338.0 1337.0,363.5Q1347.0,389.0 1347.0,417.0Q1347.0,467.0 1317.5,496.0Q1288.0,525.0 1234.0,525.0Q1181.0,525.0 1151.0,495.5Q1121.0,466.0 1121.0,418.0Q1121.0,381.0 1131.0,346.5Q1141.0,312.0 1151.0,275.0Q1161.0,238.0 1161.0,191.0Q1161.0,97.0 1099.0,40.0Q1037.0,-17.0 925.0,-17.0Q849.0,-17.0 792.5,6.0Q736.0,29.0 705.0,69.0Q674.0,109.0 674.0,161.0L674.0,161.0L674.0,163.0L674.0,165.0Q674.0,175.0 675.0,185.0Q679.0,229.0 693.5,266.5Q708.0,304.0 721.0,339.5Q734.0,375.0 734.0,412.0Q734.0,462.0 704.0,493.5Q674.0,525.0 619.0,525.0Q563.0,525.0 530.0,495.5Q497.0,466.0 497.0,417.0Q497.0,382.0 508.0,348.0Q519.0,314.0 529.5,276.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 444.5,272.5Q434.0,308.0 423.0,344.5Q412.0,381.0 412.0,424.0Q412.0,474.0 437.5,512.5Q463.0,551.0 508.5,572.5Q554.0,594.0 615.0,594.0Q707.0,594.0 763.5,547.0Q820.0,500.0 820.0,421.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0ZM753.0,166.0Q753.0,116.0 793.0,84.0Q833.0,52.0 900.0,48.0Q909.0,69.0 916.5,98.0Q924.0,127.0 924.0,152.0Q924.0,199.0 901.0,225.0Q878.0,251.0 838.0,251.0Q798.0,251.0 775.5,227.5Q753.0,204.0 753.0,166.0Z"  transform="translate(2321, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(3693, 846)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(3806, 851)"/>
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(4348, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(4913, 851)"/>
<path d="M-45.0,156.0L-19.0,104.0Q-55.0,90.0 -83.0,71.0Q-16.0,4.0 -16.0,-72.0Q-16.0,-126.0 -47.5,-162.0Q-79.0,-198.0 -132.0,-198.0Q-184.0,-198.0 -215.5,-162.0Q-247.0,-126.0 -247.0,-72.0Q-247.0,4.0 -181.0,71.0Q-210.0,89.0 -247.0,104.0L-222.0,157.0Q-172.0,139.0 -132.0,111.0Q-93.0,138.0 -45.0,156.0ZM-180.0,-72.0Q-180.0,-100.0 -167.5,-120.0Q-155.0,-140.0 -132.0,-140.0Q-109.0,-140.0 -96.5,-120.0Q-84.0,-100.0 -84.0,-72.0Q-84.0,-48.0 -95.5,-21.0Q-107.0,6.0 -132.0,32.0Q-157.0,6.0 -168.5,-21.0Q-180.0,-48.0 -180.0,-72.0Z"  transform="translate(5181, 851)"/>
<path d="M1021.0,421.0Q1021.0,381.0 1005.5,343.5Q990.0,306.0 958.0,276.0L895.0,324.0Q914.0,344.0 925.5,368.5Q937.0,393.0 937.0,421.0Q937.0,470.0 908.0,497.5Q879.0,525.0 829.0,525.0Q779.0,525.0 751.5,498.5Q724.0,472.0 724.0,428.0Q724.0,404.0 730.5,381.5Q737.0,359.0 737.0,335.0Q737.0,294.0 721.0,268.0Q705.0,242.0 681.5,224.0Q658.0,206.0 634.0,191.0Q610.0,176.0 594.0,157.5Q578.0,139.0 578.0,111.0Q578.0,89.0 586.5,73.5Q595.0,58.0 613.0,37.0L591.0,-16.0Q578.0,-17.0 561.0,-17.0Q544.0,-17.0 526.0,-17.0Q462.0,-17.0 414.0,7.0Q366.0,31.0 340.0,73.0Q314.0,115.0 314.0,170.0Q314.0,205.0 324.0,235.5Q334.0,266.0 347.0,294.5Q360.0,323.0 370.0,351.5Q380.0,380.0 380.0,411.0Q380.0,463.0 347.0,494.0Q314.0,525.0 257.0,525.0Q198.0,525.0 162.0,492.5Q126.0,460.0 126.0,398.0Q126.0,369.0 133.0,345.0Q165.0,381.0 211.0,381.0Q245.0,381.0 264.5,361.5Q284.0,342.0 284.0,313.0Q284.0,279.0 262.0,258.0Q240.0,237.0 202.0,237.0Q168.0,237.0 138.0,252.0Q133.0,228.0 131.0,198.0L84.0,202.0Q87.0,246.0 98.0,281.0Q78.0,303.0 65.5,334.5Q53.0,366.0 53.0,405.0Q53.0,491.0 109.5,542.5Q166.0,594.0 260.0,594.0Q321.0,594.0 367.5,571.5Q414.0,549.0 440.0,509.0Q466.0,469.0 466.0,414.0Q466.0,378.0 456.0,347.0Q446.0,316.0 433.0,287.0Q420.0,258.0 410.0,229.0Q400.0,200.0 400.0,170.0Q400.0,118.0 430.0,85.0Q460.0,52.0 511.0,52.0L518.0,52.0Q505.0,69.0 500.0,85.0Q495.0,101.0 495.0,122.0Q495.0,158.0 511.0,181.0Q527.0,204.0 550.0,221.0Q573.0,238.0 596.0,254.0Q619.0,270.0 635.0,291.5Q651.0,313.0 651.0,346.0Q651.0,363.0 644.5,387.5Q638.0,412.0 638.0,439.0Q638.0,508.0 690.0,551.0Q742.0,594.0 830.0,594.0Q916.0,594.0 968.5,546.5Q1021.0,499.0 1021.0,421.0ZM208.0,340.0Q175.0,340.0 155.0,302.0Q177.0,278.0 207.0,278.0Q226.0,278.0 234.0,287.5Q242.0,297.0 242.0,310.0Q242.0,326.0 232.0,333.0Q222.0,340.0 208.0,340.0Z"  transform="translate(5181, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(6189, 851)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6849 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M861.0,329.0Q861.0,245.0 833.5,163.5Q806.0,82.0 755.0,8.5Q704.0,-65.0 632.0,-124.0L572.0,-71.0Q634.0,-21.0 679.5,43.5Q725.0,108.0 750.0,181.0Q775.0,254.0 775.0,328.0Q775.0,422.0 738.0,473.5Q701.0,525.0 633.0,525.0Q578.0,525.0 542.5,488.0Q507.0,451.0 508.0,377.0L434.0,377.0Q436.0,448.0 402.0,486.5Q368.0,525.0 312.0,525.0Q244.0,525.0 205.0,467.5Q166.0,410.0 166.0,309.0Q166.0,237.0 182.0,183.0Q198.0,129.0 226.0,95.0Q242.0,135.0 273.0,158.5Q304.0,182.0 347.0,182.0Q395.0,182.0 426.0,155.0Q457.0,128.0 457.0,82.0Q457.0,38.0 425.5,9.5Q394.0,-19.0 339.0,-19.0Q265.0,-19.0 206.0,20.5Q147.0,60.0 113.5,133.5Q80.0,207.0 80.0,308.0Q80.0,441.0 140.5,517.5Q201.0,594.0 305.0,594.0Q362.0,594.0 405.0,569.5Q448.0,545.0 471.0,501.0Q496.0,545.0 540.0,569.5Q584.0,594.0 642.0,594.0Q746.0,594.0 803.5,523.0Q861.0,452.0 861.0,329.0ZM346.0,131.0Q314.0,131.0 294.0,109.5Q274.0,88.0 267.0,57.0Q302.0,35.0 344.0,35.0Q370.0,35.0 385.0,48.0Q400.0,61.0 400.0,83.0Q400.0,108.0 384.5,119.5Q369.0,131.0 346.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M820.0,421.0Q820.0,391.0 811.5,364.0Q803.0,337.0 791.0,312.0Q812.0,317.0 835.0,317.0Q906.0,317.0 950.5,275.5Q995.0,234.0 995.0,163.0Q995.0,131.0 986.5,102.5Q978.0,74.0 969.0,54.0Q1021.0,66.0 1048.5,102.0Q1076.0,138.0 1076.0,196.0Q1076.0,237.0 1066.0,272.5Q1056.0,308.0 1046.0,344.5Q1036.0,381.0 1036.0,424.0Q1036.0,501.0 1090.5,547.5Q1145.0,594.0 1233.0,594.0Q1323.0,594.0 1377.5,544.5Q1432.0,495.0 1432.0,415.0Q1432.0,376.0 1417.5,338.0Q1403.0,300.0 1372.0,272.0L1310.0,320.0Q1327.0,338.0 1337.0,363.5Q1347.0,389.0 1347.0,417.0Q1347.0,467.0 1317.5,496.0Q1288.0,525.0 1234.0,525.0Q1181.0,525.0 1151.0,495.5Q1121.0,466.0 1121.0,418.0Q1121.0,381.0 1131.0,346.5Q1141.0,312.0 1151.0,275.0Q1161.0,238.0 1161.0,191.0Q1161.0,97.0 1099.0,40.0Q1037.0,-17.0 925.0,-17.0Q849.0,-17.0 792.5,6.0Q736.0,29.0 705.0,69.0Q674.0,109.0 674.0,161.0L674.0,161.0L674.0,163.0L674.0,165.0Q674.0,175.0 675.0,185.0Q679.0,229.0 693.5,266.5Q708.0,304.0 721.0,339.5Q734.0,375.0 734.0,412.0Q734.0,462.0 704.0,493.5Q674.0,525.0 619.0,525.0Q563.0,525.0 530.0,495.5Q497.0,466.0 497.0,417.0Q497.0,382.0 508.0,348.0Q519.0,314.0 529.5,276.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 444.5,272.5Q434.0,308.0 423.0,344.5Q412.0,381.0 412.0,424.0Q412.0,474.0 437.5,512.5Q463.0,551.0 508.5,572.5Q554.0,594.0 615.0,594.0Q707.0,594.0 763.5,547.0Q820.0,500.0 820.0,421.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0ZM753.0,166.0Q753.0,116.0 793.0,84.0Q833.0,52.0 900.0,48.0Q909.0,69.0 916.5,98.0Q924.0,127.0 924.0,152.0Q924.0,199.0 901.0,225.0Q878.0,251.0 838.0,251.0Q798.0,251.0 775.5,227.5Q753.0,204.0 753.0,166.0Z"  transform="translate(914, 851)"/>
<path d="M820.0,421.0Q820.0,391.0 811.5,364.0Q803.0,337.0 791.0,312.0Q812.0,317.0 835.0,317.0Q906.0,317.0 950.5,275.5Q995.0,234.0 995.0,163.0Q995.0,131.0 986.5,102.5Q978.0,74.0 969.0,54.0Q1021.0,66.0 1048.5,102.0Q1076.0,138.0 1076.0,196.0Q1076.0,237.0 1066.0,272.5Q1056.0,308.0 1046.0,344.5Q1036.0,381.0 1036.0,424.0Q1036.0,501.0 1090.5,547.5Q1145.0,594.0 1233.0,594.0Q1323.0,594.0 1377.5,544.5Q1432.0,495.0 1432.0,415.0Q1432.0,376.0 1417.5,338.0Q1403.0,300.0 1372.0,272.0L1310.0,320.0Q1327.0,338.0 1337.0,363.5Q1347.0,389.0 1347.0,417.0Q1347.0,467.0 1317.5,496.0Q1288.0,525.0 1234.0,525.0Q1181.0,525.0 1151.0,495.5Q1121.0,466.0 1121.0,418.0Q1121.0,381.0 1131.0,346.5Q1141.0,312.0 1151.0,275.0Q1161.0,238.0 1161.0,191.0Q1161.0,97.0 1099.0,40.0Q1037.0,-17.0 925.0,-17.0Q849.0,-17.0 792.5,6.0Q736.0,29.0 705.0,69.0Q674.0,109.0 674.0,161.0L674.0,161.0L674.0,163.0L674.0,165.0Q674.0,175.0 675.0,185.0Q679.0,229.0 693.5,266.5Q708.0,304.0 721.0,339.5Q734.0,375.0 734.0,412.0Q734.0,462.0 704.0,493.5Q674.0,525.0 619.0,525.0Q563.0,525.0 530.0,495.5Q497.0,466.0 497.0,417.0Q497.0,382.0 508.0,348.0Q519.0,314.0 529.5,276.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 444.5,272.5Q434.0,308.0 423.0,344.5Q412.0,381.0 412.0,424.0Q412.0,474.0 437.5,512.5Q463.0,551.0 508.5,572.5Q554.0,594.0 615.0,594.0Q707.0,594.0 763.5,547.0Q820.0,500.0 820.0,421.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0ZM753.0,166.0Q753.0,116.0 793.0,84.0Q833.0,52.0 900.0,48.0Q909.0,69.0 916.5,98.0Q924.0,127.0 924.0,152.0Q924.0,199.0 901.0,225.0Q878.0,251.0 838.0,251.0Q798.0,251.0 775.5,227.5Q753.0,204.0 753.0,166.0Z"  transform="translate(2321, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(3693, 846)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(3806, 851)"/>
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(4348, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(4913, 851)"/>
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(5181, 851)"/>
<path d="M-45.0,156.0L-19.0,104.0Q-55.0,90.0 -83.0,71.0Q-16.0,4.0 -16.0,-72.0Q-16.0,-126.0 -47.5,-162.0Q-79.0,-198.0 -132.0,-198.0Q-184.0,-198.0 -215.5,-162.0Q-247.0,-126.0 -247.0,-72.0Q-247.0,4.0 -181.0,71.0Q-210.0,89.0 -247.0,104.0L-222.0,157.0Q-172.0,139.0 -132.0,111.0Q-93.0,138.0 -45.0,156.0ZM-180.0,-72.0Q-180.0,-100.0 -167.5,-120.0Q-155.0,-140.0 -132.0,-140.0Q-109.0,-140.0 -96.5,-120.0Q-84.0,-100.0 -84.0,-72.0Q-84.0,-48.0 -95.5,-21.0Q-107.0,6.0 -132.0,32.0Q-157.0,6.0 -168.5,-21.0Q-180.0,-48.0 -180.0,-72.0Z"  transform="translate(5592, 616)"/>
<path d="M1021.0,421.0Q1021.0,381.0 1005.5,343.5Q990.0,306.0 958.0,276.0L895.0,324.0Q914.0,344.0 925.5,368.5Q937.0,393.0 937.0,421.0Q937.0,470.0 908.0,497.5Q879.0,525.0 829.0,525.0Q779.0,525.0 751.5,498.5Q724.0,472.0 724.0,428.0Q724.0,404.0 730.5,381.5Q737.0,359.0 737.0,335.0Q737.0,294.0 721.0,268.0Q705.0,242.0 681.5,224.0Q658.0,206.0 634.0,191.0Q610.0,176.0 594.0,157.5Q578.0,139.0 578.0,111.0Q578.0,89.0 586.5,73.5Q595.0,58.0 613.0,37.0L591.0,-16.0Q578.0,-17.0 561.0,-17.0Q544.0,-17.0 526.0,-17.0Q462.0,-17.0 414.0,7.0Q366.0,31.0 340.0,73.0Q314.0,115.0 314.0,170.0Q314.0,205.0 324.0,235.5Q334.0,266.0 347.0,294.5Q360.0,323.0 370.0,351.5Q380.0,380.0 380.0,411.0Q380.0,463.0 347.0,494.0Q314.0,525.0 257.0,525.0Q198.0,525.0 162.0,492.5Q126.0,460.0 126.0,398.0Q126.0,369.0 133.0,345.0Q165.0,381.0 211.0,381.0Q245.0,381.0 264.5,361.5Q284.0,342.0 284.0,313.0Q284.0,279.0 262.0,258.0Q240.0,237.0 202.0,237.0Q168.0,237.0 138.0,252.0Q133.0,228.0 131.0,198.0L84.0,202.0Q87.0,246.0 98.0,281.0Q78.0,303.0 65.5,334.5Q53.0,366.0 53.0,405.0Q53.0,491.0 109.5,542.5Q166.0,594.0 260.0,594.0Q321.0,594.0 367.5,571.5Q414.0,549.0 440.0,509.0Q466.0,469.0 466.0,414.0Q466.0,378.0 456.0,347.0Q446.0,316.0 433.0,287.0Q420.0,258.0 410.0,229.0Q400.0,200.0 400.0,170.0Q400.0,118.0 430.0,85.0Q460.0,52.0 511.0,52.0L518.0,52.0Q505.0,69.0 500.0,85.0Q495.0,101.0 495.0,122.0Q495.0,158.0 511.0,181.0Q527.0,204.0 550.0,221.0Q573.0,238.0 596.0,254.0Q619.0,270.0 635.0,291.5Q651.0,313.0 651.0,346.0Q651.0,363.0 644.5,387.5Q638.0,412.0 638.0,439.0Q638.0,508.0 690.0,551.0Q742.0,594.0 830.0,594.0Q916.0,594.0 968.5,546.5Q1021.0,499.0 1021.0,421.0ZM208.0,340.0Q175.0,340.0 155.0,302.0Q177.0,278.0 207.0,278.0Q226.0,278.0 234.0,287.5Q242.0,297.0 242.0,310.0Q242.0,326.0 232.0,333.0Q222.0,340.0 208.0,340.0Z"  transform="translate(5775, 851)"/>
<path d="M56.0,-76.0Q56.0,-131.0 26.5,-165.0Q-3.0,-199.0 -50.0,-199.0Q-97.0,-199.0 -126.5,-162.5Q-156.0,-126.0 -156.0,-68.0Q-156.0,-5.0 -113.5,57.0Q-71.0,119.0 11.0,159.0L45.0,110.0Q14.0,94.0 -11.0,75.0Q56.0,6.0 56.0,-76.0ZM-93.0,-66.0Q-93.0,-100.0 -80.5,-119.0Q-68.0,-138.0 -49.0,-138.0Q-9.0,-138.0 -9.0,-77.0Q-9.0,-51.0 -20.0,-23.5Q-31.0,4.0 -56.0,30.0Q-76.0,5.0 -84.5,-19.5Q-93.0,-44.0 -93.0,-66.0Z"  transform="translate(6783, 851)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ꩍ꩖ꨤꨭꨵꨲ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+594|hSignFinal_cham=0+487|six_cham=1+864|la_cham=2+881|uSign_cham.narrow=2@-44,0+0|uni25CC=2+594|laMedial_ueSign_cham=2@-85,-235+0</pre>



<pre>Got     : uni25CC=0+594|hSignFinal_cham=0+487|six_cham=1+864|la_cham=2+881|uSign_cham.narrow=2@-44,0+0|uni25CC=2+594|laMedial_ueSign_cham=2@-206,-235+0</pre>



<pre>                                                                                                                                             ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3420 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(0, 851)"/>
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(594, 851)"/>
<path d="M811.0,415.0Q811.0,376.0 796.5,338.0Q782.0,300.0 751.0,272.0L689.0,320.0Q706.0,338.0 716.0,363.5Q726.0,389.0 726.0,417.0Q726.0,467.0 696.5,496.0Q667.0,525.0 613.0,525.0Q560.0,525.0 530.0,495.5Q500.0,466.0 500.0,418.0Q500.0,381.0 510.0,346.5Q520.0,312.0 530.0,275.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 445.0,272.5Q435.0,308.0 425.0,344.5Q415.0,381.0 415.0,424.0Q415.0,501.0 469.5,547.5Q524.0,594.0 612.0,594.0Q702.0,594.0 756.5,544.5Q811.0,495.0 811.0,415.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0Z"  transform="translate(1081, 851)"/>
<path d="M828.0,421.0Q828.0,381.0 814.5,344.0Q801.0,307.0 769.0,274.0L706.0,320.0Q744.0,361.0 744.0,416.0Q744.0,465.0 717.5,491.5Q691.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.5Q166.0,409.0 166.0,309.0Q166.0,237.0 182.0,183.0Q198.0,129.0 226.0,95.0Q242.0,135.0 273.0,158.5Q304.0,182.0 347.0,182.0Q395.0,182.0 426.0,155.0Q457.0,128.0 457.0,82.0Q457.0,38.0 425.5,9.5Q394.0,-19.0 339.0,-19.0Q265.0,-19.0 206.0,20.5Q147.0,60.0 113.5,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.0,553.5Q568.0,570.0 596.0,582.0Q624.0,594.0 667.0,594.0Q739.0,594.0 783.5,548.0Q828.0,502.0 828.0,421.0ZM346.0,131.0Q314.0,131.0 294.0,109.5Q274.0,88.0 267.0,57.0Q302.0,35.0 344.0,35.0Q370.0,35.0 385.0,48.0Q400.0,61.0 400.0,83.0Q400.0,108.0 384.5,119.5Q369.0,131.0 346.0,131.0Z"  transform="translate(1945, 851)"/>
<path d="M66.0,114.0Q69.0,53.0 46.5,26.5Q24.0,0.0 -11.0,0.0Q-36.0,0.0 -54.0,12.5Q-72.0,25.0 -87.0,37.5Q-102.0,50.0 -119.0,50.0Q-134.0,50.0 -145.0,40.0Q-156.0,30.0 -155.0,-4.0L-203.0,-4.0Q-206.0,58.0 -183.0,84.5Q-160.0,111.0 -126.0,111.0Q-101.0,111.0 -83.0,98.0Q-65.0,85.0 -49.5,72.5Q-34.0,60.0 -18.0,60.0Q-3.0,60.0 8.0,70.5Q19.0,81.0 19.0,114.0L66.0,114.0Z"  transform="translate(2782, 851)"/>
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(2826, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0ZM-59.0,108.0Q-45.0,91.0 -36.0,61.0Q-27.0,31.0 -27.0,-6.0Q-27.0,-53.0 -41.5,-101.0Q-56.0,-149.0 -78.0,-190.0L-149.0,-166.0Q-129.0,-128.0 -117.0,-88.0Q-105.0,-48.0 -105.0,-11.0Q-105.0,43.0 -128.0,80.0L-59.0,108.0Z"  transform="translate(3214, 616)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3420 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(0, 851)"/>
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(594, 851)"/>
<path d="M811.0,415.0Q811.0,376.0 796.5,338.0Q782.0,300.0 751.0,272.0L689.0,320.0Q706.0,338.0 716.0,363.5Q726.0,389.0 726.0,417.0Q726.0,467.0 696.5,496.0Q667.0,525.0 613.0,525.0Q560.0,525.0 530.0,495.5Q500.0,466.0 500.0,418.0Q500.0,381.0 510.0,346.5Q520.0,312.0 530.0,275.0Q540.0,238.0 540.0,191.0Q540.0,97.0 478.0,40.0Q416.0,-17.0 304.0,-17.0Q228.0,-17.0 171.5,6.0Q115.0,29.0 84.0,70.0Q53.0,111.0 53.0,165.0Q53.0,230.0 96.0,273.5Q139.0,317.0 214.0,317.0Q285.0,317.0 329.5,275.5Q374.0,234.0 374.0,163.0Q374.0,131.0 365.5,102.5Q357.0,74.0 348.0,54.0Q400.0,66.0 427.5,102.0Q455.0,138.0 455.0,196.0Q455.0,237.0 445.0,272.5Q435.0,308.0 425.0,344.5Q415.0,381.0 415.0,424.0Q415.0,501.0 469.5,547.5Q524.0,594.0 612.0,594.0Q702.0,594.0 756.5,544.5Q811.0,495.0 811.0,415.0ZM132.0,166.0Q132.0,116.0 172.0,84.0Q212.0,52.0 279.0,48.0Q288.0,69.0 295.5,98.0Q303.0,127.0 303.0,152.0Q303.0,199.0 280.0,225.0Q257.0,251.0 217.0,251.0Q177.0,251.0 154.5,227.5Q132.0,204.0 132.0,166.0Z"  transform="translate(1081, 851)"/>
<path d="M828.0,421.0Q828.0,381.0 814.5,344.0Q801.0,307.0 769.0,274.0L706.0,320.0Q744.0,361.0 744.0,416.0Q744.0,465.0 717.5,491.5Q691.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.5Q166.0,409.0 166.0,309.0Q166.0,237.0 182.0,183.0Q198.0,129.0 226.0,95.0Q242.0,135.0 273.0,158.5Q304.0,182.0 347.0,182.0Q395.0,182.0 426.0,155.0Q457.0,128.0 457.0,82.0Q457.0,38.0 425.5,9.5Q394.0,-19.0 339.0,-19.0Q265.0,-19.0 206.0,20.5Q147.0,60.0 113.5,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.0,553.5Q568.0,570.0 596.0,582.0Q624.0,594.0 667.0,594.0Q739.0,594.0 783.5,548.0Q828.0,502.0 828.0,421.0ZM346.0,131.0Q314.0,131.0 294.0,109.5Q274.0,88.0 267.0,57.0Q302.0,35.0 344.0,35.0Q370.0,35.0 385.0,48.0Q400.0,61.0 400.0,83.0Q400.0,108.0 384.5,119.5Q369.0,131.0 346.0,131.0Z"  transform="translate(1945, 851)"/>
<path d="M66.0,114.0Q69.0,53.0 46.5,26.5Q24.0,0.0 -11.0,0.0Q-36.0,0.0 -54.0,12.5Q-72.0,25.0 -87.0,37.5Q-102.0,50.0 -119.0,50.0Q-134.0,50.0 -145.0,40.0Q-156.0,30.0 -155.0,-4.0L-203.0,-4.0Q-206.0,58.0 -183.0,84.5Q-160.0,111.0 -126.0,111.0Q-101.0,111.0 -83.0,98.0Q-65.0,85.0 -49.5,72.5Q-34.0,60.0 -18.0,60.0Q-3.0,60.0 8.0,70.5Q19.0,81.0 19.0,114.0L66.0,114.0Z"  transform="translate(2782, 851)"/>
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(2826, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0ZM-59.0,108.0Q-45.0,91.0 -36.0,61.0Q-27.0,31.0 -27.0,-6.0Q-27.0,-53.0 -41.5,-101.0Q-56.0,-149.0 -78.0,-190.0L-149.0,-166.0Q-129.0,-128.0 -117.0,-88.0Q-105.0,-48.0 -105.0,-11.0Q-105.0,43.0 -128.0,80.0L-59.0,108.0Z"  transform="translate(3335, 616)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ꨒꨇꨵꨶꨲ</span> (Added by SIESTA)</li>


<pre>Expected: nhja_cham=0+1327|kha_cham=1+1309|laMed_waMed_ueSign_cham=1@49,-1+0</pre>



<pre>Got     : nhja_cham=0+1327|kha_cham=1+1309|laMed_waMed_ueSign_cham=1@-263,-1+0</pre>



<pre>                                                                     ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2636 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M1298.0,417.0Q1298.0,377.0 1284.5,342.0Q1271.0,307.0 1240.0,274.0L1176.0,320.0Q1214.0,361.0 1214.0,418.0Q1214.0,468.0 1186.0,496.5Q1158.0,525.0 1110.0,525.0Q1066.0,525.0 1040.0,497.5Q1014.0,470.0 1005.0,418.0Q997.0,370.0 980.5,341.0Q964.0,312.0 934.5,295.0Q905.0,278.0 858.0,266.0Q855.0,181.0 827.5,112.0Q800.0,43.0 731.0,-5.0Q663.0,-52.0 627.0,-83.5Q591.0,-115.0 578.0,-136.5Q565.0,-158.0 565.0,-177.0Q565.0,-196.0 577.0,-210.0Q589.0,-224.0 611.0,-224.0Q631.0,-224.0 647.0,-209.0Q663.0,-194.0 678.5,-172.0Q694.0,-150.0 712.5,-128.0Q731.0,-106.0 756.5,-91.0Q782.0,-76.0 819.0,-76.0Q863.0,-76.0 891.5,-104.0Q920.0,-132.0 920.0,-172.0Q920.0,-189.0 913.5,-211.5Q907.0,-234.0 893.0,-253.0L825.0,-222.0Q839.0,-202.0 839.0,-183.0Q839.0,-149.0 804.0,-149.0Q785.0,-149.0 770.0,-164.0Q755.0,-179.0 740.0,-201.5Q725.0,-224.0 706.5,-246.5Q688.0,-269.0 662.5,-284.0Q637.0,-299.0 600.0,-299.0Q551.0,-299.0 516.0,-266.5Q481.0,-234.0 481.0,-184.0Q481.0,-152.0 502.0,-117.5Q523.0,-83.0 573.0,-39.0L536.0,-39.0Q495.0,-39.0 474.0,-48.0Q453.0,-57.0 442.5,-81.5Q432.0,-106.0 422.0,-154.0Q409.0,-215.0 391.5,-246.5Q374.0,-278.0 342.0,-288.5Q310.0,-299.0 254.0,-299.0L212.0,-299.0L212.0,-246.0L233.0,-246.0Q275.0,-246.0 296.5,-237.0Q318.0,-228.0 328.5,-203.5Q339.0,-179.0 349.0,-131.0Q362.0,-69.0 379.5,-38.0Q397.0,-7.0 428.5,3.5Q460.0,14.0 516.0,14.0L584.0,14.0Q538.0,45.0 538.0,109.0Q538.0,186.0 599.5,239.5Q661.0,293.0 767.0,311.0L774.0,312.0Q769.0,412.0 734.0,465.0Q699.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.0Q166.0,408.0 166.0,308.0Q166.0,245.0 176.5,196.5Q187.0,148.0 204.0,113.0Q222.0,146.0 250.5,164.0Q279.0,182.0 317.0,182.0Q365.0,182.0 396.0,155.0Q427.0,128.0 427.0,82.0Q427.0,38.0 395.5,9.5Q364.0,-19.0 309.0,-19.0Q243.0,-19.0 191.5,20.5Q140.0,60.0 110.0,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.5,553.5Q569.0,570.0 597.5,582.0Q626.0,594.0 669.0,594.0Q745.0,594.0 796.5,525.5Q848.0,457.0 856.0,333.0Q889.0,346.0 906.5,371.5Q924.0,397.0 933.0,449.0Q947.0,525.0 996.0,559.5Q1045.0,594.0 1115.0,594.0Q1198.0,594.0 1248.0,545.5Q1298.0,497.0 1298.0,417.0ZM610.0,115.0Q610.0,87.0 622.5,69.0Q635.0,51.0 660.0,51.0Q706.0,51.0 736.5,103.5Q767.0,156.0 773.0,248.0Q681.0,227.0 645.5,192.0Q610.0,157.0 610.0,115.0ZM316.0,131.0Q286.0,131.0 267.0,112.5Q248.0,94.0 239.0,66.0Q272.0,35.0 314.0,35.0Q340.0,35.0 355.0,48.0Q370.0,61.0 370.0,83.0Q370.0,108.0 354.5,119.5Q339.0,131.0 316.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(1327, 851)"/>
<path d="M155.0,108.0Q169.0,91.0 178.0,61.0Q187.0,31.0 187.0,-6.0Q187.0,-53.0 172.5,-101.0Q158.0,-149.0 136.0,-190.0L65.0,-166.0Q85.0,-128.0 97.0,-88.0Q109.0,-48.0 109.0,-11.0Q109.0,43.0 86.0,80.0L155.0,108.0ZM-140.0,150.0Q-150.0,101.0 -172.0,74.0Q-194.0,47.0 -230.0,47.0Q-254.0,47.0 -273.0,55.0Q-292.0,63.0 -315.0,63.0Q-361.0,63.0 -376.0,7.0Q-371.0,7.0 -366.0,7.0Q-304.0,7.0 -263.5,-21.5Q-223.0,-50.0 -223.0,-103.0Q-223.0,-148.0 -250.5,-173.5Q-278.0,-199.0 -319.0,-199.0Q-371.0,-199.0 -408.5,-161.5Q-446.0,-124.0 -446.0,-44.0Q-446.0,30.0 -415.5,80.5Q-385.0,131.0 -327.0,131.0Q-303.0,131.0 -286.0,123.5Q-269.0,116.0 -250.0,116.0Q-230.0,116.0 -220.0,131.0Q-210.0,146.0 -205.0,172.0L-140.0,150.0ZM-363.0,-46.0Q-372.0,-46.0 -382.0,-48.0Q-381.0,-98.0 -362.5,-119.5Q-344.0,-141.0 -322.0,-141.0Q-287.0,-141.0 -287.0,-102.0Q-287.0,-75.0 -307.5,-60.5Q-328.0,-46.0 -363.0,-46.0ZM30.0,-76.0Q30.0,-131.0 0.5,-165.0Q-29.0,-199.0 -76.0,-199.0Q-123.0,-199.0 -152.5,-162.5Q-182.0,-126.0 -182.0,-68.0Q-182.0,-5.0 -139.5,57.0Q-97.0,119.0 -15.0,159.0L19.0,110.0Q-12.0,94.0 -37.0,75.0Q30.0,6.0 30.0,-76.0ZM-119.0,-66.0Q-119.0,-100.0 -106.5,-119.0Q-94.0,-138.0 -75.0,-138.0Q-35.0,-138.0 -35.0,-77.0Q-35.0,-51.0 -46.0,-23.5Q-57.0,4.0 -82.0,30.0Q-102.0,5.0 -110.5,-19.5Q-119.0,-44.0 -119.0,-66.0Z"  transform="translate(2373, 850)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2636 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M1298.0,417.0Q1298.0,377.0 1284.5,342.0Q1271.0,307.0 1240.0,274.0L1176.0,320.0Q1214.0,361.0 1214.0,418.0Q1214.0,468.0 1186.0,496.5Q1158.0,525.0 1110.0,525.0Q1066.0,525.0 1040.0,497.5Q1014.0,470.0 1005.0,418.0Q997.0,370.0 980.5,341.0Q964.0,312.0 934.5,295.0Q905.0,278.0 858.0,266.0Q855.0,181.0 827.5,112.0Q800.0,43.0 731.0,-5.0Q663.0,-52.0 627.0,-83.5Q591.0,-115.0 578.0,-136.5Q565.0,-158.0 565.0,-177.0Q565.0,-196.0 577.0,-210.0Q589.0,-224.0 611.0,-224.0Q631.0,-224.0 647.0,-209.0Q663.0,-194.0 678.5,-172.0Q694.0,-150.0 712.5,-128.0Q731.0,-106.0 756.5,-91.0Q782.0,-76.0 819.0,-76.0Q863.0,-76.0 891.5,-104.0Q920.0,-132.0 920.0,-172.0Q920.0,-189.0 913.5,-211.5Q907.0,-234.0 893.0,-253.0L825.0,-222.0Q839.0,-202.0 839.0,-183.0Q839.0,-149.0 804.0,-149.0Q785.0,-149.0 770.0,-164.0Q755.0,-179.0 740.0,-201.5Q725.0,-224.0 706.5,-246.5Q688.0,-269.0 662.5,-284.0Q637.0,-299.0 600.0,-299.0Q551.0,-299.0 516.0,-266.5Q481.0,-234.0 481.0,-184.0Q481.0,-152.0 502.0,-117.5Q523.0,-83.0 573.0,-39.0L536.0,-39.0Q495.0,-39.0 474.0,-48.0Q453.0,-57.0 442.5,-81.5Q432.0,-106.0 422.0,-154.0Q409.0,-215.0 391.5,-246.5Q374.0,-278.0 342.0,-288.5Q310.0,-299.0 254.0,-299.0L212.0,-299.0L212.0,-246.0L233.0,-246.0Q275.0,-246.0 296.5,-237.0Q318.0,-228.0 328.5,-203.5Q339.0,-179.0 349.0,-131.0Q362.0,-69.0 379.5,-38.0Q397.0,-7.0 428.5,3.5Q460.0,14.0 516.0,14.0L584.0,14.0Q538.0,45.0 538.0,109.0Q538.0,186.0 599.5,239.5Q661.0,293.0 767.0,311.0L774.0,312.0Q769.0,412.0 734.0,465.0Q699.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.0Q166.0,408.0 166.0,308.0Q166.0,245.0 176.5,196.5Q187.0,148.0 204.0,113.0Q222.0,146.0 250.5,164.0Q279.0,182.0 317.0,182.0Q365.0,182.0 396.0,155.0Q427.0,128.0 427.0,82.0Q427.0,38.0 395.5,9.5Q364.0,-19.0 309.0,-19.0Q243.0,-19.0 191.5,20.5Q140.0,60.0 110.0,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.5,553.5Q569.0,570.0 597.5,582.0Q626.0,594.0 669.0,594.0Q745.0,594.0 796.5,525.5Q848.0,457.0 856.0,333.0Q889.0,346.0 906.5,371.5Q924.0,397.0 933.0,449.0Q947.0,525.0 996.0,559.5Q1045.0,594.0 1115.0,594.0Q1198.0,594.0 1248.0,545.5Q1298.0,497.0 1298.0,417.0ZM610.0,115.0Q610.0,87.0 622.5,69.0Q635.0,51.0 660.0,51.0Q706.0,51.0 736.5,103.5Q767.0,156.0 773.0,248.0Q681.0,227.0 645.5,192.0Q610.0,157.0 610.0,115.0ZM316.0,131.0Q286.0,131.0 267.0,112.5Q248.0,94.0 239.0,66.0Q272.0,35.0 314.0,35.0Q340.0,35.0 355.0,48.0Q370.0,61.0 370.0,83.0Q370.0,108.0 354.5,119.5Q339.0,131.0 316.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(1327, 851)"/>
<path d="M155.0,108.0Q169.0,91.0 178.0,61.0Q187.0,31.0 187.0,-6.0Q187.0,-53.0 172.5,-101.0Q158.0,-149.0 136.0,-190.0L65.0,-166.0Q85.0,-128.0 97.0,-88.0Q109.0,-48.0 109.0,-11.0Q109.0,43.0 86.0,80.0L155.0,108.0ZM-140.0,150.0Q-150.0,101.0 -172.0,74.0Q-194.0,47.0 -230.0,47.0Q-254.0,47.0 -273.0,55.0Q-292.0,63.0 -315.0,63.0Q-361.0,63.0 -376.0,7.0Q-371.0,7.0 -366.0,7.0Q-304.0,7.0 -263.5,-21.5Q-223.0,-50.0 -223.0,-103.0Q-223.0,-148.0 -250.5,-173.5Q-278.0,-199.0 -319.0,-199.0Q-371.0,-199.0 -408.5,-161.5Q-446.0,-124.0 -446.0,-44.0Q-446.0,30.0 -415.5,80.5Q-385.0,131.0 -327.0,131.0Q-303.0,131.0 -286.0,123.5Q-269.0,116.0 -250.0,116.0Q-230.0,116.0 -220.0,131.0Q-210.0,146.0 -205.0,172.0L-140.0,150.0ZM-363.0,-46.0Q-372.0,-46.0 -382.0,-48.0Q-381.0,-98.0 -362.5,-119.5Q-344.0,-141.0 -322.0,-141.0Q-287.0,-141.0 -287.0,-102.0Q-287.0,-75.0 -307.5,-60.5Q-328.0,-46.0 -363.0,-46.0ZM30.0,-76.0Q30.0,-131.0 0.5,-165.0Q-29.0,-199.0 -76.0,-199.0Q-123.0,-199.0 -152.5,-162.5Q-182.0,-126.0 -182.0,-68.0Q-182.0,-5.0 -139.5,57.0Q-97.0,119.0 -15.0,159.0L19.0,110.0Q-12.0,94.0 -37.0,75.0Q30.0,6.0 30.0,-76.0ZM-119.0,-66.0Q-119.0,-100.0 -106.5,-119.0Q-94.0,-138.0 -75.0,-138.0Q-35.0,-138.0 -35.0,-77.0Q-35.0,-51.0 -46.0,-23.5Q-57.0,4.0 -82.0,30.0Q-102.0,5.0 -110.5,-19.5Q-119.0,-44.0 -119.0,-66.0Z"  transform="translate(2685, 850)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ꨐꩀ꩐ꨵꨶ</span> (Added by SIESTA)</li>


<pre>Expected: nhue_cham=0+1328|kFinal_cham=1+898|zero_cham=2+634|laMedial_waMedial_cham=2@-157,-292+0</pre>



<pre>Got     : nhue_cham=0+1328|kFinal_cham=1+898|zero_cham=2+634|laMedial_waMedial_cham=2@-241,-292+0</pre>



<pre>                                                                                        ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2860 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M1299.0,417.0Q1299.0,377.0 1285.5,342.0Q1272.0,307.0 1240.0,274.0L1177.0,320.0Q1215.0,361.0 1215.0,418.0Q1215.0,468.0 1187.0,496.5Q1159.0,525.0 1110.0,525.0Q1066.0,525.0 1040.0,497.5Q1014.0,470.0 1005.0,418.0Q997.0,370.0 980.5,341.0Q964.0,312.0 934.5,295.0Q905.0,278.0 858.0,266.0Q855.0,180.0 829.5,116.5Q804.0,53.0 760.5,18.0Q717.0,-17.0 660.0,-17.0Q599.0,-17.0 563.0,17.0Q527.0,51.0 527.0,112.0Q527.0,192.0 592.5,243.0Q658.0,294.0 767.0,312.0L774.0,313.0Q769.0,412.0 734.0,465.0Q699.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.0Q166.0,408.0 166.0,308.0Q166.0,245.0 176.5,196.5Q187.0,148.0 204.0,113.0Q222.0,146.0 250.5,164.0Q279.0,182.0 317.0,182.0Q365.0,182.0 396.0,155.0Q427.0,128.0 427.0,82.0Q427.0,38.0 395.5,9.5Q364.0,-19.0 309.0,-19.0Q243.0,-19.0 191.5,20.5Q140.0,60.0 110.0,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.5,553.5Q569.0,570.0 597.5,582.0Q626.0,594.0 669.0,594.0Q745.0,594.0 796.5,525.5Q848.0,457.0 856.0,333.0Q889.0,346.0 906.5,371.5Q924.0,397.0 933.0,449.0Q947.0,525.0 996.0,559.5Q1045.0,594.0 1115.0,594.0Q1199.0,594.0 1249.0,545.5Q1299.0,497.0 1299.0,417.0ZM610.0,115.0Q610.0,87.0 622.5,69.0Q635.0,51.0 660.0,51.0Q706.0,51.0 736.5,103.5Q767.0,156.0 773.0,248.0Q681.0,227.0 645.5,192.0Q610.0,157.0 610.0,115.0ZM316.0,131.0Q286.0,131.0 267.0,112.5Q248.0,94.0 239.0,66.0Q272.0,35.0 314.0,35.0Q340.0,35.0 355.0,48.0Q370.0,61.0 370.0,83.0Q370.0,108.0 354.5,119.5Q339.0,131.0 316.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M818.0,327.0Q818.0,242.0 789.0,158.5Q760.0,75.0 707.0,3.0Q654.0,-69.0 581.0,-122.0L523.0,-66.0Q588.0,-19.0 634.5,44.0Q681.0,107.0 706.5,179.5Q732.0,252.0 732.0,328.0Q732.0,421.0 700.0,473.0Q668.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q344.0,594.0 387.5,571.0Q431.0,548.0 455.0,504.0Q480.0,548.0 522.0,571.0Q564.0,594.0 618.0,594.0Q712.0,594.0 765.0,522.5Q818.0,451.0 818.0,327.0Z"  transform="translate(1328, 851)"/>
<path d="M580.0,288.0Q580.0,197.0 550.5,128.0Q521.0,59.0 462.5,20.5Q404.0,-18.0 317.0,-18.0Q235.0,-18.0 176.5,20.0Q118.0,58.0 86.5,127.0Q55.0,196.0 55.0,288.0Q55.0,432.0 126.0,513.0Q197.0,594.0 322.0,594.0Q406.0,594.0 463.5,555.5Q521.0,517.0 550.5,448.0Q580.0,379.0 580.0,288.0ZM143.0,288.0Q143.0,180.0 185.5,115.5Q228.0,51.0 318.0,51.0Q410.0,51.0 451.0,116.0Q492.0,181.0 492.0,288.0Q492.0,358.0 475.0,411.5Q458.0,465.0 420.5,495.0Q383.0,525.0 321.0,525.0Q233.0,525.0 188.0,463.0Q143.0,401.0 143.0,288.0Z"  transform="translate(2226, 851)"/>
<path d="M-140.0,150.0Q-150.0,101.0 -172.0,74.0Q-194.0,47.0 -230.0,47.0Q-254.0,47.0 -273.0,55.0Q-292.0,63.0 -315.0,63.0Q-361.0,63.0 -376.0,7.0Q-371.0,7.0 -366.0,7.0Q-304.0,7.0 -263.5,-21.5Q-223.0,-50.0 -223.0,-103.0Q-223.0,-148.0 -250.5,-173.5Q-278.0,-199.0 -319.0,-199.0Q-371.0,-199.0 -408.5,-161.5Q-446.0,-124.0 -446.0,-44.0Q-446.0,30.0 -415.5,80.5Q-385.0,131.0 -327.0,131.0Q-303.0,131.0 -286.0,123.5Q-269.0,116.0 -250.0,116.0Q-230.0,116.0 -220.0,131.0Q-210.0,146.0 -205.0,172.0L-140.0,150.0ZM-363.0,-46.0Q-372.0,-46.0 -382.0,-48.0Q-381.0,-98.0 -362.5,-119.5Q-344.0,-141.0 -322.0,-141.0Q-287.0,-141.0 -287.0,-102.0Q-287.0,-75.0 -307.5,-60.5Q-328.0,-46.0 -363.0,-46.0ZM30.0,-76.0Q30.0,-131.0 0.5,-165.0Q-29.0,-199.0 -76.0,-199.0Q-123.0,-199.0 -152.5,-162.5Q-182.0,-126.0 -182.0,-68.0Q-182.0,-5.0 -139.5,57.0Q-97.0,119.0 -15.0,159.0L19.0,110.0Q-12.0,94.0 -37.0,75.0Q30.0,6.0 30.0,-76.0ZM-119.0,-66.0Q-119.0,-100.0 -106.5,-119.0Q-94.0,-138.0 -75.0,-138.0Q-35.0,-138.0 -35.0,-77.0Q-35.0,-51.0 -46.0,-23.5Q-57.0,4.0 -82.0,30.0Q-102.0,5.0 -110.5,-19.5Q-119.0,-44.0 -119.0,-66.0Z"  transform="translate(2619, 559)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2860 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M1299.0,417.0Q1299.0,377.0 1285.5,342.0Q1272.0,307.0 1240.0,274.0L1177.0,320.0Q1215.0,361.0 1215.0,418.0Q1215.0,468.0 1187.0,496.5Q1159.0,525.0 1110.0,525.0Q1066.0,525.0 1040.0,497.5Q1014.0,470.0 1005.0,418.0Q997.0,370.0 980.5,341.0Q964.0,312.0 934.5,295.0Q905.0,278.0 858.0,266.0Q855.0,180.0 829.5,116.5Q804.0,53.0 760.5,18.0Q717.0,-17.0 660.0,-17.0Q599.0,-17.0 563.0,17.0Q527.0,51.0 527.0,112.0Q527.0,192.0 592.5,243.0Q658.0,294.0 767.0,312.0L774.0,313.0Q769.0,412.0 734.0,465.0Q699.0,518.0 653.0,518.0Q622.0,518.0 602.0,506.0Q582.0,494.0 564.5,477.5Q547.0,461.0 525.0,449.0Q503.0,437.0 470.0,437.0Q437.0,437.0 415.0,449.0Q393.0,461.0 375.5,477.5Q358.0,494.0 338.0,506.0Q318.0,518.0 287.0,518.0Q235.0,518.0 200.5,463.0Q166.0,408.0 166.0,308.0Q166.0,245.0 176.5,196.5Q187.0,148.0 204.0,113.0Q222.0,146.0 250.5,164.0Q279.0,182.0 317.0,182.0Q365.0,182.0 396.0,155.0Q427.0,128.0 427.0,82.0Q427.0,38.0 395.5,9.5Q364.0,-19.0 309.0,-19.0Q243.0,-19.0 191.5,20.5Q140.0,60.0 110.0,133.5Q80.0,207.0 80.0,308.0Q80.0,397.0 104.0,461.0Q128.0,525.0 171.0,559.5Q214.0,594.0 271.0,594.0Q314.0,594.0 342.0,582.0Q370.0,570.0 390.5,553.5Q411.0,537.0 429.5,525.0Q448.0,513.0 470.0,513.0Q493.0,513.0 510.5,525.0Q528.0,537.0 548.5,553.5Q569.0,570.0 597.5,582.0Q626.0,594.0 669.0,594.0Q745.0,594.0 796.5,525.5Q848.0,457.0 856.0,333.0Q889.0,346.0 906.5,371.5Q924.0,397.0 933.0,449.0Q947.0,525.0 996.0,559.5Q1045.0,594.0 1115.0,594.0Q1199.0,594.0 1249.0,545.5Q1299.0,497.0 1299.0,417.0ZM610.0,115.0Q610.0,87.0 622.5,69.0Q635.0,51.0 660.0,51.0Q706.0,51.0 736.5,103.5Q767.0,156.0 773.0,248.0Q681.0,227.0 645.5,192.0Q610.0,157.0 610.0,115.0ZM316.0,131.0Q286.0,131.0 267.0,112.5Q248.0,94.0 239.0,66.0Q272.0,35.0 314.0,35.0Q340.0,35.0 355.0,48.0Q370.0,61.0 370.0,83.0Q370.0,108.0 354.5,119.5Q339.0,131.0 316.0,131.0Z"  transform="translate(0, 851)"/>
<path d="M818.0,327.0Q818.0,242.0 789.0,158.5Q760.0,75.0 707.0,3.0Q654.0,-69.0 581.0,-122.0L523.0,-66.0Q588.0,-19.0 634.5,44.0Q681.0,107.0 706.5,179.5Q732.0,252.0 732.0,328.0Q732.0,421.0 700.0,473.0Q668.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q344.0,594.0 387.5,571.0Q431.0,548.0 455.0,504.0Q480.0,548.0 522.0,571.0Q564.0,594.0 618.0,594.0Q712.0,594.0 765.0,522.5Q818.0,451.0 818.0,327.0Z"  transform="translate(1328, 851)"/>
<path d="M580.0,288.0Q580.0,197.0 550.5,128.0Q521.0,59.0 462.5,20.5Q404.0,-18.0 317.0,-18.0Q235.0,-18.0 176.5,20.0Q118.0,58.0 86.5,127.0Q55.0,196.0 55.0,288.0Q55.0,432.0 126.0,513.0Q197.0,594.0 322.0,594.0Q406.0,594.0 463.5,555.5Q521.0,517.0 550.5,448.0Q580.0,379.0 580.0,288.0ZM143.0,288.0Q143.0,180.0 185.5,115.5Q228.0,51.0 318.0,51.0Q410.0,51.0 451.0,116.0Q492.0,181.0 492.0,288.0Q492.0,358.0 475.0,411.5Q458.0,465.0 420.5,495.0Q383.0,525.0 321.0,525.0Q233.0,525.0 188.0,463.0Q143.0,401.0 143.0,288.0Z"  transform="translate(2226, 851)"/>
<path d="M-140.0,150.0Q-150.0,101.0 -172.0,74.0Q-194.0,47.0 -230.0,47.0Q-254.0,47.0 -273.0,55.0Q-292.0,63.0 -315.0,63.0Q-361.0,63.0 -376.0,7.0Q-371.0,7.0 -366.0,7.0Q-304.0,7.0 -263.5,-21.5Q-223.0,-50.0 -223.0,-103.0Q-223.0,-148.0 -250.5,-173.5Q-278.0,-199.0 -319.0,-199.0Q-371.0,-199.0 -408.5,-161.5Q-446.0,-124.0 -446.0,-44.0Q-446.0,30.0 -415.5,80.5Q-385.0,131.0 -327.0,131.0Q-303.0,131.0 -286.0,123.5Q-269.0,116.0 -250.0,116.0Q-230.0,116.0 -220.0,131.0Q-210.0,146.0 -205.0,172.0L-140.0,150.0ZM-363.0,-46.0Q-372.0,-46.0 -382.0,-48.0Q-381.0,-98.0 -362.5,-119.5Q-344.0,-141.0 -322.0,-141.0Q-287.0,-141.0 -287.0,-102.0Q-287.0,-75.0 -307.5,-60.5Q-328.0,-46.0 -363.0,-46.0ZM30.0,-76.0Q30.0,-131.0 0.5,-165.0Q-29.0,-199.0 -76.0,-199.0Q-123.0,-199.0 -152.5,-162.5Q-182.0,-126.0 -182.0,-68.0Q-182.0,-5.0 -139.5,57.0Q-97.0,119.0 -15.0,159.0L19.0,110.0Q-12.0,94.0 -37.0,75.0Q30.0,6.0 30.0,-76.0ZM-119.0,-66.0Q-119.0,-100.0 -106.5,-119.0Q-94.0,-138.0 -75.0,-138.0Q-35.0,-138.0 -35.0,-77.0Q-35.0,-51.0 -46.0,-23.5Q-57.0,4.0 -82.0,30.0Q-102.0,5.0 -110.5,-19.5Q-119.0,-44.0 -119.0,-66.0Z"  transform="translate(2703, 559)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">꩑ꩀꨇ,ꨮꨇꨵꨳꨝ,</span> (Added by SIESTA)</li>


<pre>Expected: one_cham=0+541|kFinal_cham=1+898|kha_cham=2+1309|comma.cham=3+268|uni25CC=3+594|oeSign_cham=3@-69,0+0|kha_cham=5+1309|laMedial_cham.narrow=5@62,-3+0|yaMedial_cham=5+542|ba_cham=8+1003|comma.cham=9+268</pre>



<pre>Got     : one_cham=0+541|kFinal_cham=1+898|kha_cham=2+1309|comma.cham=3+268|oeSign_cham=3+0|kha_cham=5+1309|laMedial_cham.narrow=5@62,-3+0|yaMedial_cham=5+542|ba_cham=8+1003|comma.cham=9+268</pre>



<pre>                                                                            ++++++++++++++             ++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6138 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(0, 851)"/>
<path d="M818.0,327.0Q818.0,242.0 789.0,158.5Q760.0,75.0 707.0,3.0Q654.0,-69.0 581.0,-122.0L523.0,-66.0Q588.0,-19.0 634.5,44.0Q681.0,107.0 706.5,179.5Q732.0,252.0 732.0,328.0Q732.0,421.0 700.0,473.0Q668.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q344.0,594.0 387.5,571.0Q431.0,548.0 455.0,504.0Q480.0,548.0 522.0,571.0Q564.0,594.0 618.0,594.0Q712.0,594.0 765.0,522.5Q818.0,451.0 818.0,327.0Z"  transform="translate(541, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(1439, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(2748, 851)"/>
<path d="M-6.0,911.0Q-6.0,856.0 -33.5,807.5Q-61.0,759.0 -111.0,729.5Q-161.0,700.0 -229.0,700.0Q-275.0,700.0 -319.0,711.5Q-363.0,723.0 -388.0,745.0L-344.0,795.0Q-325.0,781.0 -295.0,772.5Q-265.0,764.0 -233.0,764.0Q-169.0,764.0 -126.0,804.0Q-83.0,844.0 -83.0,911.0L-6.0,911.0Z"  transform="translate(3016, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(3016, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0Z"  transform="translate(4387, 848)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(4325, 851)"/>
<path d="M950.0,418.0Q950.0,381.0 935.0,342.0Q920.0,303.0 889.0,276.0L827.0,325.0Q844.0,342.0 855.0,367.5Q866.0,393.0 866.0,420.0Q866.0,469.0 836.5,497.0Q807.0,525.0 756.0,525.0Q706.0,525.0 678.5,495.5Q651.0,466.0 651.0,415.0Q651.0,384.0 661.0,354.5Q671.0,325.0 683.5,296.0Q696.0,267.0 706.0,236.0Q716.0,205.0 716.0,170.0Q716.0,87.0 659.0,35.0Q602.0,-17.0 503.0,-17.0Q403.0,-17.0 345.5,35.0Q288.0,87.0 288.0,170.0Q288.0,205.0 298.0,236.0Q308.0,267.0 320.5,296.0Q333.0,325.0 343.0,354.5Q353.0,384.0 353.0,415.0Q353.0,466.0 325.0,495.5Q297.0,525.0 247.0,525.0Q196.0,525.0 166.5,497.0Q137.0,469.0 137.0,420.0Q137.0,393.0 148.5,367.5Q160.0,342.0 176.0,325.0L114.0,276.0Q84.0,303.0 68.5,342.0Q53.0,381.0 53.0,418.0Q53.0,498.0 107.0,546.0Q161.0,594.0 249.0,594.0Q333.0,594.0 385.5,547.0Q438.0,500.0 438.0,422.0Q438.0,383.0 429.0,349.5Q420.0,316.0 407.5,286.0Q395.0,256.0 386.0,227.5Q377.0,199.0 377.0,170.0Q377.0,116.0 410.5,83.5Q444.0,51.0 502.0,51.0Q561.0,51.0 593.5,83.5Q626.0,116.0 626.0,170.0Q626.0,199.0 617.0,227.5Q608.0,256.0 595.5,286.0Q583.0,316.0 574.0,349.5Q565.0,383.0 565.0,422.0Q565.0,500.0 617.5,547.0Q670.0,594.0 754.0,594.0Q843.0,594.0 896.5,546.0Q950.0,498.0 950.0,418.0Z"  transform="translate(4867, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(5870, 851)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6732 2468" transform="matrix(1 0 0 -1 0 0)">
<path d="M512.0,392.0Q512.0,268.0 404.0,198.0L362.0,171.0Q340.0,157.0 333.0,144.5Q326.0,132.0 326.0,109.0L326.0,-282.0L239.0,-282.0L239.0,118.0Q239.0,147.0 245.5,166.5Q252.0,186.0 284.0,205.0L331.0,234.0Q384.0,266.0 405.0,305.5Q426.0,345.0 426.0,387.0Q426.0,455.0 385.0,490.0Q344.0,525.0 278.0,525.0Q211.0,525.0 170.5,491.5Q130.0,458.0 130.0,396.0Q130.0,374.0 133.0,355.0Q162.0,384.0 203.0,384.0Q238.0,384.0 260.5,364.5Q283.0,345.0 283.0,311.0Q283.0,277.0 258.5,255.5Q234.0,234.0 196.0,234.0Q136.0,234.0 94.5,279.5Q53.0,325.0 53.0,401.0Q53.0,459.0 82.0,502.0Q111.0,545.0 163.0,569.5Q215.0,594.0 283.0,594.0Q350.0,594.0 401.5,570.0Q453.0,546.0 482.5,500.5Q512.0,455.0 512.0,392.0ZM199.0,346.0Q166.0,346.0 148.0,308.0Q167.0,275.0 201.0,275.0Q221.0,275.0 230.0,285.0Q239.0,295.0 239.0,311.0Q239.0,328.0 227.5,337.0Q216.0,346.0 199.0,346.0Z"  transform="translate(0, 851)"/>
<path d="M818.0,327.0Q818.0,242.0 789.0,158.5Q760.0,75.0 707.0,3.0Q654.0,-69.0 581.0,-122.0L523.0,-66.0Q588.0,-19.0 634.5,44.0Q681.0,107.0 706.5,179.5Q732.0,252.0 732.0,328.0Q732.0,421.0 700.0,473.0Q668.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q344.0,594.0 387.5,571.0Q431.0,548.0 455.0,504.0Q480.0,548.0 522.0,571.0Q564.0,594.0 618.0,594.0Q712.0,594.0 765.0,522.5Q818.0,451.0 818.0,327.0Z"  transform="translate(541, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(1439, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(2748, 851)"/>
<path d="M297.0,537.0Q308.0,537.0 315.5,529.5Q323.0,522.0 323.0,511.0Q323.0,501.0 315.5,493.0Q308.0,485.0 297.0,485.0Q287.0,485.0 279.0,493.0Q271.0,501.0 271.0,511.0Q271.0,522.0 279.0,529.5Q287.0,537.0 297.0,537.0ZM213.0,519.0Q224.0,519.0 231.5,511.5Q239.0,504.0 239.0,493.0Q239.0,483.0 231.5,475.0Q224.0,467.0 213.0,467.0Q203.0,467.0 195.0,475.0Q187.0,483.0 187.0,493.0Q187.0,504.0 195.0,511.5Q203.0,519.0 213.0,519.0ZM381.0,519.0Q392.0,519.0 399.5,511.5Q407.0,504.0 407.0,493.0Q407.0,483.0 399.5,475.0Q392.0,467.0 381.0,467.0Q371.0,467.0 363.0,475.0Q355.0,483.0 355.0,493.0Q355.0,504.0 363.0,511.5Q371.0,519.0 381.0,519.0ZM113.0,446.0Q113.0,457.0 121.0,464.5Q129.0,472.0 139.0,472.0Q150.0,472.0 157.5,464.5Q165.0,457.0 165.0,446.0Q165.0,436.0 157.5,428.0Q150.0,420.0 139.0,420.0Q129.0,420.0 121.0,428.0Q113.0,436.0 113.0,446.0ZM429.0,446.0Q429.0,457.0 437.0,464.5Q445.0,472.0 455.0,472.0Q466.0,472.0 473.5,464.5Q481.0,457.0 481.0,446.0Q481.0,436.0 473.5,428.0Q466.0,420.0 455.0,420.0Q445.0,420.0 437.0,428.0Q429.0,436.0 429.0,446.0ZM66.0,372.0Q66.0,383.0 74.0,390.5Q82.0,398.0 92.0,398.0Q103.0,398.0 110.5,390.5Q118.0,383.0 118.0,372.0Q118.0,362.0 110.5,354.0Q103.0,346.0 92.0,346.0Q82.0,346.0 74.0,354.0Q66.0,362.0 66.0,372.0ZM476.0,372.0Q476.0,383.0 484.0,390.5Q492.0,398.0 502.0,398.0Q513.0,398.0 520.5,390.5Q528.0,383.0 528.0,372.0Q528.0,362.0 520.5,354.0Q513.0,346.0 502.0,346.0Q492.0,346.0 484.0,354.0Q476.0,362.0 476.0,372.0ZM48.0,288.0Q48.0,299.0 56.0,306.5Q64.0,314.0 74.0,314.0Q85.0,314.0 92.5,306.5Q100.0,299.0 100.0,288.0Q100.0,278.0 92.5,270.0Q85.0,262.0 74.0,262.0Q64.0,262.0 56.0,270.0Q48.0,278.0 48.0,288.0ZM494.0,288.0Q494.0,299.0 502.0,306.5Q510.0,314.0 520.0,314.0Q531.0,314.0 538.5,306.5Q546.0,299.0 546.0,288.0Q546.0,278.0 538.5,270.0Q531.0,262.0 520.0,262.0Q510.0,262.0 502.0,270.0Q494.0,278.0 494.0,288.0ZM66.0,204.0Q66.0,215.0 74.0,222.5Q82.0,230.0 92.0,230.0Q103.0,230.0 110.5,222.5Q118.0,215.0 118.0,204.0Q118.0,194.0 110.5,186.0Q103.0,178.0 92.0,178.0Q82.0,178.0 74.0,186.0Q66.0,194.0 66.0,204.0ZM476.0,204.0Q476.0,215.0 484.0,222.5Q492.0,230.0 502.0,230.0Q513.0,230.0 520.5,222.5Q528.0,215.0 528.0,204.0Q528.0,194.0 520.5,186.0Q513.0,178.0 502.0,178.0Q492.0,178.0 484.0,186.0Q476.0,194.0 476.0,204.0ZM113.0,130.0Q113.0,141.0 121.0,148.5Q129.0,156.0 139.0,156.0Q150.0,156.0 157.5,148.5Q165.0,141.0 165.0,130.0Q165.0,120.0 157.5,112.0Q150.0,104.0 139.0,104.0Q129.0,104.0 121.0,112.0Q113.0,120.0 113.0,130.0ZM429.0,130.0Q429.0,141.0 437.0,148.5Q445.0,156.0 455.0,156.0Q466.0,156.0 473.5,148.5Q481.0,141.0 481.0,130.0Q481.0,120.0 473.5,112.0Q466.0,104.0 455.0,104.0Q445.0,104.0 437.0,112.0Q429.0,120.0 429.0,130.0ZM213.0,109.0Q224.0,109.0 231.5,101.5Q239.0,94.0 239.0,83.0Q239.0,73.0 231.5,65.0Q224.0,57.0 213.0,57.0Q203.0,57.0 195.0,65.0Q187.0,73.0 187.0,83.0Q187.0,94.0 195.0,101.5Q203.0,109.0 213.0,109.0ZM381.0,109.0Q392.0,109.0 399.5,101.5Q407.0,94.0 407.0,83.0Q407.0,73.0 399.5,65.0Q392.0,57.0 381.0,57.0Q371.0,57.0 363.0,65.0Q355.0,73.0 355.0,83.0Q355.0,94.0 363.0,101.5Q371.0,109.0 381.0,109.0ZM297.0,91.0Q308.0,91.0 315.5,83.5Q323.0,76.0 323.0,65.0Q323.0,55.0 315.5,47.0Q308.0,39.0 297.0,39.0Q287.0,39.0 279.0,47.0Q271.0,55.0 271.0,65.0Q271.0,76.0 279.0,83.5Q287.0,91.0 297.0,91.0Z"  transform="translate(3016, 851)"/>
<path d="M-6.0,911.0Q-6.0,856.0 -33.5,807.5Q-61.0,759.0 -111.0,729.5Q-161.0,700.0 -229.0,700.0Q-275.0,700.0 -319.0,711.5Q-363.0,723.0 -388.0,745.0L-344.0,795.0Q-325.0,781.0 -295.0,772.5Q-265.0,764.0 -233.0,764.0Q-169.0,764.0 -126.0,804.0Q-83.0,844.0 -83.0,911.0L-6.0,911.0Z"  transform="translate(3541, 851)"/>
<path d="M1256.0,417.0Q1256.0,377.0 1242.5,342.0Q1229.0,307.0 1198.0,274.0L1134.0,320.0Q1172.0,359.0 1172.0,418.0Q1172.0,468.0 1143.5,496.5Q1115.0,525.0 1065.0,525.0Q1023.0,525.0 997.5,497.5Q972.0,470.0 963.0,418.0Q955.0,370.0 938.5,341.0Q922.0,312.0 892.5,295.0Q863.0,278.0 815.0,266.0Q810.0,180.0 784.0,116.5Q758.0,53.0 715.5,18.0Q673.0,-17.0 618.0,-17.0Q557.0,-17.0 521.0,17.0Q485.0,51.0 485.0,112.0Q485.0,192.0 550.5,243.0Q616.0,294.0 725.0,312.0L732.0,313.0Q731.0,418.0 699.0,471.5Q667.0,525.0 607.0,525.0Q558.0,525.0 524.5,490.0Q491.0,455.0 493.0,379.0L418.0,379.0Q420.0,453.0 387.5,489.0Q355.0,525.0 302.0,525.0Q252.0,525.0 223.0,496.0Q194.0,467.0 194.0,420.0Q194.0,382.0 209.5,343.0Q225.0,304.0 240.5,261.0Q256.0,218.0 256.0,168.0Q256.0,84.0 204.5,27.0Q153.0,-30.0 64.0,-45.0L48.0,27.0Q104.0,38.0 137.0,75.5Q170.0,113.0 170.0,173.0Q170.0,214.0 154.5,254.0Q139.0,294.0 123.5,335.5Q108.0,377.0 108.0,424.0Q108.0,474.0 131.0,512.5Q154.0,551.0 194.5,572.5Q235.0,594.0 289.0,594.0Q345.0,594.0 388.0,570.0Q431.0,546.0 455.0,501.0Q479.0,546.0 521.5,570.0Q564.0,594.0 618.0,594.0Q706.0,594.0 758.0,526.5Q810.0,459.0 815.0,333.0Q848.0,346.0 865.0,372.0Q882.0,398.0 891.0,449.0Q905.0,525.0 953.5,559.5Q1002.0,594.0 1072.0,594.0Q1156.0,594.0 1206.0,545.5Q1256.0,497.0 1256.0,417.0ZM568.0,115.0Q568.0,87.0 580.5,69.0Q593.0,51.0 618.0,51.0Q662.0,51.0 692.0,103.0Q722.0,155.0 730.0,248.0Q638.0,227.0 603.0,191.5Q568.0,156.0 568.0,115.0Z"  transform="translate(3610, 851)"/>
<path d="M-134.0,150.0Q-144.0,101.0 -166.0,74.0Q-188.0,47.0 -224.0,47.0Q-248.0,47.0 -267.0,55.0Q-286.0,63.0 -309.0,63.0Q-355.0,63.0 -370.0,7.0Q-365.0,7.0 -360.0,7.0Q-298.0,7.0 -257.5,-21.5Q-217.0,-50.0 -217.0,-103.0Q-217.0,-148.0 -244.5,-173.5Q-272.0,-199.0 -313.0,-199.0Q-365.0,-199.0 -402.5,-161.5Q-440.0,-124.0 -440.0,-44.0Q-440.0,30.0 -409.5,80.5Q-379.0,131.0 -321.0,131.0Q-297.0,131.0 -280.0,123.5Q-263.0,116.0 -244.0,116.0Q-224.0,116.0 -214.0,131.0Q-204.0,146.0 -199.0,172.0L-134.0,150.0ZM-357.0,-46.0Q-366.0,-46.0 -376.0,-48.0Q-375.0,-98.0 -356.5,-119.5Q-338.0,-141.0 -316.0,-141.0Q-281.0,-141.0 -281.0,-102.0Q-281.0,-75.0 -301.5,-60.5Q-322.0,-46.0 -357.0,-46.0Z"  transform="translate(4981, 848)"/>
<path d="M489.0,421.0Q489.0,341.0 425.0,274.0L362.0,321.0Q382.0,341.0 393.5,367.0Q405.0,393.0 405.0,421.0Q405.0,471.0 375.5,498.0Q346.0,525.0 296.0,525.0Q246.0,525.0 217.5,499.0Q189.0,473.0 189.0,429.0Q189.0,403.0 195.5,375.5Q202.0,348.0 202.0,319.0Q202.0,269.0 163.0,231.0Q124.0,193.0 56.0,172.0L30.0,199.0Q33.0,214.0 33.0,231.0Q33.0,283.0 2.5,315.5Q-28.0,348.0 -78.0,351.0L-81.0,424.0Q-2.0,415.0 42.0,366.0Q86.0,317.0 86.0,247.0Q106.0,261.0 114.5,279.5Q123.0,298.0 123.0,320.0Q123.0,343.0 115.0,374.0Q107.0,405.0 107.0,436.0Q107.0,507.0 157.5,550.5Q208.0,594.0 296.0,594.0Q383.0,594.0 436.0,546.5Q489.0,499.0 489.0,421.0Z"  transform="translate(4919, 851)"/>
<path d="M950.0,418.0Q950.0,381.0 935.0,342.0Q920.0,303.0 889.0,276.0L827.0,325.0Q844.0,342.0 855.0,367.5Q866.0,393.0 866.0,420.0Q866.0,469.0 836.5,497.0Q807.0,525.0 756.0,525.0Q706.0,525.0 678.5,495.5Q651.0,466.0 651.0,415.0Q651.0,384.0 661.0,354.5Q671.0,325.0 683.5,296.0Q696.0,267.0 706.0,236.0Q716.0,205.0 716.0,170.0Q716.0,87.0 659.0,35.0Q602.0,-17.0 503.0,-17.0Q403.0,-17.0 345.5,35.0Q288.0,87.0 288.0,170.0Q288.0,205.0 298.0,236.0Q308.0,267.0 320.5,296.0Q333.0,325.0 343.0,354.5Q353.0,384.0 353.0,415.0Q353.0,466.0 325.0,495.5Q297.0,525.0 247.0,525.0Q196.0,525.0 166.5,497.0Q137.0,469.0 137.0,420.0Q137.0,393.0 148.5,367.5Q160.0,342.0 176.0,325.0L114.0,276.0Q84.0,303.0 68.5,342.0Q53.0,381.0 53.0,418.0Q53.0,498.0 107.0,546.0Q161.0,594.0 249.0,594.0Q333.0,594.0 385.5,547.0Q438.0,500.0 438.0,422.0Q438.0,383.0 429.0,349.5Q420.0,316.0 407.5,286.0Q395.0,256.0 386.0,227.5Q377.0,199.0 377.0,170.0Q377.0,116.0 410.5,83.5Q444.0,51.0 502.0,51.0Q561.0,51.0 593.5,83.5Q626.0,116.0 626.0,170.0Q626.0,199.0 617.0,227.5Q608.0,256.0 595.5,286.0Q583.0,316.0 574.0,349.5Q565.0,383.0 565.0,422.0Q565.0,500.0 617.5,547.0Q670.0,594.0 754.0,594.0Q843.0,594.0 896.5,546.0Q950.0,498.0 950.0,418.0Z"  transform="translate(5461, 851)"/>
<path d="M192.0,470.0Q179.0,417.0 154.5,353.5Q130.0,290.0 106.0,236.0L41.0,236.0Q55.0,293.0 69.5,361.0Q84.0,429.0 91.0,481.0L185.0,481.0L192.0,470.0Z"  transform="translate(6464, 851)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt
	* ja_cham
	* chha_cham
	* jha_cham
	* ngFinal_cham
	* nga_cham
	* nhue_cham and 8 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<674.0,161.0>--<674.0,163.0>> -> L<<674.0,163.0>--<674.0,165.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NotoSansCham-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nue_cham
	* pha_cham
	* da_cham
	* dda_cham
	* ngue_cham
	* na_cham.calt
	* ppa_cham
	* eight_cham
	* ja_cham
	* chha_cham and 27 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=279.0,Y=617.0 (should be at cap-height 616?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* O (U+004F): X=396.0,Y=617.0 (should be at cap-height 616?)

	* Q (U+0051): X=396.0,Y=617.0 (should be at cap-height 616?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* i (U+0069): X=144.0,Y=618.0 (should be at cap-height 616?) 

	* And 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<701.0,170.0>--<701.0,171.0>> -> L<<701.0,171.0>--<701.0,172.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726 

	* And Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansCham-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nhja_cham (U+AA12): L<<643.0,-10.0>--<641.0,-10.0>> -> L<<641.0,-10.0>--<572.0,-10.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<126.0,714.0>--<124.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[6] NotoSansCham[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 269. [code: invalid-default-instance-subfamily-nameid:269]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- laMedial_cham + waMedial_cham

	- waMedial_cham + uSign_cham

	- uSign_cham + waMedial_cham

	- waMedial_cham + ueSign_cham

	- ueSign_cham + uSign_cham

	- uSign_cham + ueSign_cham

	- ueSign_cham + waMedial_cham 

	- And laMedial_cham.narrow + uSign_cham [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 10 | 3 | 76 | 1101 | 62 | 963 | 0 |
| 0% | 0% | 3% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**