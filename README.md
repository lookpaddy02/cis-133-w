# JavaScript reference guide

Value	Type
""	string
0	number
1	number
"0"	string
"1"	string
[]	object
{}	object
null	object
undefined	undefined
NaN	number
Infinity	number
console	object
console.log	function
document	object
document.write	function
true	boolean
false	boolean
--------------------------
Operation	Result
"2" + "5" =	25
"2" + 5 =	25
"2" * "5" =	10
"2" * 5 =	10
"2" / "5" =	0.4
"2" / 5 =	0.4
"2" - "5" =	-3
"2" - 5 =	-3
"5" % "2" =	1
"5" % 2 =	1
---------------------------
Order of Operations	Result
10 + 5 % 2 =	11
(10 + 5) % 2 =	1
10 * 5 % 2 =	0
10 * (5 % 2) =	10
-----------------------------
Conditional (ternary)	Result
0 == 1 ? "fish" : "duck"	duck
(0 == 1) ? "fish" : "duck"	duck
0 == (1 ? "fish" : "duck")	false
---------------------------------------
Value	Truthy/Falsy
0	Falsy
1	Truthy
2	Truthy
"0"	Truthy
"1"	Truthy
"2"	Truthy
"cow"	Truthy
""	Falsy
null	Falsy
undefined	Falsy
NaN	Falsy
Infinity	Truthy
[]	Truthy
[0]	Truthy
{}	Truthy
{vegetable: "cabbage"}	Truthy
------------------------------------------
Short Circuit Evaluation	Result
"dog" || "cat" || "cow"	dog
"dog" && "cat" && "cow"	cow
