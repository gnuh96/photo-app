# Photo App

Mini projet pour la gestion des images préférés
Source : https://picsum.photos/

## Foncionnalité

- Render la liste des photos
- Filtrer les photos par catégories
- Ajoute, maj, supprime un photo

## Technologie

- ReactJs(CRA)
- Redux (Redux Toolkit)
- Form management : Formik
- Routing : React Router
- UI libs : Reactstrap
- Redux-Persist

## Tổ chức folder

```
src
|__ assets
|  |__ images
|  |__ styles (global styles)
|
|__ components (shared components)
|
|__ features
  |__ Photo
    |__ components
    |  |__ PhotoList
    |  |__ PhotoCard
    |  |__ PhotoForm
    |
    |__ pages
    |  |__ MainPage
    |  |__ AddEditPage
    |__ photoSlice.js
    |__ index.js
```
