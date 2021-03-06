
# Java ESC/POS Print Utility  
  


----------


This utility runs a server on port 7655 and accepts post request with json as follow:  
  
```json  
{"type":"INVOICE","nameOfPrinter":"Epson","content":"<CTL_LF>HEADER<TXT_ALIGN_CT><DIV><CTL_LF><DIV>", "printerSize": 58}  
```  
This will print the value of **content** passed json using the printer with name **Epson**.
Printer Size is used to set the value of **divider** and **Horizontal Tab**.


----------
## Available Tags

| Tag | Value |
| ------------- | ------------- |
| CTL_LF  | Print and line feed  |
| CAN_HT  | Cancel Horizontal Tab  |
| HT  | Horizontal Tab |
| LINE_SPACE_24  | Set the line spacing at 24  |
| LINE_SPACE_30  | Set the line spacing at 30 |
| SELECT_BIT_IMAGE_MODE  | Image  |
| HW_INIT  | Printer hardware Clear data in buffer and reset modes |
| CD_KICK_2  | Cash Drawer Sends a pulse to pin 2 |
| CD_KICK_5  | Cash Drawer Sends a pulse to pin 5 |
| PAPER_FULL_CUT  | Full cut paper  |
| PAPER_PART_CUT  | Partial cut paper  |
| TXT_NORMAL  | Normal text |
| TXT_2HEIGHT  | Double height text  |
| TXT_2WIDTH  | Double width text |
| TXT_4SQUARE  | Quad area text  |
| TXT\_UNDERL\_OFF  | Underline font OFF  |
| TXT\_UNDERL\_ON  | Underline font 1-dot ON  |
| TXT\_UNDERL2\_ON  | Underline font 2-dot ON  |
| TXT\_BOLD\_OFF  | Bold font OFF  |
| TXT\_BOLD\_ON  | Bold font ON  |
| TXT\_FONT\_A  | Font type A  |
| TXT\_FONT\_B  | Font type B  |
| TXT\_ALIGN\_LT  | Left justification  |
| TXT\_ALIGN\_CT  | Center justification  |
| TXT\_ALIGN\_RT  | Right justification  |
| LEFT_MARGIN  | Left Margin  |
| TWO_HT  | Two Horizontal Tabs  |
| THREE_HT  | Three Horizontal Tabs  |
| DIV  | Divider Line  |

----------

## ScreenShots

> Sits nicely in task bar

![Alt text](screenshots/Screenshot_2018-03-10_11-05-07.png?raw=true "Task bar")


> Logs commands sent

![Alt text](screenshots/Screenshot_2018-03-10_11-06-05.png?raw=true "GUI")