# Como publicar seu POST
Faça um fork desse repositório e em seguida adicione um arquivo em _pages ou _posts com o nome no seguinte padrão:
```
{YYYY}-{mm}-{dd}-{slug}.md
```
Onde `{YYYY}-{mm}-{dd}` são, respectivamente, o ano, mês e dia da publicação e `{slug}` é uma string com um padrão de url amigável (sem caracteres especiais e espaços), como por exemplo `integracao-com-github`. 

Adicione o seguinte trecho no início do arquivo e pode começar a escrever seu post logo abaixo do `---`. 
```
post_title: "Título do post"
author: "Seu nome"
post_date: "Data de publicação"
post_excerpt: "Resumo simplificado do post"
layout: post
permalink: >
  http://phpzm.rocks/YYYY/mm/dd/slug/
published: true
bfa_virtual_template:
  - hierarchy
---
```
Se possível use `<p style="text-align: justify;"></p>` para formatar o texto ;)

Para mais informações sobre o assunto pode dar uma olhada na documentação dessa turma aqui: https://github.com/mAAdhaTTah/wordpress-github-sync
