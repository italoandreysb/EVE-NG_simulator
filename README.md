# EVE-NG_Simulator
## Instalando o sistema
video referencia: https://www.youtube.com/watch?v=17fpe5oqce8&t=839s

Gerencia default:
	Acesso Web: admin | eve
	Acesso FTP: root | eve

Se der erro ao rodar o server: 
	https://www.youtube.com/watch?v=6f1Qckg2Zx0&t=183s

## Instalando as imagens 

Vídeo base: https://www.youtube.com/watch?v=fRoNEfALo90&t=1s

Os firmwares .qcow ficam num diretório aqui:
	opt/unetlab/addons/qmu/<vendor_modelo>/file.qcow2

Os arquivos .yaml devem ser movidos para os diretórios abaixo:
	/opt/unetlab/html/templates/amd
	/opt/unetlab/html/templates/intel

Os arquivos .png ficam em:
	/opt/unetlab/html/images
	ou
	/opt/unetlab/html/images/icons

Ao fim de tudo dê permissão:
	/opt/unetlab/wrappers/unl_wrapper -a fixpermissions
