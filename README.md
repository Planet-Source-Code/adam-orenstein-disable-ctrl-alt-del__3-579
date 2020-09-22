<div align="center">

## Disable Ctrl Alt Del


</div>

### Description

This is a very simple function i made to allow you to disable and re-enable Ctrl-Alt-Del. It's short code but works perfectly. =)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Adam Orenstein](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/adam-orenstein.md)
**Level**          |Beginner
**User Rating**    |4.4 (31 globes from 7 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/adam-orenstein-disable-ctrl-alt-del__3-579/archive/master.zip)





### Source Code

```

void DisableCtrlAltDelete(bool bDisabled)
{
SystemParametersInfo (SPI_CREENSAVERRUNNING,bDisabled,
NULL,NULL);
}
```

