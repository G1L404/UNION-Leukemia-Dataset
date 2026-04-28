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

| Nome da Base Original | Autores / Instituição | Quantidade de Amostras | Referencia (Link) |
| :--- | :--- | :---: | :--- |
| **ALL-IDB** | Labati et al. (Universidade de Milão) | [Inserir Número] | [Aceder ao Dataset](http://link-para-all-idb.com) |
| **C-NMC (ISBI 2019)** | Gupta et al. | [Inserir Número] | [Aceder ao Dataset](http://link-para-cnmc.com) |
| **[Nome da Base 3]** | [Autor ou Instituição] | [Inserir Número] | [Aceder ao Dataset](http://link...) |
| *(...adicionar as restantes até completar as 17)* | | | |

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
