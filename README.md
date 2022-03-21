# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input | Output |
| ----- | ------ |
| Green | Yellow | 
|Yellow | Red    | 
| Red   | Green  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>It takes the input of currentColor and provides an output of nextColor depending on what is entered. If a color is input that is not part of the code, an error will be returned after it exhausts all the other 'else if' options.  </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
