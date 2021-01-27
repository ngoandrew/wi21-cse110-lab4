What was the bug?
  Instead of actually returning the sum of num1 and num2, the function calculate sum concatenated the strings contained in num1 and num2. For example, "1" + "0" would result in 10 instead of the expected 1.

How did you fix it?
  I would use the parseInt() function to convert the strings into numbers before adding them.

1. citylots.json
2. part2.js
3. 11.7MB
4. 11.04s
5. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData()
