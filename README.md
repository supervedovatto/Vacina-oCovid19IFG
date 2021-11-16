# Estimativas da Vacinação contra Covid-19 no IFG/Campus Goiânia

Resultados das estimativas do número de vacinados no IFG Campus Goiânia. 

O arquivo [Estimativas Covid IFG](https://github.com/supervedovatto/VacinacaoCovid19IFG/blob/main/Estimativas-2021-11-16.xlsx?raw=true) contém um arquivo do excel com quatro planilhas contendo as estimativas de vacinados pela 1ª e 2ª Doses de alguma das vacinas contra a Covid-19. As planilhas receberam os seguintes títulos:

    - Dose 1 Comunidade Acadêmica: 1ª Dose para a Comunidade Acadêmica.
    - Dose 2 Comunidade Acadêmica: 2ª Dose para a Comunidade Acadêmica.
    - Dose 1 Profissionais Educação: 1ª Dose para os docentes.
    - Dose 2 Profissionais Educação: 2ª Dose para os docentes.

Cada planilha apresenta as seguintes colunas:

    - Faixa: Faixa etária de referência.
    - Público Potencial: Público Potencial do IFG Campus Goiânia. Incluindo Servidores Docentes Efetivos, Substitutos, Técnicos Administrativos, Discentes e Terceirizados.
    - População Projetada Goiânia 2022: População Projetada para a cidade de Goiânia para o ano de 2022 segundo divulgado pelo IMB (Instituto Mauro Borges)
    - Número de Vacinados: Número de pessoas vacinadas com a dose informada no título da aba.
    - Proporção de Vacinados: Proporção de Vacinados com a dose de referência.
    - Limite Inferior com p=95% e Limite Superior com p=95%: Determinam um intervalo para o número real de vacinados no campus. A probabilidade de que o verdadeiro número de vacinados esteja nesse intervalo é de 95%.
    - Valor Esperado de Vacinados: Valor esperado do número de vacinados no campus.
    - Desvio Padrão: Desvio padrão do número de vacinados no campus.

# Observações:

    * A população dentro de cada uma das faixas etárias do campus foi interpretada como uma amostra de uma variável aleatória Hipergeometrica com tamanho populacional N, tamanho da classe de interesse K e tamanho amostral n. O número de vacinados no campus equivale ao numero k de individuos da classe de interesse na amostra aleatória de tamanho n considerada.
    * O intervalo de 95% de probabilidade em torno da média foi calculado com base na aproximação da distribuição hipergeométrica pela normal. A aproximação se justifica pois os valores dos parâmetros N, K e n são relativamente grandes na maioria das faixas etárias onde o campus possui quantidades mais significativas de representantes no público potencial.
    * Não foi possível obter dados à respeito da distribuição das idades dos docentes atuando em Goiânia, portanto a metodologia adotada subestima o número de vacinados para os Profissionais da Educação visto que a categoria constituiu público prioritário na ordem de vacinação.
    * A projeção divulgada no IMB subestimou a população nas faixas etárias mais altas da população. Como o público interno do IFG possui relativamente poucas pessoas acima de 65 anos de idade, sugerimos averiguar a vacinação nessas faixas por meio de contato direto.
    * O Público Potencial foi obtido por meio de consulta aos Sistemas internos do IFG (Visão e SUAP) e por meio solicitando informações as empresas terceirizadas prestadoras de serviço.
    * Os dados do número de vacinados foram obtidos no [repositório oficial do SUS](https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao/resource/ef3bd0b8-b605-474b-9ae5-c97390c197a8) na data de 16 de Novembro de 2021.