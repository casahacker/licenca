# Licença Casa Hacker

[![Versão](https://img.shields.io/badge/versão-1.1-blue.svg)](./LICENSE)
[![Idioma](https://img.shields.io/badge/idioma-pt--BR-green.svg)](./LICENSE)
[![Jurisdição](https://img.shields.io/badge/jurisdição-Brasil-yellow.svg)](./LICENSE)
[![Tipo](https://img.shields.io/badge/tipo-permissiva-orange.svg)](./LICENSE)

Uma licença de software **permissiva**, redigida em português e ancorada no ordenamento jurídico brasileiro. Inspirada nas licenças MIT, Apache 2.0, MPL 2.0 e Ms-PL, adaptada à LDA, LGPD e demais normas nacionais.


## Sobre

A maioria das licenças de software livre adotadas no Brasil são traduções informais de textos em inglês concebidos sob a lógica do *common law*. Isso gera duas dores conhecidas:

1. **Insegurança jurídica** quanto à validade de certas cláusulas perante o direito brasileiro (cessão de direitos, renúncia de garantias, foro).
2. **Lacunas** em temas locais como marca, LGPD e direitos morais do autor (inalienáveis no Brasil).

A **Licença Casa Hacker** foi escrita do zero para cobrir essas lacunas sem perder a simplicidade de uma licença permissiva.


## TL;DR

> Use, modifique e venda à vontade, mas mantenha os créditos, não use o nome "Casa Hacker" para confundir o público, e não nos processe por patentes.

| Pode | Deve | Não pode |
|---|---|---|
| Usar comercialmente | Manter aviso de copyright | Usar a marca "Casa Hacker" |
| Modificar e redistribuir | Indicar modificações | Processar por patentes |
| Sublicenciar e vender | Preservar créditos | Responsabilizar autores |
| Usar em SaaS | Renomear forks | — |


## Estrutura da Licença

| # | Cláusula | Tema |
|---|---|---|
| — | Preâmbulo | Aceitação e natureza contratual |
| 1 | Definições | Termos técnicos e legais |
| 2 | Outorga | Direitos autorais e de uso |
| 3 | Patentes | Licença patentária e retaliação |
| 4 | Marcas | Proteção do nome "Casa Hacker" |
| 5 | Contribuições | Modelo DCO (sem cessão automática) |
| 6 | Atribuição | Créditos e indicação de modificações |
| 7 | Garantias | Isenção com ressalvas legais |
| 8 | Responsabilidade |
| 9 | LGPD | Conformidade com a Lei 13.709/2018 |
| 10 | Regulatório | Anticorrupção, setores regulados |
| 11 | Força maior | Art. 393 CC |
| 12 | Rescisão | Cura em 30 + 60 dias (estilo GPLv3) |
| 13 | Versões | "Esta ou posterior" |
| 14 | Compatibilidade | MIT, Apache 2.0, MPL 2.0 / GPL não |
| 15 | Foro | Arbitragem opcional + São Paulo |
| 16 | Disposições finais | Severability e tolerância |


## Como Aplicar a um Projeto

### 1. Copie o arquivo `LICENSE` para a raiz do seu repositório

```bash
curl -O https://raw.githubusercontent.com/casahacker/licenca/main/LICENSE
```

### 2. Atualize o aviso de copyright

Substitua a linha:

```
Copyright (c) 2026 Casa Hacker
```

Por:

```
Copyright (c) <ANO> <SEU NOME OU ORGANIZAÇÃO>
```

### 3. Adicione um cabeçalho curto em cada arquivo-fonte (opcional, mas recomendado)

```text
Copyright (c) <ANO> <SEU NOME>
Licenciado sob a Licença Casa Hacker v1.1.
Veja o arquivo LICENSE para detalhes.
```

### 4. (Opcional) Adicione um arquivo `NOTICE`

Para créditos de terceiros, dependências e atribuições adicionais.


## Comparativo com Outras Licenças

| Recurso | Casa Hacker 1.1 | MIT | Apache 2.0 | MPL 2.0 | GPL 3.0 |
|---|:---:|:---:|:---:|:---:|:---:|
| Uso comercial | Sim | Sim | Sim | Sim | Sim |
| Modificação | Sim | Sim | Sim | Sim | Sim |
| Redistribuição | Sim | Sim | Sim | Sim | Sim |
| Uso privado | Sim | Sim | Sim | Sim | Sim |
| Concessão de patente | Sim | Não | Sim | Sim | Sim |
| Cláusula de marca | Sim | Não | Sim | Não | Não |
| Copyleft | Não | Não | Não | Fraco | Forte |
| Indicação de modificações | Sim | Não | Sim | Sim | Sim |
| Redigida em português | Sim | Não | Não | Não | Não |
| Adaptada ao direito BR | Sim | Não | Não | Não | Não |
| Cláusula LGPD | Sim | Não | Não | Não | Não |

## Perguntas Frequentes

<details>
<summary><b>Posso usar esta licença em projetos comerciais?</b></summary>

Sim. A licença permite uso comercial sem restrições, incluindo venda de cópias, integração em produtos proprietários e oferta como serviço (SaaS).
</details>

<details>
<summary><b>Preciso liberar o código das minhas modificações?</b></summary>

Não. É uma licença **permissiva** — sem copyleft. Você pode manter suas modificações fechadas, mas deve preservar os créditos e indicar que houve modificações.
</details>

<details>
<summary><b>Posso usar o nome "Casa Hacker" no meu fork?</b></summary>

Não, salvo referência factual à origem (ex: "baseado no Software Casa Hacker"). Forks e derivados devem adotar denominação distinta para não causar confusão com a obra original.
</details>

<details>
<summary><b>É compatível com GPL?</b></summary>

Em regra, não. A GPL exige que obras derivadas também sejam GPL (copyleft forte), o que conflita com a liberdade desta licença. Para combinar código sob GPL, consulte o Licenciante.
</details>

<details>
<summary><b>É reconhecida pela OSI?</b></summary>

Ainda não. O texto foi inspirado em licenças aprovadas pela OSI (MIT, Apache 2.0, MPL 2.0), mas a submissão formal está em estudo. Contribuições são bem-vindas.
</details>

<details>
<summary><b>O TL;DR tem valor jurídico?</b></summary>

Não. O TL;DR é apenas resumo didático. Em caso de divergência, prevalece o texto integral das cláusulas oficiais.
</details>

<details>
<summary><b>Como envio uma contribuição?</b></summary>

Ao abrir um Pull Request, você certifica automaticamente (modelo DCO) que detém os direitos sobre a contribuição e a licencia sob estes termos. Não há cessão de direitos — apenas licença ampla e perpétua.
</details>


## Contribuindo

Sugestões de melhoria, correções de redação e jurisprudência relevante são bem-vindas. Abra uma *issue* ou um *pull request*.

Áreas de interesse para próximas versões:

- Tradução oficial para inglês e espanhol
- Submissão à OSI (Open Source Initiative)
- Registro junto ao INPI como marca
- Anexo opcional para uso em modelos de IA (cláusula de treinamento)


## Referências e Inspirações

- [MIT License](https://opensource.org/licenses/MIT)
- [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/)
- [Microsoft Public License (Ms-PL)](https://opensource.org/licenses/MS-PL)
- [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html)
- Lei n.º 9.609/1998 — Lei do Software
- Lei n.º 9.610/1998 — Direitos Autorais
- Lei n.º 9.279/1996 — Propriedade Industrial
- Lei n.º 13.709/2018 — LGPD

## Aviso Legal

Este projeto disponibiliza um **modelo de licença** para a comunidade. Antes de adotá-lo em projetos críticos ou comerciais, recomenda-se consulta a advogado especializado em propriedade intelectual e tecnologia.

A Casa Hacker e os contribuidores deste repositório **não prestam assessoria jurídica** e não se responsabilizam pelo uso da licença em casos concretos.


## Licença deste repositório

O próprio texto da Licença Casa Hacker está disponível sob os termos da Creative Commons Attribution 4.0 (CC BY 4.0), permitindo que outros projetos a copiem, adaptem e redistribuam, desde que mantida a atribuição.

> Esta dupla camada é proposital: o **código** que você proteger com a licença fica sob os termos dela; o **texto da licença em si** é livre para ser reutilizado por outros projetos.


Feito pela [Casa Hacker](https://github.com/casahacker).
