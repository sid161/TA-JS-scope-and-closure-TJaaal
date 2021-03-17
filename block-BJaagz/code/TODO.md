1. Implement `forEach` array method using Array.reduce

- `forEach` accepts two parameter array and callback
- It does not return anything
- It should work exactly like array `forEach` method

function forEach(arr,cb) {
  arr.reduce((acc,cv) =>{
    cb(cv, index, arr);
  })
}

```js
function forEach() {}

forEach(['Sam', 'Jon', 'Arya'], (name, i, arr) =>
  console.log(name + name, i, arr)
);
```

2. Implement `map` array method using Array.reduce

- `map` accepts two parameter array and callback
- It returns same size of array
- It should work exactly like array `map` method

```js
function map(arr,cv) {
  return arr.reduce((acc,cv) => {
    acc.push(cb(cv,i,arr));
    return acc;

  },[])
}

map(['Sam', 'Jon', 'Arya'], (name) => name + name); // ['SamSam', 'JonJon', 'AryaArya']
```

3. Implement `filter` array method using Array.reduce

- `filter` accepts two parameter array and callback
- It returns same size or smaller array
- It should work exactly like array `filter` method

```js
function filter(arr,cb) {
  return arr.reduce(acc,cv,i,arr) => {
    if(cb(cv,i,arr)){
      acc.push(cv);
    }
    return acc;
  } ,[])
}
filter(['Sam', 'Jon', 'Arya'], (name) =>
  name.startsWith('S')
); // ['Sam']
```
