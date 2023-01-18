# Flattening-arrays
 
function flattenES6(arr) {
 return [].concat(...arr);
}
var arrL1 = [1, 2, [3, 4]];
console.log(flattenES6(arrL1)); // [1, 2, 3, 4]
