# UNION Macro-Dataset: Imagens Hematológicas para Diagnóstico de Leucemias Agudas

Este repositório contém a documentação oficial e as referências de origem do *macro-dataset* **UNION**, desenvolvido e utilizado no artigo *"Abordagem Híbrida CNN-Mamba para Diagnóstico Computacional de Leucemias Agudas em Imagens Hematológicas"*, aprovado no **Simpósio Brasileiro de Computação Aplicada à Saúde (SBCAS) 2026**.

## 📌 Sobre o UNION

O diagnóstico automatizado de leucemias enfrenta um grande obstáculo: a elevada variabilidade morfológica causada por diferentes protocolos de coloração, dispositivos de aquisição e contextos multicêntricos. 

Para avaliar a robustez de modelos de Inteligência Artificial perante esta heterogeneidade interlaboratorial, construímos o **UNION**, um agrupamento de **17 bases de dados públicas e independentes**, totalizando **3.157 amostras celulares** categorizadas em:
* **HBS** (*Healthy Blood Slides* - Células Saudáveis)
* **ALL** (Leucemia Linfoide Aguda)
* **AML** (Leucemia Mieloide Aguda)

## ⚠️ Nota sobre Licenciamento e Acesso aos Dados

Por questões de licenciamento, direitos de autor e restrições de redistribuição impostas pelas instituições criadoras de cada *dataset* original, **não disponibilizamos os ficheiros de imagem diretamente neste repositório**. 

Abaixo, fornecemos a listagem completa de todas as fontes. Os investigadores interessados em reproduzir os nossos resultados ou utilizar o UNION devem aceder às ligações oficiais para transferir os dados originais.

## 📊 Composição do Macro-Dataset

O UNION é composto por 17 partições provenientes de bases públicas independentes, totalizando 3.157 amostras. Abaixo encontra-se o detalhamento quantitativo e as referências para acesso aos dados originais:

| Nome da Base Original | Autores / Instituição | Quantidade de Amostras | Referência (Link) |
| :--- | :--- | :---: | :--- |
| **ALL-IDB1 (Crop)** | Labati et al. (Universidade de Milão) | 510 | [Aceder ao Dataset]([Inserir Link]) |
| **ALL-IDB1** | Labati et al. (Universidade de Milão) | 108 | [Aceder ao Dataset]([Inserir Link]) |
| **ALL-IDB2** | Labati et al. (Universidade de Milão) | 260 | [Aceder ao Dataset]([Inserir Link]) |
| **CellaVision2** | CellaVision / [Inserir Autores] | 100 | [Aceder ao Dataset]([Inserir Link]) |
| **CELAVISION** | CellaVision / [Inserir Autores] | 109 | [Aceder ao Dataset]([Inserir Link]) |
| **ATLAS** | Atlas of Hematology | 65 | [Aceder ao Dataset]([Inserir Link]) |
| **Omid et al. 2014** | Omid et al. | 154 | [Aceder ao Dataset]([Inserir Link]) |
| **Omid et al. 2015** | Omid et al. | 27 | [Aceder ao Dataset]([Inserir Link]) |
| **ASH-OK** | ASH Image Bank | 96 | [Aceder ao Dataset]([Inserir Link]) |
| **Bloodline** | Bloodline Image Atlas | 204 | [Aceder ao Dataset]([Inserir Link]) |
| **ONKODIN** | Onkodin Image Base | 78 | [Aceder ao Dataset]([Inserir Link]) |
| **JTSC** | [Inserir Autores/Instituição] | 300 | [Aceder ao Dataset]([Inserir Link]) |
| **UFG** | Universidade Federal de Goiás (UFG) | 93 | [Aceder ao Dataset]([Inserir Link]) |
| **SN-AM** | [Inserir Autores/Instituição] | 30 | [Aceder ao Dataset]([Inserir Link]) |
| **MIDB Dataset** | [Inserir Autores/Instituição] | 498 | [Aceder ao Dataset]([Inserir Link]) |
| **LISC Dataset** | Rezatofighi et al. | 376 | [Aceder ao Dataset]([Inserir Link]) |
| **Leukocytes** | [Inserir Autores/Instituição] | 149 | [Aceder ao Dataset]([Inserir Link]) |
| **TOTAL GERAL** | - | **3.157** | - |
> **Dica para reprodução:** Após transferir todas as bases acima, recomendamos a aplicação da padronização de nomenclatura e o redimensionamento dinâmico descritos na secção de pré-processamento do nosso artigo.

## ✒️ Como Citar

Se utilizares a estrutura conceitual do UNION ou a nossa arquitetura híbrida CNN-Mamba na tua investigação, por favor, cita o nosso trabalho:

```bibtex
@inproceedings{morais2026abordagem,
  title={Abordagem Híbrida CNN-Mamba para Diagnóstico Computacional de Leucemias Agudas em Imagens Hematológicas},
  author={Morais, Gilclécio S. and Sousa, Gabriel C. and Claro, Maíla L. and Veras, Rodrigo M. S. and Valerio, Julian R. and Araújo, Selles G. F. C. and Gonçalves, Clésio A. and Silva, José C. J.},
  booktitle={Anais do Simpósio Brasileiro de Computação Aplicada à Saúde (SBCAS)},
  year={2026},
  organization={SBC}
}
