⚔️ Code & Conquer: Java Tic-Tac-Toe
Round 2 Technical Event, CodVed - 2026 · Gita Samhita - 2026
<p align="center">
<img src="https://img.shields.io/badge/Event-Gita_Samhita_2026-blue?style=for-the-badge&logo=eventbrite&logoColor=white" alt="Gita Samhita 2026" />
<img src="https://img.shields.io/badge/Competition-CodeVed-7928CA?style=for-the-badge&logo=codeforces&logoColor=white" alt="CodeVed" />
<img src="https://img.shields.io/badge/Round-Round_2_(Knockout)-e11d48?style=for-the-badge" alt="Round 2" />
<img src="https://img.shields.io/badge/College-GSSS_SSFGC,_Mysuru-0284c7?style=for-the-badge" alt="GSSS SSFGC Mysuru" />
</p>
<p align="center">
<img src="https://img.shields.io/badge/Language-HTML5_·_CSS3_·_JavaScript-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/Snippet_Domain-Java_21_Output_Prediction-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Architecture-Single_File_Zero_Dependencies-10b981?style=flat-square" alt="Zero Dependencies" />
<img src="https://img.shields.io/badge/AI_Engine-Heuristic_Tactical_Bot-6366f1?style=flat-square" alt="AI Engine" />
<img src="https://img.shields.io/badge/Developer-Nisarga_NS-0ea5e9?style=flat-square&logo=github&logoColor=white" alt="Developer" />
</p>
📌 Executive Summary
Code & Conquer: Java Tic-Tac-Toe is an interactive, browser-based technical gaming round created specifically for CodeVed, the flagship technical event of Gita Samhita - 2026 hosted at GSSS Simha Subbamahalakshmi First Grade College (GSSS SSFGC), Mysuru.
In Round 2, participants face a duel of logic and algorithmic speed: to place their X marker on any cell of a 
 grid, they must predict the console output of tricky, competitive 6-to-8 line Java snippets within a 45-second countdown. A correct output locks the grid coordinate; an incorrect answer or timeout immediately surrenders the entire game to the computer AI opponent.
code
Code
1       2       3
   ┌───────┬───────┬───────┐
 1 │   X   │       │   O   │   ◄── Java Output Challenge
   ├───────┼───────┼───────┤       Predict tricky execution traces
 2 │       │   X   │       │       under a 45s countdown timer!
   ├───────┼───────┼───────┤
 3 │   O   │       │   X   │   ◄── 3 in-a-row = ROUND WIN
   └───────┴───────┴───────┘
🏛️ Event & Academic Attribution
Attribute	Details
Institution	GSSS Simha Subbamahalakshmi First Grade College (GSSS SSFGC), Mysuru, Karnataka
Fest / Festivity	Gita Samhita - 2026 (Annual Inter-Collegiate Fest)
Technical Event	CodeVed
Event Stage	Round 2: Technical Output Prediction & Board Conquest
Lead Developer	Nisarga NS
Academic Term	Developed during 2nd Year, 4th Semester
Contact Email	nisargans011@gmail.com
🎮 Game Rules & Round 2 Protocol
Cell Targeting: Click any unoccupied cell (
 to 
) on the 
 grid.
Java Snippet Challenge: A modal dialog locks the screen displaying a randomized Java code snippet with syntax formatting and line numbers.
Timer Discipline: A 45-second timer begins ticking immediately.
Console Output Prediction:
The participant types the expected output into the console input field.
For multi-line or multi-value print statements, values are compared normalizing spaces and case.
Quick submit via button or Ctrl + Enter shortcut.
Resolution Rules:
Correct Answer: The participant claims the cell with X, marks increment by 
, and the Computer AI calculates its countermove.
Incorrect Answer or Timeout: Instant Knockout Rule. The computer claims the game, preventing arbitrary guessing.
Marks Criteria:

