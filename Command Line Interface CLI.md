--Muestra la ayuda para cuando estemos en el SFDX
    sfdx force:auth:web:login -h
    sfdx force:auth:web:login --help

--Para autorizar Dev Hub, use el flujo de inicio de sesión web
    sfdx force:auth:web:login -d -a DevHub
    Una vez que se ejecute esté comando en la terminal nos abrira una página en el navegador
    Nos logeamos con nuestras credenciales de Salesforce

--Si desea abrir la organización Dev Hub para ver organizaciones de scratch activas o su registro de espacio de nombres, 
el alias es bastante útil
    sfdx force:org:open -u DevHub