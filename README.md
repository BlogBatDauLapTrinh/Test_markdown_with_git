<p>Markdown là một ngôn ngữ có chức năng tương tự như HTML để viết các văn bản nhưng có syntax dễ học hơn. Và có thể bạn đang sử dụng nhưng không hề biết, đó chính là định dạng file của readme trong Github.</p>

### Header - Đầu đề 

|Markdown           |HTML      |Kết quả|
|-------------------|-----------------------|-------------------|
|# Header 1         |```<h1>Header 1</h1>```| <h1> Header 1</h1>|
|## Header 2        |```<h2>Header 2</h1>```| <h2> Header 2</h2>|
|### Header 3       |```<h3>Header 3</h1>```| <h3> Header 3</h3>|
|##### Header 4      |```<h4>Header 4</h1>```| <h4> Header 4</h4>|

>Lưu Ý : sau dấu # cần có 1 khoảng trắng

### Paragraphs - Đoạn văn 

##### Markdown 
```
Đây là 1 ví dụ của paragraph
```
##### HTML
```
<p>Đây là 1 ví dụ của paragraph</p>
```
##### Kết quả 

Đây là 1 ví dụ của paragraph


### Break - Xuống dòng

##### Markdown 
```
This is the first line.  
And this is the second line.
```
##### HTML

```
<p>This is the first line.<br>
And this is the second line</p>
```
##### Kết quả

This is the first line.  
And this is the second line.

### Bold - In đậm

##### Markdown 
```html
Love **is** bold
```
##### HTML
```
Love <strong> is </strong> bold
```
##### Kết quả 

Love <strong>is</strong> bold

#### Italic - Chữ nghiêng

##### Markdown 
```
A *cat* meow
```

##### HTML
```
A <em> cat </em>meow
```
##### Kết quả

A <em>cat</em> meow

### Italic and Bold Kết hợp cả nghiêng và in đậm

##### Markdown 
```
A ***cat*** meow
```
##### HTML
```
A <em><strong> cat  </strong>\</em>meow
```
##### Kết quả

A <em><strong>cat</strong></em> meow

### Blockquotes - 1 Khối  

##### Markdown 
```
>Câu thứ nhất
>
>Câu thứ hai
>
>Câu thứ ba
```
##### HTML
```
<blockquote>
    Câu thứ nhất<br>
    Câu thứ hai<br>
    Câu thứ ba<br>
</blockquote>
```
##### Kết quả
>Câu thứ nhất
>
>Câu thứ hai
>
>Câu thứ ba
</blockquote>

### Nested blockquote - Các block lồng nhau

##### Markdown
```
> Quote ở tầng 1
>
>> Quote ở tầng 2
>
>>> Quote ở tầng 3
```
##### Kết quả

> Quote ở tầng 1
>
>> Quote ở tầng 2
>
>>> Quote ở tầng 3

### Blockquote các thành phần khác

##### Markdown 
```
> ###### Đầu đề nè
>
> - item thứ nhất
>
> - item thứ hai

>>  *Ok* đây là blog  **Bất Đầu Lập Trình**
```
##### Kết quả

> ###### Đầu đề nè
>
> - item thứ nhất
> - item thứ hai
>
>  *Ok* đây là blog  **Bất Đầu Lập Trình**

### Ordered Lists - Săp xếp có số thứ tự

##### Markdown 
```
1. item số 1
2. item số 2
3. item số 3
4. item số 4
```

##### HTML

```
<ol>
<li>item số 1</li>
<li>item số 2</li>
<li>item số 3</li>
<li>item số 4</li>
</ol>
```

##### Kết quả

1. item số 1
2. item số 2
3. item số 3
4. item số 4


##### Markdown 

```
1. item số 1
2. item số 2
3. item số 3
    1. item con
    2. item con
4. item số 4
```
##### HTML

```
<ol>
<li>item số 1</li>
<li>item số 2</li>
<li>item số 3
<ol>
<li>item con</li>
<li>item con</li>
</ol>
</li>
<li>item số 4</li>
</ol>
```

##### Kết quả

1. item số 1
2. item số 2
3. item số 3
    1. item con
    2. item con
4. item số 4

### Unordered Lists - Sắp xếp không có thứ tự

##### Markdown

```
- item số 1
- item số 2
- item số 3
- item số 4
```

##### HTML

```
<ul>
<li>item số 1</li>
<li>item số 2</li>
<li>item số 3</li>
<li>item số 4</li>
</ul>
```

##### Kết quả

