<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ElasticSearch 8 YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/elasticsearch8.svg)](https://dash.yunohost.org/appci/app/elasticsearch8) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/elasticsearch8.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/elasticsearch8.maintain.svg)

[![Instalatu ElasticSearch 8 YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch8)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ElasticSearch 8 YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Paketatutako bertsioa:** 8.11.1~ynh3

**Demoa:** <https://www.elastic.co/demos>
## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizkoa ez da erabat librea**: Aplikazioak lizentzia librea du orokorrean, baina bere erabilera mugatzen duten klausulekin.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://elastic.co>
- Administratzaileen dokumentazio ofiziala: <https://www.elastic.co/guide/en/elasticsearch/reference/8.11/elasticsearch-intro.html>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/elastic/elasticsearch>
- YunoHost Denda: <https://apps.yunohost.org/app/elasticsearch8>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/elasticsearch8_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing --debug
edo
sudo yunohost app upgrade elasticsearch8 -u https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
