# IssabelBR
Patch de correções e addon para Issabel com padrões ou recursos do Brasil

wget -O - https://github.com/ibinetwork/IssabelBR/raw/master/patch-issabelbr.sh | bash

1. O processo é o seguinte:

Entre no diretório padrão de áudios do Asterisk.
cd /var/lib/asterisk/sounds/
	
2. crie uma pasta para o áudio em português.			
mkdir pt_BR			
			
3. descarregue todos os áudios em português dentro desta pasta, obedecendo a estrutura dos diretórios.			
			
4. agora basta colocar a seguinte linha no arquivo sip_general_custom.conf			
language = pt_BR			
			
onde pt_BR é o nome do diretório que você criou, onde estão os áudios em português.			


Arquivos: https://mega.nz/#!CBUBWKpT!617VE1dS_1GFDiyl57a-unAUXDV3k6CvaJIZFhZMx24
