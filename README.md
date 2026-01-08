# Ferramentas
Ferramentas genéricas para analisar conjuntos de PDFs acadêmicos.
1) **pdf_highlights_extractor.ipynb**: Permite a extração de destaques e comentários em arquivos PDFs encontrados numa pasta do Google Drive. 
2) **pdf_count_prefixes.ipynb**: Permite identificar a quantidade de ocorrências  prefixos ou palavras nos arquivos PDFs encontrados numa pasta do Google Drive.

Todas as ferramentas analisam os arquivos em uma pasta do Google Drive de maneira aninhada, ou seja, buscam recursivamente os arquivos encontrados nas subpastas existentes da pasta do Google Drive informada. A pasta pode estar num Drive Compartilhado ou ser dentro do Drive pessoal - o importante é que o e-mail da conta Google que executa a ferramenta tenha _permissão como Editor_ na pasta informada. 

# Como utilizar
Basta baixar o arquivo do código desejado, ir em [https://colab.research.google.com/](https://colab.research.google.com/) com sua conta Google, clicar em "Upload" e importar o arquivo .ipynb baixado.

![alt text](images/import.png)

Depois, leia as instruções de texto (caso existam) que aparecerão. Se houver necessidade de informar algum campo, faça-o antes de clicar no botão "Executar tudo". Preste atenção pois haverá um pop-up que se abrirá para solicitar que você permita o Jupyter Notebook a acessar os seus arquivos no Google Drive. Selecione os itens e dê a permissão para continuar.

## Como citar
SEEMANN, Wij. **PDF Scripts** \[código-fonte\]. GitHub, 2026. Disponível em: [https://github.com/bseemann/pdf_scripts](https://github.com/bseemann/pdf_scripts). Acesso em: <insira data aqui>. 