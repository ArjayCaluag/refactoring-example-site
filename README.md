# **Horiseon Marketing Refactor**
 The purpose of this project is to test our understanding of the structure of semantic elements. I have to ensure that the code followed semantic element logical structure and to refactor to make it more accessible to others. In the process of refactoring many HTML elements, I also had to make sure I implemented the correct changes to the CSS file while looking for opportunities to group and consolidate repetitive selectors.
<br><br>

![image](https://user-images.githubusercontent.com/52800632/101862357-05ae3b80-3b27-11eb-90a4-ad2c98a64669.png)

# **Installation**
Clone starting files onto your local computer with Gitbash
```bash
git clone [sshlink]
```
Complete refactoring changes and push onto your own Github Repository.

```bash
git add .
```
```bash
git commit -m "message"
```
```bash
git push origin main
```

# **Built With**

<ul>
    <li> HTML - The standard markup language for web pages </li>
    <li> CSS - used to describe the presentation of markup langauges such as HTML </li>
</ul>

# **Code Snippet**

```html 
<!-- Refactored <div> elements and its classes into semantic element <header> -->
            <!--Inserted the list of hyperlinks in the <nav> element in order to follow logical structure. -->
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
            <nav>
                <ul>
                    <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                    </li>
                    <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                    </li>
                    <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                    </li>
                </ul>
         </nav>
    </header>
```
```css
/*Consolidated .benefit-lead, .benefit-brand, and .benefit-cost*/
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```
# **Deployed Link**

https://arjaycaluag.github.io/refactoring-example-site/

# **Author**

Ron-Arjay Caluag

[Linkedin](https://www.linkedin.com/in/ron-arjay-caluag-00b29b182/)
<br>
[Github](https://github.com/ArjayCaluag)

# **License**

The MIT License (MIT)

Copyright (c) 2020 Ron-Arjay Caluag

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

