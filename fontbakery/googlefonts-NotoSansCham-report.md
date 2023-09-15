## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansCham/googlefonts/ttf', 'fonts/NotoSansCham/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Cham' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[12] NotoSansCham-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_cham
	* ai_cham
	* bba_cham
	* bba_cham.calt
	* bha_cham
	* chFinal_cham
	* cha_cham
	* chha_cham
	* da_cham
	* dda_cham and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
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

	* 82 more.

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

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansCham-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_cham
	* bba_cham
	* bba_cham.calt
	* bha_cham
	* chFinal_cham
	* cha_cham
	* chha_cham
	* da_cham
	* dda_cham
	* e_cham and 40 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* 77 more.

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

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansCham-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* a_cham
	* bba_cham
	* bba_cham.calt
	* bha_cham
	* chFinal_cham
	* cha_cham
	* chha_cham
	* da_cham
	* dda_cham
	* e_cham and 44 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 578 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
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

	* 89 more.

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

	* Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansCham-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[10] NotoSansCham-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[13] NotoSansCham-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* bba_cham
	* bba_cham.calt
	* chha_cham
	* dda_cham
	* eight_cham
	* gFinal_cham
	* ga_cham
	* ha_cham
	* ja_cham
	* jha_cham and 16 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<687.0,165.0>--<687.0,167.0>> -> L<<687.0,167.0>--<687.0,169.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* nhja_cham (U+AA12): B<<349.5,-51.5>-<362.0,-22.0>-<381.0,-6.0>>/B<<381.0,-6.0>-<352.0,-21.0>-<313.0,-21.0>> = 12.751031766142344

	* nhja_cham (U+AA12): B<<437.0,86.0>-<437.0,35.0>-<400.0,6.0>>/B<<400.0,6.0>-<418.0,14.0>-<443.0,17.5>> = 14.126283906397104 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansCham-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* bba_cham
	* bba_cham.calt
	* chha_cham
	* dda_cham
	* ja_cham
	* jha_cham
	* kha_cham
	* nFinal_cham
	* na_cham
	* na_cham.calt and 8 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* jha_cham (U+AA0F): L<<674.0,161.0>--<674.0,163.0>> -> L<<674.0,163.0>--<674.0,165.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NotoSansCham-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* bba_cham
	* bba_cham.calt
	* chFinal_cham
	* cha_cham
	* chha_cham
	* da_cham
	* dda_cham
	* e_cham
	* eiSign_cham
	* eight_cham and 27 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Cham SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* 86 more.

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

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansCham-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nhja_cham (U+AA12): L<<643.0,-10.0>--<641.0,-10.0>> -> L<<641.0,-10.0>--<572.0,-10.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<126.0,714.0>--<124.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansCham[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 44 | 12 | 66 | 1161 | 52 | 1012 | 0 |
| 2% | 1% | 3% | 49% | 2% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
