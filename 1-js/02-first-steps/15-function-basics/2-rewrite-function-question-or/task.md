الأهمية: 4

---

# اعد كتابة الدالة باستخدام '?' أو '||'

الدالة التالية ترجع `true` إذا كانت قيمة `age` أكبر من `18`.

وإلا فهي تطلب تأكيد وترجع نتيجته:

```js
function checkAge(age) {
  if (age > 18) {
    return true;
  } else {
    return confirm('Did parents allow you?');
  }
}
```

اعد كتابتها للحصول على نفس النتيجة ولكن بدون `if` وفي سطر واحد.

اعد كتابة `checkAge`:

1. باستخدام معامل علامة الاستفهام `?`
2. باستخدام OR `||`
