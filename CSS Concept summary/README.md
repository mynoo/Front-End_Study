<div align="center" id="top">
<img height="270px" width="270px" src="./logo.png"><br>
  <h1>๐๊ฐ๋ ๋ฐ ๊ถ๊ธ์ฆ ์ ๋ฆฌ</h1>
</div>

***

## !important
* CSS๋ ๊ฐ์ ์์ฑ์ ์ฌ๋ฌ ๋ฒ ์ ์ํ์ ๋, ๋์ค์ ์ค์ ํ ๊ฐ์ด ์ ์ฉ๋๋ค.
* ๋์ค์ ์ค์ ํ ๊ฐ์ด ์ ์ฉ๋์ง ์๊ฒ ํ๋ ค๋ฉด ์์ฑ๊ฐ ๋ค์ !important๋ฅผ ๋ถ์๋๋ค.
```
p {
  color: red !important;  <-- red๋ก ์ ์ฉ
}
p {
  color: blue;
}
```

## display ์์ฑ
#### block
- ๊ธฐ๋ณธ์ ์ผ๋ก ๋๋น 100%(width:100%)์์ฑ์ ๊ฐ์ง๊ณ  ์๋ค.
- enter ํค๋ฅผ ๋๋ฅด์ง ์์๋๋ฐ๋ ์ค๋ฐ๊ฟ์ ํ ํจ๊ณผ๋ฅผ ๊ฐ์ง๊ณ  ์๋ค.
<img width="80%" src="https://user-images.githubusercontent.com/83212040/125604686-0c7b6184-f9d6-4349-bda5-46fc9a07fbc5.png"/>

#### inline
- ์ปจํ์ธ ๋ฅผ ๋ฑ ๊ฐ์์ ๋์ ํฌ๊ธฐ๋ง ๊ฐ๊ฒ๋๋ค. 
- blockํ๊ทธ์ ๋ค๋ฅด๊ฒ ์ค๋ฐ๊ฟ์ด ๋์ง ์๊ณ , ๋ฐ๋์ ์ปจํ์ธ ๋ฅผ ๊ฐ์ธ๊ฒ ๋๊ณ , ํฌ๊ธฐ๋ฅผ ๋ณํ์ํฌ ์ ์๋ค.
<img width="8%" src="https://user-images.githubusercontent.com/83212040/125604981-6232abe1-e912-4203-b22d-39fa9846407c.png"/>

#### inline-block
- inline๊ณผ block์ ํน์ฑ์ ํฉ์ณ๋์ ์์ฑ์ด๋ค. 
- ๊ธฐ๋ณธ์ ์ผ๋ก๋ inline์ ์์ฑ์ ์ง๋๊ณ  ์์ง๋ง, ์์๋ก ํฌ๊ธฐ๋ฅผ ๋ฐ๊ฟ์ค ์ ์๋ค.
<img width="40%" src="https://user-images.githubusercontent.com/83212040/125605033-73d898ec-da43-430a-a8e4-d7a78526e8d6.png"/>



## font

color : #999;

font-family : dotum, tahoma ;     /* ํฐํธ์ด๋ฆ */

font-weight : bold     /* normal, lighter, border */

font-style : normal ;     /* italic, oblique */

font-size : 12px ;     /* 1.5em, 14pt, 95% */

text-variant : small-caps ;     /* ์ํ๋ฒณ ์๋ฌธ์๋ฅผ ์์ ๋๋ฌธ์๋ก ํ์ */

text-transform : uppercase ;     /* uppercase(์ํ๋ฒณ๋๋ฌธ์), capitalize(์ํ๋ฒณ ์ฒซ๊ธ์ ๋๋ฌธ์), lowercase(์ํ๋ฒณ ์๋ฌธ์) */

text-decoration : none ;    /* line-through, overline, underline */

text-align : center ;     /* left, right, justify */

text-indent : 999px ;     /* ๋ค์ฌ์ฐ๊ธฐ */

white-space : nowrap ;     /* ์๋ ์ค๋ฐ๊ฟ ๋ง๊ธฐ */

word-break : break-all ;     /* break-all (๋ฌธ์ ๋จ์ ๋๊ธฐ), keep-all(๋จ์ด ๋จ์ ๋๊ธฐ) */

word-spacing : 3px ;     /* ๋จ์ด ๊ฐ๊ฒฉ ์กฐ์  */

letter-spacing : -1px ;     /* ์๊ฐ ์กฐ์  */

line-height : 150% ;      /* ์ค๊ฐ๊ฒฉ */

line-mode : disabled ;     /* ์๋ฌธ๋ง ์๋ ฅ */




