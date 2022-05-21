# Trinkerr Backend Interview

## DB cleaning

You are given a database with corrupted data and your task is to clean the database. DB has lots of redundant entries and you have to first identify the most redundant entries in the DB in order to remove them. Determine the K most redundant data in the database.


<br>


`Input`
Given an array of DB entries.

`Sample Input 1`

<pre>
<b>Input</b>: Entries = [17, 17, 17, 18, 19, 16, 19, 19, 17], k = 2

<b>Output</b>: [17, 19]

<b>Explanation</b>: 
17 occured 4 times and 19 occured 3 times.
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: Entries = [8, 1, 2, 8], k = 2


<b>Output</b>: [8, 2]

<b>Explanation</b>: 
17 occured 4 times and 19 occured 3 times.
</pre>


NOTE: 
1. K is in between 1 and no. of unique elements. <br>
2. When many elements have the same frequency, return any one of them.

---

## Place the Criminal 

You are given an array of jail lockup places where each entry is represented by 0 or 1. 0 means there is no criminal, and 1 means there is a criminal there. Criminals when placed adjacent to each other will, start fighting, which is something you have to avoid. Given K more criminals, place them in the lockup (the lockup size is fixed, and once occupied, 0 turn into 1) such that no criminal is fighting, i.e they are not adjacent. If this task is achievable, return true, false otherwise.


`Input`:
Given an array of 0s and 1s.

`Output`:
Return true if you are able to place the criminals in the lockups without them fighting. False otherwise.

`Sample Input 1`

<pre>
<b>Input</b>: Lockup: [1,0,0,0,1], k = 1

<b>Output</b>: true

<b>Explanation</b>: 
When the new criminal is placed at index 2, none of them are adjacent. 
[1, 0, 1, 0, 1]. 
Hence true
</pre>

`Sample Input 2`

<pre>
<b>Input</b>: Lockup: [1,0,0,1], k = 1

<b>Output</b>: false
</pre>


---
