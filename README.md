# Theory of Computer Science (TCS) – JFLAP Self-Learning Assignment

**Student Name:** Ketaki Patil  
**Roll No:** 70  
**Class / Division:** D12A  
**Batch:** C  
**Subject:** Theory of Computer Science (TCS) (26CMPC51)  
**Department:** Department of Computer Engineering  
**Institution:** Vivekanand Education Society's Institute of Technology (VESIT)  
**Faculty In-Charge:** Mr. Sanjay Mirchandani  
**Academic Submission Date:** 14 November 2026 (14-11-2026)

\---

## Executive Summary

This repository contains the complete practical portfolio for the **30-Hour JFLAP Self-Learning Assignment** in Theory of Computer Science. All 15 practical modules have been designed, simulated, and formally verified across the Chomsky Hierarchy—spanning **Finite Automata, Transducers (Mealy \& Moore), Context-Free Grammars \& Pushdown Automata, Parsing Algorithms (CYK \& LL(1)), and Single/Multi-Tape Turing Machines**.

Every single `.jff` file strictly adheres to standard JFLAP XML specifications, and all files follow the institutional naming convention:
`Roll\_No.\_Name\_Topic\_DOP` $\\implies$ `70\_Ketaki\_Patil\_<Topic>\_14-11-2026.jff`

\---

## Master Practical Index \& Verification Tracker

|No.|Directory|Topic / Concept Covered|Primary JFLAP File(s)|Machine / Formal Type|Verification Status|
|:-:|-|-|-|:-:|:-:|
|**01**|[`01\_Deterministic\_Finite\_Automata`](./01_Deterministic_Finite_Automata/)|Deterministic Finite Automata (Binary Divisible by 3)|[`70\_Ketaki\_Patil\_DFA\_14-11-2026.jff`](./01_Deterministic_Finite_Automata/70_Ketaki_Patil_DFA_14-11-2026.jff)|DFA|**Validated \& Verified**|
|**02**|[`02\_Nondeterministic\_Finite\_Automata`](./02_Nondeterministic_Finite_Automata/)|Non-Deterministic Finite Automata (Contains `101`)|[`70\_Ketaki\_Patil\_NFA\_14-11-2026.jff`](./02_Nondeterministic_Finite_Automata/70_Ketaki_Patil_NFA_14-11-2026.jff)|NFA|**Validated \& Verified**|
|**03**|[`03\_NFA\_DFA\_Conversion`](./03_NFA_DFA_Conversion/)|NFA to DFA Subset Construction (Ends in `ab`)|[`70\_Ketaki\_Patil\_NFA\_Source\_14-11-2026.jff`](./03_NFA_DFA_Conversion/70_Ketaki_Patil_NFA_Source_14-11-2026.jff), [`70\_Ketaki\_Patil\_DFA\_Converted\_14-11-2026.jff`](./03_NFA_DFA_Conversion/70_Ketaki_Patil_DFA_Converted_14-11-2026.jff)|FA Conversion|**Validated \& Verified**|
|**04**|[`04\_DFA\_State\_Minimization`](./04_DFA_State_Minimization/)|DFA Minimization using Equivalence Partitioning (Ends `01`)|[`70\_Ketaki\_Patil\_DFA\_Original\_14-11-2026.jff`](./04_DFA_State_Minimization/70_Ketaki_Patil_DFA_Original_14-11-2026.jff), [`70\_Ketaki\_Patil\_DFA\_Minimized\_14-11-2026.jff`](./04_DFA_State_Minimization/70_Ketaki_Patil_DFA_Minimized_14-11-2026.jff)|FA Minimization|**Validated \& Verified**|
|**05**|[`05\_Regular\_Expression\_to\_DFA`](./05_Regular_Expression_to_DFA/)|Regular Expression to DFA Conversion (`(a+b)\*abb`)|[`70\_Ketaki\_Patil\_RE\_14-11-2026.jff`](./05_Regular_Expression_to_DFA/70_Ketaki_Patil_RE_14-11-2026.jff), [`70\_Ketaki\_Patil\_DFA\_from\_RE\_14-11-2026.jff`](./05_Regular_Expression_to_DFA/70_Ketaki_Patil_DFA_from_RE_14-11-2026.jff)|RE / FA|**Validated \& Verified**|
|**06**|[`06\_DFA\_to\_Regular\_Grammar`](./06_DFA_to_Regular_Grammar/)|DFA to Right-Linear Grammar Conversion (Starts 0, Ends 1)|[`70\_Ketaki\_Patil\_DFA\_Source\_14-11-2026.jff`](./06_DFA_to_Regular_Grammar/70_Ketaki_Patil_DFA_Source_14-11-2026.jff), [`70\_Ketaki\_Patil\_Grammar\_Converted\_14-11-2026.jff`](./06_DFA_to_Regular_Grammar/70_Ketaki_Patil_Grammar_Converted_14-11-2026.jff)|FA $\\to$ Grammar|**Validated \& Verified**|
|**07**|[`07\_Mealy\_Transducer`](./07_Mealy_Transducer/)|Mealy Machine (Sequence Detector for `101` with Overlap)|[`70\_Ketaki\_Patil\_Mealy\_14-11-2026.jff`](./07_Mealy_Transducer/70_Ketaki_Patil_Mealy_14-11-2026.jff)|Mealy Transducer|**Validated \& Verified**|
|**08**|[`08\_Moore\_Transducer`](./08_Moore_Transducer/)|Moore Machine (Binary Stream Residue Modulo 3 Evaluator)|[`70\_Ketaki\_Patil\_Moore\_14-11-2026.jff`](./08_Moore_Transducer/70_Ketaki_Patil_Moore_14-11-2026.jff)|Moore Transducer|**Validated \& Verified**|
|**09**|[`09\_Context\_Free\_Grammar`](./09_Context_Free_Grammar/)|Context-Free Grammar ($L = { a^n b^{2n} \\mid n \\ge 1 }$)|[`70\_Ketaki\_Patil\_CFG\_14-11-2026.jff`](./09_Context_Free_Grammar/70_Ketaki_Patil_CFG_14-11-2026.jff)|Grammar (Type 2)|**Validated \& Verified**|
|**10**|[`10\_Pushdown\_Automaton`](./10_Pushdown_Automaton/)|Pushdown Automata ($L = { w c w^R \\mid w \\in {a,b}^\* }$)|[`70\_Ketaki\_Patil\_PDA\_14-11-2026.jff`](./10_Pushdown_Automaton/70_Ketaki_Patil_PDA_14-11-2026.jff)|DPDA|**Validated \& Verified**|
|**11**|[`11\_Chomsky\_Normal\_Form`](./11_Chomsky_Normal_Form/)|Chomsky Normal Form Conversion ($a^n b^n$)|[`70\_Ketaki\_Patil\_CFG\_Original\_14-11-2026.jff`](./11_Chomsky_Normal_Form/70_Ketaki_Patil_CFG_Original_14-11-2026.jff), [`70\_Ketaki\_Patil\_CNF\_Converted\_14-11-2026.jff`](./11_Chomsky_Normal_Form/70_Ketaki_Patil_CNF_Converted_14-11-2026.jff)|CNF Normalization|**Validated \& Verified**|
|**12**|[`12\_CYK\_Algorithm`](./12_CYK_Algorithm/)|Cocke-Younger-Kasami (CYK) Dynamic Programming Parsing|[`70\_Ketaki\_Patil\_CYK\_14-11-2026.jff`](./12_CYK_Algorithm/70_Ketaki_Patil_CYK_14-11-2026.jff)|CYK Parser|**Validated \& Verified**|
|**13**|[`13\_LL1\_Parser`](./13_LL1_Parser/)|LL(1) Predictive Parsing for Arithmetic Expressions|[`70\_Ketaki\_Patil\_LL1\_Grammar\_14-11-2026.jff`](./13_LL1_Parser/70_Ketaki_Patil_LL1_Grammar_14-11-2026.jff)|LL(1) Parser|**Validated \& Verified**|
|**14**|[`14\_Single\_Tape\_Turing\_Machine`](./14_Single_Tape_Turing_Machine/)|Single-Tape Turing Machine (Binary Incrementer $w + 1$)|[`70\_Ketaki\_Patil\_Single\_Tape\_TM\_14-11-2026.jff`](./14_Single_Tape_Turing_Machine/70_Ketaki_Patil_Single_Tape_TM_14-11-2026.jff)|Turing Machine|**Validated \& Verified**|
|**15**|[`15\_Multi\_Tape\_Turing\_Machine`](./15_Multi_Tape_Turing_Machine/)|2-Tape Turing Machine (Binary String Duplication $w \\to ww$)|[`70\_Ketaki\_Patil\_Multi\_Tape\_TM\_14-11-2026.jff`](./15_Multi_Tape_Turing_Machine/70_Ketaki_Patil_Multi_Tape_TM_14-11-2026.jff)|Multi-Tape TM|**Validated \& Verified**|

