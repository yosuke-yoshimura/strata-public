# UI_SPEC — STRATA

This document specifies the structural UI flow of STRATA.  
It describes structure only. No behavior, logic, or explanation is included.

---

## 日本語

### 構造目的

本仕様は、STRATA における  
**対話前の条件配置構造**を示す。

UI は理解を促進しない。  
判断や結論を導かない。

---

### 基本フロー（抽象）
[ Input ]
└─ 問い / 前提 / 制約（未整理）
    ↓
[ Condition Placement ]
└─ 条件を削らずに並置
    ↓
[ Parallel Outputs ]
├─ 出力 A
├─ 出力 B
├─ 出力 C
（同一粒度）
    ↓
[ Drift Visibility ]
└─ ズレ / 張力 / 非整合（位置）
    ↓
[ Transition Options ]
└─ 遷移の可能性（非指示）

---

### UI セクション定義

#### 1. Input
- 自由入力
- 未整理のまま受け取る
- 編集・補正を行わない

#### 2. Condition Placement
- 条件を一覧表示
- 統合・要約を行わない
- 暗黙前提は仮置きとして明示

#### 3. Parallel Outputs
- 複数出力を同時表示
- 抽象度・深さを揃える
- 優劣・正否を示さない

#### 4. Drift Visibility
- 出力間のズレを位置として表示
- 数値化・評価を行わない

#### 5. Transition Options
- 行為の可能性を列挙
- 推奨・指示を行わない

---

### UI が行わないこと

- 解釈の提示
- 説明
- 判断
- 結論表示
- 成果の強調

---

## English

### Structural Purpose

This specification describes  
the **pre-dialogue condition placement structure** of STRATA.

The UI does not promote understanding.  
It does not lead to judgment or conclusions.

---

### Basic Flow (Abstract)
[ Input ]
└─ Question / Premises / Constraints (unstructured)
    ↓
[ Condition Placement ]
└─ Conditions placed side by side
    ↓
[ Parallel Outputs ]
├─ Output A
├─ Output B
├─ Output C
(equal granularity)
    ↓
[ Drift Visibility ]
└─ Misalignment / tension as positions
    ↓
[ Transition Options ]
└─ Possible transitions (non-prescriptive)

---

### UI Section Definitions

#### 1. Input
- Free-form input
- Accepted as-is
- No editing or correction

#### 2. Condition Placement
- Conditions listed as given
- No merging or summarization
- Implicit premises marked as provisional

#### 3. Parallel Outputs
- Multiple outputs displayed simultaneously
- Equal abstraction level
- No prioritization or correctness

#### 4. Drift Visibility
- Misalignments shown as positions
- No quantification or evaluation

#### 5. Transition Options
- Possible actions listed
- No recommendation or instruction

---

### What the UI Does Not Do

- Provide interpretation
- Offer explanations
- Make judgments
- Display conclusions
- Emphasize outcomes

---

End of UI specification.