- item số 1
- item số 2
- item số 3
- item số 4
### Code Blocks - Khối chứa code

##### Markdown    
```
    <html>
      <head>
      </head>
    </html>
```
##### HTML
```
<code>
    <html>
      <head>
      </head>
    </html>
</code>
```
##### Kết quả

    <html>
      <head>
      </head>
    </html>
### Images - Hình ảnh

##### Markdown
```
1. Đây là hình từ pokemon black 2
2. Game này để luyện tiếng anh hơi đỉnh.

    ![pokemon black](https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)
3. Tải game về rồi chơi nào.
```

##### HTML
```
<ol>
<li> Đây là hình từ pokemon black 2</li>
<li> Game này để luyện tiếng anh hơi đỉnh </li>

<img src="https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg" alt="pokemon black">

<li> Tải game về rồi chơi nào </li>
</ol>
```
##### Kết quả

1. Đây là hình từ pokemon black 2
2. Game này để luyện tiếng anh hơi đỉnh.

    ![pokemon black](https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)
3. Tải game về rồi chơi nào.

### Code - Code trong câu

##### Markdown 
```
Tại terminal ấn `nano`
```

##### HTML
```
Tại terminal ấn <code>nano</code>
```
##### Kết quả

Tại terminal ấn <code>nano</code>

### Escaping Backticks
##### Markdown
```
``Sử dụng `code` trong markdown``
```
##### HTML
```
code>Sử dụng `code` trong markdown</code>
```

##### Kêt quả

``Sử dụng `code` trong markdown``
### Horizontal Rules - Đường kẻ ngang kết thúc hàng

##### Markdown

```
***

---
____________________________
```

##### HTML
```
<hr>
```
##### Kết quả

<hr>

### Links with title - Link mà chưa tiêu đề

##### Markdown 
```
Blog tôi đang viết tên là  [Bắt Đầu Lập Trình](https://batdaulaptrinh.com "The best blog ever")
```

##### HTML
```
Blog tôi đang viết tên là  <a href="https://batdaulaptrinh.com" title=" The best blog ever">Bắt Đầu Lập Trình</a>
```

##### Kết quả

Blog tôi đang viết tên là  <a href="https://batdaulaptrinh.com" title=" The best blog ever">Bắt Đầu Lập Trình</a>

### URLs and Email Addresses

##### Markdown
```
<https://www.batdaulaptrinh.com>

<batdaulaptrinh@gmail.com>
```
##### HTML
```
<a href="https://www.batdaulaptrinh.com">https://www.batdaulaptrinh.com</a>

<a href="mailto:batdaulaptrinh@gmail.com">gửi email cho tôi</a>
```
##### Kết quả

<a href="https://www.batdaulaptrinh.com">https://www.batdaulaptrinh.com</a>

<a href="mailto:batdaulaptrinh@gmail.com">gửi email cho tôi</a>

### Formatting Links

##### Markdown
```
Đọc tổng kết[`ở đây`](#tổng kết)
```

##### HTML
```
Đọc tổng kết <a href="#tổng kết"><code>ở đây</code></a>
```

##### Kết quả

Đọc tổng kết <a href="#t%E1%BB%95ng-k%E1%BA%BFt"><code>ở đây</code></a>

### Formatting the First Part of the Link

>Lưu ý: Cần phải đặt đường link được trỏ tới ở đâu đó trong bài viết

[Learn-3000-words][1]

[Practise-listening][2]

[1]: https://batdaulaptrinh.com/qua-trinh-hoc-3000-tu-vung-tieng-anh-cua-minh/
[2]: https://batdaulaptrinh.com/qua-trinh-luyen-nghe-tieng-anh-cua-minh/ "Luyện nghe"

### Linking Images

##### Markdown
```
[![Phiêu lưu cùng pokemon](https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg "Xem ảnh pokemon nè")](https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)
```
##### HTML
```
<a href="https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg"><img src="https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg" alt="Phiêu lưu cùng pokemon" title="Xem ảnh pokemon nè"></a>
```
##### Kết quả

<a href="https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg"><img src="https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg" alt="Phiêu lưu cùng pokemon" title="Xem ảnh pokemon nè"></a>

### Kết hợp HTML và Markdown 

```
This **word** is bold. This <em>word</em> is italic.
```

##### Kết quả

This <strong>word</strong> is bold. This <em>word</em> is italic.

### Lệnh được dùng nhiều nhất trong bài - fenced code

##### Markdown
<pre>
```
Đây là fenced code
```
</pre>
##### HTML

