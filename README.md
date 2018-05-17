# Análise de dados referentes a pesquisa no IMD e DIMAp

O presente repositório refere-se ao trabalho da segunda unidade da disciplina **Probabilidade** (IMD0033), ministrada pelo professor [Ivanovitch Medeiros Dantas da Silva](https://github.com/ivanovitchm).

## Objetivo
Esse trabalho possui como objetivo análisar os dados referentes a pesquisa no Instituto Metrópole Digital (IMD), contexto de discentes e docentes, e no Departamento de Informática e Matemática Aplicada (DIMAp), contexto de docentes. Visto que tem-se conhecimento de que a pesquisa é realizada em ambos os departamentos, mas é comum desconhecer o perfil dos discentes e docentes envolvidos no processo de realizar pesquisa. Sendo assim, procurou-se mostrar algumas informações que aumentem o conhecimento de quem ler em relação as pesquisas realizadas no IMD e DIMAp.

**Componentes**:
- <a href="https://github.com/alvarofpp">Álvaro Ferreira Pires de Paiva</a>
  - Matrícula: 2016039162
  - E-mail: alvarofepipa@gmail.com
- <a href="https://github.com/davir8">Davi Rodrigues de Medeiros</a>
  - Matrícula: 20160143888
  - E-mail: davirodrigues8@gmail.com

## Dados
Os dados utilizados forma retirados do site de <a href="http://dados.ufrn.br/">dados abertos da UFRN</a>. Foram utilizados os seguintes conjuntos de dados:
- <a href="http://dados.ufrn.br/dataset/bolsistas-de-iniciacao-cientifica">Bolsistas de Iniciação Científica</a>
- <a href="http://dados.ufrn.br/dataset/discentes">Discentes</a>
- <a href="http://dados.ufrn.br/dataset/docentes">Docentes</a>
- <a href="http://dados.ufrn.br/dataset/pesquisadores">Pesquisadores</a>
- <a href="http://dados.ufrn.br/dataset/projetos-de-pesquisa">Projetos de pesquisa</a>


## Sumário
- [Preparando o ambiente](#ambiente)
  - [Tratamento dos dados](#tratamento)
- [Análise](#analise)
  - [Discentes](#discentes)
  - [Docentes](#docentes)
- [Conclusão](#conclusao)

## <a id="ambiente">Preparando o ambiente</a>
Nessa seção, iremos  declarar as dependências necessárias para o Jupyter Notebook executar corretamente, para isso iremos: declarar as variáveis globais que iremos utilizar, importar as libs necessárias e preparar os arquivos que temos para podermos utilizá-los nas seções seguintes.

Primeiramente, instale as dependências a seguir, utilizando seus respectivos comandos:
- **Seaborn**: `conda install -c anaconda seaborn` ([Saiba mais](https://seaborn.pydata.org/))
- **WordCloud**: `conda install -c conda-forge wordcloud` ([Saiba mais](https://github.com/amueller/word_cloud))

### <a id="tratamento">Tratamento dos dados</a>
Nessa seção, iremos tratar os dados de arquivos diferentes, de forma que iremos conseguir juntar dados de multiplos arquivos em um só, a fim de facilitar as análises que podemos realizar posteriormente.

## <a id="analise">Analise</a>
Nessa seção, iremos realizar algumas análises dos dados de discentes e docentes, a fim de entendermos melhor o papel de ambos no contexto de desenvolvimento de pesquisa científica.

### <a id="discentes">Discentes</a>
Aqui iremos analisar os dados dos discentes de Tecnologia da Informação utilizando gráficos e consultas estudados em sala de aula.

- Qual a situação dos alunos que ingressaram em BTI?
- Qual a quantidade de bolsistas por ano?
- Qual a situação atual das bolsas de iniciação cientifica dos alunos do BTI?
- Qual a porcentagem de bolsistas em cada categoria?
- Qual a quantidade de alunos bolsistas participantes de grupos de pesquisa?

### <a id="docentes">Docentes</a>
- Qual a quantidade de docentes (do IMD e DIMAP) que são e não considerados pesquisadores?
- Qual a formação dos docentes do IMD e DIMAp e qual a formação dos pesquisadores?
- Qual a quantidade média de projetos coordenados, internos e externos dos pesquisadores do IMD e DIMAP?
- Quais são as principais áreas de conhecimento que os docentes desenvolvem projetos de pesquisa?
- Quais palavras mais aparecem nas palavras chaves das pesquisas realizadas?

## <a id="conclusao">Conclusão</a>
A partir da análise dos dados dos discentes e bolsistas do BTI, foi possível extrair informações importantes que estão disponibilizadas de forma implícita pela UFRN. Essas informações nos permitiram visualizar que maior parte dos discentes que ingressaram no BTI entre os anos 2013 e 2017 desistiram ou ainda se encontram cursando e a menor parte finalizaram ou estão finalizando.

No contexto da pesquisa, é possível observar que o ano 2016 teve o maior número de bolsistas de pesquisa ativos enquanto o 2013 teve o menor, visto que foi o ano que lançaram o curso do BTI. Além disso, observamos que do total de alunos do BTI que possuem bolsas de pesquisa, metade finalizaram e a outra metade se encontra ativa ou pendente de relatório. Também é notado que a maior parte dessas bolsas são de iniciação científca, enquanto as demais são de iniciação tecnológica. Por fim, foi possível visualizar quais os grupos de pesquisa e o número bolsistas que fazem parte.

No contexto de docentes, observamos que a maioria dos docentes são envolvidos com pesquisa. Também percebemos que docentes com grau de formação "doutorado" possuem as maiores médias de participação em pesquisa, chegando a coordenar um projeto de pesquisa duas vezes mais do que alguém que possuem como grau de formação "mestrado".

Também pudemos notar que não é regra áreas de conhecimento mais abrangentes, como "Sistemas de Computação" e "Engenharia de Software", possuirem mais projetos registrados do que áreas de conhecimento mais específicas, visto que, por exemplo, "Ciência da Computação" e "Sistemas de Informação" possuem poucas pesquisas registradas. Isso é ressaltado quando análisamos as palavras-chave dos projetos e vimos que palavras-chave específicas aparecem em destaque, como "Metaheurística" e "Algoritmos Transgenéticos".

Essas análises se tornam interessantes quando queremos ter uma visão melhor sobre como a pesquisa está sendo desenvolvida no IMD e DIMAp, conhecendo melhor os dicentes e docentes envolvidos e o conhecimento gerado durante o processo.