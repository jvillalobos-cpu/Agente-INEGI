Intrucciones de apertura de servidor
Utilizar el siguiente comando para direccionar la terminal una vez descargado el zip file:
cd C:\Users\XXXX-XXXX\Downloads\AgenteINEGI\Agente-INEGI
Posteriormente utilizar siguiente comando para arrancar el servidor:

del inegi_local.db
python main_local.py setup-db
python main_local.py run-etl
python main_local.py serve
