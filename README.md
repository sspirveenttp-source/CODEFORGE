# 🔥 Code Forge — Master Coding Interviews

<div align="center">

![Code Forge Banner](https://img.shields.io/badge/Code-Forge-orange?style=for-the-badge&logo=fire&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### *A LeetCode-style coding practice platform for students preparing for technical interviews.*

[Features](#-features) · [Demo](#-demo--screenshots) · [Quick Start](#-quick-start) · [Tech Stack](#-tech-stack) · [Roadmap](#-roadmap) · [Contributing](#-contributing)

</div>

---

## ✨ Overview

**Code Forge** is a fully-functional, browser-based coding practice platform inspired by LeetCode and CodeChef. It features a real in-browser code editor, an instant test-runner that judges your code against multiple test cases, AI-powered hints (without giving away solutions), submission history, progress analytics, streaks, a global leaderboard, and a sleek dark UI.

> 🎯 **Goal:** Give every student a free, distraction-free place to practice for coding interviews — no signup walls, no paywalls, just problems.

---

## 🌟 Features

<table>
<tr>
<td width="50%">

### 📚 23+ Curated Problems
Hand-picked across **Easy**, **Medium**, and **Hard** difficulty covering Arrays, Strings, Dynamic Programming, Trees, Graphs, Sliding Window, Stack, Greedy, and 10+ more topics.

### 💻 Real Code Editor
Powered by **Monaco Editor** (the same engine VS Code uses). Syntax highlighting, auto-indent, multi-language support.

### ⚡ 4 Languages Supported
Write code in **JavaScript** (executed live), **Python**, **Java**, and **C++**.

### 🏃 Instant Verdicts
Run your code against sample test cases and see **Accepted** ✅, **Wrong Answer** ❌, or **Time Limit Exceeded** ⏱ in milliseconds.

</td>
<td width="50%">

### 🤖 AI Hint Assistant
Stuck? The built-in AI assistant gives **concept explanations** and **guided hints** — but never the full solution (intentionally).

### 📊 Dashboard & Analytics
Track your streak, problems solved, acceptance rate, and visualize activity with a 14-day area chart and a GitHub-style contribution heatmap.

### 🏆 Global Leaderboard
Compete with coders around the world. Sort by rank, problems solved, accuracy, or streak.

### 👤 User Profiles
Custom avatar, solved-problems grid, submission history, language usage stats, and verdict breakdown.

</td>
</tr>
</table>

### More Highlights
- 🔐 **Mock Authentication** — local sign-up / sign-in (data persists via localStorage)
- 🔍 **Powerful Filters** — filter problems by difficulty, tags, status (solved/attempted/todo), and free-text search
- 💾 **Auto-save** — your code is saved per-problem per-language
- 🎨 **Beautiful Dark UI** — gradient accents, glassmorphism, smooth animations
- 📱 **Fully Responsive** — looks great on phone, tablet, and desktop
- 🚀 **Zero Backend Needed** — runs as a single static HTML file

---

## 🎬 Demo & Screenshots

<div align="center">

### 🏠 Landing Page
> Branded hero, feature highlights, live editor mock, featured problems

</div>

```
┌─────────────────────────────────────────────────────────────────────┐
│  ⚡ CodeForge                                  Problems  Dashboard  │
│  Master the craft                                  Leaderboard  👤  │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   [✨ New: AI-powered hint system live now]                        │
│                                                                     │
│   Master                                  ┌──────────────────┐      │
│   coding interviews                       │ ● ● ● two-sum.js │      │
│   on Code Forge.                          │ function twoSum( │      │
│                                            │   nums, target){│      │
│   The ultimate platform for                │   const map = ...│     │
│   students and engineers ...               │ }                │      │
│                                            │ ✓ Accepted  4ms  │      │
│   [Start practicing →] [Create account]    └──────────────────┘      │
│                                                                     │
│   20+          4            15+          ∞                            │
│   Problems     Languages    Topics       Test Cases                  │
└─────────────────────────────────────────────────────────────────────┘
```

### 📚 Problem List with Filters
```
┌──────────────────────────────────────────────────────────────────────┐
│  Problems                          [Easy 12/13] [Med 7/8] [Hard 2/4] │
├──────────────────────────────────────────────────────────────────────┤
│  🔍 Search problems...    [All|Easy|Med|Hard]  [All|Solved|Todo]    │
│  Tags: [Array] [String] [Hash Table] [DP] [Stack] ...               │
├──────────────────────────────────────────────────────────────────────┤
│  Status  Title                          Difficulty  Acceptance       │
│  ────── ──────                          ──────────  ──────────       │
│  ✓       Two Sum                        [Easy]      52.3%            │
│  ✓       Valid Parentheses              [Easy]      40.2%            │
│  ◐       Add Two Numbers                [Medium]    41.2%            │
│  —       Median of Two Sorted Arrays    [Hard]      38.1%            │
└──────────────────────────────────────────────────────────────────────┘
```

### 💻 Problem Detail (Code Editor)
```
┌─────────────────────────────────────┬─────────────────────────────────┐
│ ← 1. Two Sum          [Easy] 52.3%  │ [JavaScript] [Python] [Java].. │
│   ✓ Accepted · 3 attempts            ├─────────────────────────────────┤
│ ─────────────────────────────────── │  1  function twoSum(nums, t) {  │
│ Description | Hints | Related       │  2    const map = new Map();    │
│                                     │  3    for (let i = 0; ...) {    │
│ Given an array of integers nums     │  4      const c = t - nums[i];  │
│ and an integer target, return       │  5      if (map.has(c)) ...     │
│ indices of the two numbers...       │  6      map.set(nums[i], i);    │
│                                     │  7    }                          │
│ Examples:                           │  8  }                            │
│   Input: nums = [2,7,11,15] t = 9   │                                 │
│   Output: [0,1]                     ├─────────────────────────────────┤
│                                     │ [Case 1 ✓] [Case 2 ✓] [+Custom] │
│ Constraints:                        │ ─────────────────────────────────│
│   • 2 ≤ nums.length ≤ 10⁴           │ Input:  [2,7,11,15], 9          │
│                                     │ Expected:  [0,1]                │
│ Tags: Array · Hash Table            │ Your out:  [0,1]  ✓ Matches     │
│                                     │ [▶ Run]  [📤 Submit]            │
└─────────────────────────────────────┴─────────────────────────────────┘
```

### 📊 Dashboard
```
┌──────────────────────────────────────────────────────────────────────┐
│  Welcome back, Aarav Sharma                            [Sign out]    │
├──────────────────────────────────────────────────────────────────────┤
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐            │
│  │ Solved   │  │ Accuracy │  │ Streak   │  │ This week│            │
│  │   18     │  │  62%     │  │  7 days  │  │    4     │            │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘            │
│                                                                      │
│  ┌─────────────────────────────────┐  ┌────────────────────┐         │
│  │ Activity (14 days)              │  │ Solved by difficulty│        │
│  │   ▁▂▃▅▇█▇▅▃▂▁  (area chart)     │  │     ◐ Easy 12        │        │
│  │                                 │  │   ◐ Med 5  Hard 1   │        │
│  └─────────────────────────────────┘  └────────────────────┘         │
│                                                                      │
│  Recommended for you        │  Recent submissions                   │
│  • Best Time to Buy/Sell    │  ✓ Two Sum           Accepted         │
│  • Climbing Stairs          │  ✗ Median Arrays     WA              │
│  • Move Zeroes              │  ✓ Valid Parens      Accepted         │
└──────────────────────────────────────────────────────────────────────┘
```

### 🏆 Leaderboard
```
┌──────────────────────────────────────────────────────────────────────┐
│  Leaderboard            [By rank] [By solved] [By accuracy] [Streak]│
├──────────────────────────────────────────────────────────────────────┤
│       🥇 1st              🥈 2nd              🥉 3rd                  │
│      Aarav             Priya               Chen                       │
│      512 solved        470 solved          438 solved                 │
│      78% accuracy      75% accuracy        71% accuracy               │
│                                                                      │
│  Your rank: #87   Solved: 18/23   Accuracy: 62%   Streak: 7 🔥       │
│                                                                      │
│  Rank  Coder             Solved  Easy  Med  Hard  Acc   Streak        │
│  #4    algoqueen         512     180   240   92    78%   145 🔥       │
│  #5    bitninja          470     165   220   85    75%    98 🔥       │
│  #6    dp_wizard         438     150   210   78    71%    67 🔥       │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Quick Start

### Prerequisites
- **Node.js** ≥ 18
- **npm** (or pnpm / yarn)

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/sspirveenttp-source/CODEFORGE.git
cd CODEFORGE

# 2. Install dependencies
npm install

# 3. Run the dev server
npm run dev
```

Then open **http://localhost:5173** in your browser. 🎉

### Build for Production

```bash
npm run build      # outputs dist/index.html (single static file)
npm run preview    # preview the built bundle
```

The build produces a **single self-contained `index.html`** (~810 KB, ~234 KB gzipped) — no server, no backend. You can:

- 🖱 **Double-click** `dist/index.html` to open it directly in Chrome / Safari / Firefox
- 🌐 **Upload to any static host** (Netlify, Vercel, GitHub Pages, Cloudflare Pages)

---

## 🧠 AI Hint System

Code Forge's AI assistant is intentionally designed to **never reveal full solutions**. It helps you learn the *right way* by:

| You Ask | It Tells You |
|---|---|
| "What's the core idea?" | The pattern (DP, two pointers, hash map...) and a *hint* of the recurrence |
| "What's the brute force?" | The O(n²) approach so you can verify then optimize |
| "Which data structure?" | A conceptual pointer (e.g. "a hash map turns O(n²) into O(n)") |
| "What are edge cases?" | Empty input, single element, all same, negatives |
| "Give me the solution" | "I can't — but here's a nudge..." |

> 🎓 *Because learning the path is more valuable than copying the answer.*

---

## 🛠 Tech Stack

<div align="center">

| Layer       | Technology                                                                                  |
|-------------|---------------------------------------------------------------------------------------------|
| **UI**      | ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react)          |
| **Language**| ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) |
| **Bundler** | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Styling** | ![Tailwind](https://img.shields.io/badge/Tailwind_4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Editor**  | Monaco Editor (via `@monaco-editor/react`)                                                  |
| **Charts**  | Recharts                                                                                    |
| **Routing** | React Router (HashRouter — works as a static file!)                                          |
| **Icons**   | Lucide React                                                                                |
| **State**   | React Context + localStorage                                                                |

</div>

---

## 📂 Project Structure

```
CODEFORGE/
├── public/
│   └── (static assets)
├── src/
│   ├── components/
│   │   └── Navbar.tsx           # Top nav with brand, links, streak, auth
│   ├── contexts/
│   │   └── AppContext.tsx       # Auth + progress + submissions + streak
│   ├── data/
│   │   ├── problems.ts          # 23 problems with test cases & solutions
│   │   └── users.ts             # Leaderboard seed data
│   ├── pages/
│   │   ├── Home.tsx             # Landing page
│   │   ├── Problems.tsx         # Problem list with filters
│   │   ├── ProblemDetail.tsx    # Code editor + AI + verdict
│   │   ├── Dashboard.tsx        # Charts, heatmap, recommendations
│   │   ├── Leaderboard.tsx      # Rankings + podium
│   │   ├── Profile.tsx          # User profile + submissions
│   │   └── Login.tsx            # Sign in / sign up
│   ├── judge.ts                 # Code execution + verdict engine
│   ├── App.tsx                  # Router
│   ├── main.tsx                 # Entry point
│   └── index.css                # Tailwind + custom styles
├── index.html
├── package.json
├── vite.config.ts
└── README.md
```

---

## 🎓 Problem Bank

23 hand-picked problems covering all major patterns:

| # | Title | Difficulty | Tags |
|--:|-------|:----------:|------|
| 1 | Two Sum | 🟢 Easy | Array, Hash Table |
| 2 | Add Two Numbers | 🟡 Medium | Linked List, Math |
| 3 | Longest Substring Without Repeating | 🟡 Medium | String, Sliding Window |
| 4 | Median of Two Sorted Arrays | 🔴 Hard | Array, Binary Search |
| 5 | Longest Palindromic Substring | 🟡 Medium | String, DP |
| 6 | Reverse Integer | 🟡 Medium | Math |
| 7 | Palindrome Number | 🟢 Easy | Math |
| 8 | Valid Parentheses | 🟢 Easy | String, Stack |
| 9 | Merge Two Sorted Arrays | 🟢 Easy | Array, Two Pointers |
| 10 | Maximum Subarray | 🟡 Medium | Array, DP |
| 11 | Climbing Stairs | 🟢 Easy | DP, Math |
| 12 | Merge Intervals | 🟡 Medium | Array, Sorting |
| 13 | Best Time to Buy/Sell Stock | 🟢 Easy | Array, DP |
| 14 | Contains Duplicate | 🟢 Easy | Array, Hash Table |
| 15 | Product of Array Except Self | 🟡 Medium | Array |
| 16 | Valid Anagram | 🟢 Easy | String, Hash Table |
| 17 | Binary Search | 🟢 Easy | Array, Binary Search |
| 18 | Fizz Buzz | 🟢 Easy | Math, String |
| 19 | Missing Number | 🟢 Easy | Array, Math |
| 20 | Counting Bits | 🟢 Easy | DP, Math |
| 21 | Move Zeroes | 🟢 Easy | Array, Two Pointers |
| 22 | Coin Change | 🟡 Medium | DP |
| 23 | First Missing Positive | 🔴 Hard | Array, Hash Table |

---

## 🗺 Roadmap

- [x] ✅ Landing page with branding & CTAs
- [x] ✅ Problem list with difficulty / tag / status filters
- [x] ✅ Problem detail with examples, constraints, hints
- [x] ✅ Monaco code editor + 4 languages
- [x] ✅ Real JavaScript execution & test runner
- [x] ✅ Verdict display (Accepted / Wrong Answer / TLE)
- [x] ✅ AI hint system (no full solutions)
- [x] ✅ User auth (mock) with profile page
- [x] ✅ Submission history & stats
- [x] ✅ Leaderboard with rankings
- [x] ✅ Dashboard with charts & heatmap
- [x] ✅ Streak tracking
- [x] ✅ Personalized recommendations
- [ ] 🔄 Backend with persistent user accounts
- [ ] 🔄 Real Python / Java / C++ execution via WebAssembly or server
- [ ] 🔄 Discussion forums per problem
- [ ] 🔄 Editorial solutions
- [ ] 🔄 Daily challenge with timer
- [ ] 🔄 Contest mode
- [ ] 🔄 Multiplayer head-to-head

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. 🍴 **Fork** the repo
2. 🌿 **Create** a branch: `git checkout -b feature/amazing-idea`
3. 💻 **Commit** your changes: `git commit -m "feat: add amazing idea"`
4. 📤 **Push** to the branch: `git push origin feature/amazing-idea`
5. 🔁 **Open a Pull Request**

### Adding a New Problem

Add an entry to `src/data/problems.ts`:

```typescript
{
  id: 24,
  slug: "your-problem-slug",
  title: "Your Problem Title",
  difficulty: "Medium",
  tags: ["Array", "Hash Table"],
  acceptance: 50.0,
  statement: `Your markdown-style problem statement with <code>tags</code>...`,
  examples: [{ input: "...", output: "...", explanation: "..." }],
  constraints: ["n <= 10^5", "..."],
  hints: ["Hint 1", "Hint 2"],
  funcName: "yourFunctionName",
  starterCode: { javascript: "...", python: "...", java: "...", cpp: "..." },
  testCases: [{ input: [[1,2,3], 6], expected: [0,1,2] }],
}
```

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more info.

```
MIT License — feel free to use this for your own learning, portfolio, or teaching.
```

---

## 👨‍💻 Author

<div align="center">

**Built with ❤️ and a lot of ☕ by [Sspirveenttp](https://github.com/sspirveenttp-source)**

> *"Your next interview is closer than you think."*

</div>

---

## 🙏 Acknowledgments

- 🎨 **Inspired by** [LeetCode](https://leetcode.com) and [CodeChef](https://codechef.com) — the gold standards of coding practice
- 🖥 **Editor** powered by [Monaco Editor](https://github.com/microsoft/monaco-editor)
- 📊 **Charts** by [Recharts](https://recharts.org)
- 🎯 **Icons** by [Lucide](https://lucide.dev)

---

<div align="center">

### ⭐ If Code Forge helped you land an interview prep win, **star the repo**!

[![Star on GitHub](https://img.shields.io/github/stars/sspirveenttp-source/CODEFORGE?style=social)](https://github.com/sspirveenttp-source/CODEFORGE)

**Happy coding! 🚀**

</div>
