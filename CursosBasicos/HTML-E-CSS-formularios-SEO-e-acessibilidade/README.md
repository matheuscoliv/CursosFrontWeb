# 📋 Culturama — HTML, CSS: Formulários, SEO e Acessibilidade

Formulário de **Pesquisa de Opinião** da marca fictícia Culturama. Projeto desenvolvido para praticar a criação de formulários HTML completos com foco em semântica, validação nativa, acessibilidade e boas práticas de UX.

## 🎯 Objetivos do Projeto

- Criar formulários HTML5 completos usando os principais tipos de input
- Organizar campos relacionados com `fieldset` e `legend`
- Implementar validação nativa do navegador (`required`, `min`, `max`, `pattern`)
- Garantir acessibilidade com atributos ARIA (`aria-label`, `aria-describedby`)
- Associar corretamente `label` com `input` via atributo `for`/`id`
- Estilizar o formulário com CSS e Google Fonts

## 🛠️ Tecnologias

- HTML5
- CSS3
- Google Fonts (Fjalla One + Work Sans)

## 📁 Estrutura de Arquivos

```
HTML-E-CSS-formularios-SEO-e-acessibilidade/
├── index.html
├── sucesso.html
├── culturama-favico.png
├── styles/
│   └── styles.css
└── assets/
    └── logo-culturama.png
```

## 📝 Seções do Formulário

### 1. Dados Pessoais
Coleta informações básicas do usuário:
- Nome (`text`, obrigatório)
- Idade (`number`, mín. 12, máx. 100, obrigatório)
- Data de nascimento (`date`)
- E-mail (`email`, obrigatório)
- Telefone (`tel`) com máscara de ajuda via `aria-describedby`
- Upload de foto (`file`, aceita apenas imagens)

### 2. Perfil
Caracterização do participante:
- Gênero (radio: Feminino / Masculino / Outro)
- Estado civil (`select`: Casado, Solteiro, Viúvo, Divorciado)
- Estado brasileiro (`select` com todos os 26 estados + DF)
- Cidade (`text` com `autocomplete`)

### 3. Hábitos
Preferências culturais e digitais:
- Redes sociais usadas (`checkbox`: Instagram, Facebook, TikTok, Twitter/X, LinkedIn)
- Estilo musical favorito (`input` + `datalist` com sugestões)
- Cor favorita (`input type="color"`)

### 4. Opinião
Avaliação livre e estruturada:
- Comentário aberto (`textarea`)
- Avaliação geral (radio: Ótima / Regular / Ruim)

### 5. Confirmações
Consentimento do participante:
- Aceite de participação na pesquisa (obrigatório, LGPD)
- Opção de receber resultado por e-mail

## ♿ Acessibilidade

Recursos de acessibilidade implementados:

- `aria-label` nos botões de envio e reset
- `aria-describedby` para campos com instruções complementares (telefone e upload)
- Todos os inputs possuem `<label>` associado via `for`/`id`
- Semântica nativa com `fieldset`/`legend` para agrupamento de campos relacionados

## 🚀 Como Executar

Abra o arquivo `index.html` diretamente no navegador. Ao enviar o formulário com os campos obrigatórios preenchidos, o usuário é redirecionado para `sucesso.html`.
