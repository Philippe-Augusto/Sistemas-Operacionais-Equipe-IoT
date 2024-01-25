# Sistemas-Operacionais-Equipe-IoT

Nome da Equipe: IoT

Integrantes: 

FABRICIO SILVA DIAS - 202203506

FILIPE AUGUSTO LIMA SILVA - 202203508

GUILHERME PEREIRA FERNANDES - 202203510

JOAO FELIPE PERES LIMA - 202203515

PHILIPPE AUGUSTO MONTEIRO SILVA - 202203529

# *Introdução*
A Internet das Coisas(IoT) ou "Internet of Things" é um conceito abrangente, criado por Kevin Ashton, piorneiro tecnológico britânico, em 1999 e a comunicação entre objetos físicos, por meio da internet, com objetivo de coletar, transmitir ou trocar dados teve início em 1990 por meio da Internet Toaster criada por John Romkey.

A IoT é um tema emergente de importância no âmbito social e também ecônomico. Esses dispositivos vêm transformando as formas de viver, realizar atividades ou trabalhar. Presente em vários âmbitos sociais, como : Na saúde, possibilitando o monitoramento remoto de pacientes e gestão de medicamentos; Em cidades inteligentes, otimiza o tráfego, melhora a gestão de resíduos e promove a segurança pública; Na agricultura, sensores monitoram condições climáticas e otimizam a irrigação; Na indústria, contribui para manufatura inteligente e manutenção preditiva. Essas aplicações, entre outras, destacam a versatilidade da IoT na transformação positiva de setores e na qualidade de vida.

Entretanto, conforme cresce o uso de IoT na sociedade, os ataques cibernéticos à estes dispositivos também cresce de maneira equivalente, segundo relatórios da Check Point Software Technologies, empresa de soluções de segurança digital, no ano de 2023 mais de 50\% das organizações foram alvos de ataques direcionados a dispositivos IoT, como roteadores, câmeras IP e impressoras. 

Não obstante, tivemos um transformação tecnológica impulsionada pela pandemia da covid-19, onde redes de aprendizado e empresas aderiram a ambientes digitais de comunicação. Como consequência disto o uso de câmeras IP e demais dispositivos IoT tornaram-se mais comuns, aumentando as entradas possíveis para os cibercriminosos e dificultando mais as formas de garantir a integridade de informações. Entre os setores mais afetados a educação e pesquisas estão entre os principais alvos de ataques, concentrando 131 ataques semanais.

A vasta quantidade de dispositivos conectados aumenta a exposição a ameaças, e na tentativa de mitigar esses riscos é necessário que usuários e fabricantes compartilhem da responsabilidade cabível a ambas as partes. O fabricante na garantia de um projeto seguro, atualizações de Firmware, implementação de fortes meios de autenticação e fornecer informações sobre práticas segura, as quais devem ser seguidas pelo usuários, além de seguir essas instruções devem também manter o seu dispositivo atualizado, colocar senhas fortes e monitorar atividades suspeitas.

# *Fundamentos Teóricos*
Todo dispositivo conectado à internet está vulnerável a ataques cibernéticos, e existem diversas possibilidades e pontos visados em cada tipo de ataque, cada um utilizando uma vulnerabilidade diferente. Esses ataques podem ser divididos em três tipos:
* Ataques por Engenharia Social: Foco em manipular usuários para obtenção de informações confidenciais ou realizar ações prejudiciais (Pishing, Ransomware).
* Ataques ao Sistema: Foco em comprometer a integridade do sistema ou sua disponibilidade (Ataque de Negação de Serviço(DoS), Ataques de Força Bruta, Injeção de Código(SQL, XSS)).
* Ataques a Dispositivo IoT: Foco em ter acesso/controle sobre um dispositivo conectado(Exploração de vulnerabilidade em dispositivo IoT).
Para lidar com os ataques cibernéticos aliados a vulnerabilidade do sistema, têm-se os seguintes mecanismos:
1. *Ataques ao Sistemas*
  * Firewalls
  * Sistema de Detecção de Instrusões(IDS)
  * Sistemas de Prevenção de Intrusões
