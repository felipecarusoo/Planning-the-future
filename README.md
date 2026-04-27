# Planning the future — metas do ano com contagem regressiva

Projeto front-end simples para **praticar JavaScript no 3º ano do ensino médio**: abas (“metas”) e um contador regressivo até datas-alvo. O HTML e o CSS podem ficar fixos enquanto a turma evolui o comportamento em arquivos `.js` por aula.

![Pré-visualização do layout](<img planning future.png>)

## O que o projeto faz

- Troca entre quatro metas usando botões estilizados como abas.
- Mostra, para cada meta, quanto tempo falta em dias, horas, minutos e segundos.
- Atualiza os números automaticamente a cada segundo.

## Como abrir localmente

1. Clone ou baixe esta pasta.
2. Abra `index.html` no navegador **ou** use a extensão **Live Server** no editor (recomendado para ver mudanças no JS sem surpresas de caminho).

Não é necessário instalar Node ou outra ferramenta para rodar o projeto base.

## Estrutura dos arquivos

| Item | Função |
| --- | --- |
| `index.html` | Estrutura da página, quatro painéis de meta e IDs dos contadores (`days0`…`seconds3`). |
| `style.css` | Cores, layout e classes dos botões e painéis. Carregado **depois** do Bootstrap para o tema não ser sobrescrito. |
| `main.js` | Comportamento completo de referência (abas + contagem). |
| `aulas/` | **Uma pasta por etapa da trilha** — equivalente a “branches” de trabalho: DOM, eventos, abas, datas, contador, várias metas, intervalo e refatoração final. |


## Licença

Veja o arquivo [LICENSE](LICENSE).
