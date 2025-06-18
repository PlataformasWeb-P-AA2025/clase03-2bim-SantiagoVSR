# clase03-2bim
![imagen](https://github.com/user-attachments/assets/3b170bd6-a97e-4680-94f2-c18db109f5f5)

al no definir en models.py en la clase NumeroTelefonico el related_name="mis_numeros_telefonicos") no podremos utilizarlo el e.mis_numeros_telefonicos.all en listadoestudiantesdos.html 
para eso tambien podremos defirnir de la siguiente manera e.numerotelefonico_set.all utilizando el _set.all al dinal de la clase creada en models.py
