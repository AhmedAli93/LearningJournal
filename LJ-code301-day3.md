# Learning Journal

We can then access the url parameters automatically on the ctx object by referencing ctx.params.id

/user/:id/:cool/:turkey
localhost:3000/user/3456/hi/coolturkey

ctx.params.id = 3456
ctx.params.cool = hi
ctx.params.turkey = coolturkey 

 - MiddleWare
 - PageJS
 - Identify useful urls for an app, and be able to implement those routes given the new library presented.
 - Recognize other server technologies such as Node, new dependencies