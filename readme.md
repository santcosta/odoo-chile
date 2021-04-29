# Factura electronica chile

En teoria los modulos que hay para la version 11.0 de odoo funcionan para realizar FE.

### Listado de modulos necesarios : 

- https://github.com/KonosCL/addons-konos/tree/11.0
- https://gitlab.com/dansanti (En este git esta el modulo principal de FE y hay otros modulos que se podrian probar ya que son interesantes pero puede que no esten funcionando al 100%)
    - l10n_cl
    - l10n_cl_fe
    - l10n_cl_chart_of_account
    - Estos modulos serian los basicos para funcionar.

Una ves instalados todos estos modulos hay que configurarlo.

# Documentos requeridos

- INFO de la pagina del SII (vendria a ser como AFIP) [Factura electronica](https://www.sii.cl/servicios_online/1039-como_fact_elect-1182.html)
- La empresa debe elegir alguno de las dos opciones :
``` 
Usted puede ser emisor de factura electrónica eligiendo una de las siguientes alternativas:
- Sistema de facturación gratuito del SII 	- Sistema de facturación propio o de mercado (Este seria el metodo en caso de utilizar Odoo)
```
- En ambos casos es necesario contar con un [certificado digital](https://www.sii.cl/servicios_online/1039-certificado_digital-1182.html) . En el link se detalla que es y para que sirve y como conseguir el mismo ya que hay varios proveedores por los cuales uno puede optar.

### ¿Cuáles son los pasos para inscribirse en el sistema elegido?

**Sistema de facturacion propio o de mercado**

1. Desarrollar o Adquirir un software para emitir
documentos tributarios electrónicos.
2. Postule a través del menú de Factura Electrónica.
Debe ser realizada por el representante legal,
autenticado con certificado digital.
3. El SII valida su postulación e inscribe al contribuyente
en un proceso de CERTIFICACIÓN.
4.  Aprobada la certificación, el SII emite una resolución
de autorización para ser emisor electrónico.

[POSTULACION](https://www.sii.cl/servicios_online/1039-.html)


## ¿Que debo cumplir para emitir facturas?
1.  Debe primero tener todos los temas regulados en el SII
2.  Si es primera vez que emite factura, debe solicitar verificación de giro
3.  Para inscribirse en uno de los sistemas usted primero debe contar con un certificado digital.
4.  Iniciar la postulación al proceso de certificación en el link http://www.sii.cl/servicios_online/1039-postulacion-1184.html
5.  Seleccionar sólo los documentos que usted puede emitir ( No confundir factura de compras con factura de proveedor, para emitir factura de compras, debe tener una resolución del SII para ese tema)
6.  Realizar el proceso de certificación
7.  Valida el proceso de certificación

## CONFIGURACION DE LOS MODULOS

Luego de obtener todas las certificaciones y documentos necesarios hay que configurar el odoo, este paso aun no sabria como realizarlo jeje

En principio no parece dificil teniendo el certificado lo primero seria configurar bien la empresa y esto se realiza en Ajustes-Compañia.
