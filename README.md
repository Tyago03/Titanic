# Titanic — site acadêmico

Projeto acadêmico de **HTML5, CSS3 e Bootstrap 5**, inspirado na viagem inaugural do RMS Titanic em 1912.

> **Atenção:** este é um **protótipo front-end**. O cadastro, a seleção de ingressos e os formulários de pagamento são apenas demonstrações. **Não há transações financeiras, pagamentos, envio de pedidos ou backend de compra real.**

## Funcionalidades demonstrativas

- Apresentação das três classes fictícias: **Voyager**, **Elegance** e **Majestic**.
- Navegação entre páginas de descrição, cadastro, seleção de ingressos e confirmação.
- Fluxo visual de compra e pagamento simulado.
- Layout com Bootstrap 5 e estilos personalizados.

## Tecnologias

HTML5, CSS3, Bootstrap 5.3, Font Awesome e imagens externas. Parte dos recursos visuais depende de conexões/CDNs de terceiros.

## Como visualizar

```bash
git clone https://github.com/Tyago03/Titanic.git
cd Titanic
```

Abra `index.html` no navegador. Não é necessário instalar um servidor ou dependências de backend.

## Estrutura resumida

```text
Titanic/
├── index.html                 # Página inicial
├── sobre.html                 # Contexto do site
├── usuario.html               # Cadastro demonstrativo
├── ingresso1.html             # Majestic
├── ingresso2.html             # Elegance
├── ingresso3.html             # Voyager
├── comprar.html               # Etapas de compra simulada
├── cartao.html                # Formulário visual de cartão
├── concluido*.html            # Confirmações demonstrativas
├── cadastro_concluido.html    # Confirmação visual de cadastro
└── css/
    └── style.css
```

## Limitações e próximos passos

O fluxo é visual e educativo; não existe processamento real de dados de pagamento. A etapa de seleção de método de pagamento ainda pode ser aprimorada. Os recursos externos de imagem e estilos podem deixar de funcionar se os endereços de origem mudarem.

## Licença

O código original deste projeto está sob a [licença MIT](LICENSE). Imagens, marcas, textos e conteúdos de **terceiros** usados em referências externas não são licenciados por este repositório e permanecem sujeitos aos direitos dos respectivos titulares.
