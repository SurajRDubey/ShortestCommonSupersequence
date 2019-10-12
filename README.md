# ShortestCommonSupersequence
Implementation of Shortest Common SuperSequence Algorithm In Python

## How Does it work...

We need to find a string that has both strings as subsequences and is shortest such string. If both strings have all characters different, then result is sum of lengths of two given strings. If there are common characters, then we don’t want them multiple times as the task is to minimize length. Therefore, we fist find the longest common subsequence, take one occurrence of this subsequence and add extra characters.
