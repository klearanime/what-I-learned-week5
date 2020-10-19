## what-I-learned-week5
___

### Objects
___
`Example`

1. Objects are variables that have simple values: person. Objects contain as many values put into it.

`const person = {
    firstName: 'Crystal',
    lastName: 'Young',
    age: 44,
    eyeColor: 'brown',
}`

To access the properties use the person.firstName

or

person['firstName']


### Methods
---
`Join`
  
  1. The join method returns the array as a string.  It won't change the original array:
*  `.join(specified separator)`


`Splice`

  2. The splice method adds/removes items an array, and returns the removed items: 
* `.splice(start, count)`
* `.splice(start, delete)`


`String interpolation`

 1. String interpolation is used to inject variables directly into strings.
* '`You are logged in as ${variable}, your membership status is ${variable}`'
* Use `${ }` to add variables and don't forget to wrap the string with back ticks. 
