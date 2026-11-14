# JFLAP Assignment — Theory of Computer Science (26CMPC51)

**Name:** Sanika Mejari  
**Roll No:** 39  
**Class:** T.E. Sem V, D12B  
**Date of Performance (DOP):** 14-11-2026  
**Faculty In-charge:** Mrs. Manisha Mathur

Open each `.jff` file in JFLAP (File → Open). Use *Input → Multiple Run* to test the strings listed below.

| Q | Topic | Problem | Accept (examples) | Reject (examples) |
|---|---|---|---|---|
| 01 | DFA | DFA over {0,1} that accepts strings with an even number of 0s and an odd number of 1s. | 001, 000111011, 100011101 | 000, 00111101, 000111100 |
| 02 | DFA | DFA over {0,1} that accepts strings in which the number of 1s is divisible by 3. | 000, 01010010, 010100100 | 001, 01011101, 010101110 |
| 03 | DFA | DFA over {0,1} that accepts strings containing exactly two 0s. | 001, 0111110, 11110101 | 000, 01101100, 010110010 |
| 04 | DFA | DFA over {0,1} that accepts strings ending with 100. | 100, 01011100, 010101100 | 000, 01011010, 010101101 |
| 05 | DFA | DFA over {0,1} that accepts strings that start with 1 and end with 0. | 100, 10101100, 101010100 | 000, 01000100, 010000010 |
| 06 | DFA | DFA over {0,1} that accepts strings containing 110 as a substring. | 110, 10110111, 011101011 | 000, 1010010, 000100100 |
| 07 | DFA | DFA over {0,1} that accepts strings ending with 00 or 11. | 000, 01011011, 010101100 | 001, 01011010, 010101101 |
| 08 | NFA | NFA over {0,1} that accepts strings in which the third symbol from the right is 1. | 100, 01011101, 010101110 | 000, 01011001, 010101010 |
| 09 | DFA | DFA over {0,1} that accepts strings containing 001 or 110 as a substring. | 001, 01110111, 010111101 | 000, 010111, 01011111 |
| 10 | DFA | DFA over {0,1} that accepts strings containing exactly one occurrence of the substring 00 (overlaps counted, so 000 has two). | 001, 01001111, 010111100 | 000, 01100000, 010100011 |
| 11 | RE | Regular expression over {a,b} for strings ending with abb. `(a+b)*abb` | abb, ababbabb, ababababb | aaa, ababbaba, abababbab |
| 12 | RE | Regular expression over {a,b} for strings with exactly two b's. `a*ba*ba*` | abb, aaabbaa, baaaabaa | aaa, abbbbbbb, abbaabbab |
| 13 | RE→DFA (DFA) | Construct the DFA for the regular expression (a+b)*ab (Q14 holds the regular expression, Q13 the DFA). | aab, ababbaab, abababaab | aaa, ababbabb, abababbba |
| 14 | RE→DFA (RE) | Enter the regular expression (a+b)*ab in JFLAP and convert it to an NFA, then to a DFA; compare with Q13. `(a+b)*ab` | aab, ababbaab, abababaab | aaa, ababbabb, abababbba |
| 15 | Grammar | Regular (right-linear) grammar S→aS|bA, A→bA|aB, B→bB|b. Identify the language it generates (a*b+ab+) and test strings. | bab, abbbabb, aaaaaabab | aaa, abbabbaa, ababbbabb |
| 16 | Grammar→DFA (DFA) | DFA equivalent to the grammar in Q17 (strings ending with 01). | 001, 01011001, 010101001 | 000, 01011011, 010101110 |
| 17 | Grammar→DFA (Grammar) | Grammar S→0S|1S|0A, A→1. Convert it to an NFA/DFA in JFLAP and compare with Q16. | 001, 01011001, 010101001 | 000, 01011011, 010101110 |
| 18 | Mealy | Mealy machine over {0,1} that outputs 1 whenever the input sequence 101 has just been completed (overlaps allowed), else 0. | 101→001, 10101→00101, 1101→0001 | — |
| 19 | Moore | Moore machine over {0,1} that reads a binary number (MSB first) and outputs its remainder when divided by 3 (state outputs 0, 1, 2). | 110 → 0 (6 mod 3), 101 → 2 (5 mod 3), 1111 → 0 (15 mod 3) | — |
| 20 | CFG | Context-free grammar for L = { a^(2n) b^n | n ≥ 1 }. | aab, aaaabb, aaaaaabbb | aaa, ababbabb, abababbab |

## Files

- `39_Sanika_Mejari_Q01_DFA_Even_0s_Odd_1s_14-11-2026.jff`
- `39_Sanika_Mejari_Q02_DFA_1s_Divisible_by_3_14-11-2026.jff`
- `39_Sanika_Mejari_Q03_DFA_Exactly_Two_0s_14-11-2026.jff`
- `39_Sanika_Mejari_Q04_DFA_Ends_with_100_14-11-2026.jff`
- `39_Sanika_Mejari_Q05_DFA_Starts_1_Ends_0_14-11-2026.jff`
- `39_Sanika_Mejari_Q06_DFA_Contains_110_14-11-2026.jff`
- `39_Sanika_Mejari_Q07_DFA_Ends_with_00_or_11_14-11-2026.jff`
- `39_Sanika_Mejari_Q08_NFA_Third_Symbol_from_Right_is_1_14-11-2026.jff`
- `39_Sanika_Mejari_Q09_DFA_Contains_001_or_110_14-11-2026.jff`
- `39_Sanika_Mejari_Q10_DFA_Exactly_One_Substring_00_14-11-2026.jff`
- `39_Sanika_Mejari_Q11_Regular_Expression_Ending_14-11-2026.jff`
- `39_Sanika_Mejari_Q12_Regular_Expression_Exactly_Two_b_14-11-2026.jff`
- `39_Sanika_Mejari_Q13_RE_to_DFA_DFA_14-11-2026.jff`
- `39_Sanika_Mejari_Q14_RE_to_DFA_Regular_Expression_14-11-2026.jff`
- `39_Sanika_Mejari_Q15_Regular_Grammar_14-11-2026.jff`
- `39_Sanika_Mejari_Q16_Grammar_to_DFA_DFA_14-11-2026.jff`
- `39_Sanika_Mejari_Q17_Grammar_to_DFA_Grammar_14-11-2026.jff`
- `39_Sanika_Mejari_Q18_Mealy_Machine_14-11-2026.jff`
- `39_Sanika_Mejari_Q19_Moore_Machine_14-11-2026.jff`
- `39_Sanika_Mejari_Q20_CFG_for_a_2n_b_n_14-11-2026.jff`
