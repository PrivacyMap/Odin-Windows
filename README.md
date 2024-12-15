# Odin para Windows

**Odin** é uma ferramenta essencial para dispositivos Samsung que permite realizar tarefas avançadas, como flash de firmware, recuperação de sistemas, instalação de arquivos personalizados e muito mais. Usado por técnicos e entusiastas, o Odin é compatível apenas com Windows e é uma das ferramentas mais confiáveis para gerenciamento de dispositivos Samsung.

---

## Recursos Principais

- **Flash de Firmware**: Instale firmware oficial nos dispositivos Samsung.  
- **Reinstalação de ROMs de Fábrica**: Restaure dispositivos ao estado de fábrica.  
- **Instalação de Recoveries Personalizados**: Flash de arquivos como TWRP e CWM.  
- **Atualizações de Firmware Personalizadas**: Adicione novos recursos ou versões do sistema operacional.  
- **Correção de Soft Bricks**: Restaure dispositivos que falharam em atualizações ou ficaram presos em bootloops.  
- **Compatível com Arquivos PIT**: Reparticione dispositivos, se necessário.  

---

## Requisitos do Sistema

- Sistema Operacional: **Windows 7/8/10/11**.  
- Drivers USB Samsung instalados no computador (baixe [aqui](https://developer.samsung.com/mobile/android-usb-driver.html)).  
- Dispositivo Samsung com modo Download/Odin habilitado.

---

## Como Usar o Odin

1. **Download do Odin**  
   Baixe a versão mais recente do Odin na [página de lançamentos](https://github.com/PrivacyMap/Odin-Windows/releases) e faça o download do arquivo `Odin3_<Versão>.zip`.

2. **Preparação do Dispositivo Samsung**  
   - Ative o **modo Download/Odin** no seu dispositivo Samsung:  
     - Desligue o dispositivo.  
     - Pressione e segure as teclas **Volume para Baixo + Botão Home + Power** (ou **Volume para Baixo + Bixby + Power** em dispositivos mais recentes).  
     - Pressione **Volume para Cima** para confirmar.  
   - Conecte o dispositivo ao computador usando um cabo USB.

3. **Instale os Drivers USB Samsung**  
   Certifique-se de que o computador reconhece o dispositivo Samsung corretamente.

4. **Configuração do Odin**  
   - Abra o programa **Odin**.  
   - Carregue os arquivos apropriados:
     - **BL**: Arquivo de Bootloader.  
     - **AP**: Sistema principal ou firmware.  
     - **CP**: Modem/Radio.  
     - **CSC**: Configuração de firmware personalizada (use o arquivo HOME_CSC para não apagar os dados).  

5. **Inicie o Flash**  
   - Clique em **Start** e aguarde o processo concluir.  
   - Não desconecte o dispositivo durante o procedimento.  
   - O dispositivo reiniciará automaticamente após a conclusão.

---

## Aviso de Responsabilidade

Este repositório é apenas para fins educacionais e de compartilhamento. O software **Odin** foi obtido de fontes públicas na internet e não é de autoria do Vitor Pio ou de qualquer pessoa associada à PrivacyMap. **Não nos responsabilizamos por quaisquer danos, perdas ou consequências decorrentes do uso deste software.** Use-o por sua conta e risco.

- **Riscos**: Usar o Odin incorretamente pode causar falhas no dispositivo (brick). Siga os passos com atenção.  
- **Garantia**: Alguns procedimentos podem anular a garantia do dispositivo.  

---

## Licença

O Odin é um software proprietário e não é oficialmente distribuído pela Samsung para o público em geral. Este repositório não possui nenhuma relação oficial com a Samsung.
