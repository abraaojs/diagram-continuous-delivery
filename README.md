# diagrama-continuous-delivery-
diagrama de continuous delivery 

Docker é a plataforma aberta para construir, enviar e executar aplicativos distribuídos, em qualquer lugar. No núcleo da solução Docker está um serviço de registro para gerenciar imagens e o Docker Engine para construir, enviar e executar contêineres de aplicativos. As práticas de Integração Contínua (IC) e Entrega Contínua (DC) emergiram como o padrão para testes e entrega de software moderno. A solução Docker acelera e otimiza pipelines CI / CD, mantendo uma clara separação de preocupações entre as equipes de desenvolvimento e operações.

Implantaço do continuous-delivery usando um pipeline CI composto de Docker, GitHub, Jenkins e Docker Trusted Registry (DTR). O pipeline será lançado por um commit para um repositório GitHub. O commit fará Jenkins executar (3) construir + empurrar para trabalhos DTR em um escravo Jenkins.


