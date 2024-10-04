# pushZerosToEnd


let k = 0;
let arr = [4, 5, 0, 1, 9, 0, 5, 0];

 for (let i = 0; i < arr.length; i++) {
    if (arr[i] !== 0) {
      arr[k] = arr[i];
      k++;
    }
  }

 while (k < arr.length) {
    arr[k] = 0;
    k++;
  }
}
console.log(arr);
