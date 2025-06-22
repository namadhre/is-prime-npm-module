# 🔢 @namadhre/is-prime

A simple and lightweight Node.js utility to check whether a number is a prime.

---

## 📦 Installation

```bash
npm install @namadhre/is-prime
```

---

## 🚀 Usage

```javascript
const { isPrime } = require('@namadhre/is-prime');

console.log(isPrime(7));   // true
console.log(isPrime(10));  // false
```

---

## 🧠 API Reference

### `isPrime(number)`

- **Parameters:**
  - `number` (Number): The number to check.
- **Returns:** `true` if the number is prime, `false` otherwise.

---

## 📖 Example

```javascript
const { isPrime } = require('@namadhre/is-prime');

for (let i = 1; i <= 20; i++) {
  console.log(`${i} is prime? `, isPrime(i));
}
```

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Made with ❤️ by **Mahendra Chinthamgari**  
🔗 [GitHub](https://github.com/namadhre)