Esses mecanismo são mais utilizados na tentativa de prevenção dos ataques, atualizações em vulnerabilidades conhecidas e monitoramento  contínuo são também medidas válidas.
2. *Ataques por Engenharia Social*
  * Filtros de E-mail
  * Software Anti-Virus
Ressalta-se também o treinamento de usuários para reconhecer e evitar ataques de pishing
3. *Ataques a Dispositivos IoT*
  * Atualizações de Firmware
  * Segmentação de Rede
  * Políticas de Segurança
Manter os dispositivos IoT atualizados  com as últimas correções de segurança e patches de firmware é de suma importância, por corrigir as vulnerabilidades e melhorar a segurança global, junto com a implementação robusta, por meio de senhas fortes ou métodos multifatores dificultando a entrada de invasores. Firewall baseado em rede é também uma técnica válida, pois protege os dados assim que os mesmos entram na rede, permitindo também monitorar e bloquear o tráfego fora de sua VPN, muito útil principalmente em dispositivos M2M que possuem capacidade de processamento limitada.

Parte dos desafios encontrados, quanto ao assunto de segurança em dispositivos IoT se deve às particularidades únicas de cada ecossistema, visto a grande variedade de dispositivos, impossibilitando a criação de uma solução de forma universal. Além disso, muitos dos dispositivos são compactos e móveis, assim têm maiores limitações quanto a utilização de energia, capacidade de processamento  e também armazenamento, o que faz necessário soluções de segurança que além de eficazes sejam otimizadas, para não comprometer o desempenho.

Assim, buscando lidar com tal problema, pesquisas e trabalhos desenvolvidos, vêm progredindo e com isso cada vez mais desenvolvendo uma solução, algoritmos que visão consumar menos poder computacional energético, visto as limitações de dispositivos IoT. A Lightweight Cryptography (LWC) ou criptografia leve é um campo de estudo focado no desenvolvimento de algoritmos criptográficos eficientes e otimizados, visando seu uso em IoT e sistemas embarcados. Não obstante, o fato de se ter um foco na eficiência de recursos, esses algoritmos não deixam a desejar quanto à garantia de segurança. Vários padrões de especificações foram desenvolvidos para orientar o uso da LWC em diferentes contextos, destaca-se o NIST (National Institute of Standards and Technology) e a ISO (International Organization for Standardization). A demanda por algoritmos de criptografia leve cresceu significativamente, visto a maior facilidade em aprimorar a segurança destes dispositivos, do que substituí-los por equipamentos de maior poder de processamento. Existem alguns modelos de criptografia, como SPECK, HIGHT e SIMON.

O AES (Advanced Encryption Standard) é também um algoritmo de criptografia, porém de criptografia simétrica, no entanto, é até hoje uma solução que satisfaça a necessidade de segurança e, recentemente, foi proposto uma versão otimizada deste algoritmo, por meio da simplificação de suas funções, com menos custo de desempenho e consumo de armazenamento, visando seu uso em aplicações em IoT.

# *Metodologia*

Com o propósito de atingir os objetivos delineados neste trabalho, optou-se por realizar uma revisão narrativa de literatura, uma modalidade bibliográfica que possibilita uma busca não sistemática por informações, conforme destacado por Rother (2007). Essa abordagem envolve a escolha e seleção de bases de dados e periódicos científicos de maneira conveniente.

Em conformidade com o pressuposto acima e visando acessar um maior volume de trabalhos, os autores deste estudo conduziram a pesquisa no Google Acadêmico. Essa escolha foi motivada pela expectativa de encontrar uma quantidade significativa de artigos, uma vez que o Google Acadêmico é um agregador de bases de dados que engloba diversos periódicos.

O levantamento bibliográfico ocorreu no período de 15 a 22 de janeiro, utilizando os descritores "Internet das Coisas (IoT)" e "Segurança de dados". A busca foi limitada a artigos e sites, todos pertencentes à língua portuguesa. Para inclusão na pesquisa, os estudos localizados precisavam abordar e enfatizar a segurança de dados associada à IoT. Foi dada especial atenção aos artigos que apresentavam dados sobre ataques a dispositivos da Internet das Coisas, pois esta pesquisa visa realizar uma análise comparativa entre anos anteriores e o ano presente.

