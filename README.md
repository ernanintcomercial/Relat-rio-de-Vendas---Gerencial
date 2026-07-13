# Repositório público — site

Este é o repositório que fica público e serve o GitHub Pages. A partir de
agora ele só precisa de dois arquivos na raiz:

- `index.html` — o site (não usa mais o XLSX.js, só lê o `resumo.json`)
- `resumo.json` — gerado automaticamente pelo repositório privado (nunca
  edite ele à mão; ele é sobrescrito a cada atualização)

O `resumo.json` incluído aqui é só um **exemplo**, gerado a partir dos
arquivos que você já me mandou, pra você conferir que os números batem
(a "Meta até 09/07" do Brasil dá R$ 3.701.391, igual ao que já validamos).
Assim que o repositório privado estiver configurado e rodar pela primeira
vez, ele substitui esse arquivo pelo dado real e atualizado.

## O que NÃO precisa mais estar aqui

`Extracao.xlsx`, `Dados.xlsx` e `INDEX.xlsx` **não devem mais ser enviados
para este repositório** — é exatamente isso que elimina a exposição dos
dados linha a linha (nome de representante, cidade, contrato). Se ainda
tiver esses arquivos aqui de antes, pode apagar.
