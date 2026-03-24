# 🌏 Conheça Busan — Landing Page

Projeto de estudo desenvolvido com **HTML** e **CSS**, simulando uma landing page turística sobre **Busan**, a segunda maior cidade da Coreia do Sul.

---

## 📌 Sobre o projeto

Uma página estática e informativa que apresenta Busan como destino turístico, destacando atrações históricas, templos budistas e parques. O projeto foi criado com foco na prática de estruturação semântica com HTML e estilização com CSS puro.

---

## 🎯 Objetivos de aprendizado

- Estruturar páginas com HTML semântico (`header`, `main`, `section`, `footer`)
- Aplicar estilos com CSS puro, sem frameworks
- Trabalhar com tipografia, cores e espaçamento de forma harmoniosa
- Utilizar fontes externas via **Google Fonts** (Open Sans)
- Criar layouts com `max-width` e centralização via `margin: auto`
- Organizar cards de conteúdo com espaçamento e separadores visuais

---

## 🗂️ Estrutura do projeto

```
landing-page-busan/
│
├── index.html                       # Estrutura principal da página
├── css/
│   └── style.css                    # Estilos da página
├── assets/
│   ├── aviao-logo.png               # Favicon da página
│   ├── image-cidade-1.jpg           # Imagem do header
│   ├── image-cidade-2.jpg           # Templo Haedong Yonggungsa
│   ├── image-templos-orientais.jpg  # Templo Beomeo-sa
│   └── image-cidade-3.jpg           # Parque Yongdusan
└── README.md                        # Documentação do projeto
```

---

## 🧩 Seções da página

| Seção | Descrição |
|---|---|
| **Header** | Título principal, imagem de destaque e subtítulo em itálico |
| **Main** | Introdução ao destino e 3 cards de atrações turísticas |
| **Footer** | Parágrafo de encerramento centralizado |

### Atrações apresentadas

1. 🏯 **Templo Haedong Yonggungsa** — templo budista à beira-mar, construído em 1376
2. 🌿 **Templo Beomeo-sa** — um dos maiores santuários do país, na montanha Geumjeongsa
3. 🏙️ **Parque Yongdusan** — parque central com a Torre Busan de 120 metros e dois museus

---

## 🎨 Decisões de estilo

- **Paleta de cores:** fundo em `#f5f4f0` (bege claro), textos em `#1b1b1b` e `#333333`, destaque em `#e1624f` (vermelho-alaranjado)
- **Tipografia:** fonte [Open Sans](https://fonts.google.com/specimen/Open+Sans) via Google Fonts, com variações de peso e estilo
- **Imagens:** cantos arredondados com `border-radius: 28px` e largura total (`width: 100%`)
- **Divisores:** linha horizontal sutil (`1px`, cor `#d9d9d9`) entre as seções
- **Tags de categoria** nas listas de cada atração, com cores distintas por tipo:
  - 🔵 História — `#0c51a7`
  - 🟣 Casais — `#591b98`
  - 🔴 Famílias — `#e5245e`
  - 🟠 Orçamento — `#e95e10`

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Detalhe |
|---|---|
| HTML5 | Estrutura semântica da página |
| CSS3 | Estilização, box model, cores e tipografia |
| Google Fonts | Fonte Open Sans (pesos 300–800) |

> Nenhuma biblioteca ou framework externo foi utilizado.

---

## 🚀 Como visualizar o projeto

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/CaioBrazLago/local-turistico.git
   ```
2. Abra o arquivo `index.html` diretamente no seu navegador.

Não é necessária nenhuma instalação ou servidor local.

---

## 📚 Conceitos praticados

- Semântica HTML com `header`, `main`, `section` e `footer`
- Reset de estilos com `* { padding: 0; margin: 0; box-sizing: border-box }`
- Centralização de conteúdo com `max-width` e `margin: auto`
- Separação visual com elementos divisores estilizados via CSS
- Uso de classes e IDs para aplicar estilos específicos por componente
- Estilização de listas e marcadores com `::marker`
- Integração de fontes externas via Google Fonts

---

## ✍️ Autor

Feito com 💙 como projeto de estudo front-end.

---

## 📄 Licença

Este projeto é livre para uso educacional.
