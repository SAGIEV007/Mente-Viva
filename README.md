 🌟 Assistente Inteligente para a Melhor Idade

**Assistente virtual que combate a solidão e exclusão digital de idosos, oferecendo conversas empáticas, notícias simplificadas, gerenciamento de medicamentos e acesso facilitado a serviços essenciais.**

## 📑 Índice
- [Sobre o Projeto](#-um-companheiro-digital-para-a-melhor-idade-resgatando-conexões-com-inteligência-artificial)
- [O Problema da Exclusão Digital](#-a-dor-silenciosa-da-exclusão-digital)
- [Nossa Solução](#-nossa-solução-simplicidade-com-propósito)
- [Inovações Técnicas](#-inovações-técnicas-que-fazem-a-diferença)
- [Como Funciona](#-como-funciona-tecnologia-a-serviço-da-inclusão)
- [Funcionalidades Detalhadas](#-funcionalidades-detalhadas)
- [Como Acessar no Colab](#-como-acessar-no-colab)
- [Impacto Social](#-impacto-social-e-benefícios)
- [Contribua com o Projeto](#-contribua-com-o-projeto)
- [Licença](#-licença)


<img src="https://github.com/user-attachments/assets/41ad6445-2e23-49cd-aa31-72c038bc404a" alt="idoso_usando_app" width="400">


## 👵 Um Companheiro Digital para a Melhor Idade: Resgatando Conexões com Inteligência Artificial

Em um mundo que avança tecnologicamente a passos largos, nossos queridos idosos muitas vezes ficam para trás, enfrentando não apenas a solidão física, mas também o isolamento digital. Enquanto jovens navegam com facilidade por aplicativos e redes sociais, muitos de nossos pais e avós observam essa revolução tecnológica com um misto de curiosidade e apreensão.

Imagine um cenário diferente: um rosto amigo digital que conversa em linguagem simples, que lembra dos medicamentos importantes, que filtra apenas as notícias relevantes, e que torna a tecnologia uma aliada, não uma barreira. Este é o propósito do nosso **Assistente Inteligente para a Melhor Idade** - uma ponte entre gerações, construída com empatia e tecnologia acessível.

## 💔 A Dor Silenciosa da Exclusão Digital

<img src="https://github.com/user-attachments/assets/dd58b2ae-e5f8-451b-a6ff-7024637240bf" alt="estatisticas_idosos" width="350">


A exclusão digital entre idosos não é apenas uma questão de acesso à tecnologia, mas também de design e usabilidade. Interfaces complexas, termos técnicos e a necessidade de configurações avançadas criam barreiras quase intransponíveis. Quando um idoso desiste de usar um aplicativo após várias tentativas frustradas, não perdemos apenas um usuário - perdemos uma oportunidade de conexão, de acesso à informação, de independência.

Os números são reveladores: enquanto 56% dos idosos brasileiros já acessam a internet, muitos o fazem de forma limitada, frequentemente dependendo de ajuda de familiares para tarefas básicas. Ao mesmo tempo, 39% relatam sentimentos de solidão, um problema que poderia ser amenizado com maior inclusão digital.

## 💡 Nossa Solução: Simplicidade com Propósito

Desenvolvemos um assistente virtual especialmente pensado para idosos, com quatro pilares fundamentais:

<img src="https://github.com/user-attachments/assets/22c59f9c-754f-492e-9733-dcf705becc3a" alt="fluxograma_app" width="350">


1. **Conversa Empática**: Um chatbot que fala português brasileiro com referências culturais familiares, pronto para conversar sobre o dia, contar uma piada ou simplesmente fazer companhia.

2. **Notícias Relevantes**: Curadoria inteligente de notícias sobre saúde, finanças e bem-estar, apresentadas em linguagem simples e direta.

3. **Compromissos e Medicamentos**: Sistema de lembretes para consultas médicas e horários de medicamentos

4. **Utilidades Práticas**: Acesso rápido a serviços essenciais como INSS, SUS e outros sites úteis para o dia a dia.

## 🚀 Inovações Técnicas que Fazem a Diferença

<img src="https://github.com/user-attachments/assets/2419a54a-1b8b-4eb0-8bc5-0b2b3649aacb" alt="arquitetura_sistema" width="350">


Nossa maior inovação foi tornar o sistema **acessível para todos**, sem necessidade de configurações técnicas complexas:

- **Funcionamento Dual**: O sistema agora opera com ou sem a API do Google, adaptando-se automaticamente à disponibilidade da chave.
- **Persistência Local**: Compromissos e medicamentos são salvos localmente, permitindo consulta e gerenciamento mesmo após reiniciar o aplicativo.
- **Interface Simplificada**: Botões grandes, textos legíveis e navegação intuitiva, pensados especialmente para quem tem pouca familiaridade com tecnologia.

## 🧠 Como Funciona: Tecnologia a Serviço da Inclusão

O assistente utiliza uma arquitetura flexível que combina:

1. **Interface Gradio**: Criamos uma interface web amigável e responsiva usando Gradio, com abas claramente definidas e elementos visuais intuitivos.

2. **Lógica Adaptativa**: O sistema detecta automaticamente se possui acesso à API do Google Gemini. Se disponível, utiliza inteligência artificial avançada; caso contrário, recorre a respostas pré-definidas cuidadosamente elaboradas.

3. **Armazenamento TinyDB**: Utilizamos um banco de dados leve e eficiente para armazenar histórico de conversas, compromissos e medicamentos, garantindo que nenhuma informação importante seja perdida.

4. **Conexão Opcional com APIs Externas**: Para usuários que possuem uma chave de API do Google, o sistema oferece recursos avançados como pesquisa em tempo real e análise de notícias.

## 📋 Funcionalidades Detalhadas

### 💬 Conversa Empática
O módulo de conversa foi projetado para ser mais que um simples chatbot - é um companheiro digital. Ele compreende o contexto das conversas, responde com empatia e pode discutir desde assuntos cotidianos até memórias do passado, sempre em um tom acolhedor e respeitoso.

### 📰 Curadoria de Notícias
O sistema filtra o imenso volume de informações disponíveis na internet para apresentar apenas o que é relevante para o usuário idoso. As notícias são resumidas em linguagem simples, sem jargões técnicos ou termos complexos.

### 🗓️ Gerenciamento de Compromissos e Medicamentos
Agora totalmente funcional! Os usuários podem:
- Adicionar compromissos com título, data e horário
- Visualizar todos os compromissos agendados
- Remover compromissos quando necessário
- Cadastrar medicamentos com nome, dosagem, frequência e horário
- Gerenciar a lista de medicamentos com facilidade

### 🔗 Acesso Rápido a Serviços Essenciais
Links diretos para sites importantes como INSS, SUS, Gov.br e outros, eliminando a necessidade de digitar URLs complexas ou navegar por menus de busca.


## 💻 Como Acessar no Colab
1. Acesse este notebook no Colab:
   [Abra este notebook no Colab](https://colab.research.google.com/github/SAGIEV007/Imersao-Alura-IA2025/blob/main/Assistente_pessoal_para_melhor_idade.ipynb)
Defina sua API Key em Secrets(Caso não tenha):

Abra o painel lateral e selecione 🔒 Secrets
Crie a variável GOOGLE_API_KEY com sua chave pessoal


## 🛠️ Como Instalar e Usar sem o Colab

### Pré-requisitos
- Python 3.6 ou superior
- Pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório ou baixe os arquivos:
```bash
git clone https://github.com/seu-usuario/assistente-idosos.git
cd assistente-idosos
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o aplicativo:
```bash
python app.py
```

### Configuração (Opcional)
Para utilizar recursos avançados com a API do Google Gemini:

1. Crie um arquivo `.env` na raiz do projeto
2. Adicione sua chave de API:
```
GOOGLE_API_KEY=sua_chave_aqui
```

**Importante**: O aplicativo funciona perfeitamente mesmo sem a chave de API!

## 🌈 Impacto Social e Benefícios

O Assistente Inteligente para a Melhor Idade vai além da tecnologia - é uma ferramenta de transformação social:

- **Combate à Solidão**: Oferece companhia e interação social, especialmente importante para idosos que vivem sozinhos.
- **Autonomia Digital**: Permite que idosos acessem informações e serviços sem depender constantemente de ajuda.
- **Saúde e Bem-estar**: Ajuda a manter rotinas de medicação e compromissos médicos, contribuindo para melhor qualidade de vida.
- **Inclusão Informacional**: Democratiza o acesso à informação relevante e confiável, adaptada às necessidades específicas.

## 🤝 Contribua com o Projeto

Este é um projeto em constante evolução, e sua contribuição é valiosa! Algumas formas de ajudar:

- **Desenvolvedores**: Implemente novas funcionalidades ou melhore as existentes
- **Designers**: Torne a interface ainda mais acessível e atraente
- **Especialistas em Gerontologia**: Sugira melhorias baseadas em conhecimentos específicos sobre as necessidades dos idosos
- **Usuários**: Compartilhe feedback sobre a experiência de uso

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Desenvolvido com ❤️ para aproximar gerações através da tecnologia.
