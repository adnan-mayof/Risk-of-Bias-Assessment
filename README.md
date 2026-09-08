# Step 11 — Risk-of-Bias Assessment
[← Previous Step: Data Extraction](https://github.com/adnan-mayof/Data-Extraction/blob/main/README.md)


Maya has finished full-text screening.

She now knows which studies meet the eligibility criteria for her systematic review.

But her mentor tells her that there is one more important step before she begins detailed data extraction.

> **Maya:** “Now that I know which studies are eligible, can I start extracting the data?”

> **Mentor:** “Before detailed data extraction, there is another important question.”

> **Maya:** “What is that?”

> **Mentor:** “How trustworthy are the results of these studies?”

> **Maya:** “You mean I need to assess the risk of bias?”

> **Mentor:** “Exactly.”

---

# 1. What Is Risk of Bias?

**Risk of bias** refers to the possibility that aspects of a study's design, conduct, analysis, or reporting could systematically distort its findings.

Risk of bias is different from simply asking whether a study is a “good” or “bad” study.

The assessment focuses on methodological problems that could influence the estimated effect.

For example, potential concerns may involve:

* Randomization
* Deviations from intended interventions
* Missing outcome data
* Measurement of outcomes
* Selection of reported results
* Confounding
* Selection of participants

The specific domains depend on the risk-of-bias tool being used.

---

# 2. Eligibility and Risk of Bias Are Different

Maya asks:

> **Maya:** “If a study has a high risk of bias, does that mean it should not have been eligible?”

> **Mentor:** “Not necessarily. Eligibility and risk of bias answer different questions.”

### Eligibility asks:

> **Does this study meet the criteria for inclusion in the review?**

### Risk of bias asks:

> **Could methodological problems in this study systematically influence its results?**

Therefore:

```text
Eligibility
     ↓
Does the study meet the review criteria?
     ↓
YES
     ↓
Risk-of-Bias Assessment
     ↓
How much concern exists about bias?
```

A study can therefore be **eligible for the review** while also having a **high risk of bias**.

---

# 3. Choose an Appropriate Risk-of-Bias Tool

Maya needs to select an assessment tool that matches the study designs in her review.

For example:

| Study Design                        | Possible Tool                    |
| ----------------------------------- | -------------------------------- |
| Randomized trials                   | RoB 2                            |
| Non-randomized intervention studies | ROBINS-I                         |
| Other study designs                 | Appropriate design-specific tool |

The tool should be selected **before the assessment is conducted** and should be appropriate for the designs included in the review.

Maya should not create her own scoring system simply because it seems easier.

---

# 4. Follow the Domains of the Tool

Each risk-of-bias tool has specific domains and signaling questions.

Maya follows the guidance for the selected tool.

She records:

* Domain-level judgments
* Supporting information from the study
* Concerns identified
* Overall judgment where the tool provides one
* Any information needed to justify the judgment

The goal is not simply to assign a label.

Maya needs to be able to explain **why** a judgment was made.

---

# 5. Do Not Guess When Information Is Missing

Maya encounters a study that does not provide enough information to answer one of the assessment questions.

> **Maya:** “I can't tell whether this study handled this properly.”

> **Mentor:** “Then don't guess. Follow the guidance of your risk-of-bias tool for insufficient information.”

Maya records the available evidence and applies the tool's recommended procedure.

This makes the assessment more transparent and reproducible.

---

# 6. High Risk of Bias Does Not Automatically Mean Exclusion

Maya asks:

> **Maya:** “So if a study has a high risk of bias, should I exclude it?”

> **Mentor:** “Not automatically.”

A high risk-of-bias judgment does **not by itself** mean that the study must be removed from the review or synthesis.

The protocol should specify how risk-of-bias judgments will be handled.

Possible approaches include:

* Retaining studies in the synthesis
* Considering risk of bias when interpreting findings
* Conducting sensitivity analyses
* Presenting results separately
* Excluding studies from a particular synthesis if a predefined protocol rule requires it

The important point is that Maya should **not create an exclusion rule after seeing the results**.

---

# 7. Assess Each Eligible Study

Maya now assesses the eligible studies using the selected risk-of-bias tool.

For each study, she records:

| Study ID  | Design             | Tool     | Judgment      | Supporting Evidence          |
| --------- | ------------------ | -------- | ------------- | ---------------------------- |
| Study 001 | Randomized         | RoB 2    | Low           | Evidence supporting judgment |
| Study 002 | Randomized         | RoB 2    | Some concerns | Evidence supporting judgment |
| Study 003 | Quasi-experimental | ROBINS-I | High          | Evidence supporting judgment |

The exact fields depend on the tool and review protocol.

---

# 8. If There Are Multiple Reviewers

If more than one reviewer is conducting the assessment, the protocol should specify how the process will work.

For example:

```text
Reviewer 1
     ↓
Independent assessment
     ↓
Reviewer 2
     ↓
Independent assessment
     ↓
Compare judgments
     ↓
Resolve disagreements
     ↓
Final judgment
```

Disagreements may be resolved through:

* Discussion
* Consensus
* A third reviewer

The method should follow the protocol.

If Maya is working alone, she should document her actual process rather than claiming that multiple reviewers conducted independent assessments.

---

# 9. Record the Risk-of-Bias Results

Maya creates a risk-of-bias table.

For example:

| Study ID  | Overall Judgment | Notes                         |
| --------- | ---------------- | ----------------------------- |
| Study 001 | Low risk         | No major concerns identified  |
| Study 002 | Some concerns    | Concern in one domain         |
| Study 003 | High risk        | Major methodological concerns |

The table provides a transparent record of the assessment.

---

# 10. How Risk of Bias Can Be Used in the Analysis

Risk-of-bias information can be incorporated into the synthesis in different ways.

For example, Maya may:

### Include all eligible studies

She reports the risk-of-bias judgments and considers them when interpreting the findings.

### Conduct sensitivity analysis

She compares:

```text
All eligible studies
        ↓
Primary analysis

Higher-risk studies removed
        ↓
Sensitivity analysis
```

She can then examine whether the conclusions change.

### Apply a predefined exclusion rule

If the protocol specifies a risk-of-bias threshold for a particular synthesis, studies meeting that threshold may be excluded from that synthesis.

The key is that the rule should be **prespecified**.

---

# 11. Risk of Bias and the Protocol

Maya checks her protocol.

Her protocol specifies:

* The risk-of-bias tool
* The assessment domains
* The assessment procedure
* How disagreements will be handled
* How risk-of-bias judgments will be incorporated into the synthesis
* Whether a predefined threshold affects eligibility for a particular synthesis

> **Mentor:** “This is why we developed the protocol before conducting the review. You already know how you planned to handle these decisions.”

---

# 12. Maya's Risk-of-Bias Workflow

Maya summarizes her process:

```text
Eligible Studies
       ↓
Select Appropriate Risk-of-Bias Tool
       ↓
Assess Each Study
       ↓
Record Domain-Level Judgments
       ↓
Document Supporting Evidence
       ↓
Determine Overall Judgment
       ↓
Apply Protocol-Specified Handling
       ↓
Document Results
```

Maya now understands that risk-of-bias assessment is not simply another screening decision.

It provides information about the **credibility and potential limitations of the evidence**.

---

# 13. What Should Maya Save?

Maya creates a structured risk-of-bias record.

```text
risk-of-bias/
├── risk-of-bias-tool.md
├── assessment-guide.md
├── assessment-form.xlsx
└── assessment-decisions.md
```

She also keeps documentation of reviewer decisions and disagreements when applicable.

```text
documentation/
├── reviewer-decisions.md
└── disagreement-log.md
```

This creates an audit trail for the assessment process.

---

# 14. Important Distinction: Risk of Bias vs. Study Exclusion

Maya summarizes what she has learned.

> **Maya:** “So risk of bias doesn't automatically determine whether a study belongs in my review.”

> **Mentor:** “Correct.”

A study can be:

```text
Eligible
   ↓
Risk of bias: Low
   ↓
Potentially included in synthesis
```

or:

```text
Eligible
   ↓
Risk of bias: High
   ↓
May still be included
```

or, if the protocol specifies a rule:

```text
Eligible
   ↓
Risk of bias: High
   ↓
Does not meet predefined
threshold for a particular synthesis
   ↓
Excluded from that synthesis
```

The handling depends on the **protocol and planned analysis**.

---

# 15. What Happens to the Studies After Risk-of-Bias Assessment?

Maya finishes assessing the risk of bias for all eligible studies.

She now reviews the results.

> **Maya:** “I found that some studies have low risk of bias, some have concerns, and some have high risk of bias.”

> **Mentor:** “Good. Now what happens to those studies?”

> **Maya:** “Do I exclude the studies with high risk of bias?”

> **Mentor:** “Not automatically. You need to follow the procedure you specified in your protocol.”

Maya checks her analysis plan.

Her protocol specifies that studies meeting a predefined **risk-of-bias threshold** will not contribute to the primary synthesis.

Therefore, some studies are excluded from the planned synthesis.

For example:

```text
Eligible studies after full-text screening
                ↓
              126
                ↓
       Risk-of-Bias Assessment
                ↓
       ┌────────┼────────┐
       ↓        ↓        ↓
      Low     Some      High
     Risk    Concerns   Risk
       ↓        ↓        ↓
      82       29        15
                         ↓
              Excluded from
              primary synthesis
```

Maya records the results:

| Risk-of-Bias Judgment | Number of Studies | Handling                        |
| --------------------- | ----------------: | ------------------------------- |
| Low risk              |                82 | Included in primary synthesis   |
| Some concerns         |                29 | Included according to protocol  |
| High risk             |                15 | Excluded from primary synthesis |
| **Total**             |           **126** |                                 |

> **Maya:** “So 126 studies were eligible after full-text screening, but only 111 will contribute to the primary synthesis?”

> **Mentor:** “Correct, based on the rule in your protocol.”

```text
126 eligible studies
        ↓
Risk-of-bias assessment
        ↓
15 excluded according to
predefined protocol criteria
        ↓
111 studies available
for primary synthesis
```

Maya documents the studies that were excluded and the reason for their exclusion.

For example:

| Study ID  | Risk-of-Bias Judgment | Decision                        | Reason                                         |
| --------- | --------------------- | ------------------------------- | ---------------------------------------------- |
| Study 014 | High                  | Excluded from primary synthesis | Did not meet predefined risk-of-bias threshold |
| Study 027 | High                  | Excluded from primary synthesis | Did not meet predefined risk-of-bias threshold |
| Study 041 | High                  | Excluded from primary synthesis | Did not meet predefined risk-of-bias threshold |

> **Mentor:** “Notice how you are documenting the decision. You are not simply saying that these studies were ‘bad studies.’ You are reporting the risk-of-bias judgment and explaining how your predefined protocol handled that judgment.”

---

# 16. What If the Protocol Does Not Exclude High-Risk Studies?

Maya asks another question.

> **Maya:** “What if my protocol doesn't say that high-risk studies should be excluded?”

> **Mentor:** “Then you should not create an exclusion rule after seeing the results.”

A study with high risk of bias may remain in the synthesis.

The review may instead:

* Retain the study
* Present its risk-of-bias judgment
* Consider the judgment when interpreting the evidence
* Conduct a sensitivity analysis
* Examine whether conclusions change when studies with higher risk of bias are removed

The important principle is:

> **Risk-of-bias assessment informs how evidence is interpreted and synthesized. It does not automatically determine that a study must be excluded.**

---

# 17. Why Does This Matter for Data Extraction?

Maya now understands why risk-of-bias assessment comes before detailed data extraction in her workflow.

> **Maya:** “Now I see it. If my protocol says some studies won't contribute to the primary synthesis, I don't need to spend time doing the same detailed extraction for those studies.”

> **Mentor:** “Exactly. But remember that the specific handling of those studies must be planned in advance.”

Maya now has a defined group of studies that will proceed to detailed data extraction.

```text
Eligible Studies
       ↓
Risk-of-Bias Assessment
       ↓
Determine Handling According to Protocol
       ↓
Studies for Planned Synthesis
       ↓
Data Extraction
```

---

# ⭐ Revised Important Principle

> **Risk-of-bias assessment can influence how studies are handled in the synthesis, but a high risk-of-bias judgment does not automatically mean that a study must be excluded. If the protocol specifies a risk-of-bias threshold for exclusion from a particular synthesis, apply that rule consistently and document the excluded studies and reasons. If no such exclusion rule was prespecified, do not create one simply because the results are unfavorable.**

---

# 🚀 Maya's Journey Continues

Maya finishes documenting her risk-of-bias decisions.

She now knows:

* Which studies met the eligibility criteria
* The risk-of-bias judgments for those studies
* Which studies will contribute to the planned synthesis
* Which studies were excluded from the planned synthesis, when required by her protocol
* Why each excluded study was excluded

> **Maya:** “Now I know which studies I need to work with for the next stage.”

> **Mentor:** “Exactly. Now you can systematically collect the information needed from those studies.”

Maya opens her data-extraction form.

> **Next step: Data Extraction.**

---

# Assessment

## Multiple-Choice Questions

### 1. What is the primary purpose of risk-of-bias assessment?

A. To determine whether a study has a large sample
B. To evaluate whether methodological problems could systematically influence study findings
C. To calculate the pooled effect size
D. To identify duplicate records

### 2. How is risk of bias different from eligibility?

A. They are exactly the same process
B. Eligibility asks whether a study meets review criteria, while risk of bias assesses potential methodological distortion
C. Risk of bias is completed before searching databases
D. Eligibility is only assessed after meta-analysis

### 3. What should Maya do when selecting a risk-of-bias tool?

A. Select the easiest tool
B. Create a numerical score herself
C. Select an appropriate tool that matches the study design
D. Use the same tool regardless of study design

### 4. What should Maya do when a study does not provide enough information for a risk-of-bias judgment?

A. Automatically classify the study as low risk
B. Automatically exclude the study
C. Guess based on the study's reputation
D. Follow the guidance of the selected risk-of-bias tool

### 5. Does a high risk-of-bias judgment automatically mean that a study must be excluded?

A. Yes, always
B. No
C. Only if the study is randomized
D. Only when the sample size is small

### 6. When may a study with high risk of bias be excluded from a particular synthesis?

A. Whenever Maya personally dislikes the study
B. Whenever the result is unfavorable
C. When a predefined protocol rule specifies such handling
D. Whenever the study has a small sample

### 7. Maya has 126 eligible studies. Her protocol specifies that 15 studies meeting a predefined risk-of-bias threshold will not contribute to the primary synthesis. How many studies remain for the primary synthesis?

A. 101
B. 111
C. 126
D. 141

### 8. Why should Maya document the reason for excluding a study from the primary synthesis?

A. To make the decision transparent and reproducible
B. To increase the pooled effect
C. To avoid reporting risk of bias
D. To replace the eligibility criteria

### 9. What should Maya do if her protocol does not specify exclusion of high-risk studies?

A. Create the exclusion rule after seeing the results
B. Automatically remove all high-risk studies
C. Follow the planned approach and consider other methods such as sensitivity analysis
D. Ignore the risk-of-bias assessment

### 10. Why does the risk-of-bias assessment affect Maya's data-extraction workflow?

A. It can identify studies that, under a prespecified protocol rule, will not contribute to a particular synthesis
B. It eliminates the need for a research question
C. It replaces full-text screening
D. It determines the search terms

### 11. Which statement best describes the relationship between risk of bias and synthesis?

A. Risk of bias has no relevance after screening
B. High risk always prevents synthesis
C. Risk-of-bias judgments can inform how evidence is synthesized and interpreted
D. Risk of bias determines the database search strategy

### 12. What should Maya do if no exclusion rule was prespecified but she notices that high-risk studies produce unfavorable results?

A. Exclude them immediately
B. Create a new exclusion rule and apply it only to those studies
C. Retain the planned approach and consider an appropriately planned sensitivity analysis
D. Change the eligibility criteria

---

# Answer Key

| Question | Answer |
| -------: | :----: |
|        1 |    B   |
|        2 |    B   |
|        3 |    C   |
|        4 |    D   |
|        5 |    B   |
|        6 |    C   |
|        7 |    B   |
|        8 |    A   |
|        9 |    C   |
|       10 |    A   |
|       11 |    C   |
|       12 |    C   |

---

# Repository Structure

```text
step-10-risk-of-bias-assessment/
│
├── README.md
│
├── risk-of-bias/
│   ├── risk-of-bias-tool.md
│   ├── assessment-guide.md
│   ├── assessment-form.xlsx
│   └── assessment-decisions.md
│
├── documentation/
│   ├── reviewer-decisions.md
│   └── disagreement-log.md
│
└── assessment/
    └── assessment.md
```

## 🚀 Maya's Journey Continues

Maya has now **completed the Risk-of-Bias Assessment Stage**.
The next challenge is to conduct the Decide Whether Meta-Analysis Is Appropriate.

She is now ready to move to:

### Next Step

### **[Step 12 — Decide Whether Meta-Analysis Is Appropriate](https://github.com/adnan-mayof/Decide-Whether-Meta-Analysis-Is-Appropriate/blob/main/README.md)**
