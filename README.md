# Lesson Plans: Mock Lessons for the "Teaching Methods for Mathematics Teachers 1" (数学科指導法１) Course

This repository contains the lesson plan overviews and the interactive web simulators for **three** mock lessons designed for the 数学科指導法１ course.

---

## Lesson Plan A: Linear Functions (一次関数)

### Overview
- **Subject:** Mathematics
- **Target Grade:** Junior High School 2nd Year (8th Grade equivalent)
- **Unit:** Chapter 3: Linear Functions
- **Section:** Application of Linear Functions (Regarding relationships as linear functions)

### 1. Unit Concept & Value (単元観)
This unit builds upon the concepts of proportional and inversely proportional relationships learned in the first year. The primary goal is to deepen students' understanding of linear functions, particularly focusing on the rate of change and the characteristics of their graphs.

In the real world, the relationship between two quantities does not always change perfectly uniformly. However, by focusing on a set of observed data and **"regarding it as a linear function" (idealising and abstracting the phenomenon)**, it becomes possible to predict unknown values and analyse overall trends.

Through activities that mathematically model specific phenomena—such as weather data—students will experience the process of problem-solving. This will help them understand how mathematics is utilised in society and realise the practical utility of functional thinking.

### 2. Student Profile (生徒の実態)
A common characteristic among the students in this class is that while they are relatively proficient in mechanical calculation processes (such as solving equations), many struggle to interpret the meaning behind their calculation results or to connect mathematical concepts with real-world phenomena.

### 3. Learning Goals (学習目標)
Based on the Japanese Course of Study (学習指導要領), this lesson focuses on the following evaluation criteria:

* **Knowledge & Skills:** Understand that certain real-world phenomena can be modelled as linear functions, and express these relationships using tables, equations ($y = ax + b$), and graphs.
* **Thinking, Judging, & Expressing:** Regard the relationship between two quantities in a specific phenomenon (e.g., elevation and temperature) as a linear function, predict unknown values based on this assumption, and logically explain the problem-solving method to others.
* **Attitude:** Reflect on the problem-solving process using linear functions, and actively try to apply mathematical thinking to daily life and future learning.

### 4. Instructional Strategies (指導の手立て)
To address the students' current learning profile and achieve the goals above, the lesson will employ the following strategies:

* **Contextualised Problem Solving:** Instead of abstract math problems, the lesson uses highly relatable scenarios such as predicting the temperature at the summit of Mt. Fuji based on the elevation-temperature rule, or analysing the length of a burning incense stick over time. A 3D terrain map of the area around Mt. Fuji is also used to visualise where each observation station sits.
* **ICT Integration (Interactive Web Simulator):** Students use a custom-built, interactive HTML/JS simulator on their tablets. They manipulate sliders for the slope ($a$) and y-intercept ($b$) to manually fit a straight line to scattered experimental data points. This dynamic, hands-on activity bridges the gap between raw data and the formula $y = ax + b$.
* **Collaborative Learning (Pair Work):** The core activity requires students to explain their reasoning to a partner. They must articulate *why* they chose a specific slope and intercept (e.g., "The temperature drops by 0.6°C for every 100 m, so the slope is..."), and *how* they predicted the unknown future value. This ensures they are not just calculating, but truly understanding the mathematical model.

---

## Lesson Plan B: Square Roots (平方根)

### Overview
- **Subject:** Mathematics
- **Target Grade:** Junior High School 3rd Year (9th Grade equivalent)
- **Unit:** Chapter 2: Square Roots
- **Section:** Multiplication of Expressions Containing Radicals (Discovery through Geometric Figures)

### 1. Unit Concept & Value (単元観)
Rather than treating the multiplication of square roots simply as a mechanical algebraic rule to memorise, this unit aims to have students discover the mathematical laws through a geometric perspective, much like ancient Greek mathematicians who equated multiplication with finding the area of a rectangle.

By visualising numerical values as lengths, it provides a strong foundation that prevents common misconceptions in later lessons (such as confusing the rules of multiplication with those of addition). Transitioning from sensory puzzle activities (intuitive geometry) to formal algebraic proofs allows students to experience the beauty of mathematical generalisation and appreciate the logical expansion of the number system.

### 2. Student Profile (生徒の実態)
A common characteristic among the students in this class is that while they are generally enthusiastic and proficient in calculation processes, some struggle to interpret the true meaning behind the operations or to connect new ideas with previously learned concepts (such as the definition of a square root).

