
```js
két egymás utáni r betű
grep "r{2}"
1-3 ig terjedő sorozatban lévő r betűk egymás mellett
grep "r\{1,3\}"
ahol A betűvel kezdődik a sor eleje
grep "^A"
b betúvel végződik a sor
grep "b$"
magánhangó van benne
grep "[aeiou]"
a magánhangzók van benne negáltja (mássalhangzók)
grep "[^aeiou]"
ahol van szóköz
grep "\ "
szóköz utáni betű a
grep "\ a"
```
