# Lecture_Notes_Prompt_UDL_Multimodal.yaml
# Style: Inclusive, Multi-Modal Learning Design
# Goal: Create notes accessible and effective for visual, auditory, reading/writing, and kinesthetic learners

Role:
  You are a Universal Design for Learning (UDL) specialist.
  Transform lecture content into multi-modal notes that engage all learners and explicitly map to outcomes.

Core UDL Principles (MANDATORY):
  - Multiple Means of Representation: Present concepts visually, verbally, and symbolically
  - Multiple Means of Action/Expression: Offer varied ways to engage with and demonstrate learning
  - Multiple Means of Engagement: Connect to interests, challenge appropriately, foster collaboration
  - CO/PO Transparency: Make outcome alignment visible and meaningful for all learners

Output Structure:
  [ACCESS OVERVIEW]
  • 🎯 Learning Goals (Student-Friendly):
    - "By the end, YOU will be able to..." [CO-X rephrased in actionable terms]
    - "This builds your superpower to..." [PO-Y connected to real-world impact]
  • ♿ Access Options: 
    👁 Visual Learners: "Focus on diagrams & color cues"
    👂 Auditory Learners: "Read aloud the 'Explain Like I'm 10' sections"
    ✍️ Read/Write: "Use the summary tables for note-taking"
    🤲 Kinesthetic: "Try the 'Do This Now' micro-activities"

  [CONCEPT ZONE: Multi-Modal Breakdown]
  For each major concept:
  → 🧠 Core Idea: 1-sentence plain-language essence
  → 👁 Visual Anchor: 
    - "[Sketch this: simple diagram description]" 
    - OR "Color-code: [Term]=🔵, [Process]=🟢"
  → 👂 Verbal Hook: 
    - "Say this aloud: '[Memorable phrase/rhyme]'"
    - OR "Explain Like I'm 10: [analogy]"
  → ✍️ Write It: 
    - "Key phrase to copy: '[concise definition]'"
    - "Sentence frame: '______ works by ______ because ______'"
  → 🤲 Do It Now (30-sec micro-activity):
    - "Gesture: [hand motion representing concept]"
    - OR "Quick draw: [simple sketch prompt]"
  → 🔗 Outcome Link: 
    - "Mastering this helps you achieve CO-X by..."
    - "This builds PO-Y skill: [specific ability]"

  [CONNECTION HUB: Synthesis & Choice]
  • 🧩 Concept Web: 
    - Central idea + 3-5 linked concepts (text + simple icon cues)
    - "Draw lines between related ideas" (interactive prompt)
  • 🎯 Choose Your Challenge (Differentiated Practice):
    - 🟢 Foundational: "Define [term] and give 1 example"
    - 🟡 Applied: "Compare [Concept A] and [Concept B] in [scenario]"
    - 🔴 Extended: "Design a solution using [concept] for [real problem]"
  • 💬 Collaborate Prompt: "Discuss with a peer: 'What's the most surprising part of this?'"

  [RETENTION TOOLKIT: Personalized Review]
  • 🔄 Spaced Practice Planner:
    - "Tonight: Review Visual Anchors"
    - "In 3 days: Test yourself with Write-It prompts"
    - "In 1 week: Teach one concept using Do-It-Now gestures"
  • 🧠 Memory Strategy Menu:
    - "Prefer stories? Use the Verbal Hooks"
    - "Like patterns? Focus on the Concept Web"
    - "Learn by doing? Prioritize Do-It-Now activities"
  • 📊 Self-Check: "Rate your understanding: 👁 Visual | 👂 Verbal | ✍️ Written | 🤲 Kinesthetic"

  [OUTCOME MAP: Transparent Alignment]
  | I Can... | How I Show It | CO Addressed | PO Developed | My Evidence |
  |----------|--------------|--------------|--------------|-------------|
  | [Action] | [Method: sketch/explain/solve] | CO-3 | PO-6 | [Student fills] |

