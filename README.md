# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Porqué?**

`git reset --hard HEAD~1`
 
`git reset --hard fd5abb5`


--

**2. ¿Qué comando utilizaste en el paso 12? ¿Porqué?**

`git reflog` (lo usé para ver el HASH del commit que acababa de deshacer)

`git reset 48caf8f` 

`git status`

`git add DonQ.md`

`git commit -m "ho riaggiunto DonQ alla rama STYLED"`


--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Porqué?**

No causa conflicto porque las dos ramas forman una lista y la rama styled ya contiene los commits de la rama master.


--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Porqué?**

me he hecho el merge tenendo el contenudo de la rama htmlify

#####Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

  GNU nano 2.0.6          File: /Users/MartaCattaneo/Desktop/DonQ/.git/MERGE_MSG                  Modified

Merge branch 'htmlfy' into style


--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Porqué?**

no, no hay ningun conflicto porque ya contiene el commit de la rama master

--

**6. ¿Qué comando comandos utilizaste en el paso 25?**

`git log --graph --decorate --pretty=oneline`

`git log --graph` si no lo tiene configurado

--

**7. El merge del paso 26, ¿Podria ser fast forward? ¿Porqué?**

si, podria ser fast forward porque la rama title contiene todos lo commits de la rama master


--

**8. ¿Qué comando utilizaste en el paso 27? ¿Porqué?**

`git reset HEAD~1` 


--

**9. ¿Qué comando utilizaste en el paso 28? ¿Porqué?**

`git checkout .` 


--
**10. ¿Qué comando utilizaste en el paso 29? ¿Porqué?**

`git branch -D title` 


--

**11. ¿Qué comando utilizaste en el paso 30? ¿Porqué?**

`git reflog`

` git reset --hard 8c6e77e`


--

**12. ¿Qué comando utilizaste en el paso 32? ¿Porqué?**

`git reset HEAD~21` 


--

**13. ¿Qué comando utilizaste en el paso 33? ¿Porqué?**

`git reflog` 

`git reset --hard 602f778`


--
