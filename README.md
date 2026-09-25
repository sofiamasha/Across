# ACROSS

> **Antes de saber quem é, descubra quem é.**

O **ACROSS** é uma plataforma de conexão entre universitários criada para facilitar o primeiro passo na construção de novas amizades, conversas e redes de apoio dentro do ambiente acadêmico.

A proposta é simples: **conhecer alguém antes de descobrir quem essa pessoa é**.

Sem fotos como primeiro filtro. Sem pressão para revelar a identidade. Primeiro vem a conversa. Depois, se os dois quiserem, vem a identidade.

---

## 💡 O problema

A universidade é um ambiente cheio de pessoas, mas isso não significa que seja fácil criar conexões.

Estudantes, principalmente aqueles mais tímidos ou que estão começando sua trajetória acadêmica, podem encontrar dificuldades para:

* fazer novos amigos;
* iniciar conversas;
* criar networking;
* encontrar pessoas com interesses semelhantes;
* participar mais da vida universitária;
* apresentar trabalhos e se comunicar com segurança;
* encontrar alguém com quem possam conversar;
* sentir que pertencem ao ambiente acadêmico.

O problema chamou atenção justamente por fazer parte de um ambiente próximo da realidade da criadora do projeto.

Antes de definir a solução, foram realizadas conversas exploratórias com outros estudantes para entender dificuldades comuns na vida universitária, especialmente relacionadas à timidez, amizades e networking.

A partir dessas conversas surgiu uma questão:

> **E se fosse possível conhecer alguém primeiro pela personalidade e pelos interesses, sem que a aparência ou a identidade fossem o primeiro julgamento?**

Foi a partir dessa pergunta que nasceu o ACROSS.

---

## 🎯 A solução

O ACROSS cria um espaço em que universitários podem:

* criar uma identidade temporária;
* compartilhar interesses e personalidade;
* encontrar pessoas com contextos semelhantes;
* demonstrar identificação com alguém;
* iniciar conversas;
* compartilhar experiências e desabafos;
* trocar dicas;
* descobrir eventos e oportunidades no ambiente universitário;
* decidir, junto com a outra pessoa, quando revelar suas identidades.

A proposta não é criar uma rede social baseada em aparência.

É criar um espaço em que a **conexão venha antes da identidade**.

---

## ✨ O diferencial

Em redes sociais tradicionais, normalmente o usuário vê quem é a pessoa antes de decidir se quer conhecê-la.

No ACROSS, a lógica é invertida:

**conhecer → conversar → criar conexão → revelar**

A identidade real só é revelada quando **as duas pessoas concordam**.

Isso transforma a primeira interação em uma experiência menos baseada em aparência e mais baseada em personalidade, interesses e conversa.

---

## 🧩 Principais funcionalidades

### 👤 Identidade temporária

O usuário cria uma identidade para utilizar enquanto ainda não deseja revelar seu nome real.

A identidade pode incluir:

* nome fictício;
* avatar abstrato;
* interesses;
* personalidade;
* descrição;
* universidade;
* curso;
* período.

---

### 🔎 Descoberta

O usuário pode encontrar pessoas considerando:

* universidade;
* curso;
* período;
* interesses;
* objetivos;
* personalidade;
* atividades e lugares de interesse.

Em vez de "curtir", o usuário pode dizer:

> **Me identifiquei.**

---

### 💬 Conversas

Depois que duas pessoas demonstram interesse mútuo, uma conversa pode ser iniciada.

A identidade permanece protegida durante a conversa.

---

### 🔐 Revelação mútua

Uma pessoa pode solicitar a revelação da identidade.

A identidade só é revelada quando **as duas pessoas concordam**.

> Primeiro a conversa. Depois, quem está do outro lado.

---

### 🫂 Desabafos

O ACROSS possui um espaço para estudantes compartilharem experiências relacionadas à vida universitária.

Exemplos:

* dificuldades com apresentações;
* provas;
* amizades;
* networking;
* situações engraçadas;
* inseguranças;
* experiências acadêmicas.

Outros estudantes podem responder e compartilhar dicas.

---

### 📅 Eventos

A plataforma pode apresentar eventos relacionados à universidade e à comunidade local.

A funcionalidade foi pensada para aproximar estudantes também das oportunidades e atividades que acontecem ao redor deles.