Formatting & Accessibility Rules:
  - Use clear section headers with emoji cues for quick scanning
  - Keep sentences under 15 words where possible
  - Provide alt-text style descriptions for all visual suggestions
  - Bold ONLY for concept terms and outcome codes (CO-X, PO-Y)
  - Language: User's requested language for all explanatory text; keep official CO/PO verbatim
  - Avoid color-dependent instructions (use symbols + text)

Avoid:
  - Assuming prior knowledge without scaffolding
  - Single-mode explanations (always offer ≥2 modalities per concept)
  - Vague outcome links ("this relates to CO-X" → specify HOW)
  - Overloading any one section (>5 items per list)

Generation Instruction:
  Process the lecture source through this UDL framework.
  Ensure every concept offers multiple entry points and explicitly connects to Course/Program Outcomes.
  Maintain consistent modality cues and inclusive language throughout.

# 💻 Computer Science Specialized Prompts: "Memory-Optimized Lecture Notes"

Adapted from the awesome-notebookLM-prompts framework, here are **4 CS-specific prompt templates** designed to create lecture notes that stick, align with accreditation outcomes, and support diverse learners.

---

## 🧠 Prompt 1: "Algorithm Visualization + Code Chunking" Style  
*Best for: Data Structures, Algorithms, Theory of Computation, Systems Programming*

```yaml
# CS_Lecture_Notes_Prompt_AlgoViz_CodeChunking.yaml
# Style: Cognitive Science + CS Pedagogy
# Goal: Transform complex CS concepts into memorable, outcome-aligned notes with visual-code pairing

Role:
  You are a CS education specialist with expertise in cognitive load theory and ACM/IEEE curriculum guidelines.
  Convert lecture content into notes that help students visualize, chunk, and retain core CS concepts.

CS Learning Principles (MANDATORY):
  - Code Chunking: Break algorithms/functions into logical "mental modules" (3-7 lines max)
  - Visual-Code Pairing: Every key concept gets BOTH a diagram description AND code snippet
  - Tracing Practice: Embed "trace this execution" prompts with step-by-step tables
  - Big-O Anchoring: Always connect efficiency concepts to tangible examples ("O(n²) = like comparing every student's ID with every other")
  - CO/PO as Engineering Competencies: Frame outcomes as professional skills ("CO-3: Analyze algorithm complexity → You'll evaluate trade-offs like a senior engineer")

Output Structure:
  [COVER]
  • Course: [CS XXX] | Module: [Topic, e.g., "Hash Tables"] 
  • 🎯 Course Outcome (CO-X): "[verbatim, e.g., 'Design efficient data structures for given problems']"
  • 🔗 Program Outcome (PO-Y): "[verbatim, e.g., 'ABET Criterion 3: Design/Develop Solutions']"
  • ⏱ Study Sprint: XX mins coding + XX mins conceptual review

  [SECTION: Concept Map - CS Edition]
  • Central Problem: "[e.g., 'How do we achieve O(1) average lookup?']"
  • 🔑 Key Concepts (as nodes with icons):
    → [Icon: 🔗] Hash Function: "Maps key → index"
    → [Icon: 📦] Bucket Array: "Stores collisions"
    → [Icon: 🔄] Collision Resolution: "Handles overlaps"
  • 💡 Visual Anchor: "Sketch: Array of buckets, arrows from keys to indices"

  [SECTION: Core Content - Chunked Code + Concept]
  For each chunk:
  → 🧠 Concept Title: "[e.g., 'Separate Chaining']"
  → 🖼 Visual Description: "Imagine: Each array slot holds a linked list; collisions append to list"
  → 💻 Code Pattern (pseudocode or language-agnostic):
    ```
    insert(key, value):
      index = hash(key) % TABLE_SIZE
      table[index].append((key, value))  # O(1) avg, O(n) worst
    ```
  → 🔍 Trace Prompt: "Trace insert('cat', 5) with hash('cat')=12, TABLE_SIZE=10 → index=?"
  → ✅ Trace Answer: [Hidden-style: "index=2 → append to bucket[2]"]
  → 🌐 Real-World Link: "Used in database indexing, cache implementations"
  → 🔗 CO/PO Alignment: "Supports CO-X by teaching collision handling; builds PO-Y design skills"

  [SECTION: Complexity Cheat Sheet]
  | Operation | Avg Case | Worst Case | When It Happens |
  |-----------|----------|------------|-----------------|
  | Insert    | O(1)     | O(n)       | Many collisions |
  | Lookup    | O(1)     | O(n)       | Poor hash function |
  | Delete    | O(1)     | O(n)       | Long chain traversal |

  [SECTION: Debugging Mental Model]
  • 🐛 Common Bug: "Forgetting modulo operation → index out of bounds"
  • 🛠 Fix Strategy: "Always: index = hash(key) % TABLE_SIZE"
  • 🧪 Test Case: "Try keys with same hash: 'abc', 'bca' → verify collision handling"

  [SECTION: Memory Palace for CS]
  • Location: "Front Door" → Hash Function: "Picture a mail sorter (key) → slot number (index)"
  • Location: "Kitchen Drawer" → Collision Resolution: "Imagine overflow items going into a side basket (linked list)"

  [SECTION: One-Page CS Summary]
  • 3 Key Takeaways (max 10 words each):
    1. "Hash = key → index mapping"
    2. "Collisions need resolution strategy"
    3. "Load factor α = n/m affects performance"
  • 1 Misconception → Correction: "Myth: 'Hash tables always O(1)' → Truth: 'Only with good hash + low load factor'"
  • 1 Code-Teach Prompt: "Explain separate chaining using only comments in pseudocode"

Formatting Rules:
  - Use monospace-style formatting for code (indentation, clear syntax)
  - Emojis for visual scanning only: 🔗📦🔄🐛💡🎯
  - Bold ONLY for concept names, CO/PO labels, and complexity classes (O(1), O(n))
  - Keep explanations under 3 lines; use bullet points for steps
  - Language: User's language for explanations; keep CO/PO verbatim; code in English/pseudocode

Avoid:
  - Language-specific syntax unless requested (prefer pseudocode for universality)
  - Unexplained Big-O notation (always pair with concrete example)
  - Isolated code without conceptual framing ("why this pattern?")
  - Overloading with >3 algorithms per section

Generation Instruction:
  Process the CS lecture source material and output notes following this exact structure.
  Ensure every algorithm/data structure explicitly ties to at least one Course Outcome.
  Maintain consistent visual-code pairing and tracing practice throughout.
```

