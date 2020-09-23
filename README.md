<div align="center">

## Alternate Row Colors


</div>

### Description

Ever want alternate the row colors of your record set? This code is the easiest way to do it!
 
### More Info
 
Alternating row colors.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Khoury](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-khoury.md)
**Level**          |Intermediate
**User Rating**    |2.9 (26 globes from 9 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-khoury-alternate-row-colors__4-6768/archive/master.zip)





### Source Code

```
if intRowColor = 0 Then
	Response.Write "<TR bgcolor=""#ddddfc"">"
	intRowColor = 1
Else
	Response.Write "<TR bgcolor=""#ffffff"">"
	intRowColor = 0
End if
```

