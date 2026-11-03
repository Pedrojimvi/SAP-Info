# SAP-Info

Transacciones:<br>
<br>SU01 - creación y modificación de usuarios
<br>PFCG - creación órdenes de transporte y detalle de roles
<br>SE16 - visualización tablas SAP
<br>SE01/SE10 - órdenes de transporte
<br>SU53 - ver errores de autorización
<br>SU10 - adicción de roles a varios usuarios
<br>SUIM - información de usuarios (borrados o no)
<br>STMS_QA - aprobación de órdenes para paso de producción
<br>/n/ui2/flpcm_cust - ver catálogo, tiles y roles
<br>SOST - mensajes/órdenes de envío (Correos)
<br>/n/ui2/flpd_cust - gestionar catálogos
<br>SM12 - eliminar bloqueos (GRP)
<br>SE38  (PFCG_MASS_VAL) => actualización en masa de valores de autorización
<br>SE38 (PRGN_COMPARE_ROLE_MENU) => actualizar menús y catálogos
<br>SPRO => creación o modificación de sociedades
<br>s_alr_87101203 => ver fecha último acceso de los usuarios
<br>SE63 => traducción de textos https://community.sap.com/t5/technology-blogs-by-members/cache-cleanup-in-sap-netweaver-gateway/ba-p/13362971
<br>SE38 => ejecutar programas
<br>RZ11 (login/password_max_idle_initial) => máximo días una password hasta que se resetee
<br>SU24 - para ver los objetos de propuesta de las transacciones
<br>SLG1 - visualización de Logs
<br>SE11 - visualización de tablas, dominios…
<br>SM35 - ejecutar y visualizar jobs de fondo
<br>SM36 - crear jobs planificados
<br>SM37 - ejecutar y visualizar cargas masivas de fondo
<br>SM04 - ver sesiones activas del usuario
<br>SE93 - modificar y crear transacciones
<br>T001K - relación sociedades y objetos organizativos
<br>SE37 - creación funciones
<br>SM30 - añadir información a tablas
<br>SM59 - conexiones con el sistema
ST22 - ver DUMPs
<br>/n/ui2/SEMOBJ - creación del objeto semántico de las FIORI APPS. (para el momento de fiorizar una transacción )
<br>KE51 - creación de CEBE
<br>SQVI - autorizadores de un rol
<br>SM51 - cambiar de instancias en un sistema (cuando se quiera acceder a otra trx, debe hacerse desde la misma)
<br>SE91 - ver mensajes error
<br>RSM37 - parametros de input de los jobs de fondo
<br>SUGR - creación Grupo usuarios
<br>STAUTHTRACE - mirar registro de entradas a transacciones de usuario
<br>GRFNMW_CONFIGURE - revisión procesos, variables de notif. MSMP
<br>SOTR_EDIT - editor de OTR para textos con alias
<br>SE61 - revisar, modificar textos usados en correos…

<br>TABLAS DE LA SE16:<br>
<br>AGR_DEFINE: para descripción e información de roles
<br>AGR_TEXTS: para únicamente descripción
<br>AGR_1251: para objetos no organizativos
<br>AGR_1252: para objetos organizativos
<br>AGR_USERS: asignación de roles a usuarios 
<br>T001 - correspondencia de sociedades
<br>TSTC - descripción de transacciones
<br>USR02 - maestro de usuarios
<br>USR03 - nombre usuarios
<br>GRACUSER y GRACUSERCONN (GRP) => saber si un usuario existe en todos los sistemas a la vez
<br>USVAR - descripción niveles organizativos
<br>USER_ADDR - información Direc. Usuarios
<br>AGR_1016 - estado de generación de roles
<br>GRACUSERROLE - ver id roles usuarios
<br>GRACRLCONN - ver nombre roles por id
<br>UJE_PROFILE_AGR - UJE_TEAM_AGR - UJE_USER_AGR - tablas para mirar la relación entre los Teams y los roles
<br>T001K - relación Sociedad Centro
<br>TVKO - org. de ventas
<br>USH02 - tabla user históricos
<br>TKA02 - tabla para comprobar los KOKRS de los BUKRS
<br>FAGL_SEGMT - para ver la relación entre sociedad y segmento
<br>FAGLFLEXT - información relacionada con sociedades y segmentos
<br>USOBT - conexión entre objetos de autorización y transacciones
<br>GRACACTUSAGE - ver uso de programas en el sistema
<br>USR01 - obtener los Person number
<br>ADR6 - filtro con los person number
<br>AGR_HIER -  ver los valores del Menú de varios roles
<br>CDPOS - información del cambio real en una transacción
<br>CDHDR - información del cambio sin detalle de una transacción
<br><br>T001K para los WERKS del BUKRS
<br>TKA02 para el KOKRS del BUKRS
<br>CEPC_BUKRS para los PRCTR del BUKRS
<br>FAGLFLEXT y BSEG para los SEGMENT del BUKRS
<br>PRPS para los PS_PRART del BUKRS
<br>CSKS para los KOSTL del BUKRS
<br>TVKO para los VKORG del BUKRS (entre otros)
<br>EKKO para los EKORG y EKGRP del BUKRS
<br>TVSTZ para los WERKS y VSTEL (pasando por las tablas T001 para el LAND y la T001K para los BUKRS y WERKS)
<br>LFA1 para los KTOKK del BUKRS
