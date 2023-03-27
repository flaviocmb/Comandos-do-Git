## Comandos do Git

<details>
<summary>Documentação</summary>
  
https://git-scm.com/docs/git

</details>
<details>
<summary>Ajuda com um comando?</summary>

```
git help commit
```

```
git commit --help
```

</details>
<details>
<summary>Comandos gerais de uso do Git (repositório local)</summary>

```
git init
```

```
git config --global user.name "nomedeusuario"
```  

```
git config --global user.email "emaildeusuario"
```
  
```
git config user.name "nomedeusuario"
```  

```
git config user.email "emaildeusuario"
```
  
```
git add .
```
  
```
git add -A
```

```
git add --all
```

```
git add segundo_arquivo.txt
```

```
git commit -m "texto para explicar funcionalidades implementadas"
```

```
git commit _m "texto para explicar funcionalidades implementadas"
```

```
git commit segundo_arquivo.txt -m "texto para explicar funcionalidades implementadas"
```
  
```
git branch
```

```
git branch nova_branch
```

```
git checkout nova-branch
```

</details>
<details>
<summary>Enviando (push) para o GitHub pela primeira vez</summary>
  
```
git remote add origin https://github.com/NOMEDEUSUARIO/NOMEDOPROJETO.git
```

```
git branch -M main
```

```
git push -u origin main
```
 
</details>
<details>
<summary>Enviando (push) para o GitHub após a primeira vez - tríade do dia a dia</summary>
  
```
git add -A
```

```
git commit -m “MENSAGEM”
```

```
git push
```
 
</details>
<details>
<summary>Renomeando branch de master para main</summary>

```
git branch -m master main
```

</details>
<details>
<summary>Recebendo (pull) do GitHub (repositório remoto) pela primeira vez</summary>

```
git clone https://github.com/NOMEUSUARIO/PROJETO.git
```

</details>
<details>
<summary>Recebendo (pull) do GitHub (repositório remoto) após a primeira vez</summary>

```
git remote show origin
```

```
git pull
```

</details>
