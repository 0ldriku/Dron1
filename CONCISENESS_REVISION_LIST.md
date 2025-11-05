# Comprehensive Conciseness Revision List

**Generated**: 2025-11-05
**Purpose**: Identify verbose passages that can be condensed to make the thesis more concise for busy reviewers
**Total Potential Savings**: ~1,200 words (~3-4 pages)

---

## 🔴 CRITICAL - Must Fix (High Impact, Easy Wins)

### 1. Chapter 12:20 - Repetitive Sentence
**Location**: `Chapters/Chapter12.tex:20`
**Problem**: Two nearly identical sentences back-to-back

**Current text**:
```latex
This consistency validates CLT's architectural claims for real-time L2 performance \parencite{sweller2010,sweller2019}. This pattern is consistent with CLT's architectural commitments to real time L2 performance\parencite{sweller2010,sweller2019}.
```

**Why verbose**: Says the same thing twice with same citations

**How to fix**: Delete the second sentence entirely

**Words saved**: ~20 words

---

### 2. Chapter 12:26 - Duplicate Framing
**Location**: `Chapters/Chapter12.tex:26` (end of paragraph)
**Problem**: "This reframes modality..." appears twice in same paragraph

**Current text**:
```latex
This reframes modality as learner-contingent alignment rather than universal design prescription, extending CLT beyond split-attention principles to schema-format matching. [...] This reframes modality as a learner-contingent alignment variable rather than a universal design prescription.
```

**Why verbose**: Says "reframes modality" twice

**How to fix**: Delete the second "This reframes..." sentence, keep only the first

**Words saved**: ~20 words

---

### 3. Chapter 2 Section 2: Lines 9-11 - Verbose CAF Trade-off Explanation
**Location**: `Chapters/chapter02-s2.tex:9-11`
**Problem**: 200+ word paragraph repeating well-known CAF trade-off concept

**Current text**: Full paragraph starting "Under high task or presentation demands, speakers reallocate limited resources..."

**Why verbose**: Over-explains basic CAF trade-off that's covered elsewhere, too many hedges and qualifications

**How to fix**: Condense to 2 sentences:
```latex
Under high demands, speakers reallocate limited resources among CAF dimensions \parencite{housen2009}. When online pressure is eased through planning time or clear goals, learners typically sustain steadier flow and attempt more elaborated language \parencite{EllisYuan2004}.
```

**Words saved**: ~150 words

---

### 4. Chapter 2 Section 1: Lines 34-38 - Verbose Historical Background
**Location**: `Chapters/chapter02-s1.tex:34-38`
**Problem**: 2 full paragraphs explaining historical development of CLT (means-ends analysis, worked examples)

**Current text**: Starting "The development of CLT was initially motivated by evidence that conventional problem-solving..."

**Why verbose**: Historical background that doesn't directly support thesis; professors don't need CLT 101

**How to fix**: Condense both paragraphs to 3 sentences:
```latex
CLT was motivated by evidence that means-ends analysis consumes working memory without supporting schema acquisition \parencite{sweller1988,sweller2010}. Goal-free problems, worked examples, and completion problems reduce unnecessary search, freeing capacity for learning \parencite{sweller2019}. Format effects (integrated sources, redundancy reduction) follow from this element interactivity logic \parencite{chandler1991}.
```

**Words saved**: ~180 words

---

### 5. Chapter 2 Section 1: Lines 50-56 - Verbose Consolidation Section
**Location**: `Chapters/chapter02-s1.tex:50-56`
**Problem**: 2 paragraphs of meta-commentary about CLT's current state

**Current text**: Starting "Recent summaries portray CLT as consolidated and refined..."

**Why verbose**: Says "CLT is well-established" in many words; doesn't add empirical content

**How to fix**: Condense to 2 sentences:
```latex
Recent work integrates CLT with motivational theories, showing that load management combined with autonomy support yields lower reported load and higher engagement \parencite{evans2024,skulmowski2023}. Applied summaries extend these mechanisms to L2 teaching, recommending explicit instruction and redundancy control for adult novices until schemas consolidate \parencite{Sweller2017TESL}.
```

