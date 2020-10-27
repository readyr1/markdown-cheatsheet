# markdown-cheatsheet
  # Header
  # This is an ``<h1>`` tag
  ## This is an ``<h2>`` tag
  ###### This is an ``<h6>`` tag

  LISTS
 UNORDERED
* Item 1.  
* Item 2.  
 * Item 2a.  
 * Item 2b.  
 
 ORDERED.  
1. Item 1.   
2. Item 2.  
3. Item 3.  
 * Item 3a.  
 * Item 3b.  

BLOCKQUOTES
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.
As Grace Hopper said:
 I've always been more interested
 in the future than in the past.

TASK LISTS
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), 
**formatting**, and <del>tags</del> 
supported
- [x] list syntax required (any 
unordered or ordered list supported)

 ![image](https://images.alphacoders.com/789/thumb-350-789452.jpg)

### Images
#### Syntax
```
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
```
As same as links, but add an exlamation mark (!) before opening square bracket.  
The square bracket contains `alt` for the image and parenthesis contains image source.  
Image source can be either a location from the local machine or any valid image URL.  
the last part contains additional information about the image shown when use hovers through it.
#### Appearence
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
 

### Linking Image
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

#### Syntax
```
 [![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)
```

#### Appearance
[![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)


### Tables

#### Syntax
```git
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |
```

#### Appearance
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |


### CheckBox

#### Syntax
```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```

#### Appearance

* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected


### Block Quotes

#### Syntax
```git
> This is a block quoted text
```

#### Appearance
> This is a block quoted text


### Horizontal Line
#### Syntax
```git
***
___
--- 
```
#### Appearance
All three will be rendered as:
___


### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
1. Whitespace (Four Spaces Indentation)
1. Fenced Code Block (Three Backticks *or* Tildes)

#### Syntax
    `this` is an example of inline code.
    
    '''
    console.log('Used backticks to show snippets')
    '''
    
    console.log('four whitespace works too!')
    
    
#### Appearance
`this` is an example of inline code.
```
console.log('Used backticks to show snippets')
```
    console.log('four whitespace works too!')
    

### Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

#### Syntax
    ```js
    console.log('javascript')
    ```
    
    ```python
    print('python')
    ```
    
    ```java
    System.out.println('java')
    ```
       
    ```json
    {
      "firstName": "Kaushal",
      "lastName": "Joshi
      "age": 18
    }
    ```



#### Appearance 
```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```

```json
{
  "firstName": "Kaushal",
  "lastName": "Joshi",
  "age": 18
}
```
####Emphasis
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

####Insert a break between lines</br>
You can add </br>
```git
<br>
```
between lines to insert a break

This text has a break in between that will make the second part </br> to be written onto the next line. 

