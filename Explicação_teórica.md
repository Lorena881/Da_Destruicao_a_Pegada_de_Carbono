# O dataframe

A iniciativa do grupo Reino_de ∑L² é trabalhar com dados relacionados à área de ecologia, devido a isso o dataframe escolhido fala sobre esse tema, ele foi conseguido por meio do site kaggle por "IBM Watson AI XPRIZE - Environment" cuja devida referência está no arquivo "Referências" junta das demais referências usadas no trabalho, o autor do dataframe disponibilizou dois dados para download, um deles relaciona a pegada ecológica ao crescimento do PIB e o outro, utilizado pelo grupo, possui dados relacionados às áreas destinadas a diversar atividades e a pegada ecológica decorrente desses valores, representando grande importância para o estudo ecológico de uma região ao esclarecer a participação de cada um dos países catalogados na luta pela sustentabilidade tão discutida e buscada no contexto das mudanças climáticas atual. O dataframe contém 13 colunas e quase cem mil linhas com dados. Cada coluna representa:

"index": o índice de cada linha.
"country": nome do país.
"year": ano dos dados.
"country_code": código do país.
"record": tipo de registro.
"crop_land": área usada para cultivo.
"grazing_land": área usada para pastagem.
"forest_land": área usada para florestas.
"fishing_ground": área usada para pesca.
"built_up_land": área usada para áreas construídas.
"carbon": pegada de carbono.
"total": pegada ecológica total.
"QScore": pontuação de qualidade.

Na coluna "record" as linhas são usadas para diferenciar o registro de cada um das medições, tais registros são, respectivamente:

"AreaPerCap" e "AreaTotHA": área destinada per capita e total em hectare.
"BiocapPerCap" e "BiocapTotGHA": biocapacidade per capita e total em hectare.
"EFConsPerCap" e "EFConsTotGHA": consumo per capita e total em hectare.
"EFExportsPerCap" e "EFExportsTotGHA" exportação per capita e total em hectare.
"EFImportsPerCap" e "EFImportsTotGHA" importação per capita e total em hectare.
"EFProdPerCap" e "EFProdTotGHA" produção per capita e total em hectare.

É importante destacar que foi preciso retirar linhas com dados faltantes a partir do comando dropna, além disso foi preciso escolher um dos registros assim, o utilizado foi o da biocapacidade total, a escolha se deu pois biocapacidade é uma medida da capacidade de uma região em produzir resursos renováveis e absorver resíduos, sendo uma informação que por só já diz muito sobre a sustentabilidade dessa região, devido a isso esse tipo de informação foi a favorita para trabalho pelos membros do grupo.
