# Dashboard de Performance Operacional

Projeto de portfólio desenvolvido para demonstrar conhecimentos em Python, tratamento de dados, análise operacional e construção de dashboards interativos.

**Todos os dados utilizados neste projeto são fictícios e foram criados exclusivamente para fins de demonstração.**

## Sobre o projeto

O dashboard apresenta uma simulação de acompanhamento de instalações por unidade, região e data. A página é estática e carrega o conjunto demonstrativo incluído no repositório por um caminho relativo.

## Objetivo

Demonstrar um fluxo de análise de dados, desde a geração e preparação de dados sintéticos até a apresentação de indicadores operacionais em uma interface interativa e responsiva.

## Tecnologias utilizadas

- Python
- Pandas
- HTML
- CSS
- JavaScript
- Data Analytics
- Dashboard Interativo

## Pipeline de dados

1. **Geração:** criação reprodutível de dados sintéticos para simular um cenário operacional.
2. **Tratamento:** padronização de campos e representação de valores ausentes.
3. **Validação:** conferência de registros, datas e consistência do cruzamento.
4. **Transformação:** seleção e agregação de instalações por data, unidade e região.
5. **Análise:** cálculo de métricas para apoiar a leitura dos resultados.
6. **Dashboard:** visualização interativa dos indicadores.

## Principais análises

- Volume de instalações por dia;
- instalações por unidade e região;
- participação de cada unidade no total;
- lojas identificadas e registros sem unidade;
- evolução dos indicadores conforme o recorte selecionado.

## Funcionalidades do dashboard

- Filtros multisseleção por data, unidade e região, com pesquisa;
- seleção completa, limpeza e restauração da visão geral;
- cinco indicadores que respondem aos filtros;
- quatro gráficos interativos;
- controle para incluir ou ocultar registros sem unidade nos gráficos por unidade;
- layout responsivo para desktop, notebook e telas menores.

## Estrutura do projeto

```text
PUBLICAR_GITHUB/
├── index.html
├── portfolio_data.js
├── README.md
└── src/
    ├── gerar_dados_ficticios.py
    └── processar_dados.py
```

`index.html` carrega `portfolio_data.js` do mesmo diretório. Os scripts em `src/` documentam a geração e o processamento dos dados sintéticos; eles não são necessários para abrir a página publicada.

## Publicação e execução local

Para testar localmente, abra `index.html` em um navegador moderno. Para publicar com GitHub Pages, use o conteúdo desta pasta como origem do site. A página inicial e o arquivo de dados devem permanecer juntos para que o caminho relativo continue funcionando.

Os scripts demonstrativos requerem Python, Pandas e NumPy. Eles podem ser executados localmente com:

```bash
python src/gerar_dados_ficticios.py
python src/processar_dados.py
```

## Observação sobre dados fictícios

Todos os nomes de unidades, vendedores e demais valores foram inventados para demonstração. O projeto não contém cadastros, arquivos ou informações de uma operação real.
