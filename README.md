# javascriptInterviewQuestions

//https://stackoverflow.com/questions/29640254/when-why-to-use-map-reduce-over-for-loops

forEach(): Executes a provided function(callback) once for each array element. Doesn’t return anything (undefined) but this callback is allowed to mutate the calling array.

map(): Executes a provided function(callback) once for each array element and creates a new array with the results of this executions. It cannot mutate the calling array content.

Conclution Use map() when you need to return a new array, use forEach() or for when you want to change the original array.
