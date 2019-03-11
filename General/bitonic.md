**Challenge:** checking if an array of numbers is bitonic

**Description:** Write a function to receive an array that will _always_ only consist of numbers or be empty. Then the output from the function is a boolean where true is outputted if the array is bitonic and false if it's not.

**What Being Bitonic Is:** Being bitonic is where the numbers in the array strictly increase and then strictly decrease. This also implies that the array has to have atleast 3 elements as that's the smallest array that can strictly increase and then decrease.

**Test Suite In Javascript:**

```javascript
console.log('Should be true: ' + f([1, 2, 1]));
console.log('Should be true: ' + f([1, 5, 7, 9, 8, 2]));
console.log('Should be true: ' + f([3, 4, 5, 1]));
console.log('Should be true: ' + f([-1, 0, 3, 2]));

console.log('Should be false: ' + f([]));
console.log('Should be false: ' + f([1, 2]));
console.log('Should be false: ' + f([2, 1]));
console.log('Should be false: ' + f([1, 2, 1, 2]));
console.log('Should be false: ' + f([1, 3, 5, 7]));
console.log('Should be false: ' + f([7, 5, 3, 1]));
console.log('Should be false: ' + f([1, 5, 5, 2]));
console.log('Should be false: ' + f([5, 2, 1, 3]));
```
