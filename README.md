# Nexa - Análise Avançada de Imagens e Texto com IA na AWS
# OCR Lista Escolar

Projeto usado para exemplificar o uso do [AWS Textract](https://docs.aws.amazon.com/pt_br/textract/latest/dg/API_DetectDocumentText.html) na extração de textos em imagens simples.

Este projeto é de estudo e tem como base o projeto base do curso da [DIO](https://github.com/digitalinnovationone/nexa-analise-avancada-de-imagens-e-texto-com-ia-na-aws/tree/main).

## 🎯 Objetivo

O objetivo principal é automatizar o processo de digitalização de listas de material escolar, convertendo imagens em texto estruturado e organizando os itens em um formato padronizado.

## 🚀 Funcionalidades

- Extração de texto de imagens usando AWS Textract
- Processamento e estruturação de itens da lista
- Identificação automática de quantidades e descrições
- Geração de relatório formatado
- Tratamento de erros e validações
- Suporte a múltiplos formatos de entrada

## 💡 Insights e Aprendizados

Durante o desenvolvimento deste projeto, vários insights importantes foram obtidos:

1. **Pré-processamento de Imagens**
   - A qualidade da imagem afeta significativamente a precisão do Textract
   - Imagens com bom contraste e resolução têm melhores resultados

2. **Estruturação de Dados**
   - O uso de dataclasses torna o código mais organizado e tipado
   - A estruturação correta facilita análises posteriores

3. **Boas Práticas**
   - Tratamento adequado de erros é essencial
   - Documentação clara ajuda na manutenção
   - Uso de type hints melhora a legibilidade

## 📊 Resultados

### Exemplo de Entrada
![Lista de Material Original](images/lista-material-escolar.jpeg)

### Exemplo de Saída
```text
Lista de Material Escolar Processada:

3x rolos de fita crepe
1x bloco de canson A4
1x fita adesiva
5x folhas de cartolina
3x placas de EVA
1x EVA com gliter
5x papel colorset
1x caneta permanente
1x pacote palito de sorvete
4x papel cartão
1x kit leoni n. 1
1x dicionário
1x pincel n.14
1x pasta 20mm
```
