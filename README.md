# Maximum Number of Vowels in a Substring of Given Length

## Problem Description

Given a string `s` and an integer `k`, return the **maximum number of vowel letters** in any substring of `s` with length `k`.

Vowel letters in English are `'a'`, `'e'`, `'i'`, `'o'`, and `'u'`.

## Examples

### Example 1:
**Input:**  
`s = "abciiidef"`  
`k = 3`  
**Output:**  
`3`  

**Explanation:**  
The substring `"iii"` contains 3 vowel letters.

---

### Example 2:
**Input:**  
`s = "aeiou"`  
`k = 2`  
**Output:**  
`2`  

**Explanation:**  
Any substring of length 2 contains 2 vowels.

---

### Example 3:
**Input:**  
`s = "leetcode"`  
`k = 3`  
**Output:**  
`2`  

**Explanation:**  
The substrings `"lee"`, `"eet"`, and `"ode"` each contain 2 vowels.

---

## Constraints
- `1 <= s.length <= 10⁵`
- `s` consists of lowercase English letters.
- `1 <= k <= s.length`
