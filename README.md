# Aulas – EBAC Android

Projetos das atividades de Android (Introdução, Layouts Parte 1).

## GitHub (só esta pasta)

O Git está configurado **apenas** na pasta `Aulas`. As pastas `petz-android`, `petz-ds-lib` e `android-app-dependencies` em StudioProjects **não** são parte deste repositório.

### Conectar a um repositório no GitHub

1. No GitHub, crie um repositório novo (ex.: `Aulas` ou `ebac-android`). **Não** marque "Add a README" se já tiver commit local.

2. Na pasta **Aulas**, no terminal:
   ```bash
   cd C:\Users\Gabriel\StudioProjects\Aulas
   git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
   git branch -M main
   git push -u origin main
   ```

3. Troque `SEU_USUARIO` e `NOME_DO_REPO` pela sua conta e pelo nome do repositório.

### Próximos envios

Depois de alterar algo no projeto:

```bash
cd C:\Users\Gabriel\StudioProjects\Aulas
git add -A
git commit -m "Descrição da alteração"
git push
```