\---

## Standard Repository Architecture

Each practical directory follows a consistent academic standard:

1. **Native JFLAP File(s) (`.jff`):** Validated XML models loadable directly into JFLAP with zero warnings or parsing exceptions.
2. **Comprehensive Report (`README.md`):**

   * Precise Problem Statement \& Linguistic Characterization.
   * Formal Mathematical Tuple Specifications (5-tuple, 6-tuple, or 7-tuple).
   * Operational Logic, Stack Behavior, and Transition Tables.
   * Instantaneous Descriptions (IDs) and step-by-step trace deductions.
   * Comprehensive Test Suite with Accepted vs Rejected classifications.
   * GUI execution instructions for JFLAP.
3. **Formal Test Log (`validation\_log.md`):** Complete test matrix detailing input vectors, expected vs observed outputs, and pass/fail indicators.

\---

## How to Run and Test in JFLAP

### Prerequisites:

* Java Runtime Environment (JRE 8 or above).
* Official JFLAP `.jar` distribution (available from [jflap.org](https://www.jflap.org/)).

### Execution Steps:

1. Launch JFLAP:

```bash
   java -jar JFLAP.jar
   ```

2. In JFLAP, click **File $\\to$ Open** and choose any `.jff` file from this repository.
3. To test multiple strings simultaneously:

   * Click **Input $\\to$ Multiple Run**.
   * Input test vectors as documented in the practical's `README.md` and click **Run Inputs**.
4. To observe step-by-step state animations:

   * Click **Input $\\to$ Step with State...** and advance through input transitions.

---

## 👨‍🎓 Author Information
- **Student Name:** Ketaki Patil
- **Roll Number:** 70
- **Division / Batch:** D12A / C
- **Department:** Computer Engineering, Vivekanand Education Society's Institute of Technology (VESIT)
- **Course:** Theory of Computer Science (26CMPC51)
- **Academic Year:** 2026 – 2027
