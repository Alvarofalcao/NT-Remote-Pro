# NT Remote Pro

**A configuração de compilação antiga foi desativada porque apenas renomeava o executável original do RustDesk.**

Para compilar o código-fonte personalizado, faça upload dos arquivos **extraídos** do pacote `NT_Remote_Pro_Para_GitHub.zip` na raiz deste repositório (substituindo os arquivos existentes). O pacote contém o fluxo de build Windows x64 real, com Rust e Flutter.

Depois de fazer commit e push: **Actions → NT Remote Pro - Compilar fonte Windows x64 → Run workflow**. Se concluir com sucesso, o executável estará em **Artifacts → NT-Remote-Pro-Windows-x64**.

Código-fonte baseado no RustDesk, licença AGPL-3.0: https://github.com/rustdesk/rustdesk
