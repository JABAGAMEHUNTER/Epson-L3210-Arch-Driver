# Epson-L3210-Arch-Driver
Arch Linux Package for Epson EcoTank L3210 A4 All-in-One Ink Tank Printer Driver

## Instalacao
1. Extraia o arquivo em uma pasta desejada
2. Dentro da pasta, abra o terminal e digite
   ```
   makepkg -si
   ```
3. Copie o comando para criação de atalho para o filtro da impressora e execute no terminal
   ```
   sudo ln -s /opt/epson-inkjet-printer-202101w/cups/lib/filter/epson_inkjet_printer_filter /usr/lib/cups/filter/epson_inkjet_printer_filter
   ```
4. Tudo pronto! Agora voce pode instalar a impressora com o driver pelo CUPS e imprimir uma página de teste

A impressão com o driver possibilita o uso correto de funções da impressão como mudança de qualidade da impressão e impressão para outros tipos de papel.
Caso não funcione por algum motivo no futuro, o driver para a impressora L3250 (disponível na AUR) também funciona rasoavelmente com a impressora, no entanto perde funções de precisão de qualidade.