Every successfully conquered cell awards 1 Mark, rewarding participants who demonstrate deep Java runtime mastery.
🧠 Question Bank & Conceptual Syllabus
The challenge bank contains rigorous 6–8 line snippets focusing on common technical interview traps and JVM edge cases:
code
Code
┌──────────────────────────────────────┬────────────────────────────────────────────────────────┐
│ Core Domain                          │ Specific Java Language Mechanics                       │
├──────────────────────────────────────┼────────────────────────────────────────────────────────┤
│ Iterations & Loops                   │ for, while, do-while, multi-variable stepping          │
│ Loop Control Signals                 │ break, continue, labeled blocks                        │
│ Operator Precedence & Evaluation     │ Pre-increment (++x) vs Post-increment (x++) combos     │
│ String & Arithmetic Concat           │ Operator overloading: "Java" + a + b vs a + b + "Java" │
│ Bitwise & Shift Operators            │ >>, <<, &, |, ^ on signed integers                     │
│ Short-Circuit Logic                  │ Logical AND (&&) vs Logical OR (||) evaluation skipping│
│ Primitive Type Promotion             │ Integer division truncating vs double casting          │
│ Character Arithmetic                 │ 'A' + 2 integer widening vs (char) casting             │
│ Array Traversal                      │ Step-stride loops, out-of-boundary prevention          │
│ State Accumulation                   │ Factorial while-loops, compound assignment (%=, *=)   │
└──────────────────────────────────────┴────────────────────────────────────────────────────────┘
⚡ Technical Architecture & Design Decisions
1. Pure Web Standards (Single-File Distribution)
Built with zero external dependencies or build steps required. The entire application runs natively in any standard web browser using semantic HTML5, pure CSS3, and vanilla ES6+ JavaScript.
2. Heuristic Computer AI Engine
The AI opponent implements a priority-based tactical decision tree:
Immediate Win Detection: Scans all 8 winning lines to identify if O can win this turn.
Threat Block: Scans all 8 lines to prevent X from completing a winning line.
Strategic Center Take: Claims Cell 5 (index 4) if available.
Corner Optimization: Selects from remaining corners (0, 2, 6, 8).
Random Open Edge: Claims available edge cells if no higher priority applies.
3. Native <dialog> Modal & Focus Trap
Uses the HTML5 <dialog> API with showModal() to provide built-in backdrops, screen reader accessibility, and keyboard focus containment (Ctrl+Enter submit, auto-focus input).
4. Mathematical Grid-Paper Retro Aesthetic
Styled using dynamic CSS variables with a crisp grid-paper background, high-contrast monospace code typography (Consolas, Courier New), and neubrutalist card borders.
📂 File Directory Structure
code
Code
├── README.md               # Comprehensive project documentation
├── code/                   # Production-ready code bundle
│   ├── index.html          # Clean semantic HTML interface
│   ├── style.css           # Grid paper styling & responsive theme
│   └── script.js           # 3x3 game state, AI, timer & question bank
└── src/                    # Consolidated Vite/React dev engine
    ├── App.tsx             # Complete single-component interactive UI
    ├── index.css           # Global typography & layout rules
    └── main.tsx            # React root mount
🚀 How to Run the Project
Option A: Direct Browser Execution (Zero Setup)
Navigate to the /code/ folder (or copy the single-file HTML).
Double-click index.html (or right-click 
 Open with Chrome / Firefox / Edge / Safari).
The game launches immediately with complete functionality offline.
Option B: Local Node / Vite Development Server
code
Bash
# 1. Install dependencies
npm install

# 2. Start local development server
npm run dev

# 3. Build for production distribution
npm run build
⌨️ Accessibility & Keyboard Shortcuts
Ctrl + Enter (or Cmd + Enter on macOS): Instant answer submission from inside the code output textarea.
Enter inside Participant Name field: Automatically starts the game.
Tab / Shift + Tab: Natural focus traversal across grid buttons, controls, and dialog elements.
prefers-reduced-motion: Disables non-essential pop animations for users with vestibular sensitivity.
👨‍💻 Author & Credits
Developer: Nisarga NS
Email: nisargans011@gmail.com
Institution: GSSS Simha Subbamahalakshmi First Grade College (GSSS SSFGC)
KRS Road, Mysuru, Karnataka 570016
Occasion: Gita Samhita - 2026 · CodeVed (Round 2)
Academic Milestone: Created during B.C.A., 2nd Year (4th Semester)
<p align="center">
<i>Developed with precision for GSSS SSFGC CodeVed 2026. Empowering students to master core Java fundamentals through competitive gamification.</i>
</p>
