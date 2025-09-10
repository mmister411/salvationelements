
# The Semantic Domain Scriptural Catalog

The **Semantic Domain Scriptural Catalog** is a collective of discrete propositional records. Each entry is a self-contained statement tied to scripture, categorized and labeled to clarify its type (such as assertion, alias, inference, function, or corruption). Together, these rows form a comprehensive catalog that organizes biblical content system-by-system and element-by-element, enabling precise, diagnostic, and contextually grounded analysis of scripture across multiple aspects.

Every entry is structured with six parts — **System, Element, Category, Label, Detail, and ScriptureBlock** — ensuring that each statement is precisely defined, contextually anchored, and supported by scripture.

----------

## Categories and Labels

-   **Synonymous Terminology** → AKA  
    Entries capture alternate names and shared designations.
    
-   **Causal Dependency** → Cause, Prerequisite, Enabled By, Enables, Causes  
    Entries identify roots, sources, or enabling factors.
    
-   **Evidentiary Statements** → Accounts For, Affirmation, Negation, Assertion of Proof, Rebuttal to Objection  
    Entries provide scriptural warrants, confirmations, counter-arguments, or explanatory consequences.
    
-   **Implicative Considerations** → Exceptions, Alert, Corruptions, Exemptions, Inference, Limitations  
    Entries record deductions, warnings, distortions, exclusions, and boundaries.

----------

### Rules for a Valid Entry in the Semantic Domain Scriptural Catalog

**Row Structure**  
Every entry must contain exactly six parts:

| System | Element | Category | Label | Detail | ScriptureBlock |
|--------|---------|----------|-------|--------|-----------------|
| Theological Big Picture Item | Specific component of the System Item | Category of Detail | Label of Detail | Detail proposition of category label related to Item Element | multiple scripture references (Book Ch:Vs; Book Ch:Vs; etc) |

----------

**Rules for Detail**

-   Must be a **self-contained** & **discrete proposition**, not a paragraph or summary and can stand alone if read outside the catalog..
    
-   May be a **direct scripture excerpt** or a **concise active-voice assertion** derived from scripture.
    
-   Must **not include headers, sublists, or nested content**.
    
-   Must avoid **parenthetical explanations** (except scripture references).
    
-   Should be **stated positively where possible**; negations only under the correct label (_Negation, Rebuttal to Objection_).
    
----------

**Rules for ScriptureBlock**

-   Every entry requires at least **one supporting scripture reference** in parentheses.
    
-   Prefer multiple references where possible.
    
-   References should be chosen in this order of priority:
    
    1.  Direct statements of the proposition.
        
    2.  Passages that directly imply the assertion.
        
    3.  Passages that chain together to establish the assertion.
        
    4.  References derivable from original language terms.
        
-   ScriptureBlock must be **references only** (e.g., `(John 1:1; Colossians 1:16)`), never commentary or paraphrase.


# Examples

| System | Element | Category | Label | Detail | ScriptureBlock |
| --- | --- | --- | --- | --- | --- |
| Elements of Salvation | Replacement Human Spirit | Synonymous Terminology | AKA | Born-again | (John 3:3; 1 Pet 1:23) |
| Elements of Salvation | Replacement Human Spirit | Causal Dependency | Caused By | Holy Spirit breathes new life into the person | (Job 33:4; John 20:22; Rom 8:11) |
| Elements of Salvation | Judicial Pardon | Synonymous Terminology | AKA | Justification | (Rom 5:1; Rom 4:22--24) |
| Elements of Salvation | Decontaminating the Soul | Causal Dependency | Enables | The word of God sanctifies and cleanses | (John 17:17; Eph 5:26) |
| Scriptural Christology | Uncreated Divinity | Evidentiary Statements | Assertion of Proof | Jesus receives worship from angels and humans without rebuke | (Matt 28:9,17; Heb 1:6; John 20:28) |
| Scriptural Christology | Word of the Lord becomes Lord | Synonymous Terminology | AKA | The Angel of the LORD | (Gen 16:7--13; Exod 3:2--6; Judg 13:3--22) |
| Scriptural Christology | Restorative Seed of Creation | Evidentiary Statements | Assertion of Proof | The Word became flesh and dwelt among us | (John 1:14) |
| Scriptural Christology | Immortal High Priest | Evidentiary Statements | Accounts For | Jesus' priesthood secures ongoing access to God | (Heb 4:16; Heb 10:19--22) |


# Prompt

**Instruction to Generator:**  
Given any amount of starting information, create one or iterate over possible entries.

-   If given **System + Element + Category + Label**, then generate one or more entries of that label.
    
-   If given **System + Element + Category**, then iterate over the applicable labels for that element.
    
-   Output must always follow the six-part row structure.
