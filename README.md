# 🎹 Teclinhas

Um app web gratuito e open source para aprender piano no estilo "notas caindo", feito para usar no tablet com o piano conectado por cabo USB (MIDI).

## Como usar

1. Abra o site no **Chrome** do tablet Android, com o piano conectado pelo cabo USB/MIDI.
2. Permita o acesso aos dispositivos MIDI quando o Chrome pedir.
3. No menu do Chrome, toque em **Adicionar à tela inicial** para ele virar um ícone de app.

Também funciona sem piano: dá para tocar nas teclas da tela ou, no computador, usar as teclas `A W S E D F T G Y H U J K`. A barra de espaço pausa.

## Recursos

- Biblioteca com músicas de domínio público em 3 níveis
- Modos **Ouvir**, **Esperar** (a música para até a nota certa) e **No ritmo** (com pontuação)
- Mão direita, mão esquerda ou as duas; o app toca a outra mão como acompanhamento
- Velocidade ajustável de 30% a 120%
- Importação de arquivos `.mid`: duas trilhas viram mão direita e mão esquerda automaticamente

## Técnico

Um único `index.html` sem dependências, que usa Web MIDI, Web Audio e Canvas. O Web MIDI exige HTTPS, por isso o app é publicado pelo GitHub Pages.
