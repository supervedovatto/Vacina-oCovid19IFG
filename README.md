# Número esperado de vacinados contra Covid-19 no IFG Campus Goiânia

O documento [Estimativas Covid IFG](https://github.com/supervedovatto/VacinacaoCovid19IFG/blob/main/Estimativas-2021-11-16.xlsx?raw=true) é um arquivo do excel com quatro planilhas contendo informações acerca do número esperado de vacinados por qualquer um dos imunizantes contra a Covid-19. As planilhas possuem os seguintes títulos:

**Dose 1 Comunidade Acadêmica**: 1ª Dose para a Comunidade Acadêmica.

**Dose 2 Comunidade Acadêmica**: 2ª Dose para a Comunidade Acadêmica.

**Dose 1 Profissionais Educação**: 1ª Dose para os docentes.

**Dose 2 Profissionais Educação**: 2ª Dose para os docentes.

Todas as planilhas contem tabulações com as seguintes colunas:

**Faixa**: Apresenta as diversas faixas etárias consideradas.

**Público Potencial**: Público potencial do IFG Campus Goiânia no caso de um retorno presencial imediato. Inclui servidores docentes efetivos, substitutos, técnicos administrativos, discentes e terceirizados.

**População Projetada Goiânia 2022**: População projetada para a cidade de Goiânia para o ano de 2022.

**Número de Vacinados**: Número de pessoas vacinadas em Goiânia.

**Proporção de Vacinados**: Proporção de vacinados em Goiânia.

**Limite Inferior** e **Limite Superior**: Determinam um intervalo que contêm o número real de vacinados no campus Goiânia com probabilidade de 95%.

**Valor Esperado de Vacinados**: Valor esperado do número de vacinados no Campus Goiânia.

**Desvio Padrão**: Desvio padrão do número de vacinados no Campus Goiânia.

# Observações:

O público potencial do Campus Goiânia dentro de uma mesma faixa etária foi interpretado como uma amostra proveniente de uma variável aleatória Hipergeométrica com tamanho populacional N, tamanho da classe de interesse K e tamanho amostral n. O total de vacinados no campus Goiânia equivale ao numero k de individuos da classe de interesse na amostra aleatória de tamanho n considerada.
    
O intervalo de 95% de probabilidade em torno do valor esperado de vacinados foi calculado com base na aproximação da distribuição hipergeométrica pela normal. A aproximação se justifica pois os valores dos parâmetros N, K e n são relativamente grandes na maioria das faixas etárias onde o campus possui quantidades mais significativas de representantes.

O Público Potencial do Campus Goiânia do IFG foi obtido por meio de consulta aos sistemas internos ([Visão IFG](https://visao.ifg.edu.br/entrada/) e [SUAP](https://suap.ifg.edu.br/accounts/login/?next=/)) e pelas informações fornecidas pelas empresas terceirizadas prestadoras de serviço. Os dados sobre vacinação em Goiânia foram obtidos no [repositório oficial do SUS](https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao/resource/ef3bd0b8-b605-474b-9ae5-c97390c197a8) na data de 16 de Novembro de 2021.

Não foi possível obter dados à respeito da distribuição das idades dos docentes atuando em Goiânia, portanto a metodologia adotada subestima o número de vacinados para os Profissionais da Educação visto que a categoria constituiu público prioritário na ordem de vacinação e deve, portanto, apresentar um número real de vacinados superior ao apresentado.

 A população projetada para Goiânia em 2022 foi obtida junto ao [Banco de Dados Estatísticos de Goiás](https://www.imb.go.gov.br/bde/) mantido pelo [Instituto Mauro Borges](https://www.imb.go.gov.br/). A projeção divulgada no IMB subestimou a população nas faixas etárias mais altas da população. Como o público interno do IFG possui relativamente poucas pessoas acima de 65 anos de idade, sugerimos averiguar a vacinação nessas faixas por meio de contato direto.