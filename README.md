# mvseq

Rename files in a directory to sequential names, while keeping original filename order, with optional prefix/suffix.

Only changes files in the directory specified (non-recursive).

# Usage

```bash
mvseq images --padzeros --padlen 2 --suffix ".jpg"
```

Changes:
```
images/12.jpeg    ->  images/01.jpg
images/27.jpg     ->  images/02.jpg
images/abc.jpeg   ->  images/03.jpg
images/eeefa.jpg  ->  images/04.jpg
```
