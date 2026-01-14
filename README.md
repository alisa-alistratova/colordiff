# Color Difference Perception Study

This repository contains a small web-based experiment created as part of an **IB Math SL school project**.  
The goal of the project is to study how humans perceive differences between colors and to compare these subjective judgments with distances computed in different color models.

**Live experiment:** https://colordiff.pythonanywhere.com/

---

## What is this experiment about?

Participants are shown pairs of colored rectangles and asked to rate **how similar the two colors look** on a numerical scale.  
By collecting many independent ratings for the same color pairs, we can estimate an average “human-perceived distance” and compare it with distances calculated using different mathematical color models.

The project explores questions such as:
- How well do simple RGB-based distances match human perception?
- Do perceptually motivated models (e.g. CIELAB / ΔE) correlate better with human judgments?
- How consistent are human color difference estimates across participants?

---

## How it works

- The experiment runs entirely in the browser.
- Participants can rate as many color pairs as they like and stop at any time.
- Progress is saved locally in the browser.
- All responses are anonymous and used only in aggregated form for the school project.
- A simple Python backend stores submitted ratings for later statistical analysis.

---

## Data analysis (overview)

After data collection:
- Responses from unreliable participants are filtered using simple consistency criteria.
- For each color pair, multiple ratings (typically 60–80) are aggregated using robust statistics.
- Human-perceived distances are compared with model distances using correlation measures (Pearson and Spearman).

---

## Project context

This experiment was designed for an **IB Mathematics SL Internal Assessment**.  
The focus is on applying mathematical tools (statistics, correlation, distance measures) to a real-world perceptual problem, rather than on advanced or overly complex modeling.

---

## Participation

If you would like to contribute data, simply visit the experiment link above and start rating color pairs.  
Every contribution helps improve the reliability of the results.

Thank you for participating!