Therefore, before introducing operational rules, the lesson incorporates activities that link the abstract concept of square roots to concrete visual representations, such as finding the side length of a square from its known area.

### 3. Learning Goals (学習目標)
Based on the Japanese Course of Study (学習指導要領), this lesson focuses on the following evaluation criteria:

* **Knowledge & Skills:** Understand the rules for multiplying numbers with radical signs and be able to perform these calculations efficiently.
* **Thinking, Judging, & Expressing:** Investigate the mechanism and validity of the multiplication rule ($\sqrt{a} \times \sqrt{b} = \sqrt{ab}$) based on specific numbers, approximations, and geometric area expansion, and logically explain the reasoning to others.
* **Attitude:** Proactively attempt to find the rules for calculating with square roots by utilising figures and previously learned mathematical definitions, appreciating the consistency of mathematical laws.

### 4. Instructional Strategies (指導の手立て)
To address the students' current learning profile and achieve the goals above, the lesson will employ the following strategies:

* **Geometric Approach for Conceptual Understanding:** Instead of jumping straight into algebraic formulas, the lesson introduces the historical view of "multiplication = area of a rectangle." Students use a "rectangle expansion puzzle" to visually deduce that if a rectangle with an unknown area $S$ is scaled by $\sqrt{2}$ vertically and $\sqrt{3}$ horizontally, the new area becomes $6$. Since the area is multiplied by $S$, they derive $S^2 = 6$, leading to the natural conclusion that the original area $S$ is $\sqrt{6}$.
* **ICT Integration (Interactive Web Simulator):** Students use a custom-built, interactive HTML/JS simulator distributed via LoiLoNote on their tablets. By manipulating independent sliders for the vertical and horizontal scale factors, they can visually and dynamically experiment with how the area changes. The simulator provides real-time feedback, highlighting when the resulting area becomes a perfect integer, bridging the gap between raw experimental data and the mathematical formula. After reaching area 6, an "exploration mode" unlocks where students can search for other integer areas.
* **Collaborative Learning and Rigorous Proof:** Students engage in pair work to articulate *why* the area changes using the concept of scaling factors. Following the visual and empirical conviction, the lesson guides them through a formal algebraic proof using the definition of square roots. Crucially, students explicitly verify the positive and negative signs (since length and area must strictly be positive) to ensure the logical completeness of their proof.

---

## Lesson Plan C: Spatial Figures (空間図形)

### Overview
- **Subject:** Mathematics
- **Target Grade:** Junior High School 1st Year (7th Grade equivalent)
- **Unit:** Chapter 6: Spatial Figures
- **Section:** How to View and Investigate Solids (The condition for a plane to be uniquely determined)

### 1. Unit Concept & Value (単元観)
Rather than presenting the fact "a plane is determined by three points not on the same straight line" as a rule to be memorised, this unit lets students **discover** the condition through a familiar, concrete question: *"From where was this photograph of the Leaning Tower of Pisa taken?"*

By abstracting the tilted tower as a **single straight line** and the map/ground as a **plane**, students investigate why one viewpoint fixes exactly one picture. Moving from an intuitive, photographic problem to a general geometric condition lets them experience how a real-world situation is idealised into mathematics, and appreciate why the condition (not on one line, three points) is *necessary* — not just true.

### 2. Student Profile (生徒の実態)
A common characteristic among the students in this class is that many find it difficult to reason about three-dimensional space from two-dimensional representations, and tend to accept conditions such as "three points determine a plane" without grasping *why* fewer points, or collinear points, are insufficient.

Therefore, before stating the condition, the lesson links the abstract idea to concrete, manipulable experiences — a tilted pencil as a line, a fingertip as a point, and a plastic board as a plane — so that students feel the "wobble" that remains until the plane is finally fixed.

### 3. Learning Goals (学習目標)
Based on the Japanese Course of Study (学習指導要領), this lesson focuses on the following evaluation criteria:

* **Knowledge & Skills:** Understand positional relationships between lines and planes in space, and that a plane is determined by "three points not on the same straight line" (equivalently, by a line and a point not on it).
* **Thinking, Judging, & Expressing:** Regard the tower as a line and the camera's viewpoint as a point; investigate why the shooting position is fixed to just one; and logically explain the condition to others using the ideas of a *rotation axis*, *turning*, and *being fixed*.
* **Attitude:** Proactively relate the condition to everyday objects and solids (camera tripods, the vertices of a rectangular solid), appreciating the consistency and usefulness of the mathematical condition.

