---
title: "Announcement"
date: 2021-02-23T09:22:17-05:00
draft: false
tags: ["Framework","Hugo"]
categories: ["Framework"]

---
This post is just a test to verify the functional components of the new blog framework before migrating the old posts
``` JavaScript

function toProper(str) {
  return str.replace(
    /(\w*\W*|\w*)\s*/g,
    function(txt) {
    return(txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase())
    }
  );
}
const properName = toProper("jane doe");
```
 ``` csharp

 string ToProperName(this string input)
 {
    CultureInfo culture = Thread.CurrentThread.CurrentCulture;
    TextInfo textInfo = culture.TextInfo;
    return textInfo.ToTitleCase(txt);     
 }
var message = "hello C#";
var properString = message.ToProper());
 ```

 ``` python
def toProper(s):
	return s.title()

print(toProper("hello python"))

```

``` go
package main
import (
		"fmt"
		"strings"
		)
func main(){
	fmt.Println(strings.Title("hello Go"))
	}

```
