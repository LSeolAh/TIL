## #Lv.1 76501

[https://school.programmers.co.kr/learn/courses/30/lessons/76501](https://school.programmers.co.kr/learn/courses/30/lessons/76501)

## #Lv.1 12935

[https://school.programmers.co.kr/learn/courses/30/lessons/12935](https://school.programmers.co.kr/learn/courses/30/lessons/12935)

<aside>
π‘ splice() β λ°°μ΄μ κΈ°μ‘΄ μμλ₯Ό μ­μ  λλ κ΅μ²΄νκ±°λ μλ‘μ΄ μμλ₯Ό μΆκ°νμ¬ λ°°μ΄μ λ΄μ© λ³κ²½

</aside>

```jsx
const months = ['Jan', 'March', 'April', 'June'];
months.splice(1, 0, 'Feb');
// Inserts at index 1
console.log(months);
// Expected output: Array ["Jan", "Feb", "March", "April", "June"]

months.splice(4, 1, 'May');
// Replaces 1 element at index 4
console.log(months);
// Expected output: Array ["Jan", "Feb", "March", "April", "May"]

---

let arr = ['a', 'b', 'b', 'c'];

// μμ 'b' μ­μ 
for(let i = 0; i < arr.length; i++) {
  if(arr[i] === 'b')  {
    arr.splice(i, 1);
    i--;
  }
}

document.writeln(arr); // ['a', 'c']
```
