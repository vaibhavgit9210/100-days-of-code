# #100DaysOfCode Log - Round 1 - Vaibhav Kumar

The log of my #100DaysOfCode challenge. Started on August 4, Tuesday, 2026.

Rules I'm holding myself to: training mode  AI may explain, AI never writes the code. NeetCode-150 in roadmap order, 1–2 problems a day, pattern logged here daily.

## Log

### R1D1 August 4, 2026
**Today's Progress:** Solved LeetCode [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) and [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) in C++.

**Pattern learned:** Hashing with `unordered_map` / `unordered_set`  trade O(n) space for O(1) average lookups, turning "have I seen this before?" (217) and "do these frequency counts match?" (242) from O(n²)/sorting problems into single-pass O(n).

**Thoughts:** Here I go again, for the nth time 🤡  but this round has a system behind it (external graders, one block at a time) instead of vibes.

### R1D2 August 5, 2026

**Today's Progress:** Solved LeetCode [1. Two Sum](https://leetcode.com/problems/two-sum/) in C++.

**Pattern learned:** Hash map complement lookup  instead of checking every pair (O(n²)), store previously seen values in an `unordered_map` and look up the required complement (`target - current`) in O(1) average time while traversing the array once, reducing the solution to O(n).

**Thoughts:** I had seen this problem before, but this time the focus wasn't just getting Acceptedit was understanding *why* the one-pass hash map works and recognizing it as a reusable pattern. One more pattern added to the toolbox.

### R1D3 August 6, 2026

**Today's Progress:** Solved LeetCode [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) in C++.

**Pattern learned:** Lexicographic sorting. After sorting the array of strings, the longest common prefix of the entire array must be the common prefix between the first and last strings. Comparing only these two strings reduces the problem to a single linear scan after sorting.

**Thoughts:** It was satisfying to realize that the solution doesn't require comparing every string with every other string. Once I understood why the first and last strings after sorting capture the maximum possible difference, the approach felt surprisingly elegant.

### R1D4 August 7, 2026

**Today's Progress:** Solved a Trie-based problem. I had to find the Longest Common Prefix between 2 strings, given n strings. (Not LeetCode 14.)

**Pattern learned:** I first built the Trie using a 2D array, which led to memory-exceeded problems. Then I learned on the internet (ChatGPT, actually) that using pointers and classes allows us to allocate memory dynamically, instead of unnecessarily allocating space for the entire 2D array upfront.

**Thoughts:** When it comes to pointers, it's always interesting, but it takes patience to learn.

### R1D5 August 8, 2026

**Today's Progress:** Solved LeetCode [208. Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) and [211. Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) in C++.

I was supposed to work on something related to LangGraph today, but didn't get to it. LeetCode was the backup so I could still code something and stay true to the #100DaysOfCode challenge.

**Pattern learned:** Wildcard search in a Trie. When `.` is encountered, DFS and backtracking explores the possible child nodes while continuing normally for regular characters.

**Thoughts:** The wildcard search was the interesting part today. It was a good exercise in combining Trie traversal with DFS and backtracking.

### R1D6 — August 9, 2026

**Today's Progress:** Tried solving LeetCode [212. Word Search II](https://leetcode.com/problems/word-search-ii/) on my own, but couldn't complete it.

**Pattern learned:** Trie combined with backtracking. I'm still working on understanding how to implement the Trie traversal and backtracking together for this problem.

**Thoughts:** This one is taking more time to understand, especially how the Trie and backtracking work together. I'll continue working on it.

### R1D7 — August 10, 2026

**Today's Progress:** Solved LeetCode [212. Word Search II](https://leetcode.com/problems/word-search-ii/) on my own.

**Pattern learned:** Trie combined with DFS & backtracking. Also, I need to learn the differnece between '*' & '&' when creating and calling functions, as well as when declaring variables.

**Thoughts:** A lot of errors were found while I tried to compile the code that I wrote. 

### R1D8 — August 11, 2026

**Today's Progress:** I didn't solve any problems today. Instead, I went thorough a few mock interviews for AI Engineer role.

**Pattern learned:** Embeddings, Retrieval Augmented Generation (RAG), NLP (Natural Language Processing)

**Thoughts:** I plan to do better tomorrow.

### R1D9 August 12, 2026

**Today's Progress:** No coding progress today.

**Thoughts:** Back tomorrow.

### R1D10 — August 13, 2026

**Today's Progress:** Solved a Trie based problem in C++. The solution inserts all words into a Trie, reverses each word, and searches for its reverse to count matching pairs.

**Pattern learned:** Instead of comparing every pair of strings, I used a Trie for efficient lookups after reversing each word. This reinforced using Trie as a fast search structure for string transformations.

**Thoughts:** Good practice combining string manipulation with Trie based lookups.
