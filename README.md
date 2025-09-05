# Desafio de Projeto DIO: Análise de Sentimentos com Language Studio no Azure AI

Este repositório documenta a jornada de aprendizado e exploração das ferramentas de Inteligência Artificial da Microsoft Azure, especificamente o **Language Studio** e o **Speech Studio**. O objetivo deste desafio é praticar a análise de linguagem natural e demonstrar a compreensão dos serviços cognitivos do Azure.

## ✒️ Descrição do Projeto

Este laboratório prático focou na utilização do Azure Language Studio para realizar a análise de sentimentos em textos. O processo envolveu a configuração de recursos no portal do Azure, a exploração da interface do Language Studio e a execução de testes com diferentes tipos de frases para avaliar a precisão da IA na identificação de sentimentos (positivo, negativo, neutro e misto).

## 🤖 Ferramentas Utilizadas

* **Microsoft Azure**: Plataforma de nuvem utilizada para criar e gerenciar os recursos de IA.
    * **Azure AI Language Studio**: Ferramenta principal para análise de sentimentos e mineração de opinião.
    * **Azure AI Speech Studio**: (Opcional) Utilizado para explorar funcionalidades de conversão de texto em fala e reconhecimento de fala.
* **GitHub**: Utilizado para a criação do repositório e documentação do projeto.
* **Markdown**: Linguagem de marcação para formatar o arquivo README.md.

## ⚙️ Passo a Passo da Exploração

### 1. Criação do Recurso no Portal Azure

O primeiro passo foi criar um recurso de **Serviços Cognitivos** no portal do Azure. Este recurso centraliza os serviços de linguagem e fala, fornecendo as chaves de API e o ponto de extremidade necessários para acessar os estúdios de IA.



![Criação do Recurso no Azure](images/criar_recurso.png)

### 2. Análise de Sentimentos no Language Studio

Com o recurso configurado, acessei o **Language Studio** e utilizei a funcionalidade de **Análise de Sentimentos e Mineração de Opiniões**.

**Testes Realizados:**

Foram submetidos textos com diferentes cargas emocionais para observar a resposta da IA.

* **Texto Positivo:** "Estou muito feliz com o resultado do projeto! A equipe fez um trabalho excelente."
* **Texto Negativo:** "O produto chegou com defeito e o suporte ao cliente não resolveu meu problema."
* **Texto Misto:** "O design do aplicativo é incrível, mas a performance em dispositivos mais antigos é muito lenta."

**Resultados e Insights:**

A ferramenta conseguiu identificar com precisão o sentimento geral de cada frase e, no caso do texto misto, foi capaz de apontar os sentimentos associados a cada aspecto (aspect-based sentiment analysis).



### 3. (Opcional) Exploração do Speech Studio

Para complementar o estudo, explorei o **Speech Studio** para entender como os serviços de voz e linguagem podem ser integrados. Realizei um teste simples de **Speech-to-text** (Fala para Texto), onde um áudio foi transcrito. O texto resultante poderia ser, em uma aplicação real, enviado diretamente para a API de Análise de Sentimentos.



## ✨ Conclusão

Este desafio foi uma excelente oportunidade para aplicar de forma prática os conceitos de Inteligência Artificial e Processamento de Linguagem Natural utilizando os serviços do Azure. As ferramentas são intuitivas e poderosas, permitindo que mesmo usuários iniciantes possam experimentar e construir soluções de IA. A análise de sentimentos se mostrou robusta, oferecendo insights valiosos que poderiam ser aplicados em cenários de negócios, como análise de feedback de clientes ou monitoramento de redes sociais.

## 🔗 Links Úteis

* [Documentação do Azure Language Studio](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/language-studio)
* [Documentação do Azure Speech Studio](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-studio)
* [Meu Perfil na DIO](https://web.dio.me/users/SEU_USUARIO_AQUI)

---
