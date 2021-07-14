# cpl
Characters per line

## Characters per line

Source | Characters per line
------ | -------------------
[Wikipedia](https://en.wikipedia.org/wiki/Characters_per_line) | 72...80
[RFC 678](https://www.rfc-editor.org/rfc/pdfrfc/rfc678.txt.pdf) | 72 on logical page
[Linus Torvalds terminal style](http://lkml.iu.edu/hypermail/linux/kernel/2005.3/08168.html) | 80
[Readability: the Optimal Line Length](https://baymard.com/blog/line-length-readability) | 50...75
[4 reasons I use large type](http://mikeyanderson.com/optimal_characters_per_line) | 45...75

## Line height

Line heignt by [Golden Ratio Typography Calculator](https://grtcalculator.com/).

Golden Ratio value is `1.61803398874989484820...`(etc.).

## Example of line

Unicode symbols are have different symbol width.

```go
package main

import "fmt"

func main() {
	for i := 0; i < 44; i++ {
		fmt.Printf("界")
	}
	fmt.Printf("\n")
	for i := 0; i < 80; i++ {
		fmt.Printf("Й")
	}
	fmt.Printf("\n")
	for i := 0; i < 80; i++ {
		fmt.Printf("&")
	}
	fmt.Printf("\n")
}
```

```
界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界界
ЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙЙ
&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&
```
