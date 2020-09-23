<div align="center">

## tool tip


</div>

### Description

simple code to show tool tip
 
### More Info
 
for the element where u want tool tip call tooltip_show('ur message') for onmouseenter

and tooltip_hide() for onmouseleave

ur lovely tool tip

amazamanet


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Pulsar180](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/pulsar180.md)
**Level**          |Beginner
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/pulsar180-tool-tip__2-3211/archive/master.zip)





### Source Code

```
<HTML>
<HEAD>
<META NAME="GENERATOR" Content="Microsoft Visual Studio 6.0">
<TITLE></TITLE>
<SCRIPT ID=clientEventHandlersJS LANGUAGE=javascript>
<!--
function tooltip_show(txttip) {
tooltip.style.posTop = event.y;
tooltip.style.posLeft = event.x;
tooltext.innerHTML = txttip;
tooltip.style.visibility = 'visible';
}
function tooltip_hide() {
tooltip.style.visibility = 'hidden';
}
//-->
</SCRIPT>
</HEAD>
<BODY>
<div id="tooltip" style="{z-index:10;visibility:hidden; position:absolute; }">
<table border="0" align="center" bgcolor="#ffffe0" cellpadding="2" cellspacing="0" style="{BORDER-WIDTH: 1px; BORDER-BOTTOM-COLOR: #ffffff; BORDER-BOTTOM-STYLE: outset; BORDER-LEFT-COLOR:#ffffff; BORDER-LEFT-STYLE:outset; BORDER-RIGHT-COLOR:#ffffff; BORDER-RIGHT-STYLE:outset; BORDER-TOP-STYLE:outset; BORDER-TOP-COLOR:#ffffff;}">
<tr>
<td align="center"><FONT face="verdana" COLOR="#000000" SIZE="1">
<span id="tooltext">
</span>
</font>
</td>
</tr>
</table>
</div>
<TABLE WIDTH=75% BORDER=1 CELLSPACING=1 CELLPADDING=1>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD></TD>
		<TD></TD>
		<TD></TD>
	</TR>
	<TR>
		<TD>d</TD>
		<TD>d</TD>
		<TD>d</TD>
	</TR>
	<div id="row20" style="{position:absolute;}" >
	<TR>
		<TD id="atd" LANGUAGE=javascript >d</TD>
		<TD><input type="text" id="name" value="" LANGUAGE=javascript onmouseenter="return tooltip_show('Enter your Name')" onmouseleave="return tooltip_hide()"></TD>
		<TD>d</TD>
	</TR>
	</div>
</TABLE>
<P>&nbsp;</P>
</BODY>
</HTML>
```

