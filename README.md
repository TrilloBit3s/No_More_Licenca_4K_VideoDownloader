# No_More_Licenca_4K_VideoDownloader


# Instruções para desativar o limite de downloads no 4K Video Downloader

1. Pressione `Win + R` para abrir o comando de execução.
2. Digite `regedit` e pressione Enter.
3. Clique em `Sim` para confirmar a abertura do Editor de Registro.
4. Navegue até o seguinte caminho:

    HKEY_CURRENT_USER \SOFTWARE \4K Video Downloader+ \Limits
  
OBS: Agora, do lado direito da tela, você verá 3 arquivos:
    - AB (Padrão)
    - 011 dayDownloadCount
    - 011 dayDownloadDATE

5. Clique no arquivo do meio (011 dayDownloadCount) e abra-o.
6. No campo "Dados do Valor", substitua o valor por `0` (zero).

Depois de fazer isso, você poderá baixar seus vídeos sem precisar esperar 24 horas ou pagar.

**Pronto! Agora, o limite foi desativado.**

