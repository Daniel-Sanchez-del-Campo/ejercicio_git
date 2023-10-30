# Este es mi primer proyecto en Git, Hala Madrid

## Cosas mixtas 
- Elemento 1
- Elemento 2
  - Subelemento 1
  - Subelemento 2



[marca](https://www.marca.com/)


| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Celda 1,1    | Celda 1,2    |
| Celda 2,1    | Celda 2,2    |




## 2

PS C:\Users\dsanc\mi_proyecto> git log master
commit d24ec652973521957502d0bd11536e481f22660a (HEAD, master)
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 16:10:23 2023 +0100

    tercer readme.md

commit 1baaa16e87057c4f4b2cabe12f7729f4b519522a
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 16:02:34 2023 +0100

    segundo readme.md

commit 158d5b6c3a5e77a77662f370e65646f6e8203475
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 15:58:50 2023 +0100

    Anadido readme.md



# Ejercicio 3 
# 2 git log master 
commit 736ee7bf17b4bc04d6eacbba5d29117adba2afb7 (master)
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 16:14:05 2023 +0100

    cuarto readme.md

commit d24ec652973521957502d0bd11536e481f22660a (HEAD)
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 16:10:23 2023 +0100

    tercer readme.md

commit 1baaa16e87057c4f4b2cabe12f7729f4b519522a
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 16:02:34 2023 +0100

    segundo readme.md

commit 158d5b6c3a5e77a77662f370e65646f6e8203475
Author: Daniel <daniel.sanchez.delcampo2003@gmail.com>
Date:   Mon Oct 30 15:58:50 2023 +0100

    Anadido readme.md



# Ejercicio 4 
## 1
PS C:\Users\dsanc\mi_proyecto> git log --oneline
e177280 (HEAD) quinto
d24ec65 (master) tercer readme.md
1baaa16 segundo readme.md
158d5b6 Anadido readme.md
PS C:\Users\dsanc\mi_proyecto> git checkout d24ec65
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  e177280 quinto

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> e177280

HEAD is now at d24ec65 tercer readme.md
PS C:\Users\dsanc\mi_proyecto> git log --oneline
d24ec65 (HEAD, master) tercer readme.md
1baaa16 segundo readme.md
158d5b6 Anadido readme.md

# Ejercicio 6
En el codigo destaca en rojo que se ha eliminado (-- Elemento 3)

PS C:\Users\dsanc\mi_proyecto> git diff
diff --git a/readme.md b/readme.md
index 021bb9c..04fbd0b 100644
--- a/readme.md
+++ b/readme.md
@@ -5,7 +5,7 @@
 - Elemento 2
   - Subelemento 1
   - Subelemento 2
-- Elemento 3
+


 [marca](https://www.marca.com/)

