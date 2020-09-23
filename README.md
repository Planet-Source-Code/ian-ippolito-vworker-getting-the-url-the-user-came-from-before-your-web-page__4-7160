<div align="center">

## Getting the URL the user came from before your web page\!


</div>

### Description

This is a great tip that is NOT documented in the Interdev help..how to get the referring URL of the browser. You can use this to track what traffic you are getting and from where.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Beginner
**User Rating**    |3.8 (19 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-getting-the-url-the-user-came-from-before-your-web-page__4-7160/archive/master.zip)





### Source Code

Note: Just typing something in your browser and then typing your test page URL will NOT cause this to work. Your browser must follow an actual link from a domain other than your own to your test page to work. Otherwise it returns the empty string.</b><BR>
<BR>
<BR>
response.write "You came from " & Request.ServerVariables("HTTP_REFERER")<BR>
<BR>
<BR>
That's it...enjoy!

