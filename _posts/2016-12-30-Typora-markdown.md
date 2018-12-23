### Typora Markdown语法  

*2016-12-10 20:23:38*  

---  

**Strong**  

*Italic*  

<u>Underline</u>  

Subscript~note~  

Superscript^2^  

==highlight==  

~~Strike through~~  

:smile:  

> Blockquotes  

##### unordered list  

- item1  
- item2  


##### Tasks  

-[ ] task1  
-[ ] task 2  
-[x] task 3  

<!--Comment-->

`code`  

code fence  

```python  
f = function(){  
  print("hello")  
  pass  
}  
```  

### Table  

Left-Aligned  | Center Aligned  | Right Aligned  
:------------ | :-------------: | ------------:    
col 3 is      | some wordy text |         $1600    
col 2 is      |    centered     |           $12    
zebra stripes |    are neat     |            $1    

You can create footnotes like this[^footnote].  

[^Note]: Here is the **text\** of the ***\*footnote****.  

This is [an example](http://example.com/ "Title") inline link.  

[This link](http://example.net/) has no title attribute.  

This is [an example][1] reference-style link.  

Then, anywhere in the document, you define your link label like this, on a line by itself:  

[1]: http://example.com/	"Optional Title Here"  
