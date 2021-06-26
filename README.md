# tripitaka91
พระไตรปิฎกและอรรถกถาแปล ชุด 91 เล่ม ฉบับมหามกุฏราชวิทยาลัย (เล่มสีน้ำเงิน)

# Usage
Just import the files and use.  Each folder represents a book volume number. The files are organized by sutta. The files are named after the first database row number that the sutta was found in from the original database `thaimm.sqlite`

Each sutta has three files.
1. A raw file that is copied from the database
2. A converted HTML file
3. A JSON meta file

The JSON meta file contains all the metadata about the sutta. Here is an example structure.
```javascript
{
    "title": "มงคลสูตรที่ ๔",
    "subtitle": "ว่าด้วยอุดมมงคล ๓๘",
    "description": "การไม่คบคนพาล การคบบัณฑิต การบูชาบุคคลที่ควรบูชา",
    "row": 27580,
    "volume": 47,
    "volume_orig": 25,
    "page_start": 124,
    "page_end": 198,
    "item": [317, 318],
    "status": "in progress"
}
```
Note: This is a work in progress. So some files may be incomplete. Please check `status` attribute of the sutta.


## What?
This is a collection of HTML files for the Thai Tripitaka Mahamakut Buddhist University 91 Blue Books Edition. The data is converted from E-Tipitaka's (https://etipitaka.com/) database `thaimm.sqlite`

## Why?
The data in the existing form is not a well-formed HTML. It is raw text data that was scanned from the original Tripitaka physical books. As a result, the data looks and feels like a book's page. There are many extra spaces and line breaks that do not make sense to exist on a web page. This makes the Tripitaka hard to read on a screen. To make the Tripitaka easier to read, there needs to be some formatting and cleanup.

## When?
No idea. This is a work in progress since Tripitaka is huge.

## Who?
Anyone who wants to build an app that reads Tripitaka can use this.

