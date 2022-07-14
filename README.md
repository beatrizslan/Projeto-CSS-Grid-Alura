# Alura - Solução do Projeto de CSS Grid da Alura Store

Codificação de um projeto disponibilizado durante o curso de Front-end da [Alura](https://www.alura.com.br/formacao-front-end).

## Indíce

Visão Geral | [Desafio](#desafio) | [Screenshot](#screenshot) | [Links](#links)
---|---|---|---

Meu Processo | [Construído com](#construído-com) | [O que eu aprendi](#o-que-eu-aprendi) | [Recursos úteis](#recursos-úteis)
---|---|---|---

Considerações Finais | [Autor](#autor) | [Agradecimentos](#agradecimentos)
---|---|---

## Visão Geral

### Desafio

O desafio foi construir este projeto com CSS Grid Layout e fazê-lo parecer o mais próximo possível do design. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![Captura de Tela (201)](https://user-images.githubusercontent.com/105252003/178905557-b9129eb9-2d33-4bd8-bc5d-4b2412e7cf95.png)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-CSS-Grid-Alura/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-CSS-Grid-Alura/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- CSS grid layout;
- Flexbox;
- Media queries.

### O que eu aprendi

- Trabalhar com o CSS Grid Layout;
- Trabalhar com Grid e Flexbox juntos;
- Desenvolver uma página responsiva, com media queries.

```CSS
.app {
    background: #f1f1f1;
    display: grid;  
    font-family: Arial, Helvetica, sans-serif;
    grid-template-areas: 
        "cabecalho"
        "conteudo"
        "rodape";
    grid-template-columns: auto;
    grid-template-rows: 50px auto auto;
}
```

### Recursos úteis

- [Guia Completo do CSS Grid Layout](https://css-tricks.com/snippets/css/complete-guide-grid/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Grid Layout e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos móveis.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan | Alura](https://beatrizslan.github.io/Projeto-CSS-Grid-Alura/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.
