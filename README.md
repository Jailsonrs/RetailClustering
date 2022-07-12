
<p align="center">
  <img src="design/logo_beta.png" />
</p>




Acesse a versão em desenvovimento do App em: https://jailson-rodrigues.shinyapps.io/Cluster-dev/

## Project Structure

```
.
├── app
│   ├── data
│   │   ├── raw
│   │   │   └── dados_municipais.csv
│   │   └── transformed
│   │       ├── clustered_dataset
│   │       ├── dados_limpos.csv
│   │       └── UMAP_embeddings.csv
│   ├── index.html
│   ├── rsconnect
│   │   └── shinyapps.io
│   │       └── jailson-rodrigues
│   │           └── Cluster-test.dcf
│   ├── server.R
│   ├── src
│   │   └── R
│   │       ├── libs.R
│   │       ├── modules
│   │       │   ├── inputs.R
│   │       │   └── outputs.R
│   │       ├── multiClassSummary.R
│   │       └── MyGgthemes.R
│   ├── ui.R
│   └── www
│       ├── alert.js
│       └── style.css
├── appscreen.png
├── data
│   ├── raw
│   │   └── dados_municipais.csv
│   └── transformed
│       ├── clustered_dataset
│       ├── dados_limpos.csv
│       └── UMAP_embeddings.csv
├── README.md
├── src
│   ├── clustering.py
│   ├── Dockerfile
│   ├── ranking.py
│   └── sankey.R
└── UMAP-GMM.ipynb



```

## Screenshots

![alt text](appscreen.png)

### Application Structure:
<p align="center">
  <img src="PoneghlypArct.png" />
</p>
