Set-Content -Path CONTRIBUTING.md -Value @"

\# Guía de Contribución - NetResilience ODS9



¡Gracias por interesarte en mejorar la infraestructura tecnológica de Xalapa! Este proyecto busca soluciones innovadoras, sostenibles y éticas.



\## 1. Estándares Éticos de Desarrollo

\* \*\*Privacidad por Diseño:\*\* No incluyas logs que capturen datos personales o IPs privadas.

\* \*\*Inclusividad:\*\* La documentación debe ser clara y accesible.



\## 2. Flujo de Trabajo (Git Workflow)

Usamos un flujo de \*\*Historial Lineal\*\*:

1\. Crea una rama descriptiva: \\`git checkout -b feature/nombre\\`.

2\. Sincronización mediante Rebase: \\`git rebase origin/main\\`.



\## 3. Estilo de Commits

Usamos \*\*Conventional Commits\*\*: \\`feat:\\`, \\`fix:\\`, \\`docs:\\`.

"@