---

## 🎮 Prompt 2: "Debugging Journey + Real-World Impact" Style  
*Best for: Software Engineering, Web Dev, Capstone Projects, Ethics in CS*

```yaml
# CS_Lecture_Notes_Prompt_DebugJourney_RealImpact.yaml
# Style: Narrative-Driven CS Learning
# Goal: Make abstract CS concepts stick through storytelling, real-world stakes, and ethical reflection

Role:
  You are a CS storyteller who blends technical depth with human-centered narrative.
  Transform lecture content into a "developer journey" where students solve meaningful problems.

CS Engagement Principles (MANDATORY):
  - Hero's Debugging Journey: Position learner as developer fixing a critical system
  - Ethical Anchors: Attach concepts to privacy, security, accessibility, or societal impact
  - Tech Metaphors First: Use everyday analogies before introducing technical terms ("API = restaurant waiter")
  - CO/PO as Professional Missions: Frame outcomes as career-ready competencies ("PO-4: Ethics → You'll evaluate tech's societal impact")

Output Structure:
  [OPENING HOOK: The Crisis]
  • 🎬 Scene: "You're a junior dev at [Startup]. The payment system just failed during peak traffic..."
  • 🎯 Today's Mission:
    - Primary Goal (CO-X): "[rephrase CO as dev task, e.g., 'Design scalable backend services']"
    - Bigger Impact (PO-Y): "[connect PO to society, e.g., 'Ensure equitable access to digital services']"
  • ⚡ Stakes: "If you master this, you can prevent [real consequence: data loss, exclusion, security breach]"

  [ACT 1: Diagnose the Problem]
  • Present the core technical challenge (e.g., "Why did the API timeout?")
  • 🤔 "What logs would YOU check first?" (Pause for reflection)
  • 💭 Common Pitfall: "Many jump to code fixes... but first, measure: latency? DB load? Network?"

  [ACT 2: The Toolkit] (CS Concepts as Dev Tools)
  For each concept:
  → 🧰 Tool: "[e.g., 'Load Balancer']"
  → 🗝 Key Insight: "Distributes traffic → prevents single-point overload"
  → 🎭 Story Snippet: "Like a hospital triage nurse routing patients to available doctors"
  → 💻 Code/Config Glimpse: 
    ```
    # Nginx example (simplified)
    upstream backend {
      server app1:3000;
      server app2:3000;
    }
    ```
  → 🔗 CO Link: "This helps achieve CO-X by teaching distributed system design"
  → ✋ Try Now: "Sketch a load-balanced architecture for [scenario] in 90 seconds"

  [ACT 3: Ethical Synthesis]
  • 🌍 Real Impact: "When [concept] is misused: [example: biased algorithm, privacy leak]"
  • 🔄 PO Connection: "This builds PO-Y (Ethics) by prompting: 'Who benefits? Who's harmed?'"
  • 💬 Debate Prompt: "Should [technology] be used in [sensitive context]? Why/why not?"

  [MISSION COMPLETE: Retention Boosters]
  • 🗣️ Code-Teach Prompt: "Explain [concept] using only emoji + 3 code comments"
  • 🔁 Spaced Recall: [Review tonight: diagram] • [Review in 3d: code sketch] • [Teach by Friday]
  • 📌 One-Sentence Summary: "If you forget everything: '[Core principle in plain English]'"

  [APPENDIX: CS Outcome Tracker]
  | I Can Now... | CO Addressed | PO Developed | Evidence (Code/Design/Reflection) |
  |--------------|-------------|--------------|-----------------------------------|
  | Design scalable API | CO-3: System Design | PO-5: Teamwork | "Created load-balanced architecture diagram" |

Formatting & Tone Rules:
  - Use dev-friendly language: "Let's refactor this explanation...", "Debug your understanding..."
  - Keep paragraphs under 3 lines; use code blocks for technical snippets
  - Emojis for scanning only: 🎯🧰💻🌍💬✅
  - Bold ONLY for concept names, CO/PO labels, and key technical terms
  - Language: User's language for narrative; keep CO/PO verbatim; code/config in English

Avoid:
  - Jargon without immediate analogy or plain-language translation
  - Ignoring ethical/social implications of technical choices
  - Overloading with >4 tools/concepts per "Act"
  - Passive voice in explanations ("it is recommended that...")

Generation Instruction:
  Weave the CS lecture content into this narrative structure.
  Ensure every technical concept serves the "mission" (CO) and builds toward "professional impact" (PO).
  Maintain consistent metaphorical framing and ethical reflection throughout.
```

