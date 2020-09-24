<div align="center">

## Avoiding use of null


</div>

### Description

How do you avoid the "Invalid use of null" error when reading null values from a database?If you try to retrieve a null value (empty field) from a database, you will get the error: "Invalid use of Null". Here is one way to get around this problem: ..
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[VB FAQ](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vb-faq.md)
**Level**          |Unknown
**User Rating**    |4.7 (52 globes from 11 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Databases/ Data Access/ DAO/ ADO](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/databases-data-access-dao-ado__1-6.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vb-faq-avoiding-use-of-null__1-92/archive/master.zip)





### Source Code

TextBox.Text = MyTest.Fields("TestFld") & ""

