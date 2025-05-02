**Dashboard de Vendas – Apache Superset:**
---

Este repositório contém os arquivos de exportação (`.yaml`) dos dashboards de vendas desenvolvidos na ferramenta de BI Apache Superset. 
Ele serve para versionar e facilitar a reimportação dos dashboards em diferentes ambientes (desenvolvimento, homologação, produção).

**Como importar no Superset:**
1 - Acesse o Superset via navegador.
2 - Vá até Settings > Import dashboards.
3 - Faça o upload dos arquivos .yaml desejados.
4 - Verifique se todas as dependências (bancos, datasets) já existem ou foram importadas.

**Observações:**
1 - Os arquivos YAML foram gerados via funcionalidade de exportação do Superset.
2 - Recomendado usar controle de versão para rastrear mudanças em dashboards ao longo do tempo.
3 - Algumas importações podem exigir ajuste manual se houver mudanças no nome dos datasets ou conexões.
