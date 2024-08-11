# DSA-with-JavaScript

<details >
<summary>
Write an Program Palindrome Number.
</summary>

---

```
let isPalindrome = function(number) {
return number<0 ? false: number === +number.toString().split('').reverse().join('');
}

const result = isPalindrome(123)
console.log(result)
```

</details>
<br>
