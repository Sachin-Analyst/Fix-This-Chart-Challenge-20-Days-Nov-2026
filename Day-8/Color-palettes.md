# Day 8 Color Palettes

Hex codes used in the Day 8 pages and charts of the Fix This Chart challenge.

---

## Document Colors

Set in Canva, for the pages. Same template as Day 1 to Day 7.

| Color | Hex Code | Used For |
| --- | --- | --- |
| Cream | `#FCF8E8` | Page background (Problem, Solution and Bonus pages) |
| Light blue | `#DCEEF8` | Question boxes, solution point box, Rule #8 page background |
| Yellow | `#FFDE59` | Day pill and creator pill |
| Light yellow | `#FFEEAB` | Bonus box |
| Orange | `#FF751F` | Number circles and dashed annotation boxes (dashed boxes are set at reduced opacity) |

---

## Problem Chart Colors

Set in Power BI, one column chart "Daily Orders FY25" with 365 daily bars (Date on the axis, Sum of Orders as the value). The bars use the default theme blue (Fluent2, first color of the palette). The value axis keeps its gridlines, there is no unit label and no annotation, so the pattern is hard to read. The page label "● Problem" is a separate text box above the chart.

| Color | Hex Code | Used For |
| --- | --- | --- |
| Default blue | `#118DFF` | All 365 daily bars |
| Dark grey | `#242424` | Chart title "Daily Orders FY25", axis text (theme default) |

---

## Solution Chart Colors

Set in Power BI, one line chart with two lines: Sum of Orders (raw daily) and the "Orders 7-Day Avg" measure. Focus approach: blue is the only accent, and it marks the trend. The raw daily line is pushed to a light grey behind it for context. Gridlines are off, the value axis has the title "Orders per day", and the legend is hidden. The header text box carries "● ORDER VOLUME:" in blue and "FY25 DAILY PATTERN" in dark grey. The Diwali annotation and the numbered callouts are added in Canva.

| Color | Hex Code | Used For |
| --- | --- | --- |
| Blue | `#3F7FF3` | 7-day average line, "● ORDER VOLUME:" word in the header |
| Light grey | `#DDDFE7` | Raw daily orders line (behind the average) |
| Dark grey | `#242424` | "FY25 DAILY PATTERN" in the header, action title "Orders grow steadily, Diwali week is the one spike", axis text, axis title (theme default) |

The 7-day average blue (`#3F7FF3`) is close to the default theme blue (`#118DFF`) used in the Problem chart, but a little softer. On screen they read as the same family.

---

## Problem vs Solution at a Glance

| | Problem Chart | Solution Chart |
| --- | --- | --- |
| Visual type | Column chart (365 bars) | Line chart (two lines) |
| Colors | 1 default theme blue | 1 accent blue + 1 light grey |
| Label color | `#E66C37` | `#0EAA4C` |
