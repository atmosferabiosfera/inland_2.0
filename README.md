# inland_2.0


    Modelo Inland 2.0 - 06/03/2018

         Descrição:

         - Módulo de culturas agrícolas ( Soja, Milho, Trigo e Cana-de-Açúcar );
         - Suporte a parametrização vegetação heterogênea espacializada;
         - Subgrid tile;
         - Código migrado do ccm3-ibis e ibis/sage;
         - Subrotinas separadas em arquivos;
         - Padronização estrutural do código (F90, Precisão Dupla, Alocação Dinâmica);
         - Implementado o GNU Build System;
         - Baixo consumo de memória;
         - Compatibilidade com diferentes compiladores (gfortran, ifort e pgf90);
         - Implementado OpenMP;
         - Subrotina para leitura externa de C02;
         - Mudança de inland.infile para namelist;
         - Restart para simulações em modo GRID (Dinâmica da Vegetação ativa ou cold-start);
         - Modelo preparado para simulações com dados observacionais diários e/ou mensais;
         - Modo de simulação (Global, Regional, Single-Point) .       
