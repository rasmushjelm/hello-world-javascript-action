# hello-world-javascript-action

practicing making custom github action.  
  

# Hello World javascript action
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## INPUTS

## who-to-greet
**Required** Thename of the person to greet. Default "World"

## Outputs

## `time`
The time we greeted you.

## Example usage
uses: actions/hello-world-javascript-action@v1.1  
with:  
    who-to-greet: 'Mona the Octocat'  
