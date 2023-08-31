# et-library-booklist

Book List of ET-Library

英文|English [中文|Chinese](README_CHS.md)

## To post a new book

### Method 1 (Use GitHub Pull Request)

If you know how to open a pull request, please refer to the current booklist.json format and insert your post. Then open a pull request.  
**Attention: Your pull request should include additional information(except those in the file change) including the download address(for us mankind to download so web drives are acceptable).**
Read Method 2 to know optional info.

### Method 2 (Use Email)

Send an email to publish_etl@tsstudio.top.

#### The email **must** include:

Name of the book.  
Authors of the book. (**Must** include all authors on the cover, could include others)  
ISBN of the book.  
Publisher of the book.  
Revision of the book.  
The pdf file or the download link.

#### The email **could** include

The barcode of the book.
The cover image of the book.

## The coding pattern of download links

A download link can be divided into 2 parts: Endpoint and index. The final link is Endpoint + index.  
An endpoint is a mirror of the library. Starting with `https://` and ending with `/`.

To calculate the index of a book itself: book/
`sha256(ISBN+revision)`

To calculate the index of a book cover(optional): cover/
`sha256(ISBN+revision)`
