# 单选框

```html
 <input type="radio" name="checktime" value="2"> <label>半小时自动巡检</label>
 <input type="radio" name="checktime" value="1" checked> <label>半小时自动巡检</label>
```

## 说明：

* type input类型  input可以是多种类型 单选框时必须为radio
* name 一组单选框的名字 js中通过该值找到单选框
* value  js获取的值
* ckecked 默认选中
* js获取当前选中的值

```javascript
function checkout() {
           $(":radio").click(function(){
             alert("您是..." + $(this).val());
         });
     }
获取单选框的值

$('input:radio:checked').val()；
$("input[type='radio']:checked").val();
$("input[name='id']:checked").val(); 建议使用第一个
```

# label

修改label的值

```javascript
   function checkout() {
         var div=document.getElementById('ckecktime');
         div.innerHTML =formatDate(new Date().getTime());
   }
```

