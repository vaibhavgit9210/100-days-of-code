# #100DaysOfCode Log - Round 1 - Vaibhav Kumar

The log of my #100DaysOfCode challenge. Started on August 4, Tuesday, 2026.

Rules I'm holding myself to: training mode — AI may explain, AI never writes the code. NeetCode-150 in roadmap order, 1–2 problems a day, pattern logged here daily.

## Log

### R1D1 — August 4, 2026
**Today's Progress:** Solved LeetCode [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) and [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) in C++.

**Pattern learned:** Hashing with `unordered_map` / `unordered_set` — trade O(n) space for O(1) average lookups, turning "have I seen this before?" (217) and "do these frequency counts match?" (242) from O(n²)/sorting problems into single-pass O(n).

**Thoughts:** Here I go again, for the nth time 🤡 — but this round has a system behind it (external graders, one block at a time) instead of vibes.

### R1D2 — August 5, 2026

**Today's Progress:** Solved LeetCode [1. Two Sum](https://leetcode.com/problems/two-sum/) in C++.

**Pattern learned:** Hash map complement lookup — instead of checking every pair (O(n²)), store previously seen values in an `unordered_map` and look up the required complement (`target - current`) in O(1) average time while traversing the array once, reducing the solution to O(n).

**Thoughts:** I had seen this problem before, but this time the focus wasn't just getting Accepted—it was understanding *why* the one-pass hash map works and recognizing it as a reusable pattern. One more pattern added to the toolbox.