**Words saved**: ~140 words

---

## 🟡 MEDIUM PRIORITY - Should Fix (Moderate Impact)

### 6. Chapter 2 Section 2: Lines 16-25 - Verbose Task Sequencing Section
**Location**: `Chapters/chapter02-s2.tex:16-25`
**Problem**: 2 long paragraphs with excessive detail about SSARC and sequencing studies

**Current text**: Starting "Sequencing proposals such as SSARC..."

**Why verbose**: Too much detail about specific sequencing studies; loses focus

**How to fix**: Condense to 1 paragraph (4 sentences):
```latex
Sequencing proposals such as SSARC make explicit commitments about ordering \parencite{Robinson2005}. Experimental work shows complex-to-simple sequences advantage complexity and accuracy, while simple-to-complex sequences advantage fluency \parencite{chen2025}. Validation remains important, as only large increases in elements yield measurable load differences \parencite{sasayama2016}. Classic supports such as pre-task planning buffer fluency costs under higher conceptual load \parencite{ryu2018}.
```

**Words saved**: ~120 words

---

### 7. Chapter 2 Section 2: Lines 28-37 - Verbose Comprehension Signatures
**Location**: `Chapters/chapter02-s2.tex:28-37`
**Problem**: First paragraph has 200+ words with nested explanations

**Current text**: Starting "In comprehension, capacity constraints have well-documented ocular correlates..."

**Why verbose**: Over-explains temporal vs. spatial measures with too many parenthetical clarifications

**How to fix**: Condense to 4 sentences:
```latex
In comprehension, increased complexity raises first-fixation and gaze duration, increases regressions, and shortens forward saccades, reflecting effortful integration \parencite{rayner1998,sweller2019}. Early measures index lexical access; later measures index integration and discourse binding. Spatial measures (radius of gyration, convex hull area) capture attentional distribution across text \parencites{schad2012zoom,torres2021eye}. Linguistic complexity broadens attentional gradients and suppresses forward saccade generation \parencite{engbert2005swift,schad2012zoom}.
```

**Words saved**: ~100 words

---

### 8. Chapter 12:59-61 - Verbose Multivariate Logic Extension
**Location**: `Chapters/Chapter12.tex:59-61`
**Problem**: Second paragraph in multivariate section repeats the point

**Current text**: "This multivariate logic extends beyond the present studies..."

**Why verbose**: Already made the point in previous paragraph; this is just repetition

**How to fix**: Delete entire paragraph

**Words saved**: ~70 words

---

### 9. Chapter 12:148-151 - Verbose Effect Size Interpretation
**Location**: `Chapters/Chapter12.tex:148-151`
**Problem**: Second paragraph hedges excessively about modest effects

**Current text**: "These modest effects are interpretable in two ways..."

**Why verbose**: Over-qualifies limitations already stated

**How to fix**: Condense to 1 sentence:
```latex
These modest effects may reflect either genuine small impacts with other unmeasured factors accounting for more variance, or conservative multimethod verification that filtered noisier effects.
```

**Words saved**: ~50 words

---

### 10. Chapter 12:196 - Verbose Equity Paragraph
**Location**: `Chapters/Chapter12.tex:196` (second-to-last paragraph)
**Problem**: Final two sentences are repetitive

**Current text**: Ending with "...this research provides evidence-based guidance for creating more equitable learning environments. Second language proficiency has become essential..."

**Why verbose**: Already made the equity point; second sentence restates

**How to fix**: Delete the last two sentences of that paragraph (starting "Second language proficiency has become...")

**Words saved**: ~50 words

---

## 🟢 LOW PRIORITY - Optional (Minor Impact)

### 11. Chapter 2 Section 1: Line 70 - Excessive Japanese Writing Detail
**Location**: `Chapters/chapter02-s1.tex:70`
**Problem**: Long sentence about kanji stroke counts