### 4. Instructional Strategies (指導の手立て)
To address the students' current learning profile and achieve the goals above, the lesson will employ the following strategies:

* **Contextualised Problem Solving:** The lesson opens with the textbook's activity "Where was it taken? (どこから撮ったのかな？)", matching three photographs (ア・イ・ウ) of the leaning tower to three positions (A・B・C) on the map of the Piazza dei Miracoli. Because the tower leans in a fixed direction, its apparent tilt (left / straight / right) depends on where the photographer stands — a vivid entry point into "your viewpoint determines what you see."
* **ICT Integration (Interactive Web Simulator):** Students use a custom-built HTML / Three.js simulator on their tablets. Selecting one of the three sample photos **automatically moves the camera to that photo's shooting position**, so students immediately see the view from there; sliders for position, height, direction, and elevation angle then let them explore how the tower's appearance changes as they "walk around" it (a full 360° orbit animation is also provided), with a top-view map showing the candidate positions. A second tab lets them test 1 / 2 / 3 (collinear) / 3 (non-collinear) points and discover that **only three points not on one line** stop the plane from rotating about an axis.
* **Collaborative Learning with Concrete Manipulatives:** After individual exploration, students explain to a partner *why* the viewpoint is unique ("the tower (line) and where I stand (point) are both fixed, so the view is one"), then confirm the general condition with fingertips (points) and a plastic sheet (plane), feeling how the board keeps turning about an axis until a third, non-collinear point fixes it.

---

## Files / コードの説明

| File | Role | Notes |
|---|---|---|
| [`lesson.html`](./lesson.html) | **一次関数 シミュレーター** (中2) | 標高と気温・おもちゃの車・線香の3シナリオを内側タブで切り替え。スライダーで傾き $a$ と切片 $b$ を動かして観測点に直線を合わせ、未知の値を予測する。Chart.js を使用。 |
| [`sqrt.html`](./sqrt.html) | **平方根 シミュレーター** (中3) | $\sqrt{2}$ 倍・$\sqrt{3}$ 倍した長方形の面積を SVG で可視化。スライダー（縦 $\sqrt{a}$ 倍 ／ 横 $\sqrt{b}$ 倍）で動かし、面積がピッタリ 6 になるとアンロックボタンが現れ、押すと「発展版（探索モード）」に遷移して別の整数面積を探せる。 |
| [`index.html`](./index.html) | **富士山周辺 地形3Dマップ** (中2 一次関数 補助) | Plotly で描いた立体の地形図。マウス／指でぐるぐる回して、観測所の標高と位置の関係を立体的に確認できる。標高と気温の話題の導入用。 |
| [`index2.html`](./index2.html) | 地形3Dマップ（ヘッダー無し版） | `index.html` から授業タイトル等のヘッダーを取り除いた版。プレーンに3Dマップだけ見せたい時に。 |
| [`spatial/`](./spatial/) | **空間図形 シミュレーター** (中1) | ピサの斜塔（＝斜めに立てた1本の直線）を撮った3枚の写真（ア・イ・ウ）を選ぶと、その撮影位置へカメラが自動で移動。位置・高さ・向き・仰角のスライダーで塔のまわりを1周でき、立つ位置で見え方が変わることを体感。第2タブでは点1／2／3（一直線上）／3（一直線上にない）を試し、平面が1つに決まる条件を発見する。Three.js を使用。 |
| [`qr.html`](./qr.html) | **QRコード掲示用ページ** | 上記3ページ（`lesson.html` ／ `sqrt.html` ／ `index.html`）への QRコードを並べて表示。`window.location` を基に絶対URLを生成するので、GitHub Pages・学内サーバー・ローカルファイル、どこに置いてもそのホストの該当ページを正しく指す。`@media print` 対応で印刷配布も可。 |

### QR コードの使い方

1. このリポジトリを GitHub Pages 等で公開（または同じフォルダごとサーバー／LoiLoNote 等で配布）。
2. 教員機で [`qr.html`](./qr.html) を開き、プロジェクターで投影。
3. 生徒は使う単元の QR コード（青：一次関数 ／ 緑：平方根 ／ オレンジ：地形3D）をタブレットで読み取り、直接シミュレーターを開く。

> 公開URL例（GitHub Pages 有効時）: `https://momohayashi304.github.io/math-pedagogy-1/qr.html`
