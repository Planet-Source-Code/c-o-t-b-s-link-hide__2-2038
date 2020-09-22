<div align="center">

## Link Hide


</div>

### Description

If you want to hide your links from the status bar use this script <--very easy
 
### More Info
 
Paste this code into the < head > of your document and it wall display a permanent massge in the status bar.

To change what is displayed just simply change the 'DISPLAYS THIS IN STATUS BAR' part.Enjoy


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[C\.O\.T\.B\.S](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/c-o-t-b-s.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/c-o-t-b-s-link-hide__2-2038/archive/master.zip)





### Source Code

```
<script language="JavaScript">
var message = 'DISPLAYS THIS IN STATUS BAR';
statuss();
function statuss()
{
window.status = message;
timerID = setTimeout("statuss()", 25);
}
</script>
```

