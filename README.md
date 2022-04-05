|  Berliana Noviansyah  |     312010373    |
|-----------------------|------------------|
|       TI.20.A1        |  Pemrograan Web  |
|      Praktikum 4      |    Pertemuan 5   |

# Praktikum 4 Pertemuan 5
Pada pertemuan kali ini kita akan membahas bagaimana cara emembuat **Website Layout** dengan property **Float** dan membuat **Box Element**


# 1). Membuat dokumen HTML dengan nama lab_4_box.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Element</title>
</head>
<body>
    <header>
        <h1>Box Element</h1>
    </header>
</body>
</html>
```


# 2). Membuat Box Element

***code css***
```css
 <style>
        div{
            float: left;
            padding: 10px;
        }
        .div1{
            background: pink;
        }
        .div2{
            background: plum;
        }
        .div3{
            background: purple;
        }
    </style>
```

***code html***
```html
 <section>
        <div class="div1">Div 1</div>
        <div class="div2">Div 2</div>
        <div class="div3">Div 3</div>
    </section>
```

***Hasil outputnya:***
![membuat_box_element](img/boxelement.png)
# 3). Mengatur Clearfix Element
 
 Berikut adalah contoh code nya :
 ***code css***
 ```css
 .div4{
            background-color: palevioletred;
            clear: right;
            float: none;
        }
```


***code html***
```html
 <div class="div4">Div 4</div>
 ```

***Dan berikut adalah hasil outputnya:***
![clearfix](img/clearfix.png)


**Selanjutnya buatlah folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama home.html dan file css dengan nama style.css**


# 4). Membuat kerangka layout dengan Semantic Element

**Contoh outputnya adalah sebagai berikut :**

![membuat_layout_sederhana](img/layout_sederhana.png)


**codingnya:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Layout Sderhana</h1>
        </header>
        <nav>
            <a href="home.html">home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">about</a>
            <a href="kontak.html">kontak</a>
        </nav>
        <section id="hero"></section>
        <section id="wrapper">
            <section id="main"></section>
            <aside id="sidebar"></aside>
        </section>
        <footer>
            <p>© 2022-Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

