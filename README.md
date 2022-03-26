# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
|       |        | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td></td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible


## Inputs and Outputs

| Input | Output |
| :---: | :---: |
| Tiffany, Warren, 49 | {firstName:"Tiffany" lastName:"Warren" age: 49} |
| Emily, Butler, 23 | {firstName:"Emily" lastName:"Butler" age: 23} |
| Kristin, Warwick, 19 | {firstName:"Kristin" lastName:"Warwick" age: 19} |


```js

const firstName = ["Tiffany", "Emily", "Kristin"]
const lastName = ["Warren", "Butler", "Warwick"]
const age = [49, 23, 19]

function (firstName, lastName, age){
  const person = {
    firstName: firstName,		
    lastName: lastName,			
    age: age,				
  }

  return person				// firstName: Tiffany, lastName: Warren, age: 49,
					// firstName: Emily, lastName: Butler, age: 23,
					// firstName: Kristin, lastName: Warwick, age: 19 
}

```

## Summary

By using an array, it will allow multiple items to be pulled by one function.


