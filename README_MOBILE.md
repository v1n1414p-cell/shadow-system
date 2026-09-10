# SHADOW SYSTEM — build pelo celular

Este projeto já inclui um workflow do GitHub Actions para compilar o APK na nuvem, sem Android Studio.

## Pelo celular

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. Abra a aba **Actions**.
4. Selecione **Build SHADOW SYSTEM APK**.
5. Toque em **Run workflow**.
6. Quando terminar, abra a execução concluída e baixe o artefato **shadow-system-debug-apk**.
7. Dentro do ZIP estará o APK para instalar no Android.

O workflow usa GitHub Actions, JDK 17 e Gradle 8.7. Nenhum PC é necessário para a compilação depois que o projeto estiver no GitHub.
