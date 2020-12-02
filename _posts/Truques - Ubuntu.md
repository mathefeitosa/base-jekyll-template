# Trocar o brilho do monitor pelo *shell*
- Descobrir qual o nome do dispositivo
	- `xrandr -q | grep "connected"`
- Mudar o brilho de acordo com o dispositivo \<device>
	- `xrandr --output <device> --brightness 0.5`
	- Exemplo: `xrandr --output HDMI-A-0 --brightness 0.5`
- O valor de `--brightness` vai de 0 a 1 —  onde 1 é 100%.