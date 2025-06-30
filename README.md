# Processador de PDFs - UTFPR

Sistema web para extração automática e inteligente de dados patrimoniais a partir de arquivos PDF, desenvolvido para facilitar o controle de inventário em instituições como a UTFPR.

## ✨ O que é este projeto?

O Processador de PDFs - UTFPR é uma ferramenta que utiliza Inteligência Artificial para ler PDFs de inventário patrimonial, extrair dados relevantes (como Tombo Novo, Tombo Antigo, Instituição, Descrição do Bem e Local Físico) e apresentar essas informações de forma organizada em uma tabela editável e exportável para CSV.

## Principais Recursos

- Upload de múltiplos PDFs simultaneamente
- Extração automática de dados estruturados via IA (OpenAI + n8n)
- Interface amigável, responsiva e com design inspirado na UTFPR
- Visualização instantânea dos dados extraídos em tabela
- Download dos resultados em formato CSV, pronto para Excel ou Google Sheets

## Como funciona?

1. Faça o upload dos arquivos PDF diretamente pela interface web.
2. Acompanhe o progresso do processamento na tela.
3. Veja os dados extraídos organizados em uma tabela dinâmica.
4. Faça o download dos dados no formato CSV.

## Tecnologias utilizadas

- HTML5, CSS3, JavaScript (Frontend)
- n8n para automação e processamento dos PDFs
- OpenAI para leitura e extração inteligente dos dados

## Como usar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/processador-pdf-utfpr.git
    ```
2. Abra o arquivo `index.html` em seu navegador.

> O processamento dos PDFs é feito via integração com um fluxo n8n. Consulte a documentação ou o arquivo do n8n para detalhes de configuração da automação.

## Possíveis Aplicações

- Inventário patrimonial em universidades, órgãos públicos e empresas
- Digitalização e organização de acervos físicos
- Transformação de documentos PDF em planilhas estruturadas

## Licença

Este projeto está licenciado sob a **Creative Commons Zero v1.0 Universal (CC0 1.0)**.  
Você pode copiar, modificar, distribuir e executar o trabalho, mesmo para fins comerciais, sem pedir permissão.  
Para mais informações, consulte [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.pt_BR).

---

### Equipe

- Breno Israel Jaworski Müller  
- Gabriel Hunger Machado  
- Jonathan Leonildes De Souza  
- Jonathan Abreu Segantini
