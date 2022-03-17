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

|          Input           |         Output         |
| ------------------------ | ---------------------- |
|    Blair, Bristow, 24    |    Blair Bristow 24    | 
|    Lamar, Jackson, 25    |    Lamar Jackson 25    | 
|      Billy, Bob, Joe     |     Billy Bob Joe      | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>
      This program creates an Array entitled person based on the firstName, lastName, and age values 
      passed to it by the user. This program does not have any built in way to verify if an actual 
      age is given, either by reading the string or requiring a number, so any string given to the 
      function would be saved as the age. 
    </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
