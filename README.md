# 🎬 PeliculasApp

PeliculasApp es una aplicación móvil desarrollada con **Ionic Framework y Angular** que permite a los usuarios explorar películas en tres categorías: Nuevas, En Cartelera y Populares. También ofrece detalles completos de cada película y permite guardarlas como favoritas para su consulta posterior.

---

## 📌 Descripción General

Esta aplicación simula una plataforma de consulta de películas. A través de una interfaz moderna y adaptativa, los usuarios pueden:

- Navegar entre películas destacadas mediante carruseles.
- Consultar información detallada como sinopsis, géneros, reparto, calificación y número de votos.
- Guardar películas como favoritas y acceder a ellas desde una pestaña dedicada.
- Navegar de forma intuitiva usando una barra de pestañas (`ion-tab-bar`).

---

## ⚙️ Tecnologías y Dependencias

La aplicación está construida con las siguientes herramientas y librerías:

- [Ionic Framework 6](https://ionicframework.com/)
- [Angular 15+](https://angular.io/)
- TypeScript
- HTML + SCSS
- Angular Router
- Ionic Components (`ion-card`, `ion-slides`, `ion-chip`, `ion-button`, etc.)

### Dependencias Clave

```json
"@ionic/angular": "^6.x.x",
"@angular/core": "^15.x.x",
"rxjs": "^7.x.x",
"zone.js": "~0.11.4"

src/
├── app/
│   ├── pages/
│   │   ├── home/         # Vista principal
│   │   ├── detail/       # Detalle de película
│   │   └── favoritos/    # Lista de favoritas
│   ├── services/         # Lógica y datos simulados
│   └── app-routing.module.ts
├── assets/
├── index.html
└── theme/