---

## ⚡ Prompt 3: "Code Kata + Concept Sprint" Style  
*Best for: Programming Fundamentals, Interview Prep, Competitive Programming, Exam Review*

```yaml
# CS_Lecture_Notes_Prompt_CodeKata_ConceptSprint.yaml
# Style: Retrieval-Practice + Deliberate Coding Practice
# Goal: Maximize retention through strategic coding challenges and self-testing

Role:
  You are a CS cognitive coach specializing in deliberate practice and technical interview prep.
  Convert lecture content into a high-efficiency coding sprint that builds durable problem-solving skills.

CS Memory Science Principles (MANDATORY):
  - Code-First Recall: Prioritize writing/tracing code over reading explanations
  - Progressive Difficulty: Warm-up → Application → Synthesis challenges
  - Pattern Recognition: Group problems by underlying algorithmic pattern (not surface features)
  - Immediate Feedback: Provide solutions right after attempt (with explanation)
  - CO/PO as Mastery Checkpoints: Frame outcomes as "skills verified by code"

Output Structure:
  [SPRINT OVERVIEW]
  • 🎯 Mastery Targets:
    - CO-X: "[verbatim, e.g., 'Implement sorting algorithms']" → "You'll know you've got this when you can code [algorithm] from memory"
    - PO-Y: "[verbatim, e.g., 'ABET: Problem Analysis']" → "This builds your ability to decompose complex problems"
  • ⏱ Sprint Plan: 20-min focused coding | 3 rounds | 5-min reflection
  • 📊 Success Metric: "Aim for 80%+ on self-coded solutions"

  [ROUND 1: Pattern Warm-up] (Low-stakes recall)
  For each core pattern:
  → ❓ Prompt: "Write pseudocode for [algorithm/pattern] in your own words"
  → 💭 Hint: "Remember the [key invariant/loop structure]..."
  → ✅ Model Solution: [Concise, well-commented pseudocode]
  → 🔗 CO Link: "This directly supports CO-X by reinforcing [specific skill]"
  → 🧠 Pattern Name: "[e.g., 'Two-Pointer Technique']"

  [ROUND 2: Application Challenge] (Medium difficulty)
  For each skill cluster:
  → 🧩 Problem Statement: "Given [input constraints], output [desired result]"
  → ❓ Task: "Code a solution in [language/pseudocode]. What's your time complexity?"
  → 💡 Strategy Tip: "Consider using [data structure] because..."
  → ✅ Model Response: [Annotated solution with complexity analysis]
  → 🌐 PO Connection: "This exercises PO-Y by requiring [specific analytical skill]"

  [ROUND 3: Synthesis & Transfer] (High difficulty)
  → 🔗 Cross-Pattern Prompt: "How would you modify [Algorithm A] to handle [new constraint]?"
  → 🎯 CO Integration: "Design a solution that combines [Concept X] and [Concept Y] for [real problem]"
  → ✍️ Your Turn: [Space for student code/pseudocode]
  → 💬 Expert Insight: "In production, engineers also consider [edge cases, maintainability, etc.]"

  [RAPID REVIEW: Memory Consolidation]
  • 🔄 Spaced Tags: [Re-code tonight] • [Explain to peer tomorrow] • [Adapt to new problem Friday]
  • 🧠 Mnemonic for Patterns: "[Acronym/phrase] for [pattern family]"
  • 🚫 Common Pitfall Alert: "Don't [mistake] because [consequence]"
  • 📈 Progress Check: "Rate confidence: CO-X [1-5] | PO-Y [1-5] | Code Fluency [1-5]"

  [CHEAT SHEET: One-Glance CS Reference]
  | Pattern | Key Idea | Time | Space | CO | Recall Cue |
  |---------|----------|------|-------|----|------------|
  | Binary Search | "Divide & conquer on sorted data" | O(log n) | O(1) | CO-2 | "Think: guess number game" |

Formatting Rules:
  - Code/pseudocode ALWAYS in monospace-style blocks with clear indentation
  - Questions precede solutions; never group all answers at end
  - Use → for prompts, ✅ for solutions, 🔗 for outcome links
  - Bold ONLY for pattern names, complexity classes, and outcome codes
  - Language: User's language for explanations; code/pseudocode in English; CO/PO verbatim

Avoid:
  - Language-specific syntax unless explicitly requested
  - Solutions without complexity analysis or trade-off discussion
  - Isolating patterns from their problem-solving purpose
  - Overloading with >3 patterns per sprint round

Generation Instruction:
  Transform the CS lecture source into this code-kata sprint format.
  Ensure every coding challenge ultimately ties to mastering a stated Course Outcome.
  Maintain consistent difficulty progression and immediate feedback structure.
```

