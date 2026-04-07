# A Systematic Approach to Multilingual Audio-Visual Speech Recognition Models

AlexandrePereira

This systematic literature review pave a pathway to understanding how Audio-Visual Speech Recognition Models work and compare state-of-art models showing performance and metrics including best use cases for each one.

## Planning

Analisar e sintetizar sistematicamente pesquisas sobre modelos de tradução audiovisual multilíngue de fala para fala (AV-S2ST), com foco em sua adaptabilidade multilíngue, estratégias de fusão multimodal, métricas de desempenho (por exemplo, pontuações BLEU, precisão de sincronização), robustez ao ruído e avaliação em conjuntos de dados de referência. A revisão comparará diferentes abordagens arquitetônicas, incluindo aprendizagem autosupervisionada e síntese baseada em unidades discretas, ao mesmo tempo que identificará desafios importantes, como escassez de dados, fidelidade de sincronização e escalonamento multilíngue. Além disso, destacará lacunas nos conjuntos de dados de referência, usabilidade em tempo real e generalização multilíngue imediata.

### PICOC

- **Population:** Modelos completos de tradução audiovisual multilíngue de fala para fala projetados para mapear diretamente a fala audiovisual de um idioma para outro, sem representação intermediária de texto.
- **Intervention:** Técnicas que melhoram os modelos AV-S2ST: treinamento multilíngue, mecanismos de sincronização/sincronização labial, robustez ao ruído, pré-treinamento autossupervisionado e fusão multimodal.
- **Comparison:** Comparação entre modelos end-to-end e modelos cascata, só áudio e áudio-visual e estratégias de sincronização (baseadas em perdas, modelos de duração, rastreamento 3D)
- **Outcome:** Identificação de melhores práticas, avaliação de desempenho multimodal e multilíngue, resolução de desafios e orientação de futuras direções de pesquisas.
- **Context:** Campos de pesquisa que cruzam AV-S2ST: Tradução Automática, PNL Multilíngue, Síntese de Fala, Dublagem de IA e Ferramentas Assistivas de Tradução AV. Abrange aplicações multimídia do mundo real

### Research Questions

- Como os modelos AV-S2ST integram modalidades audiovisuais (por exemplo, movimentos labiais) para melhorar a precisão e robustez da tradução e garantem uma sincronização labial precisa?
- Como os modelos AV-S2ST são dimensionados em vários idiomas e quais técnicas melhoram a tradução frente a falta de conjuntos de dados audiovisuais multilíngues em grande escala?
- Quais métricas são usadas para avaliar os modelos AV-S2ST e como elas equilibram a precisão da tradução (BLEU) e a sincronização audiovisual (LSE-D, MOS)?
- Quais técnicas melhoram o desempenho do modelo AV-S2ST em ambientes ruidosos e como a informação visual contribui para a robustez?

### Keywords and Synonyms

| Keyword                              | Synonyms |
| ------------------------------------ | -------- |
| AV-S2ST                              |          |
| Audio-Only vs. AV Models             |          |
| BLEU                                 |          |
| Cross-Modal Fusion                   |          |
| End-to-End Models                    |          |
| End-to-End vs. Cascaded Systems      |          |
| LSE-D                                |          |
| Lip-Sync Loss                        |          |
| Low-Resource Languages               |          |
| MOS                                  |          |
| Multilingual Speech Translation      |          |
| Pretrained Speech Models vs. AV-S2ST |          |
| Self-Supervision                     |          |
| Speaker Retention                    |          |
| Speech Robustness                    |          |
| Synchronization Error                |          |
| Talking Heads                        |          |
| Temporal Alignment                   |          |
| WER                                  |          |

### Search String

("speech-to-speech translation" OR "S2ST" OR "speech translation")  
<br/>AND ("end-to-end" OR "direct" OR "unit-based" OR "self-supervised" OR "cross-modal" OR "transformer")  
<br/>AND ("audio-visual" OR "multimodal" OR "lip-synchrony" OR "lip-sync" OR "visual speech" OR "talking head")  
<br/>AND ("multilingual" OR "cross-lingual" OR "zero-shot" OR "low-resource language")  
<br/>AND ("BLEU" OR "word error rate" OR "WER" OR "LSE-D" OR "LSE-C" OR "MOS" OR "synchronization")

### Sources

- ACM Digital Library (<https://dl.acm.org/>)
- ArXiv (<https://arxiv.org/>)
- Elsevier ScienceDirect (<https://www.sciencedirect.com/>)
- IEEE Xplore (<https://ieeexplore.ieee.org/>)

### Selection Criteria

**Inclusion Criteria:**

- O artigo analisa como informações visuais contribuem para a inteligibilidade e qualidade perceptual da fala traduzida?
- O artigo propõe novos métodos ou aprimoramentos para modelos end-to-end de AV-S2ST?
- O artigo trata de desafios específicos na tradução de múltiplos idiomas, como interferência entre línguas ou aprendizado zero-shot?
- O estudo aborda limitações de dados e testa metodologias para melhorar o desempenho em cenários de poucos recursos?
- O estudo investiga como diferentes estratégias de fusão audiovisual afetam a precisão e naturalidade da tradução?
- O estudo propõe ou avalia novas métricas para balancear fidelidade da tradução e sincronização audiovisual?

**Exclusion Criteria:**

- O artigo enfatiza apenas um idioma ou não discute estratégias para tradução multilíngue?
- O artigo foca em tradução de fala, mas sem considerar integração audiovisual?
- O artigo ignora aspectos perceptuais importantes, como realismo da sincronização labial ou qualidade audiovisual combinada?
- O estudo não testa métodos que possam ser generalizados para modelos de AV-S2ST ou não discute implicações para casos práticos?
- O estudo trata apenas de reconhecimento ou síntese de fala, sem abordar tradução entre idiomas?
- O estudo usa métricas padrão de tradução ou síntese, sem adaptar a avaliação para um contexto audiovisual?

### Quality Assessment Checklist

**Questions:**

**Answers:**

### Data Extraction Form

## Conducting

### Digital Libraries Search Strings

### Imported Studies

- **ACM Digital Library:** 18
- **ArXiv:** 129
- **Elsevier ScienceDirect:** 22
- **IEEE Xplore:** 78
