快速開始
===========

Note: 這是一個靜態的基於mdwiki修改的markdown wiki，非常適合快速搭建簡單的wiki系統，如果你想瞭解更多詳情，請訪問 [https://github.com/Dynalon/mdwiki/](https://github.com/Dynalon/mdwiki/)

Markdown基本語法
--------

MDWiki 支持最基本的Markdown語法，同時支持直接書寫HTML和語法高亮、表格.

一個簡單的例子:

```
標題
=======

子標題
----------

 * 列表
 * 列表
    1. sdf
    2. 列表項

這裡是一個連接 [fifsky](http://fifsky.com)，顯示一個`tag`

如果不想顯示圖片的話:

![圖片Alt](http://placekitten.com/g/250/250)

 > 這裡是引用的內容
 > 這裡是引用的內容

```

創建鏈接
-------

站外鏈接:

    [fifsky](http://www.fifsky.com)

wiki鏈接:

    [Go to index](index.md)

wiki鏈接會自動添加hash `#!` :

[Go to index](index.md)

##表格
如果你想顯示表格，可以參照下面的例子:

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

- - - -

##語法高亮

一段php語法高亮的例子:

    ```php
    <?php
        $a = true;
        if($a){
            echo 'hello world';
        }
    ?>
    ```

render:

```php
<?php
    $a = true;
    if($a){
        echo 'hello world';
    }
?>
```

支持語言列表如下:

|Language       |Keyword      |
|---------------|-------------|
|Bash           |bash         |
|C#             |csharp       |
|Clojure        |clojure      |
|C++            |cpp          |
|CSS            |css          |
|CoffeeScript   |coffeescript |
|CMake          |cmake        |
|HTML           |html         |
|HTTP           |http         |
|Java           |java         |
|JavaScript     |javascript   |
|JSON           |json         |
|Markdown       |markdown     |
|Objective C    |objectivec   |
|Perl           |perl         |
|PHP            |php          |
|Python         |python       |
|Ruby           |ruby         |
|R              |r            |
|SQL            |sql          |
|Scala          |scala        |
|Vala           |vala         |
|XML            |xml          |

##公式

你想要玩更高級的功能嗎？你可以像下面這樣

    $$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$
[gimmick: math]()    
$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$


$$ \frac{\partial \phi}{\partial x} \vert_b = \frac{1}{\Delta x/2}(\phi_0-\phi_b) $$

$$ \int u \frac{dv}{dx}\,dx=uv-\int
\frac{du}{dx}v\,dx\lim_{n\rightarrow \infty }
\left (  1 +\frac{1}{n} \right )^n
$$

> End enjoy!