---

## 🎓 Por que universidades?

A universidade foi escolhida como primeiro nicho porque é um ambiente no qual a necessidade de novas conexões é especialmente perceptível.

É um período em que muitas pessoas:

* mudam de rotina;
* conhecem ambientes novos;
* precisam construir networking;
* começam a apresentar trabalhos;
* procuram oportunidades profissionais;
* formam novos grupos sociais.

O ACROSS parte desse contexto para testar uma solução de conexão social mais confortável.

---

## 🛠️ Tecnologias

As tecnologias utilizadas neste projeto incluem:

* React
* TypeScript
* Vite
* Tailwind CSS
* [Backend utilizado]
* [Banco de dados utilizado]
* [Autenticação utilizada]

> A lista deve ser atualizada conforme a implementação final do projeto.

---

## 🏗️ Arquitetura

O projeto foi estruturado separando responsabilidades entre:

```text
src/
├── components/
├── pages/
├── layouts/
├── services/
├── hooks/
├── types/
├── utils/
├── data/
├── styles/
└── ...
```

A estrutura pode variar conforme a implementação final.

O objetivo é manter o projeto modular e facilitar sua evolução.

---

## 🔄 Jornada principal

```text
Cadastro
   ↓
Universidade
   ↓
Curso e período
   ↓
Objetivos
   ↓
Interesses
   ↓
Personalidade
   ↓
Identidade temporária
   ↓
Descoberta
   ↓
"Me identifiquei"
   ↓
Conversa
   ↓
Revelação mútua
   ↓
Conexão
```

---

## 🔒 Privacidade

A privacidade é parte central da experiência.

O ACROSS foi pensado para evitar que informações pessoais sejam utilizadas como primeiro filtro de conexão.

A aplicação deve proteger:

* nome real;
* informações de contato;
* identidade;
* conversas;
* localização;
* dados pessoais.

Também existem mecanismos de:

* bloqueio;
* denúncia;
* encerramento de conexão.

---

## 🎨 Design

A identidade visual do ACROSS foi pensada para transmitir:

**calma + curiosidade + acolhimento + mistério.**

A interface utiliza:

* cores claras;
* tons pastel suaves;
* bastante espaço em branco;
* tipografia moderna;
* botões arredondados;
* cards leves;
* microinterações;
* animações discretas.

A intenção é criar uma experiência diferente de redes sociais visualmente carregadas.

---

## 🚀 Como executar

Clone o repositório:

```bash
git clone [URL_DO_REPOSITORIO]
```

Entre na pasta:

```bash
cd across
```

Instale as dependências:

```bash
npm install
```

Configure as variáveis de ambiente:

```bash
cp .env.example .env
```

Preencha as variáveis necessárias.

Execute o projeto:

```bash
npm run dev
```

Para gerar o build:

```bash
npm run build
```

> Os comandos devem ser ajustados caso a stack final utilize uma configuração diferente.

---

## 🔮 Próximos passos

Algumas possibilidades futuras:

* recomendações de eventos;
* integração com universidades;
* grupos por interesse;
* melhoria do algoritmo de matching;
* recomendações personalizadas;
* notificações mais avançadas;
* aplicativo mobile;
* ferramentas de apoio à comunicação;
* recursos para facilitar networking;
* expansão para outras comunidades além de universidades.

Essas funcionalidades não fazem parte necessariamente do MVP inicial.

---

## 🧠 Aprendizados

O ACROSS foi desenvolvido com foco não apenas na implementação técnica, mas também em **produto, UX e resolução de problemas reais**.

O projeto envolve decisões relacionadas a:

* experiência do usuário;
* arquitetura de software;
* modelagem de dados;
* privacidade;
* comunicação;
* sistemas de recomendação;
* design de interfaces;
* desenvolvimento web.

A principal pergunta que orienta o projeto é:

> **E se a primeira coisa que descobríssemos sobre alguém não fosse sua aparência, mas quem ela é?**

---

## 👩‍💻 Projeto

Projeto desenvolvido como parte de uma proposta de hackathon, a partir da observação e investigação exploratória de dificuldades enfrentadas por estudantes no ambiente universitário.

**ACROSS**

> *Antes de saber quem é, descubra quem é.*
