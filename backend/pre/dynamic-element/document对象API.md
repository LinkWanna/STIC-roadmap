当涉及到前端开发，`document` 对象是非常重要的，它代表了整个HTML文档。在这里，我会详细列出一些 `document` 对象中常用的方法和属性：

## 常用的方法：
1. `getElementById(id)`：通过元素的 ID 获取对应的 DOM 元素。
2. `getElementsByClassName(className)`：通过类名获取一组具有相同类名的 DOM 元素。
3. `getElementsByTagName(tagName)`：通过标签名获取一组特定标签的 DOM 元素。
4. `querySelector(selector)`：使用选择器（类似于CSS选择器）获取匹配的第一个 DOM 元素。
5. `querySelectorAll(selector)`：使用选择器获取匹配的所有 DOM 元素。

6. `createElement(tagName)`：创建一个指定标签名的新 DOM 元素。
7. `appendChild(node)`：将一个节点添加为另一个节点的子节点。
8. `removeChild(node)`：从父节点中移除指定的子节点。
9. `setAttribute(attribute, value)`：设置元素的属性值。
10. `removeAttribute(attribute)`：移除元素的指定属性。
11. `addEventListener(event, callback)`：为元素添加事件监听器。
12. `removeEventListener(event, callback)`：移除元素的事件监听器。
13. `innerHTML`：获取或设置元素的 HTML 内容。
14. `innerText`：获取或设置元素的文本内容，不包括 HTML 标签。
15. `classList`：获取包含元素类名的 DOMTokenList 对象，可用于添加、删除和切换类名。


## 常用的属性：
1. `title`：获取或设置页面的标题。
2. `head`：获取文档的头部（`<head>`）。
3. `body`：获取文档的主体部分（`<body>`）。
4. `documentElement`：获取文档的根元素，通常是 `<html>` 元素。
5. `domain`：获取或设置文档的域名部分。
6. `referrer`：获取引用页面的 URL。
7. `URL`：获取文档的完整 URL。
8. `forms`：获取页面中所有表单元素的集合。
9. `images`：获取页面中所有图片元素的集合。
10. `links`：获取页面中所有链接元素的集合。

这只是 `document` 对象中一部分常用的方法和属性。理解并熟练运用这些方法和属性将有助于你在前端开发中更加灵活地操作 DOM 以及与页面交互。如果你需要更详细的解释或其他问题，请随时提问。