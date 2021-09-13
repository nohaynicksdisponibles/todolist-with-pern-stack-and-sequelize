# todolist-with-pern-stack-and-sequelize
Todo List Web Application using Postgres SQL, Express, React JS, and Node JS with Sequelize as ORM
</br>
PASOS para utilizar la app:
1) clonar el proyecto
2) instalar las dependencias
3) cambiar los datos del conector (Sequelize) en la ruta ./server/util/databaseconnect.js por los correspondientes de tu base de datos local
3) lanzar la aplicación!

App para crear TODO LIST

<img src="https://bl3302files.storage.live.com/y4mS6epbX-8wBtK1EHXJcrDlaUWhtlc3CbS7z2DlDqJZvh7mLucIexVApMO9xTqB6ESpFROEgeIEZXKyqGiphgLIGp4XUsspb73iLDe8LM-D5AiqjEofaNgl7SoVpzRCRvoGpaAQ131YGTfxHFcIlvnN6Repz_OGQeErxVpNAUai_45csASThRcYW8KzKE9C54P?width=1342&height=574&cropmode=none" width="1342" height="574" />

Se debe crear una categoría para asignarla al nueva item, sin la misma no se podrá guardar en la TODO LIST

el campo categoría no se puede vacio!
<img src="https://bl3302files.storage.live.com/y4mhEuCS5233umXmRGy93ch1_rkeciNOjGeISJmO5332fwH9iseo1yoqjsVryzmgQ488RTH7STSBK_ERZCZahvx6Mmd9oZ4WFL-_79Uy6ubKFzxUXQo-hi0BQHlx5BIa0p-bdEhZvSgJMk4mGpOYbLADjZfnD1FL2Y8vKAaIXcDlKHl8F48WHSbTRmHoyCr_wpx?width=1346&height=576&cropmode=none" width="1346" height="576" />

luego de agregar la categoría aparecerá en el dropdown y se podrá asignar al nuevo ITEM
<img src="https://bl3302files.storage.live.com/y4msLF2JOSRYodLLLl3iIVSlA0j3RcKzkqt5utHtOTMQaCm05fC8t91yoLKC7LHnQCnC10_ZSanz6cqOLF-Opw83jpCK5h2JebDS1XZWtnFfAE4cbqgRNgzXDlOG56HkpvbbeWjZ1rFUAAQuNCOflx6aL3bX0cvW3-pllXumJgzPMOE-qCyyy_kGsMMc3jMN3vt?width=1290&height=556&cropmode=none" width="1290" height="556" />

La tabla con los items podrá filtrar por categorías para facilitar la busqueda de los mismos.
<img src="https://bl3302files.storage.live.com/y4mRCTFkuGH8UEdIET7jfToCul0fX2Gr_F99C6GbGOj7NWUHMC91Eui1_83fGzQ5vty4r7GDTDvB9xnyBxF7qt9agfSrh7pXMPdBixt7fsByZEWj0xo7NVsT6oaZGO4v7BkrABuBUSBGMgnIuNEXYbJSv8Xg1mollN3od_PXui2D4Gb1MJYzkzoA8zqbw5BT5DY?width=1308&height=569&cropmode=none" width="1308" height="569" />

Aquí se muestra como ejemplo el filtrado con la cetegoría jugos
<img src="https://bl3302files.storage.live.com/y4mY9HAkrV8TPuQeEIEB9vDbJ0yMhYLW9NGx1h35NCu_Q7xgYHqqSWYsdmCErHtHRBnpgqAdghCjUZrgKQaJ-DczxXsvUiPXk4X7QkzGhA45cMberltQ4eEkc04fa3uKpuq5SPzq40ylWj2HuDsMKFQybJYAUSePiA04iS0LhY7ptNc6sIdzcD65hELcdaEwv4O?width=1281&height=306&cropmode=none" width="1281" height="306" />
