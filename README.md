
                                Modelo Integrado de Processos Superficiais - INLAND 

O Modelo Integrado de Processos Superficiais (Inland) é o pacote de superfície do Modelo Brasileiro do Sistema Climático Global. O projeto Inland é coordenado por Marcos Heil Costa <mhcosta@ufv.br> (UFV - www.ufv.br) e Gilvan Sampaio <gilvan.sampaio@inpe.br> (INPE - www.inpe.br), com financiamento dos programas Rede Clima e INCT do Ministério da Ciência, Tecnologia e Inovação.

Quando completado, o Inland vai representar diversos processos superficiais:

1. Biofísica do dossel, incluindo balanço de água e energia, formação de gelo, turbulência e  aerodinâmica;

2. Fisiologia vegetal, incluindo interceptação da luz, fotossíntese e respiração, condutância do dossel e interações com a fertilidade do solo;

3. Física do solo, incluindo balanço de água e energia, infiltração, escoamento superficial, e drenagem profunda;

4. Dinâmica de vegetação de curto prazo (fenologia);

5. Dinâmica de vegetação de longo prazo, incluindo GPP, NPP, alocação de carbono, crescimento primário e secundário, mortalidade e competição entre tipos funcionais de plantas;

6. Distúrbios e incêndios;

7. Fenologia e manejo de culturas agrícolas, incluindo datas de plantio, emergência, crescimento, enchimento de grãos, senescência e colheita;

8. Biogeoquímica de solos, com diferentes níveis de complexidade para carbono, nitrogênio e fósforo no solo;

9. Processos hidrológicos superficiais, incluindo rios, lagos, e áreas inundadas. 

O modelo é forçado por dados meteorológicos horários (versão pontual) ou dados climáticos regionais ou diários ou mensais (versão em grade), ou pode ser acoplado a modelos atmosféricos regionais ou globais.

Inland é baseado no modelo IBIS - Integrated Biosphere Simulator, desenvolvido pela Universidade de Wisconsin-Madison - https://www.wisc.edu/.

Modelo compatível com diferente compiladores (gfortran, ifort e pgf90) e paralelizado com OpenMP - https://www.openmp.org/

Principais caratacteristicas do modelo:

- Módulo de culturas agrícolas ( Soja, Milho, Trigo e Cana-de-Açúcar );
- Suporte a parametrização vegetação heterogênea espacializada;
- Subgrid tile;
- Subrotina para leitura externa de C02;
- Restart para simulações em modo GRID (Dinâmica da Vegetação ativa ou cold-start);
- Modelo preparado para simulações com dados observacionais diários e/ou mensais;
- Modo de simulação (Global, Regional, Single-Point).       
  
