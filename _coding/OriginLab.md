---
title: "Originlab"
collection: coding
type: "originlab"
permalink: /coding/originlab
venue: " University of Naples &quotFederico II&quot, Department of Physics"
date: 2022-03-25
location: "Napoli, Italy"
---

Using Originlab script **Labtalk**

1. Save the figure using Labtalk script

```
expGraph type:=png path:="C:\xx\xx\xx\xx" filename:="TEST" ;
```

2. Insert or delete rows in columns

```
wks.deleteRows(3); // Delete the third row in all columns
wks.deleteRows(3, 5); // Delete 5 rows beginning with the third row in all columns:
wks.deleteRows(3, 5, 2); // Delete 5 rows beginning with the third row in columns from the second to the end
wks.deleteRows(3, 5, 2, 4); // Delete 5 rows beginning with the third row in columns 2 to 4

wks.insertRows(3); // Insert a row in front of the third row in all columns
wks.insertRows(3, 5); // Insert 5 rows in front of the third row in all columns
wks.insertRows(3, 5, 2); // Insert 5 rows in front of the third row in columns from the second to the end
wks.insertRows(3, 5, 2, 4); // Insert 5 rows in front of the third row in columns 2 to 4
```

3. Figure size

Maximum Single column: ACS 85mm, APS 86mm.

Thus, the 42 mm x 40 mm is always to be used.
