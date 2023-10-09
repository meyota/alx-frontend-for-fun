# Fun with CSS
In this project, you will experiment and implement fun layout with HTML and CSS  **ONLY**!

Yes, no JavaScript!

Enjoy!
## Tasks

### 0. Sprite languages

#advanced


By using this HTML:

Explain

`<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>` 

And this image file:  [0-sprite.png](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=cfe59bdfb1af04e4ce6656a6bbd699ef93103da702c31d56239c43facf2e4ca6 "0-sprite.png")

Create  `0-styles.css`  and generate this layout:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=602f2ace54ab1d297fea2e70d635d756ebaf58ff0aece249deeffa10ce37aa8d)

You are not allowed to change the image and the HTML -  _sprite is cool!_


### 1. Move the (under)line

#advanced


By using this HTML:

Explain

`<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>` 

Create  `1-styles.css`  and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=598afc74f46930fc0abc00a08bf87a0f878ed58551fffbc9089da20d9ec8062e)

You are not allowed to change the HTML


### 2. Toggle

#advanced


By using this HTML:

Explain

`<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>` 

Create  `2-styles.css`  and generate this layout where the  `<input>`  is has this custom toggle layout:

**Checked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ebc44fd381c346f42aa144d3c65d03fc159805f16b9fbfbd728363a82e1e0031)

**Unchecked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=563566ecfed2600cd65bc2249a180b1a33f27bd1918b8d815446926f9659e7ac)

You are not allowed to change the HTML


### 3. Menu

#advanced


By using this HTML:

Explain

`<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>` 

Create  `3-styles.css`  and generate this layout/animation:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231009T083444Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=78248b483e9f8c0be576c5b140096a27a82f357ba699ad41521f66b5e5627400)

You are not allowed to change the HTML
