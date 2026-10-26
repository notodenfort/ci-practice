# ci-practice

Учебный проект практической работы «CI/CD-пайплайн для автоматического запуска тестов».
Итоговый workflow — `.github/workflows/ci.yml` (этапы: lint → unit (4 шарда) → docker-tests → deploy-staging, плюс карантинный job).
Поэтапные версии workflow из заданий 2, 3, 4 лежат в `workflow_stages/` (для отчёта и сравнения).
