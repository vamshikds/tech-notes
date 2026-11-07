Basics of Google Colab note taking:
# Colab Basics
## 1. Headings:
The following are used for various heading types:
```
# Chapter Title (Heading 1)
## Major Section (Heading 2)
### Subsection (Heading 3)
```
## 2. Table of Contents:
Colab automatically generates a Table of contents in the left sidebar based on headings; #, ##, ###
## 3. Tables
We can create clean data tables using pipes (|) and hyphens (-). Sample is as below:
```
|Sl. No. |Name|Roll No.|Maths Marks|Chemistry Marks|
| :--- |:---| :---:|---:|---:|
|1. |Vamshi|30|85|95|
|2. |Krishna|25|25|98|
|3. |Srilakshmi|28|58|67|
```
:--- is left alligned, ---: is right alligned, :---: is center alligned-
Output of the above table is as follows:
|Sl. No. |Name|Roll No.|Maths Marks|Chemistry Marks|
| :--- |:---| :---:|---:|---:|
|1. |Vamshi|30|85|95|
|2. |Krishna|25|25|98|
|3. |Srilakshmi|28|58|67|
## 4. Text Stylling:
Bold: `**bold text**` -> **bold text**  
italics: `*italic text*` -> *italic text*  
Inline code: `` `code_variable` `` -> `inline code`  
Qoute: ` > this is a quote.` -> 
> this is a quote.
Bullet points: use either `+` or `-` or `*`:
`+ Bullet with +` ->: 
  + Bullet with +.
`- Bullet with -` ->:
  - Bullet with -.
`* Bullet with *` ->:
  * Bullet with *.
to create a sub bullet just make two spaces or 4 spaces then follow the bullet process or click one tab:
* First bullet line.
  * Second bullet line.