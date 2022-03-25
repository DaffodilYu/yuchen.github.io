---
title: "CMD Shell"
collection: coding
type: "Cmd Shell "
permalink: /coding/cmd
venue: " University of Naples &quotFederico II&quot, Department of Physics"
date: 2022-03-25
location: "Napoli, Italy"
---

## Some tips:

1. Rename

To rename a single file, use the command **Rename-Item "old-file-name.extension" "new-file-name.extension"** and press **Enter**.

To rename multiple files, input the following command and press **Enter**: **Dir | %{Rename-Item $_ -NewName ("batch-rename-files{0}.jpg" -f $nr++)}**

```c
ls *.csv | Rename-Item -NewName {$_.name -replace "Default","VOD"}

ls *.dat | Rename-Item -NewName {$_.name -replace "Rvs","R"}
ls *.dat | Rename-Item -NewName {$_.name -replace "Vg","V"}
ls *.dat | Rename-Item -NewName {$_.name -replace "_D",""}
ls *.dat | Rename-Item -NewName {$_.name -replace "2021_","21_T"}

```
