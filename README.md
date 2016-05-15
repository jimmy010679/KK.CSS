# KKK.CSS

ㄎㄎㄎ.CSS (科科科)

Front-end Framework

基於Flexbox所製作的框架

##版本訊息

**最新版本：** v1.0.1

**歷史訊息**
- 2016/03/04 - v1.0.0  (正式發布)
- 2016/03/05 - v1.0.1  (修正IE11、10所產生跑板問題)

##未來
輕量框架，學習練習用途 o'_'o



努力趕工中.....xD

##使用方式
**引入CSS**
``` html
<link rel="stylesheet" href="./css/kkk.css">
 ```
 
##版型結構

12欄制

**基本3欄**
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
* [flexbugs](https://github.com/philipwalton/flexbugs)
* [IE (11), padding on child elements #3](https://github.com/philipwalton/flexbugs/issues/3)
