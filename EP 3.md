# ๐ง **Ep 3. ํ๋ก๊ทธ๋๋ฐ 1**

## ๐ง **์ค๋ ๋ฐฐ์ธ ๋ถ๋ถ**
- ์ข๋ชฉ ์ฝ๋๋ฅผ ์๋ ฅ๋ฐ๊ณ , ์ด๋ค ์ข๋ชฉ์ ๊ธฐ๋ก์ ์ฌ๋์ง ์๋ด ํ๋ ๋ถ๋ถ

## ๐ง **์ฝ๋**
```py
record = []
event = ['33', '22', '44', '55', '66', '77', '3BLD', 'FMC', 'OH',
         'Clock', 'Mega', 'Pyra', 'Skewb', 'SQ-1', '4BLD', '5BLD', 'MBLD']
worst = 0.0001
best = 1000000.0

ev = int(input('์ข๋ชฉ ์ฝ๋: '))
print('๋น์ ์ด ์ ํํ ์ข๋ชฉ์', event[ev-1], '์๋๋ค.')
print('')
```

## ๐ง **์ฝ๋ํด์ค**
- ๊ธฐ๋ก ์๋ ฅ๊ณต๊ฐ
```py
record = [] '''ํ๋ธ ๊ธฐ๋ก์ด ๋ค์ด๊ฐ ๊ณต๊ฐ. [] ์์๋ ์๋ฌด ๊ฒ๋ ๋ค์ด๊ฐ๋ฉด ์๋จ.'''
```
- ์ข๋ชฉ
```py
event = ['33', '22', '44', '55', '66', '77', '3BLD', 'FMC', 'OH',
         'Clock', 'Mega', 'Pyra', 'Skewb', 'SQ-1', '4BLD', '5BLD', 'MBLD'] '''WCA ๊ณต์ธ์ข๋ชฉ'''
```

- ๊ธฐ๋ก
```py
worst = 0.0001 '''๊ฐ์ธ ์ต์ ๊ธฐ๋ก(Ao 5)'''
best = 1000000.0 '''๊ฐ์ธ ์ต๊ณ ๊ธฐ๋ก(Ao 5)'''
```

- ์ข๋ชฉ ์ฝ๋ ์๋ ฅ๋ถ
```py
ev = int(input('์ข๋ชฉ ์ฝ๋: ')) '''์ข๋ชฉ ์ฝ๋ ์๋ ฅ'''
print('๋น์ ์ด ์ ํํ ์ข๋ชฉ์', event[ev-1], '์๋๋ค.') '''์ ํํ ์ข๋ชฉ ์๋ด'''
print('')
```



## ๐ง **Credit**
- Maker : Leo Kim([@llleeo0421](https://github.com/llleeo0421))
  - E-mail : dev.augustleo@gmail.com
  - GitHub : [@August-Leo-0805](https://github.com/August-Leo-0805)
  - Twitter : [@llleeo0421](https://www.twitter.com/llleeo0421)
  - Linkedin : [@augustleo](https://www.linkedin.com/in/augustleo)
  - Blog : [๋  ์ฐพ์์จ ๋ฏ์  ์ฌํ์](https://llleeo0421.tistory.com)
