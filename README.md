# GoAdmin Official Themes

- [adminlte](https://github.com/Lifelong-Study/themes/tree/master/adminlte)
- [sword](https://github.com/Lifelong-Study/themes/tree/master/sword)

[中文介绍](./README_CN.md)

## How to use

- Import the theme
- Set in the global configuration of GoAdmin

```go

package main

import (
	...
	_ "github.com/Lifelong-Study/themes/adminlte"
	...
)

func main()  {

	...

	cfg := config.Config{
    		...

    		Theme: "adminlte",

    		...
    	}

	...

}

```

## How to modify and make it work

Use the Makefile under each theme directory.