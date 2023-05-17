## 1-Browser environment, specs
## 1-Brauzer muhiti, texnik xususiyatlari

```js
function sayHi() {
  alert("Hello");
}

// global functions are methods of the global object:
// global funktsiyalar global ob'ektning usullari:
window.sayHi();
```
---------------
```js
alert(window.innerHeight); // inner window height : ichki oyna balandligi
```
-----------
**DOM (Document Object Model)**
**DOM (Hujjat obyekti modeli)**

```js
// change the background color to red
document.body.style.background = "red";

// change it back after 1 second
// 1 soniyadan keyin uni qayta o'zgartiring
setTimeout(() => document.body.style.background = "", 1000);
```
```
DOM faqat brauzerlar uchun emas**
DOM spetsifikatsiyasi hujjatning tuzilishini tushuntiradi va uni boshqarish uchun ob'ektlarni taqdim etadi. DOM-dan foydalanadigan brauzer bo'lmagan asboblar ham mavjud.

Masalan, HTML-sahifalarni yuklab oladigan va ularni qayta ishlovchi server tomonidagi skriptlar ham DOM-dan foydalanishi mumkin. Ular spetsifikatsiyaning faqat bir qismini qo'llab-quvvatlashi mumkin.
```

