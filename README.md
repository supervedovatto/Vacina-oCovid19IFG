# Estimativas da Vacinação contra Covid-19 no IFG/Campus Goiânia

Resultados das estimativas do número de vacinados no IFG Campus Goiânia. 

O arquivo [Estimativas Covid IFG](https://github.com/supervedovatto/VacinacaoCovid19IFG/blob/main/Estimativas-2021-11-16.xlsx?raw=true) contém um arquivo do excel com quatro planilhas contendo as estimativas de vacinados pela 1ª e 2ª Doses de alguma das vacinas contra a Covid-19. As planilhas receberam os seguintes títulos:

**Dose 1 Comunidade Acadêmica**: 1ª Dose para a Comunidade Acadêmica.

**Dose 2 Comunidade Acadêmica**: 2ª Dose para a Comunidade Acadêmica.

**Dose 1 Profissionais Educação**: 1ª Dose para os docentes.

**Dose 2 Profissionais Educação**: 2ª Dose para os docentes.

Cada uma dessas planilhas apresenta uma estrutura contendo as seguintes colunas:

**Faixa**: Faixa etária de referência.

**Público Potencial**: Público Potencial do IFG Campus Goiânia. Incluindo Servidores Docentes Efetivos, Substitutos, Técnicos Administrativos, Discentes e Terceirizados.

**População Projetada Goiânia 2022**: População Projetada para a cidade de Goiânia para o ano de 2022.

**Número de Vacinados**: Número de pessoas vacinadas com a dose informada no título da aba.

**Proporção de Vacinados**: Proporção de Vacinados com a dose de referência.

**Limite Inferior com p=95%** e **Limite Superior com p=95%**: Determinam um intervalo para o número real de vacinados no campus. A probabilidade de que o verdadeiro número de vacinados esteja nesse intervalo é de 95%.

**Valor Esperado de Vacinados**: Valor esperado do número de vacinados no campus.

**Desvio Padrão**: Desvio padrão do número de vacinados no campus.

# Observações:

A população dentro de cada uma das faixas etárias do campus foi interpretada como uma amostra de uma variável aleatória Hipergeométrica com tamanho populacional N, tamanho da classe de interesse K e tamanho amostral n. O número de vacinados no campus equivale ao numero k de individuos da classe de interesse na amostra aleatória de tamanho n considerada.
    
O intervalo de 95% de probabilidade em torno do valor esperado de vacinados foi calculado com base na aproximação da distribuição hipergeométrica pela normal. A aproximação se justifica pois os valores dos parâmetros N, K e n são relativamente grandes na maioria das faixas etárias onde o campus possui quantidades mais significativas de representantes.

O Público Potencial do Campus Goiânia do IFG foi obtido por meio de consulta aos sistemas internos ([Visão IFG](https://visao.ifg.edu.br/entrada/) e [SUAP](https://suap.ifg.edu.br/accounts/login/?next=/)) e pelas informações fornecidas pelas empresas terceirizadas prestadoras de serviço. Os dados do número de vacinados em Goiânia foram obtidos no [repositório oficial do SUS](https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao/resource/ef3bd0b8-b605-474b-9ae5-c97390c197a8) na data de 16 de Novembro de 2021.

Não foi possível obter dados à respeito da distribuição das idades dos docentes atuando em Goiânia, portanto a metodologia adotada subestima o número de vacinados para os Profissionais da Educação visto que a categoria constituiu público prioritário na ordem de vacinação.

 A população projetada para Goiânia em 2022 foi obtida junto no [Banco de Dados Estatísticos de Goiás](https://www.imb.go.gov.br/bde/) mantido pelo [Instituto Mauro Borges](https://www.imb.go.gov.br/). A projeção divulgada no IMB subestimou a população nas faixas etárias mais altas da população. Como o público interno do IFG possui relativamente poucas pessoas acima de 65 anos de idade, sugerimos averiguar a vacinação nessas faixas por meio de contato direto.