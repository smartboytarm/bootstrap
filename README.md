# bootstrap
<!-- --------------
id: bootstrap_tamdna
title: bootstrap_tamdna
-------------- -->


##### nav bootstrap
navbar-light dinh nghia do **tuong phan** cua  mau chu

#### margin or space bootstrap
thuong gap o the ul
mr-auto 0 1 2 3 4 5 auto
mr = mx my
mx-3 = 1rem
my-3 = 1rem
mr = margin-right
ml = margin-left

> Dung margin cho khoang cach giua the voi the

#### reboot la file cua bootstrap
:x: bootstrap dung scss
> margin-bottom: 0!important; overlap old css affect

#### color
linear-gradient() 
+ 1 param: direction

#### inline-block
+ inline: khong rot hang
+ block: xet kich thuoc cho before vaf aftr

#### slider
- - - goi la indicator
__tao cung id cho cac items thi slider se co 2 mui ten previous arrow and next arrow__

+ hieu ung khac la fade: carousel-fade
```<div id="movieCarousel" class="carousel slide carousel-fade" data-ride="carousel">```
data-ride="carousel" : de chuyen carousel

#### dinnh nghia lop
khi dinh nghia chung 1 the 
.carousel-indicators li.active {
    
}
phai li.active <=> dinh lien nhau

#### grid trong bootstrap 
ban than cua class .row da co flex do bootstrap qui dinh --> tu dong flex