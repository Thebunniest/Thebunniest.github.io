# 使用日志

## 1 增加导航栏栏目

假如想要增加导航栏的栏目，执行以下操作：

1. 在`index.html`中增加导航栏的代码部分，比如：

```html
<!-- Contact-->
    <section class="bg-gradient-primary-to-secondary-gray mt5 md5" id="contact">
        <div class="container px-5">
            <header>
                <h2 id="contact-subtitle"><i class="bi bi-envelope-fill"></i>&nbsp;CONTACT</h2>
            </header>
            <div class="main-body" id="contact-md"></div>
        </div>
    </section>
    <!-- Contact -->
```

2. 在`contents/`目录下增加对应的`md`文件，比如`contact.md`，并在其中编写内容。
3. 在`js/script.js`中的`section_names`数组中增加对应的栏目名称，比如：

```javascript
const section_names = ["home", "about", "projects", "contact"];
```
