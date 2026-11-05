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

Evidência: 
<img width="1021" height="717" alt="1sem-edição" src="https://github.com/user-attachments/assets/4a69bffb-8582-4512-bd64-ef35bec1b31d" />
<img width="1021" height="700" alt="2" src="https://github.com/user-attachments/assets/ce292c1f-9be6-4e54-a991-e8eacdcef8e6" />
<img width="1022" height="720" alt="2 1" src="https://github.com/user-attachments/assets/519e5b90-9295-4677-aa0b-671c05bec461" />
<img width="1020" height="697" alt="3" src="https://github.com/user-attachments/assets/e6ff2c01-5164-40d8-966d-8181c53bb1a6" />
<img width="1021" height="721" alt="4" src="https://github.com/user-attachments/assets/696ca1d0-de01-405e-96ac-77f0ad1f6308" />
<img width="1021" height="722" alt="5" src="https://github.com/user-attachments/assets/83d382b1-5969-4310-8501-d50d161d5316" />
<img width="1022" height="719" alt="6" src="https://github.com/user-attachments/assets/88b246a9-fa14-4ab3-8c00-596377a5043d" />
<img width="1022" height="718" alt="7" src="https://github.com/user-attachments/assets/50a2efa2-1e2a-429c-b66b-d2ad4e90f691" />
<img width="1022" height="696" alt="8" src="https://github.com/user-attachments/assets/d0770a77-30b3-425a-85f5-a7736c2a060d" />

Observação: Após a identificação dos registos repetidos da coluna A, verífiquei que somente a linha 8 e 9 continham todas as informações iguais, na linha 2 e 3 foi identificado que o número de registro foi repetido por conta de um erro manual do operador da planilha e corrigido consecutivamente. e a linha 8 foi removida como mostram nas evidências.

<img width="1363" height="695" alt="9" src="https://github.com/user-attachments/assets/265d4b71-d880-499b-a399-8b34ecd91d2a" />
<img width="1360" height="716" alt="10" src="https://github.com/user-attachments/assets/e043c8fe-daab-4ef2-a913-c828ec58616e" />
<img width="1362" height="697" alt="11" src="https://github.com/user-attachments/assets/f52e802c-1ef1-460e-b8ad-7d9378a21aee" />

2. Identificação de células vazias

Aplicação da Formatação Condicional para destacar células sem preenchimento.

Os valores ausentes serão analisados para identificar a necessidade de correção e seus possíveis impactos na qualidade da base.

Evidência: 
<img width="1364" height="699" alt="1" src="https://github.com/user-attachments/assets/066f9715-5a8a-49a9-a2e7-59a6caaf8392" />
<img width="1364" height="720" alt="2" src="https://github.com/user-attachments/assets/78440dec-276c-4e4c-8f04-e756c57704fc" />
<img width="1363" height="721" alt="3" src="https://github.com/user-attachments/assets/2af57f57-e564-407a-94a9-179c3e2b6fc5" />
<img width="1365" height="718" alt="4" src="https://github.com/user-attachments/assets/8aed0c18-caad-47a7-8a39-e64219d7b774" />
<img width="1363" height="722" alt="5" src="https://github.com/user-attachments/assets/c3a6609f-6e38-46a4-b5d1-ad37eb3c938e" />
Observação: Na coluna C11 foi adicionado o dia e na coluna G16 foi adicionado a faixa etária porém na coluna M12 foi necessário verificar a descrição do produto de acordo com o preço unitário, e na coluna N13 foi necessário verificar a quantidade com o calculo de Preço unitário - Custo unitário isso gera o valor do lucro multiplicado na quantidade de bicicletas ou seja 1 unidade na célula N23 conforme mostrado nas evidêcias


3. Separação de informações textuais

Utilização da ferramenta Texto para Colunas no campo Product_Description.

Serão aplicados delimitadores de espaço e vírgula para separar informações relacionadas à descrição do produto, como tamanho e cor.

O objetivo é facilitar a organização e a utilização individual dessas informações em análises posteriores.

Evidência: 
<img width="1364" height="717" alt="1" src="https://github.com/user-attachments/assets/4b1dbc77-bad0-4a72-89cd-8b7ca1fbaa8e" />
<img width="1363" height="715" alt="2" src="https://github.com/user-attachments/assets/dd0466e5-7291-41ec-919c-69d7025c50de" />
<img width="1363" height="720" alt="3" src="https://github.com/user-attachments/assets/1532bdaa-8230-436b-88cc-fc88e9f1ed9e" />
<img width="1364" height="717" alt="4" src="https://github.com/user-attachments/assets/b4f3c048-7b77-4573-b5a7-e376a211cebb" />
<img width="1364" height="721" alt="5" src="https://github.com/user-attachments/assets/acdad720-2874-41e4-bb28-65170d544a31" />
Observação: Foram adicionadas duas colunas ao lado da coluna de descrição do Produto, "Color", "Size", para a descrição de cores e tamanho conforme as evidências

4. Remoção de espaços extras

Identificação de inconsistências causadas por espaços desnecessários em campos de texto.

Aplicação das funções:

=ARRUMAR(A2) — remove espaços excedentes e mantém um único espaço entre palavras.

=NÚM.CARACT(A2) — conta a quantidade de caracteres de uma célula, incluindo espaços.

A comparação da quantidade de caracteres permitirá verificar diferenças entre valores aparentemente iguais e validar as correções, para isso, adicionei duas colunas ao lado da coluna Estado "QT.CHAR", "TRIM", para validar a quantidade de caracteres e filtros nas colunas "Country" e "State" assim identificando as divergências e corrigindo

Observação: Na coluna I foi encontrado divergência como o nome do país "United States". Ele aparece em 3 formatos diferentes, 2 formatos ocupando 14 caracteres e 1 formato ocupando 13 caracteres que é o correto. Utilizei a função =ARRUMAR para corrigir 


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
