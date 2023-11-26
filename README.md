<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Kriptografi</h1>
  <img src="images/theory.jpg" alt="Logo" width="400" >
</div>

<!-- TABLE OF CONTENTS -->
<details style="margin-top: 24px;">
  <summary>Table of Contents</summary>
      <ul>
          <li><a href="#about-the-prototype">About The Prototype</a></li>
          <li><a href="#MonoAlphabet">MonoAlphabet</a></li>
          <li><a href="#PolyAlphabet">PolyAlphabet</a></li>
          <li><a href="#PolyAlphabet-Block">PolyAlphabet Block</a></li>
          <li><a href="#PolyAlphabet-Character">PolyAlphabet Character</a></li>
          <li><a href="#PolyAlphabet-Zigzag">PolyAlphabet Zigzag</a></li>
          <li><a href="#MonoAlphabet-Slide">MonoAlphabet Slide</a></li>
          <li><a href="#Vigenere-Numerical">Vigenere Numerical</a></li>
          <li><a href="#Vigenere-Alphabet">Vigenere Alphabet</a></li>
          <li><a href="#Play-Fair">Play Fair</a></li>
          <li><a href="#Transposition">Transposition</a></li>
          <li><a href="#Transposition-Zigzag">Transposition Zigzag</a></li>
          <li><a href="#Transposition-Triangle">Transposition Triangle</a></li>
          <li><a href="#Transposition-Spiral">Transposition Spiral</a></li>
          <li><a href="#Transposition-Diagonal">Transposition Diagonal</a></li>
      </ul>
</details>

<!-- ABOUT THE PROJECT -->
## About The Prototype

Prototipe kumpulan teknik kriptografi. Kriptografi bisa pula diartikan sebagai suatu ilmu atau seni menjaga keamanan pesan. Untuk mencoba, silahkan gunakan file .jar yang sudah terlampir.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## MonoAlphabet

![MonoAlphabet][monoalphabet]

```java
 // siapkan teks yang akan di cipher dan jumlah pergeseran
 MonoAlphabet monoalphabet = new MonoAlphabet(text,range);
 String encrypt = monoalphabet.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## PolyAlphabet

![PolyAlphabet][polyalphabet]

```java
 // siapkan teks yang akan di cipher dan teks kunci
 PolyAlphabet polyalphabet = new PolyAlphabet(text, key);
 String encrypt = polyalphabet.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## PolyAlphabet Block

![PolyAlphabet Block][polyalphabet-block]

```java
 // siapkan teks yang akan di cipher, jumlah karakter dalam satu block, dan satu atau lebih teks kunci
 PolyAlphabetBlock polyalphabetBlock = new PolyAlphabetBlock(text, key, range);
 String encrypt = polyalphabetBlock.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## PolyAlphabet Character

![PolyAlphabet Character][polyalphabet-character]

```java
 // siapkan teks yang akan di cipher dan satu atau lebih teks kunci
 PolyAlphabetCharacter polyAlphabetCharacter = new PolyAlphabetCharacter(text, array_key);
 String encrypt = polyAlphabetCharacter.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## PolyAlphabet Zigzag

![PolyAlphabet Zigzag][polyalphabet-zigzag]

```java
 // siapkan teks yang akan di cipher dan satu atau lebih teks kunci
 PolyAlphabetZigzag polyAlphabetZigzag = new PolyAlphabetZigzag(text, array_key);
 String encrypt = polyAlphabetZigzag.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## MonoAlphabet Slide

![MonoAlphabet Slide][monoalphabet-slide]

```java
 // siapkan teks yang akan di cipher dan jarak alphabet melakukan pergeseran
 MonoAlphabetSlide monoAlphabetSlide = new MonoAlphabetSlide(text, range);
 String encrypt = monoAlphabetSlide.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Vigenere Numerical

![Vigenere Numerical][vigenere-numerical]

```java
 // siapkan teks yang akan di cipher dan jarak alphabet melakukan pergeseran
 VigenereNumerical vigenereNumerical = new VigenereNumerical(text, range);
 String encrypt = vigenereNumerical.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Vigenere Alphabet

![Vigenere Alphabet][vigenere-alphabet]

```java
 // siapkan teks yang akan di cipher dan teks kunci
 VigenereAlphabet vigenereAlphabet = new VigenereAlphabet(text, key);
 String encrypt = vigenereAlphabet.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Play Fair

![Play Fair][play-fair]

![Play Fair][play-fair-2]

```java
 // siapkan teks yang akan di cipher
 PlayFair playFair = new PlayFair(text);
 String encrypt = playFair.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Transposition

![Transposition][transposition]

```java
 // siapkan teks yang akan di cipher dan jumlah kolom
 Transposition transposition = new Transposition(text, array_key);
 String encrypt = transposition.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Transposition Zigzag

![Transposition Zigzag][transposition-zigzag]

```java
 // siapkan teks yang akan di cipher dan jumlah baris
 TranspositionZigzag transpositionZigzag = new TranspositionZigzag(text, array_key);
 String encrypt = transpositionZigzag.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Transposition Triangle

![Transposition Triangle][transposition-triangle]

```java
 // siapkan teks yang akan di cipher
 TranspositionTriangle transpositionTriangle = new TranspositionTriangle(text);
 String encrypt = transpositionTriangle.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Transposition Spiral

![Transposition Spiral][transposition-spiral]

```java
 // siapkan teks yang akan di cipher
 TranspositionSpiral transpositionSpiral = new TranspositionSpiral(text);
 String encrypt = transpositionSpiral.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Transposition Diagonal

![Transposition Diagonal][transposition-diagonal]

```java
 // siapkan teks yang akan di cipher
 TranspositionDiagonal transpositionDiagonal = new TranspositionDiagonal(text);
 String encrypt = transpositionDiagonal.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LINK BADGE & IMAGE-->
<!-- https://github.com/Ileriayo/markdown-badges -->

[theory]: images/theory.jpg
[monoalphabet]: images/monoalphabet.png
[polyalphabet]: images/polyalphabet.png
[polyalphabet-block]: images/block.png
[polyalphabet-character]: images/character.png
[polyalphabet-zigzag]: images/zigzag.png
[monoalphabet-slide]: images/slide.png
[vigenere-numerical]: images/number.png
[vigenere-alphabet]: images/alphabet.png
[play-fair]: images/playfair.png
[play-fair-2]: images/playfair-2.png
[transposition]: images/transposition.png
[transposition-zigzag]: images/transposition-zigzag.png
[transposition-triangle]: images/triangle.png
[transposition-spiral]: images/spiral.png
[transposition-diagonal]: images/diagonal.png
