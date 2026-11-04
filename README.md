Limpeza e Preparação de Dados com Excel

📌 Sobre o projeto

Este projeto tem como objetivo aplicar técnicas de limpeza, tratamento e padronização de dados em uma base de vendas de bicicletas, utilizando o Microsoft Excel.

A atividade faz parte do curso Fundamentos de Análise de Dados, oferecido pela Cisco Networking Academy, e foi utilizada como referência para desenvolver habilidades práticas relacionadas à qualidade e à preparação de dados.

O projeto documenta a identificação de inconsistências, os procedimentos de correção e a validação dos dados para utilização em análises futuras.

🎯 Objetivos

Identificar e tratar registros duplicados.

Localizar e analisar células vazias.

Separar informações contidas em uma mesma coluna.

Identificar e remover espaços desnecessários.

Detectar valores potencialmente inconsistentes em campos numéricos.

Padronizar informações categóricas.

Verificar e corrigir possíveis erros ortográficos.

Garantir maior consistência e confiabilidade à base de dados.

🛠️ Ferramentas e recursos utilizados

Ferramenta: Microsoft Excel

Recursos e funções:

Formatação Condicional

Remover Duplicatas

Texto para Colunas

Função ARRUMAR (TRIM)

Função NÚM.CARACT (LEN)

Localizar e Substituir

Verificação Ortográfica

📂 Base de dados

O conjunto de dados contém informações relacionadas às vendas de bicicletas, incluindo pedidos, clientes, produtos e informações financeiras.

Entre os campos presentes na base estão:

Identificação dos pedidos

Datas das vendas

Idade e gênero dos clientes

País e localização

Descrição dos produtos

Quantidade vendida

Custos e preços unitários

Receita e lucro

Origem: Material educacional do curso da Cisco Networking Academy.

🔎 Etapas de limpeza e tratamento

1. Identificação e remoção de duplicatas

Utilização da Formatação Condicional para identificar registros potencialmente duplicados.

Após a identificação, os registros serão analisados e as duplicatas confirmadas serão removidas utilizando a ferramenta Remover Duplicatas.

Evidência: [Inserir captura de tela]

2. Identificação de células vazias

Aplicação da Formatação Condicional para destacar células sem preenchimento.

Os valores ausentes serão analisados para identificar a necessidade de correção e seus possíveis impactos na qualidade da base.

Evidência: [Inserir captura de tela]

3. Separação de informações textuais

Utilização da ferramenta Texto para Colunas no campo Product_Description.

Serão aplicados delimitadores de espaço e vírgula para separar informações relacionadas à descrição do produto, como tamanho e cor.

O objetivo é facilitar a organização e a utilização individual dessas informações em análises posteriores.

Evidência: [Inserir captura de tela]

4. Remoção de espaços extras

Identificação de inconsistências causadas por espaços desnecessários em campos de texto.

Aplicação das funções:

=ARRUMAR(A2) — remove espaços excedentes e mantém um único espaço entre palavras.

=NÚM.CARACT(A2) — conta a quantidade de caracteres de uma célula, incluindo espaços.

A comparação da quantidade de caracteres permitirá verificar diferenças entre valores aparentemente iguais e validar as correções.

Evidência: [Inserir captura de tela]

5. Identificação de valores numéricos inconsistentes

Aplicação da Formatação Condicional para destacar valores iguais a zero em campos relacionados a custos e preços unitários.

Os registros identificados serão analisados como possíveis inconsistências, evitando alterações automáticas sem verificação.

Evidência: [Inserir captura de tela]

6. Padronização de dados categóricos

Utilização da ferramenta Localizar e Substituir para padronizar os valores da coluna de gênero.

Valor original

Valor padronizado

F

Feminino

M

Masculino

A padronização facilita a interpretação e o agrupamento dos registros.

Evidência: [Inserir captura de tela]

7. Verificação ortográfica

Utilização do recurso de verificação ortográfica do Excel para identificar possíveis erros de escrita.

O objetivo é evitar que diferenças ortográficas prejudiquem filtros, agrupamentos, pesquisas e consultas realizadas na base.

Evidência: [Inserir captura de tela]

📊 Resultados

Esta seção será preenchida após a execução e validação do tratamento.

Indicador

Resultado

Registros na base original

A preencher

Registros duplicados removidos

A preencher

Células vazias identificadas

A preencher

Valores textuais padronizados

A preencher

Valores numéricos suspeitos

A preencher

Registros na base final

A preencher

📸 Comparação antes e depois

Base original

[Inserir imagem da base antes do tratamento]

Base tratada

[Inserir imagem da base após o tratamento]

💡 Aprendizados

Seção a ser concluída após a atividade.

Este projeto busca consolidar conhecimentos sobre qualidade de dados, identificação de inconsistências e utilização de recursos do Excel para preparação de bases de dados.

Também permite exercitar a documentação das etapas de tratamento e a importância da validação antes de realizar análises.

📚 Referências

Curso: Fundamentos de Análise de Dados
Instituição: Cisco Networking Academy
Atividade: Bike Sales — Lab 3.4.7
Ferramenta: Microsoft Excel

Observação: Projeto educacional de portfólio, desenvolvido a partir de uma atividade prática do curso. A publicação dos dados originais dependerá das permissões de uso do material.
