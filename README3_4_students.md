Mini guideline pre študentov (do ich template)

Do README.md v student/private template:

## How to publish
1) Urob poriadok v `public/` (markdown + obrázky, pdf).
2) Vytvor tag `publish-YYYYMMDD` na poslednom commite:


git tag publish-20250901
git push origin publish-20250901

3) V public repo ročníka otvor **Publish request** a vyplň:
- Repo: `06-STH-Projects/st2025-ST012-assign01`
- Ref: `publish-20250901`
- Path: `public/`
4) Po schválení mentorom sa spraví PR → po merge budeš vidieť svoju stránku.