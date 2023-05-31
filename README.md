
# Altklausuren Sammlung Angewandte Informatik

## Structured List

You can find a list of all Files of the Repository here: [Link](list.md)

---
## How to commit


1. clone the repository
```bash
git clone https://github.com/EduTechVault/Altklausuren.git
```
2. change into the repository
```bash
cd Altklausuren
```

3. set the local variables in order to commit as Anonymous
```bash
git config user.name 'Anonymous'
git config user.email ''
```

4. disable commit signing to avoid getting busted
```bash
git config commit.gpgsign false
```

5. commit your changes
```bash
git add .
git commit -m 'Added some Exams'
git push
```

---

## What to commit

Please commit any Exams or Exam-like documents as *.pdf or *.docx document.

The Naming convention is as follows:
```
<Year>_<ModuleNr>_<Dozent(en)>_<Document-Type>_<Other-usefull-stuff>.pdf
```

e.g:
* 2069_A69_Musterman_Musterfrau_Klausur.pdf
* 2069_A69_Musterman_Nachholklausur.pdf
* 2069_A69_Musterman-Doppelname_Klausur.pdf
* 2069_A69_Probeklausur.pdf