<pre>
Đây là fenced code
</pre>

### Sử dụng \ để bỏ qua các ký tự đặc biệt

##### Ví dụ
```
\*a*
\'a'
\# h1
```
##### Kết quả

\*a*

\'a'

\# h1

Có thể bỏ qua các ký tự khác nữa

### Tổng kết

##### Bảng tóm tắt

|Markdown           |HTML      |Kết quả|
|-------------------|-----------------------|-------------------|
|\# Header 6         |```<h6>Header 1</h6>```| <h6> Header 6</h6>|
|a paragraph         |```<p>a paragraph</p>```| <p>a paragraph</p>|
|enter         |```<br>```| xuống dòng|
|\*\*bold**         |```<strong>bold<strong>```| <strong>bold</strong>|
|\*italic*         |```<em>italic<em>```| <em>italic</italic>|
|\*\*\*italic + bold***         |```<em><strong>italic + bold </strong><em>```| <em><strong>italic + bold</strong></em>|
|>blockquote         |```<blockquote>blockquote</blockquote>```|<blockquote>blockquote</blockquote>|
|1.ordered list         |```<ol><li>ordered list</li></ol>```| <ol><li>ordered list</li></ol>|
|- unorderlist         |```<ul><li>ordered list</li></ul>```|<ul><li>ordered list</li></ul>|
| \tab  codeblock        |```<code><html>codeblock</html></code>```| <code><html>codeblock</html></code>|
|\![pokemon black]\(https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)         |```<img src="https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg" alt="pokemon black">```| ![pokemon black](https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)|
|\`code inline`         |```<code>code inline</code>```|`code inline` |
|\``balckticks``        |```<code>blackticks</code>```| <code>blackticks</code>|
|\----         |```<hr>```| <hr>|
|\[Bắt Đầu Lập Trình](https://batdaulaptrinh.com "The best blog ever") có title         |```<a href="https://batdaulaptrinh.com" title=" The best blog ever">Bắt Đầu Lập Trình</a>```| [Bắt Đầu Lập Trình](https://batdaulaptrinh.com "The best blog ever") có title|
|\[Bắt Đầu Lập Trình](https://batdaulaptrinh.com) không title         |``` <a href="https://batdaulaptrinh.com">Bắt Đầu Lập Trình</a> không title```| <a href="https://batdaulaptrinh.com">Bắt Đầu Lập Trình</a> không title|
|\<https://www.batdaulaptrinh.com>       |```<a href="https://www.batdaulaptrinh.com"> https://www.batdaulaptrinh.com</a>```| <a href="https://www.batdaulaptrinh.com">https://www.batdaulaptrinh.com</a>|
|\<batdaulaptrinh@gmail.com>         |```<a href="mailto:batdaulaptrinh@gmail.com"> gửi email cho tôi</a>```|<a href="mailto:batdaulaptrinh@gmail.com"> gửi email cho tôi</a>|
|\[Learn-3000-words]\[1]        |```None```| [Learn-3000-words][1]|
|\[![Phiêu lưu cùng pokemon]\(https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg "Xem ảnh pokemon nè")]\(https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)|```<a href="https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg"><img src="https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg" alt="Phiêu lưu cùng pokemon" title="Xem ảnh pokemon nè"></a>```| [![Phiêu lưu cùng pokemon](https://icon-library.com/images/click-here-arrow-icon/click-here-arrow-icon-4.jpg "Xem ảnh pokemon nè")](https://www.redbrick.me/wp-content/uploads/2020/09/pokemon-black.jpg)|
|\```fenced code\```         |```<pre>fenced code</pre>```| <pre>fenced code</pre>|
|\\# h1         |```None```| \# h1|
|This \**word** is bold. This &lt;em&gt;word&lt;/em&gt; is italic.    |```None```| This **word** is bold. This <em>word</em> is italic.|
##### Nhận xét

Và trên đây là một số syntax cơ bản để sử dụng markdown. Và nếu chỉ sử dụng ở múc cơ bản thì markdown có ưu thế tuyệt đối. Nhưng nếu muốn cusotm được tốt hơn thì HTMl lại hỗ trợ đa dạng hơn. Ví dụ font chữ, màu sắc, hoặc là chỉnh sửa kích cỡ hình ảnh hiển thị.
<p>Bạn có thể tải bài viết này dưới dạng Markdown từ link <a href="https://github.com/Huythanh0x/Test_markdown_with_git" target="_blank" rel="noreferrer noopener">https://github.com/Huythanh0x/Test_markdown_with_git</a></p>
