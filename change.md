## V2.6.0 (2024-31-07)

### Tasks

* [25162] Agregado guía de migración v2.4.0 a v2.5.0
* [25942] Agregada columna client_id a la tabla employees
* [25802] Agregado endpoint para listar y filtrar jornadas
* [25801] Agregados ajustes en el endpoint para cerrar jornadas desde el panel de administración
* [25804] Agregado endpoint workdays/options para la lista de jornadas
* [25101] Agregado el mock de los endpoints del CRUD de vehículos SR
* [25485] Agregada la propiedad "is_editable" en el endpoint user by id
* [26081] Modificada la tabla vehicle_type para permitir valores nulos en la columna load_site_category_id
* [26040] Ajustado el endpoint GET /field-service/vehicle-types/options
* [25886] Ajustado el endpoint POST /field-service/vehicle-types
* [25883] Agregada la implementación del endpoint POST /field-service/vehicle-types/:id
* [25881] Ajustado el endpoint /field-service/vehicle-types/options
* [25621] Agregado el LOV para los estados de las jornadas
* [25620] Agregada la columna "status" a la tabla workdays
* [24988] Agregada la columna "functional_area" a la tabla employees
* [24987] Agregada la columna "functional_area" a la tabla vehicles
* [24986] Agregada la columna "functional_area" a la tabla vehicle_type

### Features

* [25942] Agregado de Script para agregarle el client_id a los employees existentes
* [25501] Agregado de implementación endpoints para iniciar y finalizar jornada
* [25921] Agregado la creacion de la tabla pivot para relacionar la tabla "vehicle_type" con "tasks"
* [25580] Agregado la implementación de los endpoints para listar Tipo de Vehículo SR
* [25500] Agregado la creación del endpoint GET /field-service/vehicle-types/options
* [25489] Agregado la creación del endpoint POST /field-service/vehicle-types
* [25161] Agregado de la lov "functional_areas" a la tabla lov

### Bug Fixes

* [25121] Bug al filtrar los Tipos de Contenedores en el crud de contenedores
* [25340] Bug en Modal de Recoleccion parcial/total
* [25522] Bug al crear SR
