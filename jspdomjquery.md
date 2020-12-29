# jsp

```html
<input type="button" onclick="getData();"/>
<script>
	function getData(){
        var i = document.getElementById("dsdf");
        alert(i.value);
    }
</script>

function fun_name(params){

}
for(var i in collection){

}
dom_obj.onclick = fun_name(){
	this.xxx #指的是就是这个元素
};
dom_obj.addEventListener('click',function(){console.log("aaa"),false})# false冒泡不捕捉
```

# dom

```javascript
document.getElementById();
document.createElement('div')
elem.style.background('xxx xxx xxx')
elem.getattribute()
slem.setattribute()// 不会立马修改，使用elem.value
```

# jquery

1. 选择器
2. $('selector').each(function(index){ this.name = 12;})#index是索引的下标#this是dom要$(this)变成jquery对象
3. $('selector').prop(checked, true) #内部自己for循环，批量操作 dom是 dom_obj.checked = true;
4. $('slector').click(function(){})
5. $('selector').addClass('hide') / removeClass('hide')
