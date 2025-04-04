# Amor-em-codigo
Surpreenda sua namorada(o) com um clique: foto, música e amor em um site simples.

# Site Romântico com Foto, Música e Contador

Um site simples, feito com HTML, CSS e JavaScript, para surpreender alguém especial.  
Ao clicar no botão inicial, o site revela uma foto, toca uma música romântica e mostra há quanto tempo vocês estão juntos. 🥰

## ✨ Como funciona

- Ao abrir, o site mostra um botão "❤️ Click ❤️".
- Ao clicar, aparece:
  - Uma **foto do casal** (`nossa_foto.jpeg`)
  - Um **áudio tocando automaticamente** (`musica.mp3`)
  - Um **contador** que mostra quantos dias, horas, minutos e segundos desde o início do relacionamento.
  - Uma **mensagem romântica** personalizada.

## 💖 Demonstração visual

![imagem do site](https://raw.githubusercontent.com/Educofseal/Amor-em-codigo/main/Captura%20de%20tela%20de%202025-04-04%2020-32-22.png)


---

## 🛠️ Tecnologias utilizadas

- **HTML**: estrutura da página
- **CSS**: estilos com cores, fontes e posicionamento
- **JavaScript**: lógica para mostrar o conteúdo e iniciar o contador

---

## 🔧 Como personalizar

Se você quiser adaptar este site para sua namorada(o), basta:

1. **Trocar a imagem**  
   Substitua o arquivo `nossa_foto.jpeg` por uma foto sua com ela/ele.

2. **Trocar a música**  
   Substitua o arquivo `musica.mp3` por uma música de vocês (MP3).

3. **Alterar a data do relacionamento**  
   No JavaScript (`index.html`), edite esta linha com a data correta:
   ```js
   iniciarContagem(new Date("2025-01-13T00:00:00"));
