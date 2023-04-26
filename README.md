### Array methods
#### arr.map()

const arr = [1, 2, 3, 4, 5, 6];
const obj = {
    a: 2,
    b: 8,
    c: 3,
    d: 9,
    e: 10,
    f: 21
}

const result = Object.entries(obj).map(([key, value]) => {
    return [key, value * 2];
})
console.log(result);

RESULT:
[
    [ 'a', 4 ],
    [ 'b', 16 ],
    [ 'c', 6 ],
    [ 'd', 18 ],
    [ 'e', 20 ],
    [ 'f', 42 ]
  ]
---
