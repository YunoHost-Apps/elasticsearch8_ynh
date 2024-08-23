<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# ElasticSearch 8 untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/elasticsearch8.svg)](https://ci-apps.yunohost.org/ci/apps/elasticsearch8/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/elasticsearch8.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/elasticsearch8.maintain.svg)

[![Pasang ElasticSearch 8 dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=elasticsearch8)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang ElasticSearch 8 secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the [Elastic Stack](https://www.elastic.co/products). You can use Elasticsearch to store, search, and manage data for logs, metrics, search backend, application monitoring, Endpoint security.
To learn more about Elasticsearch’s features and capabilities, see the [product page](https://www.elastic.co/products/elasticsearch).


**Versi terkirim:** 8.11.1~ynh3

**Demo:** <https://www.elastic.co/demos>
## :red_circle: Antifitur

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://elastic.co>
- Dokumentasi admin resmi: <https://www.elastic.co/guide/en/elasticsearch/reference/8.11/elasticsearch-intro.html>
- Depot kode aplikasi hulu: <https://github.com/elastic/elasticsearch>
- Gudang YunoHost: <https://apps.yunohost.org/app/elasticsearch8>
- Laporkan bug: <https://github.com/YunoHost-Apps/elasticsearch8_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing --debug
atau
sudo yunohost app upgrade elasticsearch8 -u https://github.com/YunoHost-Apps/elasticsearch8_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
