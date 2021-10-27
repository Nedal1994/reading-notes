# Read01 Summary

## Array map

![map](https://www.freecodecamp.org/news/content/images/size/w2000/2021/03/javascript-map-function.png)

Mapping in Javascript is based on creating a new array with the results of calling a function for every array element which calls the provided function once for each element in an array, in order.

## Array reduce

![reduce](https://dmitripavlutin.com/static/c3793b2edfc8fc4cf02f66458679d155/05127/cover-3.png)

The reduction method is based on executing a reducer function for each value of an array which returns a single value which is the function's accumulated result.

## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

### .then()

` request
   .get('https://example.com/search')
   .then(res => {
      // res.body, res.headers, res.status
   })
   .catch(err => {
      // err.message, err.response
   });
`

### async/await

`async function () {
  try {
    var response = await request.post('/user/').send({foo: 4})
  } catch (err) {
    // do something with err...
  }
}`

**Are all callback functions considered to be Asynchronous? Why or Why Not?**

Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. For example there's forEach in Array. It iterates over each item and calls the function once per item.