# *Resultado e Conclusões
Um estudo realizado por Sevin e Mohammed (2021), trás teste comparativos no uso de blockchiphers para IoT, e como resultado, os algoritmos PRESENT, SPECK, SIMON e CLEFIA fazem melhor o papel custo-benefício, consumindo menos armazenamento RAM/ROM e sem grande perda de velocidade. Partindo deste, em uma avaliação experimental, Vinícius et al. (2022) trouxeram testes, feita a aplicação deste códigos em equipamentos IoT da área da saúde, utilizando métricas de vazão e latência para analisar o impacto desses LWC. Foi concluído que dentre os algoritmos testados, o Present apresentou o menor desempenho satisfatível, apresentando uma baixa taxa de transferência, como consequência foi escolhido o descarte deste algoritmo. Por outro lado, o AES-256 CBC teve a melhor performance entre os testados, com maior velocidade tanto na encriptação como na desencriptação da mensagem. Os resultados apresentados por essa avaliação são os seguintes:

![Resultado Avaliação Desempenho](https://github.com/Philippe-Augusto/Sistemas-Operacionais-Equipe-IoT/assets/66576938/7b971238-dcab-4f2b-a10f-b5c72e161364)

Entretanto, quando analisados quanto ao consumo energético causado por estes algoritmos, não se tem uma conclusão, afinal, foram testados em diferentes aparelhos e a questão de hardware infere diferenças. Adiante, foram pontuadas diferentes formas de funcionamento, não chegando a concluir alguma semelhança entre os LWC.

Por fim, concluiu-se que os algoritmos AES-256 CBC, SPECK obtiveram os melhores resultados de desempenho, o SPECK, com menor variações abruptas nos quesitos de vazão e latência conforme maior demanda de transmissão, o AES-256 CBC obteve resultado semelhante mas com mudanças mais significativas conforme a crescente taxa de transmissão.

# *Referências*
[1] DE OLIVEIRA, Nairobi Spiecker et al. Segurança da informaçao para internet das coisas (iot): uma abordagem sobre a lei geral de proteçao de dados (lgpd). Revista Eletrônica de Iniciação Científica em Computação, v. 17, n. 4, 2019.
[2] CARVALHO, André Ferreira Almeida de; SANTOS, Christyan Matteus Lima; GONÇALVES, Lucas Vaz. Segurança em IoT. 2022.
[3] ABRANET. Ataques a disposiftivos da Internet das Coisas (IoT) crescem 41%. ABRANET. 24/04/2023. Disponível em: https://www.abranet.org.br/Noticias/Ataques-a-dispositivos-da-internet-das-coisas-(IoT)-crescem-41%25-4300.html? Acesso em: 16 jan. 2024.
[4] Carlos Campo. O que é Segurança em IoT? Riscos, Exemplos e Soluções. EMNIFY. Disponível em: https://www.emnify.com/pt-br/glossario-iot/seguranca-iot#:~:text=Falta%20de%20criptografia&text=Muitos%20dispositivos%20IoT%20n%C3%A3o%20criptografam,transmitidas%20para%20e%20do%20dispositivo.. Acesso em: 16 jan. 2024.
[5] VAZ, Yuri Silva; MATTOS, Júlio CB; SOARES, Rafael Iankowski. AES Otimizado para Uso em Aplicações IoT. In: Anais Estendidos do XIII Simpósio Brasileiro de Engenharia de Sistemas Computacionais. SBC, 2023. p. 31-36.
[6] SEVIN, Abdullah; MOHAMMED, Abdu Ahmed Osman. A survey on software implementation of lightweight block ciphers for IoT devices. Journal of Ambient Intelligence and Humanized Computing, v. 14, n. 3, p. 1801-1815, 2023.
[7] ZANON, Vinícius Rodrigues et al. Avaliação experimental de uma camada de segurança implementada em dispositivo vestível cardíaco para Internet das Coisas Médicas. In: Anais do XXII Simpósio Brasileiro em Segurança da Informação e de Sistemas Computacionais. SBC, 2022. p. 97-110.
