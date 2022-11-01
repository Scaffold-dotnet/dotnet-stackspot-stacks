# Stack Spot

Stack Spot é uma ferramenta open source com foco em geração de scaffold agnóstica a tecnologia, compatível com todas tecnologias presentes hoje do mercado como .net, go, python etc.

## Stack

### O que é uma stack no stack spot?

Stack é um centralizar para ferramenta onde pode ser adicionado N templates ou N Plugins.

### Como usar uma stack no stack spot?

Para criar um stack é muito simples, basta instalar o CLI do stack spot e rodar o comando abaixo.

```csharp
stk create stack {nome_da_stack}
```

ou também você pode usar uma stack compartilhada usando o argumento --remote, com o comando abaixo.

```csharp
stk create stack --remote {url_do_projeto} 
```

📝**Note:** O repositório remoto deve ser git.

## Template

### O que é um template no stack spot?

O template é aquele modelo de código usado todas as vezes ao precisar um novo projeto, podendo ser uma api já contendo todas configurações necessárias e padrões de código, ou um worker já configurado com um provider de mensageria.

### Como usar um template?

Para criar um template, basta executar o comando abaixo dentro da pasta da stack.

```csharp
stk create template {nome_template}
```

Ou também você pode usar um template compartilhado de uma organização usando o argumento --remote, com o comando abaixo.

```csharp
stk create template --remote {url_do_template}
```

📝**Note:** O repositório remoto deve ser git.

## Plugin

### O que é um plugin no stack spot?

Plugin é aquela lib que pode ser reutilizado cross template, podendo ser uma abstração de acesso a dados, mensageria ou algum acesso a serviços na cloud.

### Como usar um plugin?

```csharp
stk create plugin {nome_plugin}
```

Ou você pode importar um plugin compartilhado usando o argumento --remote, com o comando abaixo.

```csharp
stk create plugin --remote {url_do_template}
```
