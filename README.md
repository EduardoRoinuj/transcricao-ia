# Transcrição IA

Aplicação de desktop para Windows que transcreve áudio em texto no seu próprio computador, usando o motor Whisper. O áudio não é enviado para servidores.

## Descarregar

A versão mais recente está em [Releases](../../releases/latest). Descarregue o ficheiro `TranscricaoIA_v1.zip`, descompacte e execute `TranscricaoIA.exe`.

## O que faz

- Transcreve MP3, WAV e M4A com modelos de IA (Base, Small, Medium, Large V3)
- Grava pelo microfone e reproduz o áudio sincronizado com o texto
- Traduz entre português e inglês e melhora a pontuação do texto
- Exporta para TXT, PDF, DOCX e legendas SRT

## Grátis e PRO

A versão gratuita transcreve, grava, traduz e exporta TXT. A versão PRO (pagamento único) desbloqueia a exportação para PDF, DOCX e SRT e a melhoria de texto por IA.

## Instalar o motor Whisper

A aplicação usa o whisper.cpp, que deve estar em `C:\whispercpp` (executável `whisper-cli.exe` e modelos em `C:\whispercpp\models`). As instruções completas estão no ficheiro `LEIA-ME_INSTALACAO.md` incluído no download.

## Requisitos

Windows 10 ou 11 (64 bits). Mínimo 4 GB de RAM. O modelo Large V3 precisa de cerca de 4 GB livres; para a maioria dos casos use o modelo Medium.

## Autor

Eduardo F. Guambe Júnior — [LinkedIn](https://www.linkedin.com/in/eduardoguambejunior/)
