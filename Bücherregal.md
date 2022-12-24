# Mein Bücherregal

```dataview
TABLE WITHOUT ID
("![cover|100](" + cover + ")") as Cover,
"[[" + file.name + "|" + title + "]]" As Titel,
author As Autor,
publisher + " " + publish As Verlag
from "Books"
Where contains(owned,"owned")
```

# Meine Leseliste
```dataview
TABLE WITHOUT ID
("![cover|100](" + cover + ")") as Cover,
"[[" + file.name + "|" + title + "]]" As Titel,
author As Autor,
publisher + " " + publish As Verlag
from "Books"
Where contains(owned,"owned")
Where contains(read,"unread")
```

# Meine Wunschliste
```dataview
TABLE WITHOUT ID
("![cover|100](" + cover + ")") as Cover,
"[[" + file.name + "|" + title + "]]" As Titel,
author As Autor,
publisher + " " + publish As Verlag
from "Books"
Where contains(owned,"unowned")
```