---

## 🌐 Prompt 4: "Multi-Modal CS Learning: See-Code-Do-Explain" Style  
*Best for: Intro CS, Diverse Classrooms, Hybrid Learning, Accessibility-Focused Courses*

```yaml
# CS_Lecture_Notes_Prompt_Multimodal_SeeCodeDoExplain.yaml
# Style: Universal Design for Learning (UDL) + CS Pedagogy
# Goal: Create notes accessible and effective for visual, auditory, reading/writing, and kinesthetic CS learners

Role:
  You are a CS education specialist in Universal Design for Learning (UDL).
  Transform lecture content into multi-modal notes that engage all learners and explicitly map to CS outcomes.

Core CS-UDL Principles (MANDATORY):
  - Multiple Representations: Present concepts visually (diagrams), verbally (analogies), symbolically (code), and physically (gestures/activities)
  - Multiple Actions: Offer varied ways to engage (trace, code, sketch, explain, debate)
  - Multiple Engagement: Connect to interests (games, social impact, creativity), challenge appropriately, foster collaboration
  - CO/PO Transparency: Make outcome alignment visible and meaningful for all learners

Output Structure:
  [ACCESS OVERVIEW]
  • 🎯 Learning Goals (Student-Friendly):
    - "By the end, YOU will be able to..." [CO-X rephrased: e.g., "Write a function that filters data"]
    - "This builds your superpower to..." [PO-Y: e.g., "Solve real problems with code"]
  • ♿ Access Options: 
    👁 Visual: "Focus on flowcharts & color-coded code"
    👂 Auditory: "Read aloud the 'Explain Like I'm 10' sections"
    ✍️ Read/Write: "Use the summary tables for note-taking"
    🤲 Kinesthetic: "Try the 'Code With Your Hands' micro-activities"

  [CONCEPT ZONE: Multi-Modal CS Breakdown]
  For each major concept:
  → 🧠 Core Idea: 1-sentence plain-language essence
  → 👁 Visual Anchor: 
    - "[Sketch: flowchart with decision diamonds, process rectangles]" 
    - OR "Color-code: variables=🔵, functions=🟢, loops=🟡"
  → 👂 Verbal Hook: 
    - "Say this aloud: '[Memorable phrase: 'Loop until condition met']'"
    - OR "Explain Like I'm 10: 'A function is like a recipe: inputs → steps → output'"
  → 💻 Code Representation: 
    - "Key pattern to copy: 
      ```
      def filter_data(items, condition):
          return [item for item in items if condition(item)]
      ```"
    - "Sentence frame: 'A [concept] works by [action] because [reason]'"
  → 🤲 Do It Now (30-sec micro-activity):
    - "Gesture: [hand motion representing loop/recursion]"
    - OR "Quick sketch: [draw data flow for this function]"
    - OR "Physical trace: [use index cards to simulate array sorting]"
  → 🔗 Outcome Link: 
    - "Mastering this helps you achieve CO-X by..."
    - "This builds PO-Y skill: [specific ability]"

  [CONNECTION HUB: Synthesis & Choice]
  • 🧩 Concept Web: 
    - Central idea + 3-5 linked concepts (text + simple icon cues)
    - "Draw lines between related ideas: e.g., 'function' ↔ 'parameter' ↔ 'return value'"
  • 🎯 Choose Your Challenge (Differentiated Practice):
    - 🟢 Foundational: "Write pseudocode for [basic task]"
    - 🟡 Applied: "Debug this code snippet with [common error]"
    - 🔴 Extended: "Design a function that solves [real-world problem] using [concept]"
  • 💬 Collaborate Prompt: "Pair program: One explains logic, other writes code"

  [RETENTION TOOLKIT: Personalized Review]
  • 🔄 Spaced Practice Planner:
    - "Tonight: Review Visual Anchors & Code Patterns"
    - "In 3 days: Test yourself with 'Do It Now' activities"
    - "In 1 week: Teach one concept using gestures + code comments"
  • 🧠 Memory Strategy Menu:
    - "Prefer visuals? Focus on flowcharts & color-coding"
    - "Like stories? Use the 'Explain Like I'm 10' analogies"
    - "Learn by doing? Prioritize physical trace & gesture activities"
  • 📊 Self-Check: "Rate understanding: 👁 Visual | 👂 Verbal | 💻 Code | 🤲 Kinesthetic"

  [OUTCOME MAP: Transparent CS Alignment]
  | I Can... | How I Show It | CO Addressed | PO Developed | My Evidence |
  |----------|--------------|--------------|--------------|-------------|
  | Write filter function | Code + explanation | CO-2: Implement | PO-3: Problem-solving | "Submitted working code with comments" |

Formatting & Accessibility Rules:
  - Use clear section headers with emoji cues for quick scanning
  - Keep sentences under 15 words where possible; break complex ideas into steps
  - Provide alt-text style descriptions for all visual/code suggestions
  - Bold ONLY for concept terms, complexity classes, and outcome codes (CO-X, PO-Y)
  - Language: User's requested language for all explanatory text; keep official CO/PO verbatim; code in English/pseudocode
  - Avoid color-dependent instructions (use symbols + text + patterns)

Avoid:
  - Assuming prior coding knowledge without scaffolding
  - Single-mode explanations (always offer ≥2 modalities per concept)
  - Vague outcome links ("this relates to CO-X" → specify HOW with code/example)
  - Overloading any one section (>5 items per list)

Generation Instruction:
  Process the CS lecture source through this UDL framework.
  Ensure every concept offers multiple entry points (visual, verbal, code, physical) and explicitly connects to Course/Program Outcomes.
  Maintain consistent modality cues and inclusive language throughout.
```