**Current text**: "Visual complexity within characters also matters: words containing high-stroke kanji are fixated more often..."

**Why verbose**: Too specific for this context; more appropriate for methods

**How to fix**: Delete this sentence

**Words saved**: ~40 words

---

### 12. Chapter 2 Section 2: Lines 51-56 - Verbose Pupillometry Caveats
**Location**: `Chapters/chapter02-s2.tex:51-56`
**Problem**: Full paragraph explaining inverted-U and disengagement

**Current text**: "However, this relationship is not always linear..."

**Why verbose**: Over-explains measurement nuances better left to methods chapter

**How to fix**: Condense to 2 sentences:
```latex
However, pupil dilation shows an inverted-U response: it increases with difficulty up to manageable levels, then declines when tasks become unmanageable, reflecting disengagement \parencite{herrmann2024pupil,vanderwel2018pupil}. Lower dilation in complex conditions can indicate under-allocation due to overload rather than low demand \parencite{minassian2004pupillary}.
```

**Words saved**: ~80 words

---

### 13. Chapter 6:19-21 - Minor Verbose Explanation
**Location**: `Chapters/Chapter06.tex:19-21`
**Problem**: Paragraph repeats "capacity-limited" framing

**Current text**: "In a capacity-limited system this is a sensible reshaping..."

**Why verbose**: Slightly verbose but acceptable; could tighten

**How to fix**: Optional - condense to:
```latex
This reallocation is sensible: as relations increase, message formulation and lexical selection absorb more control, leaving less for phrasal units and tempo.
```

**Words saved**: ~20 words

---

### 14. Chapter 12:67 - Verbose Verification Paragraph
**Location**: `Chapters/Chapter12.tex:67`
**Problem**: Long third sentence repeats principle

**Current text**: "The principle is conservative, analyses proceed only when multiple indices align..."

**Why verbose**: Slightly repetitive with previous sentence

**How to fix**: Split into clearer sentences or trim hedges

**Words saved**: ~15 words

---

### 15. Chapter 12:173 - Verbose Intervention Example
**Location**: `Chapters/Chapter12.tex:173`
**Problem**: Middle sentence over-explains the design

**Current text**: "Pre-post designs could therefore be used to teach this trade-off awareness. This involves explaining..."

**Why verbose**: Over-explains obvious design

**How to fix**: Merge: "Pre-post designs could teach this awareness by explaining that slowing to maintain accuracy is strategic, testing whether metacognitive calibration improves prioritization."

**Words saved**: ~10 words

---

## Summary Statistics

| Priority | Items | Total Words Saved |
|----------|-------|-------------------|
| 🔴 Critical (Must Fix) | 5 | ~510 words |
| 🟡 Medium (Should Fix) | 5 | ~390 words |
| 🟢 Low (Optional) | 5 | ~165 words |
| **TOTAL** | **15** | **~1,065 words** |

---

## Implementation Priority Order

1. **Fix Critical duplications (Items #1-5)**: Immediate, high impact
   - Chapter 12 duplications (#1, #2)
   - Chapter 2 verbose background (#3, #4, #5)
   - **Impact**: ~510 words saved (~1.5 pages)

2. **Condense Medium sections (Items #6-10)**: Moderate effort, good return
   - Chapter 2 technical details (#6, #7)
   - Chapter 12 repetitions (#8, #9, #10)
   - **Impact**: ~390 words saved (~1 page)

3. **Optional Low priority (Items #11-15)**: Only if you want maximum conciseness
   - Minor tightening across chapters
   - **Impact**: ~165 words saved (~0.5 page)

---

## Notes

- The critical issues are mostly in **Chapter 2 (framework)** and **Chapter 12 (conclusions)** - these are chapters busy professors will read most carefully, so tightening them has the highest payoff.
- Most savings come from removing **repetitions** and **over-explanations of well-known concepts** (CLT basics, CAF trade-offs).
- The thesis is generally well-written; these are refinements for maximum conciseness.
