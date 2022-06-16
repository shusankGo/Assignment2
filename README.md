Q1> Given a string s, return the longest palindromic substring in s.

Example 1:

Input: s = "babad"
Output: "bab"
Explanation: "aba" is also a valid answer.
Example 2:

Input: s = "cbbd"
Output: "bb"

---

Q2> Write a JavaScript program to list the properties of a JavaScript object.
Sample object:
var student = {
name : "David Rayy",
sclass : "VI",
rollno : 12 };
Sample Output: name,sclass,rollno

---

Q3> Write a JavaScript program to group data depending upon the key passind

let groupData = [
{ name: "vpg-10", id: 1, storage: "30 GB" },
{ name: "vpg-12", id: 2, storage: "42 GB" },
{ name: "vpg-14", id: 3, storage: "38 GB" },
{ name: "vpg-10", id: 4, storage: "31 GB" },
{ name: "vpg-12", id: 5, storage: "72 GB" },
]

Expected Output for key = "name"

// result : {
// vpg-10:[
// { name: "vpg-10", id: 1, storage: "30 GB" },
// { name: "vpg-10", id: 4, storage: "31 GB" },
// ],
// vpg-12:[
// { name: "vpg-12", id: 2, storage: "42 GB" },
// { name: "vpg-12", id: 5, storage: "72 GB" },
// ],
// vpg-14:[
// { name: "vpg-14", id: 3, storage: "38 GB" },
// ],
// }

Note: Key will be passed to the method as groupDataMethod("name")

---

Q4> Create a function which will return the value at path in an Object

\*/

// const obj = {
// a: 1,
// b: 2,
// c: {
// d: 4,
// e: {
// i: 'Hey'
// }
// },
// j: 'k'
// }

Output for getValuebyKey(obj, 'c.e.i') => should return Hey
