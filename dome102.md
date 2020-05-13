we can show all the different properties and methods attached to the document object by executing this code:
```javascript
 console.dir(document);
```
You can print out the domain you are working on
```javascript
console.log(document.domain);
```
You can access the URL
```javascript
console.log(document.URL);
```
Get title of the page
```javascript
console.log(document.title);
```
We can change the title of the page
```javascript
document.title = 'new title';
```
Get the Doctype
```javascript
console.log(document.doctype);
```
You can get the head and body tag
```javascript
console.log(document.head);
``` 
this will print out everything in the head tag to the console. same thing with the body tag.

```javascript
console.log(document.all);
```
this will give you an **array** of everything in the **html** element.