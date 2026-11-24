# projeto-hemodepressao\
**Projeto HemoDepressão — Protótipo de Software**\
**Software desenvolvido para fins acadêmicos e institucionais, sem registro formal de patente ou licença comercial vinculada.**\
**Objetivo:** Digitalizar e automatizar a aplicação do Inventário de Autoavaliação de Ansiedade em pacientes submetidos a tratamento de hemodiálise.

**Idealização / Concepção:** Profa. Dra. Fabiana de Souza Orlandi\
**Desenvolvimento Low-Code (End-to-End) e UI/UX Design:** Rita de Cassia Zanetti Marchi\
**Instituição:** Universidade Federal de São Carlos (UFSCar)\
**Front-end / Interface:** Microsoft Power Apps\
**Linguagem de Fórmulas:** Power Fx\
**Microsoft Power Platform (Web, Android e iOS via Power Apps Mobile)**\
**Banco de Dados: Microsoft SharePoint (Listas Relacionais)**

**Status atual:** Pausado. No aguardo de etapas futuras (MVP funcional concluído)\
**Nível de validação:** 0 - O protótipo encontra-se totalmente funcional, realizando o fluxo completo de preenchimento, cálculo/processamento e gravação estruturada dos dados no banco de dados.\
**Testes realizados:** O protótipo funcional do aplicativo em andamento foi apresentado à idealizadora, obtendo avaliação positiva quanto à interface, usabilidade e aderência aos objetivos propostos.\
**Aviso de Uso Clínico:** Esta versão destina-se apenas à demonstração técnica e simulação de ambiente. O protótipo ainda não está liberado para aplicação direta com pacientes/usuários finais.\
**O código-fonte e os arquivos da aplicação encontram-se disponibilizados neste repositório no estágio atual de desenvolvimento para fins de registro, transparência e continuidade futura.**\
**Mês / Ano de desenvolvimento:** 05/2026 à 09/2026

**Notificação e Relatório Automatizado:** Ao acionar o comando de gravação, o sistema envia automaticamente uma cópia estruturada das respostas ao profissional de saúde responsável pela avaliação psicológica do paciente. O relatório discrimina cada questão, sua respectiva pontuação individual e o escore total obtido, permitindo identificar rapidamente os itens de maior impacto e subsidiar a definição de estratégias terapêuticas personalizadas.
**Exemplo** e-mail gerado:

Olá, segue Avaliação Final do Paciente: Nome do Paciente

1. Sente-se angustiado(a) ou mal-humorado(a)? = 2\
2.Redução da interação social (falta de vontade de se comunicar com outras pessoas? = 1\
3.Perda de interesse do autocuidado (perda de interesse em se vestir, em se arrumar)? = 1\
4.Falta de motivação para fazer as coisas no dia a dia? = 2\
5.Sente-se culpado(a) ou com sentimento de culpa? = 3\
6.Sente-se um peso na situação econômica (financeira) da família? = 1\
7.Sente-se um peso na situação psicológica (emocional) da família? = 2\
8.Sente-se desvalorizado(a) ou fracassado(a)? = 3\
9.Tem pensamentos constantes de morte, incluindo ideias de suicídio? = 1\
10.Sente-se incapaz de realizar qualquer coisa? = 0\
11.Sente-se pessimista ou decepcionado(a)? = 3\
12.Sente que precisa se esforçar muito para se concentrar em algo? = 2\
13.Sente perda de interesse em atividades que antes gostava? = 3\
14.Sente-se sozinho(a)? = 2\
15.Chora facilmente? = 3\
16.Tem se movimentado mais devagar e demorado a responder? = 2\
17.Tem perda de memória (dificuldade em se lembrar de algo)? = 3\
18.Sente-se indigno (merecedor) para receber cuidados dos outros? = 3
   

Pontuação Total: 37


abaixo, nome e tipo de cada campo no sharepoints denominado: HemoAvaliacaoAnsiedade
 
| Nome do Campo | Tipo do Campo |
| :--- | :--- |
| `Titulo` | Texto com uma linha |
| `NomePaciente` | Texto com uma linha |
| `DataNascimento` | Data e Hora |
| `Sexo` | Opção |
| `DataAvaliacao` | Data e Hora |
| `Pergunta1` | Texto com várias linhas |
| `Resposta1` | Número |
| `Pergunta2` | Texto com várias linhas |
| `Resposta2` | Número |
| `Pergunta3` | Texto com várias linhas |
| `Resposta3` | Número |
| `Pergunta4` | Texto com várias linhas |
| `Resposta4` | Número |
| `Pergunta5` | Texto com várias linhas |
| `Resposta5` | Número |
| `Pergunta6` | Texto com várias linhas |
| `Resposta6` | Número |
| `Pergunta7` | Texto com várias linhas |
| `Resposta7` | Número |
| `Pergunta8` | Texto com várias linhas |
| `Resposta8` | Número |
| `Pergunta9` | Texto com várias linhas |
| `Resposta9` | Número |
| `Pergunta10` | Texto com várias linhas |
| `Resposta10` | Número |
| `Pergunta11` | Texto com várias linhas |
| `Resposta11` | Número |
| `Pergunta12` | Texto com várias linhas |
| `Resposta12` | Número |
| `Pergunta13` | Texto com várias linhas |
| `Resposta13` | Número |
| `Pergunta14` | Texto com várias linhas |
| `Resposta14` | Número |
| `Pergunta15` | Texto com várias linhas |
| `Resposta15` | Número |
| `Pergunta16` | Texto com várias linhas |
| `Resposta16` | Número |
| `Pergunta17` | Texto com várias linhas |
| `Resposta17` | Número |
| `Pergunta18` | Texto com várias linhas |
| `Resposta18` | Número |
| `HoraAvaliacaoI` | Data e Hora |
| `HoraAvaliacaoF` | Data e Hora |
| `PontuacaoTotal` | Número |
| `Modificado` | Data e Hora |
| `Criado` | Data e Hora |
| `Criado por` | Pessoa ou Grupo |
| `Modificado por` | Pessoa ou Grupo |



