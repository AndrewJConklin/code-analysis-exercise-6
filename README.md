# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (numbers){
  let sum = 0
  for (let number of numbers){
    sum = sum + number**2
  }

  return sum
}
```

Inputs and outputs should be valid JavaScript values!

| Input         | Output |
| [1, 2, 3]     | 14     |
| [0, 1]        | 1      | 
| [1, 2, 3, 4]  |  30    | 
|               |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an input that is an array of numberd and adds together the squares of each number in the array. The program then returns the sum of each the squares. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
