<p>Markdown là một ngôn ngữ có chức năng tương tự như HTML để viết các văn bản nhưng có syntax dễ học hơn. Mình thường dùng để viết Readme trong Git và Colab. Và hôm nay thì mình mới phát hiện blog mình cũng hỗ trỡ Markdown nên mình viết luôn bài này để thực hành.</p>

### Header - Đầu đề 

|Markdown|HTML      |Kết quả|
|--------|----------|-----|
|# Header 1|\<h1>Header 1\</h1>| <h1> Header 1</h1>
|## Header 2|\<h2>Header 2\</h1>| <h2> Header 1</h2>
|### Header 3|\<h3>Header 3\</h1>|<h3> Header 1</h3>
|#### Header 4|\<h4>Header 4\</h1>|<h4> Header 1</h4>

*Lưu Ý :* sau dấu # cần có 1 khoảng trắng

### Paragraphs - Đoạn văn 

#### Markdown 
>Đây là 1 ví dụ của paragraph

#### HTML
><p>Đây là 1 ví dụ của paragraph</p>

#### Kết quả 
>Đây là 1 ví dụ của paragraph

### Break - Xuống dòng

#### Markdown 

>This is the first line.  
>And this is the second line.

#### HTML

>\<p>This is the first line.\<br><br>
>And this is the second line.\</p>

#### Kết quả
>This is the first line.  
>And this is the second line.

### Emphasis - Nhấn mạnh

### ok

### Bold - In đậm

#### Markdown 
>Love **is** bold

#### HTML
>Love \<strong> is \</strong> bold

#### Kết quả

>Love <strong>is</strong> bold

#### Italic - Chữ nghiêng

#### Markdown 
>A *cat* meow


#### HTML
>A\<em> cat \</em>meow

#### Kết quả

>A <em>cat</em> meow

### Italic and Bold Kết hợp cả nghiêng và in đậm

#### Markdown 
>A ***cat*** meow


#### HTML
>A\<em><strong> cat \</strong>\</em>meow

#### Kết quả

>A ***cat*** meow

### Blockquotes - 1 Khối  

#### Markdown 
<blockquote>

\>Câu thứ nhất

\>Câu thứ hai

\>Câu thứ ba
</blockquote>

#### HTML
<blockquote>

&#x3C;blockquote&#x3E;<br>
C&#xE2;u th&#x1EE9; nh&#x1EA5;t<br>
C&#xE2;u th&#x1EE9; hai<br>
C&#xE2;u th&#x1EE9; ba<br>
&#x3C;/blockquote&#x3E;
</blockquote>

#### Kết quả

<blockquote>
<blockquote>
Câu thứ nhất

Câu thứ hai

Câu thứ ba
</blockquote>
</blockquote>

### Nested blockquote - Các block lồng nhau

### Markdown

>\> Quote ở tần 1
>
>\>> Quote ở tầng 2
>
>\>>> Quote ở tầng 3

#### Kết quả

>> Quote ở tần 1
>
>>> Quote ở tầng 2
>
>>>> Quote ở tầng 3

### Blockquote với các thành phần khác

#### Markdown 

>\> ##### Đầu đề nè
>
>\> - item thứ nhất
>
>\> - item thứ hai
>
>\>  *Ok* đây là blog  **Bất Đầu Lập Trình**

#### Kết quả

> ##### Đầu đề nè
>
> - item thứ nhất
> - item thứ hai
>
>  *Ok* đây là blog  **Bất Đầu Lập Trình**
