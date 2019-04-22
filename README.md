# koop-provider-socrata

# Prerequisitos

- NodeJS
- [ngrok](https://ngrok.com/) - Cuenta gratuíta con github


## Clonar este repo

```bash
git clone https://github.com/ntkog/POC_Koop_Socrata_CAT.git
cd POC_Koop_Socrata_CAT
```

## Instalar las dependencias


```bash
npm i
```

## Arrancamos Koop

```bash
npm run start
```


## Abre otro terminal y teclea lo siguiente

```bash
ngrok http 8080
```

> Te aparecerán unas URLS . Copia la que empiece con https


## Desde AGOL

Ir a **Contenido** y seleccionar **desde la web**

Seleccionar **ArcGIS Server**

Introducir la URL del servicio desplegado

> Ejemplo ( A modo ilustrativo, esta URL no está publicada) :

[https://556674d1.ngrok.io/socrata-example/rest/services/analisi.transparenciacatalunya.cat/cg46-ysub/FeatureServer/0](https://https://556674d1.ngrok.io/socrata-example/rest/services/analisi.transparenciacatalunya.cat/cg46-ysub/FeatureServer/0)
