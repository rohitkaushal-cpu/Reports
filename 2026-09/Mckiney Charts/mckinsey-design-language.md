# The McKinsey / MGI exhibit system, reverse-engineered

Source material: `D:\Reports\Mckiney Charts` — *MGI: 2025 in charts* (24pp), *MGI: 2024 in charts* (18pp), *Capturing the next big arenas of competition in ten charts* (20pp), *Economic conditions outlook, December 2025* (7pp), *India's turning point* (176pp). Read page by page, with the embedded font tables extracted.

---

## 1. Typography: two faces, strictly divided by job

The embedded fonts are unambiguous. Every document uses exactly two families:

**McKinsey Sans** — Light, Regular, Medium, LightItalic. This carries **everything functional**: exhibit titles, unit lines, axis labels, data values, legends, category names, body copy, footnotes, source lines.

**Bower Bold** — a high-contrast transitional serif. It appears **only** in four places:
- Section-divider display type ("Productivity & Prosperity", "Global Connections")
- Chapter numerals in article decks (the large "1", "2", "3" at far left)
- Pull quotes set in bright blue
- **Display statistics inside exhibits**: "2%", "63%", "36%", "1.3×", "37×", "54×", "57"

That last one matters. The serif never touches the data layer, but it is the face used for the one number the exhibit wants you to remember. The chart is sans; the conclusion is serif.

This directly contradicts the generic data-viz guidance I built the current exhibits against, which says never to put a serif on a hero figure. McKinsey does it deliberately and consistently, and it is a large part of why their exhibits read as editorial rather than as dashboard output.

## 2. Colour: two tones and a neutral, not a palette

Observed across all four decks:

| Role | Approx. hex | Use |
|---|---|---|
| Deep navy | `#051C2C` | The comparator series, endpoint bars, "everything else" |
| Bright blue | `#2251FF` | Section covers, pull quotes, occasional highlight |
| Cyan | `#00A9F4` | The subject of the exhibit, the series being argued about |
| Mid grey | `#9BA3AB` | The third, neutral category ("the same", "no change") |
| Pale grey | `#E6E6E6` / `#F0F0F0` | Inactive track, left narrative column field |
| Magenta / teal | `#B02A8F` / `#00847E` | Only in genuine multi-category charts (the FDI network map) |

The default is **two-tone emphasis**: cyan for the thing under discussion, navy for what it is being compared against, grey where a neutral third is genuinely needed. A categorical palette appears only when the data is actually categorical, which is roughly one exhibit in ten.

## 3. The page is the unit, not the chart

The MGI "in charts" format runs a fixed split:

- **Left ~33%**, pale grey field: the narrative. Opens with a **bold lead clause** that runs straight into regular-weight body text, with in-line blue hyperlinks to the underlying research.
- **Right ~67%**, white: the exhibit.
- Running footer, right-aligned: publication name in Medium, page number.

The article decks (arenas, econ outlook) use a different grid: a Bower numeral at far left, two columns of body copy, then the exhibit below at full width.

## 4. The exhibit stack, in invariable order

Every exhibit in all four documents follows the same seven-part structure:

1. **`Exhibit N`** — small, grey, sentence case. Present in article decks; omitted in the MGI charts collection.
2. **Action title** — McKinsey Sans Medium, sentence case, **always terminated with a full stop**. States a finding, never a topic. Wraps to two lines without concern. Examples: *"A few 'Standout' firms shape the majority of productivity growth."* / *"One-third of global household wealth growth since 2000 was on paper."* / *"Ease of rearrangement varies across products. Cotton T-shirts? Fairly easy. Fireworks? Impossible."*
3. **Unit line** — the signature move. The metric name in **Medium**, running directly into the unit in Light: *"**Share of national sample's productivity growth,** %"* / *"**Company ranking by market cap,** $ billion"* / *"**Distribution of work hours in the US, by technical automation potential, 2024,** %"*. The weight change inside a single line separates *what is measured* from *how it is measured*.
4. **The plot.**
5. **`Note:`** — optional, small grey, for rounding and methodology.
6. **`Source:`** — report title in italic, then publisher, then month and year.
7. **`McKinsey & Company`** — wordmark, Medium, ~8px.

