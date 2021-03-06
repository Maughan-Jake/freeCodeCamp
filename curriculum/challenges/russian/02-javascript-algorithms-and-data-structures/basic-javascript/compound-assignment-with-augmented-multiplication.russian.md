---
id: 56533eb9ac21ba0edf2244b1
title: Compound Assignment With Augmented Multiplication
challengeType: 1
videoUrl: https://scrimba.com/c/c83vrfa
forumTopicId: 16662
localeTitle: Соединение с расширенным умножением
---

## Description
<section id='description'>
Оператор <code>*=</code> умножает переменную на число. <code>myVar = myVar * 5;</code> умножит <code>myVar</code> на <code>5</code> . Это можно переписать как: <code>myVar *= 5;</code>
</section>

## Instructions
<section id='instructions'>
Преобразуйте присвоения для <code>a</code> , <code>b</code> и <code>c</code> чтобы использовать оператор <code>*=</code> .
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>a</code> should equal <code>25</code>
    testString: assert(a === 25);
  - text: <code>b</code> should equal <code>36</code>
    testString: assert(b === 36);
  - text: <code>c</code> should equal <code>46</code>
    testString: assert(c === 46);
  - text: You should use the <code>*=</code> operator for each variable
    testString: assert(code.match(/\*=/g).length === 3);
  - text: Do not modify the code above the line
    testString: assert(/var a = 5;/.test(code) && /var b = 12;/.test(code) && /var c = 4\.6;/.test(code));

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a = a * 5;
b = 3 * b;
c = c * 10;

```

</div>

### After Tests
<div id='js-teardown'>

```js
(function(a,b,c){ return "a = " + a + ", b = " + b + ", c = " + c; })(a,b,c);

```

</div>

</section>

## Solution
<section id='solution'>

```js
var a = 5;
var b = 12;
var c = 4.6;

a *= 5;
b *= 3;
c *= 10;
```

</section>
