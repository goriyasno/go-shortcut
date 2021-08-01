# go-shortcut

Shortcut for number and bytes abbreviations

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
go get -u github.com/goriyasno/go-shortcut
```

## Usage

```go
package main
import (
	"fmt"
    "github.com/goriyasno/go-shortcut"
)
func main()  {
    fmt.Println(shortcut.KKK)
    // 1 000 000 000 
    fmt.Println(shortcut.GB)
	// 1 000 000 000 
    fmt.Println(shortcut.Billion)
	// 1 000 000 000 
}
```