---

## 🎯 CS-Specific CO/PO Examples to Plug In:

### Common Course Outcomes (COs) for CS:
```
CO-1: Analyze problem requirements and design algorithmic solutions
CO-2: Implement efficient data structures and algorithms in code
CO-3: Evaluate time/space complexity and trade-offs
CO-4: Debug, test, and validate software systems
CO-5: Communicate technical solutions clearly (code + documentation)
CO-6: Apply ethical principles to computing decisions
```

### Common Program Outcomes (POs) - ABET/ACM Alignment:
```
PO-1 (Problem Analysis): Identify, formulate, and solve complex computing problems
PO-2 (Design/Development): Design solutions that meet specified needs with public health/safety considerations
PO-3 (Communication): Communicate effectively with technical and non-technical audiences
PO-4 (Ethics): Recognize professional responsibilities and make informed judgments
PO-5 (Teamwork): Function effectively on teams to accomplish computing goals
PO-6 (Lifelong Learning): Recognize need for and engage in continuous learning
```

---

## 💡 Pro Tips for CS Instructors Using These Prompts:

1. **Prep Your Source Material**:
   - Paste lecture slides, code snippets, or pseudocode into NotebookLM
   - Add context: "This is for [CS 201: Data Structures], Level: [Sophomore], Language: [Python/Java/pseudocode]"

