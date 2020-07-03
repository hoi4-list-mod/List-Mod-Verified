**Структура:**

  mainlist.json - Список модов.

  manifest_mod/id.json - файл манифеста мода с значением id

Example mainlist.json:
```json
[{ 
 "1" : {
   "mainfest": "mainfest_mod/1.json",
   "nameMod": "Econimic Crisis", 
 },
 "2" : {
   "mainfest": "mainfest_mod/2.json",
   "nameMod": "EaW", 
 },
 "3" : {
   "mainfest": "mainfest_mod/3.json",
   "nameMod": "KaiserReich", 
 }
}]
```

Example for mod in mainlist.json
```json
 "end_id" : {
   "mainfest": "mainfest_mod/end_id.json",
   "nameMod": "NameMod", 
 }
