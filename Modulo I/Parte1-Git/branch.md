# Branch

Um **"branch"** (ou "ramo", em português) em Git é essencialmente uma linha de desenvolvimento independente dentro de um repositório. Ele permite que você trabalhe em diferentes partes do seu projeto simultaneamente sem interferir no progresso de outras partes. Cada branch possui seu próprio conjunto de commits, representando um histórico único de alterações.

* E uma forma de separar as versões de cada projeto

* Cada nova features do projeto ficar em uma branch separado e no final as branches serão unidas



## Criando Branch

```bash
git branch <nome-da-branch|ramo>
```

## Informa sua Branch

```bash
git branch
```

## Removendo Branch

```bash
git branch -d <nome_do_branch>
```

## Mudando de Branch

```bash
git checkout -b <nome_do_novo_branch>
```