Parts 2, 3, 6 and 7 are never omitted. An exhibit can be torn out of the deck and still stand alone.

## 5. Chart construction: the moves that define the look

**Values go inside the mark.** White on dark fills, dark on light. Not at the bar tip. This is the single biggest visual difference from conventional chart libraries.

**Axes are frequently deleted entirely.** The stacked bar on page 4 of the 2025 deck has no y-axis. The industry-pair bars on page 9 of the arenas deck have no axis. The rule is: if every value is printed, the axis is redundant, so remove it.

**Gridlines are usually absent.** Where they appear (the four ESG line charts), there are four or five, hairline, solid, never dashed.

**Bars are thin, square-ended and unrounded.** No radius anywhere in any of the four decks.

**Leader lines do the work legends would do.** The rearrangement-ratio exhibit has 200-plus bubbles and 30 labels connected by hairlines. They do not simplify to make it clean; they annotate their way through the complexity.

**Annotation rectangles mark periods.** A thin box drawn around a span with the multiplier printed outside it (ESG charts), or a pale grey band marking a period of interest (trade indicators).

**The right rail carries the "so what".** A vertical strip beside the plot with a coloured dot, a short label, and a Bower display figure: *"● Standouts / **2%** of firms / **63%** of national positive productivity growth."*

**Slope charts for two-period comparisons.** Open circle for the prior period, filled circle for the current, a shaded quadrilateral between them. Elegant, and directly reusable for before/after data.

**Small donuts are allowed at ~40px** for a single two-value split, with the number inside the ring. A rare deliberate exception to the usual prohibition on pies.

## 6. The philosophy underneath

1. **The title carries the argument.** The chart is evidence for a claim the reader has already been given, which is why every title ends in a full stop. It is an assertion, not a label.
2. **One exhibit, one claim.** Never two findings in one picture.
3. **Labels beat axes.** Print the value, delete the scale.
4. **Emphasis beats category.** Two tones handle most exhibits because most exhibits are about one thing against a background.
5. **Annotate like a document, do not decorate like a poster.** Every mark that is not data is a label, a leader line, or a rule.
6. **Density is permitted.** Complexity is met with more annotation, not with simplification.
7. **Self-containment is mandatory.** Unit, note, source, wordmark, every time.

---

## 7. Where the current LATAM exhibits diverge

| # | Ours | McKinsey | Severity |
|---|---|---|---|
| 1 | No unit line under the title | Every exhibit has metric in Medium + unit in Light | **Structural miss** |
| 2 | Titles have no terminal period | Always a full stop | High, it is what makes a title read as a claim |
| 3 | Values sit outside the bar tip | Values sit inside the mark | High |
| 4 | 4px rounded bar ends | Square, unrounded | Medium |
| 5 | Eyebrow set as `EXHIBIT 2 · MEXICO`, uppercase and letterspaced | `Exhibit 2`, sentence case, grey, no subject | Medium |
| 6 | Grey rounded-corner "step" boxes for prose blocks | Hairline-separated blocks, or nothing | Medium, ours reads as a slide deck |
| 7 | Generic blue/orange/grey data palette | Navy comparator, cyan subject, grey neutral | Medium |
| 8 | Sans for display figures | Bower serif for the one number that matters | Medium, this is a signature |
| 9 | Axis-free where possible ✓ | Same ✓ | Aligned |
| 10 | Action titles stating findings ✓ | Same ✓ | Aligned |
| 11 | Source line on every exhibit ✓ | Same ✓ | Aligned |
| 12 | No publisher wordmark | `McKinsey & Company` closes every exhibit | Low, would need a Vikram equivalent |

**The three that would change the most for the least effort:** add the unit line, put the values inside the bars, and put a full stop on every title.

**One deliberate divergence to keep.** McKinsey's left-hand narrative column exists because these are pages in a PDF. Our exhibits are inline images in a LinkedIn article, where the surrounding article *is* the narrative column. Reproducing it would duplicate the body text.

**One judgement call.** Bower is a licensed typeface. A free high-contrast serif in the same register would be needed to borrow the sans/serif split honestly, and the effect depends on the contrast being genuinely high.
