# Oliveira & Associados — Site Institucional

Site institucional completo para um escritório de advocacia fictício, construído do zero em HTML, CSS e JavaScript. É o projeto mais extenso que fiz sem framework: nove seções, todas responsivas.

**[▶ Ver no ar](https://guilhermeoliveira337.github.io/Projeto-advocacia/)**

![Preview do site](./preview.png)

## As nove seções

| Seção | O que resolve |
|---|---|
| **Hero** | Proposta de valor, dois call to action e três números de credibilidade |
| **Sobre** | Diferenciais do escritório |
| **Galeria** | Grade de imagens institucionais em CSS Grid |
| **Áreas de atuação** | Seis cards de especialidade jurídica |
| **Casos de sucesso** | Prova social com resultados |
| **Benefícios** | Lista numerada de motivos para contratar |
| **Depoimentos** | Avaliações em cards com estrelas |
| **FAQ** | Acordeão que abre e fecha, em JavaScript puro |
| **Contato** | Formulário e dados do escritório |

## Decisões técnicas

- **Variáveis CSS** para a paleta inteira — o dourado e o azul-marinho são definidos uma vez e reaproveitados em toda a folha de estilo
- **CSS Grid** na galeria e nos cards; **Flexbox** no alinhamento interno de cada componente
- **JavaScript puro** para menu mobile, acordeão do FAQ, rolagem suave e o botão "voltar ao topo" que aparece conforme a página desce
- **HTML semântico** — `header`, `nav`, `section`, `footer`, em vez de `div` para tudo
- **Media queries** em três faixas: até 768px, 768–1024px e acima de 1024px

## Tecnologias

`HTML5` · `CSS3 (Grid, Flexbox, Variáveis)` · `JavaScript (ES6)` · `Font Awesome`

## Rodando localmente

```bash
git clone https://github.com/GuilhermeOliveira337/Projeto-advocacia.git
cd Projeto-advocacia
```

Abra o `index.html` no navegador.

## Estrutura

```
Projeto-advocacia/
├── index.html    # as nove seções
├── style.css     # paleta, layout e responsividade
└── script.js     # menu, FAQ, rolagem e voltar ao topo
```

> O escritório é fictício e as imagens são do Unsplash, para uso educacional.

---

Desenvolvido por **Guilherme Oliveira** · [LinkedIn](https://www.linkedin.com/in/guilherme-oliveira-frontend)