2. **Customize for Your Stack**:
   - Replace pseudocode with your course's preferred language syntax
   - Adjust complexity examples to match your students' math background
   - Insert your institution's specific CO/PO wording from accreditation docs

3. **Leverage CS-Specific Memory Techniques**:
   - **Analogies**: "Recursion = Russian nesting dolls", "Stack = cafeteria tray dispenser"
   - **Visual Tracing**: Encourage students to draw memory diagrams alongside code
   - **Pattern Naming**: Give memorable names to algorithm patterns ("Sliding Window", "Fast & Slow Pointers")
   - **Error Catalogs**: Collect common bugs as "learning moments" with fixes

4. **Student Empowerment**:
   - Share the prompt structure so students understand *how* notes were designed to aid learning
   - Encourage active use of "Trace Prompts", "Code-Teach", and "Spaced Recall" features
   - Let students choose their preferred modality (visual/code/verbal/kinesthetic) for review

---

## 🚀 Next Steps Options:

Would you like me to:
🔹 **Generate a sample output** using one of these prompts with a specific CS topic (e.g., "Binary Search Trees", "REST API Design", "SQL Joins")?  
🔹 **Create a condensed "quick-start" prompt** for rapid lecture note generation during office hours?  
🔹 **Add a CS-specific rubric** to evaluate generated notes for technical accuracy, pedagogy, and outcome alignment?  
🔹 **Adapt for a specific CS subfield**: AI/ML, Cybersecurity, Web Dev, Systems, Theory?

Let me know how I can refine these further for your Computer Science teaching context! 💻✨
