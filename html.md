# html

- <link/>

  ```html
  <link rel = "stylesheet/shortcut icon..." type = "text/css" href = "css/1.css">
  ```

  

- <style/>

- <script/>

- a

  ```html
  <a href = "http://www.baidu.com">content</a> &nbsp;
  
  href = "#12"锚点
  ```

- img

  ```html
  <a href = "">
  <img src="c:/nantong/a.jpg" style="height=12px;width=132px"/  alt = "" title="">
  </a>
  
  ```

  

- p/h1~h6(块级标签)/div<白>

  ```html
  <p>
      this is paragraph 1
      <br/>
  </p>
  ```

- span(行内)

- div

- input

  ```html
  <form action = "http://localhost:11212/index" method = "GET/POST">
  	<input type="text/passwrod/submit/reset/button..." value="123" name = "user"/>    
      A <input type="radio" name = "gender" value = "1"/>
      B <input type="radio" name = "gender" value = "2"/>
      C <input type="radio" name = "gender" value = "3"/>   
      <!--用name + value来区分不同的选择-->
  	<input type = "file" name = "fname"/> + from[attr](enctype = "multipart/form-data")
      
      <textarea name="">abcdefg</textarea> #默认值是在中间的，而不是自闭和的
  
      <select name="" size = 10 multipul="multipul"> #默认是1，这样就可以多选了#多选
  		<optgroup label=" ">
      	    <option value = "1"></option>
  	        <option value = "2"></option>        
          </optgroup>
  
          <option value = "3" slected = "selected"></option>        #设置默认值
      </select>
      
  </form>
  
  ```

- ul/li

  ```html
  <ul>
      <li></li>
      <li></li>
      <li></li>
  <ul>
  <ol>#有序的
      
  </ol>
  
  <dl>
      
  </dl>
  ```

- table

  ```html
  <table border="1">
      <tr>
      	<td></td>
          <td></td>
          <td></td>
      </tr>
  </table>
  colspan/rowspan
  ```

- label

  ```html
  <label for="username">content</label>
  <input id="username" type="text" name="user"/>
  ```
