# Challenge de dos días:

Vamos a realizar el PUT de un usuario. Solo hay un punto de corte y debe quedar como la imagen.

Dia 1: Vamos a realizar el backend. Para ello tendremos 2 rutas:

- (GET) /user/:id
- (PUT) /user/:id

Nota: No hay que hacer el POST, se pueden dar de alta los usuarios en la colección usando Atlas. La información de la entidad user la podéis obtener del diseño.
Nota 2: NO hay que autenticar las rutas.
Nota 3: Para la imagen de perfil debemos utilizar Multer con supabase
Nota 4: Para las validaciones debemos usar express-validation

Día 2: Vamos a realizar el frontend. App react-redux con una única página que tenga el path /user/:id que recupere la información de ese usuario y que permita actualizar dicha información.

## Necesito un .env y levantar el servidor para que pueda funcionar en Render
