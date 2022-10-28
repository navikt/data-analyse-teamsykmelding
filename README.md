# data-analyse-teamsykmelding

Datapakke/datapakker for team sykmelding

Her er linker til dokumentasjon og andre nyttige sider:

Docs Jupyter notebooks: https://docs.knada.io/prosessere-data/notebook_intro/

Jupyter teamsykmelding: https://53c5249546289eb6-dot-europe-west1.notebooks.googleusercontent.com

Repo: https://github.com/navikt/data-analyse-teamsykmelding

CronJob:
Kjøres via Notebook
1 gang hver natt kl 03:00

https://docs.knada.io/dataprodukter/produsere/skedulering/notebook-gcp-cronjob/

### Hemmligheter
Tokenet som vi benytter i datafortelling ligger i Secret manager google:
https://console.cloud.google.com/security/secret-manager/secret/teamsykmelding_datastory_token_prod/versions?project=teamsykmelding-prod-2acd

#### oppdatere mijø variablen
```
os.environ.update(DATASTORYTOKEN="$sometoken")
```

### Kontakt/spørsmål

Prosjektet er vedlikeholdt av [teamsykmelding](CODEOWNERS)

Spørsmål og/eller feature requests? Vennligst lag ein [issue](https://github.com/navikt/data-analyse-teamsykmeldin/issues).

Dersom du jobber i [@navikt](https://github.com/navikt) kan du nå oss på slack
kanalen [#team-sykmelding](https://nav-it.slack.com/archives/CMA3XV997).
