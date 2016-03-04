# KYJ-UI
基於Flexbox所製作的UI

版本 1.0.0

已知Bug，IE11會跑版，待修正。

趕工中.....xD

##使用方式
**引入CSS**
``` html
<link rel="stylesheet" type="text/css" href="./css/kyj-ui.css">
 ```
 
##版型結構

**基本4欄**
``` html
<div class="container">
  <div class="row">
    <div class="col">
    </div>
    <div class="col">
    </div>
    <div class="col">
    </div>
  </div>
</div>
 ```
 
 **加入不同解析度，顯示不同版型**
 ``` html
<div class="container">
  <div class="row">
    <div class="col md-4 xs-6">
    </div>
    <div class="col md-4 xs-6">
    </div>
    <div class="col md-4 xs-6">
    </div>
  </div>    
</div>
 ```
 
 **一覽表**
 
| name          | px           |
| ------------- |:-------------:|
| xs            | < 544 px      |
| sm            | < 768 px      |
| md            | < 992 px      |
| lg            | < 1200 px     |
| xl            | < 1400 px     |
| xxl           | > 1400 px     |


**重直置中**

 ``` html
<div class="container">
  <div class="row">
    <div class="col align-self-center">
    </div>
  </div>    
</div>
 ```
 or
 ``` html
<div class="container">
  <div class="row flex-center">
    <div class="col">
    </div>
  </div>    
</div>
 ```
 
 **排序**
 
 反相向
 ``` html
<div class="container">
  <div class="row dir-row_rev">
    <div class="col">
      001
    </div>
    <div class="col">
      002
    </div>
  </div>    
</div>
 ```
 
 

  
##參考資料
* [CSS Tools: Reset CSS](http://meyerweb.com/eric/tools/css/reset/)
* [Flexbox playgroung](http://codepen.io/enxaneta/pen/adLPwv)
* [Bootstrap 4 Flex Box Grid Demo](http://codepen.io/ncerminara/pen/EjqbPj/)
* [Flexbox Grid](http://flexboxgrid.com/)
  








