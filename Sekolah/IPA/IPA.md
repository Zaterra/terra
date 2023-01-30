---
file-created: 2023-01-12
---
tags:: #ipa
Hal yang dipelajari di ipa:
1. **Fisika**
    Mempelajari unsur-unsur dasar pembentukan alam semesta dan sifat fisik suatu benda
2. **Kimia**
     Mempelajari penyusun unsur/materi
3. **Biologi**
    Mempelajari hal tentang mahluk hidup

**Dasar**

```dataview
list 
WHERE file.folder=this.file.folder and file.name!=this.file.name
```

## Fisika
**List berdasarkan kelas sekolah**

```dataview
table kelas as "Kelas"
WHERE this.file.folder+"/Fisika" and kelas
sort kelas
```

## Kimia
**List berdasarkan kelas**
```dataview
table kelas as "Kelas"
WHERE file.folder=this.file.folder+"/Kimia" and kelas
sort kelas
```

## Biologi


