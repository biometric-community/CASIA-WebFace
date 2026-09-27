# CASIA-WebFace

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCASIA--WebFace-181717?logo=github)](https://github.com/biometric-community/CASIA-WebFace)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html)

**CASIA-WebFace** — tbiom catalog packaging for `casia-webface` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/CASIA-WebFace
- **Upstream source**: http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `casia-webface` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: CASIA WebFace; registration / academic request.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/CASIA-WebFace.git
cd CASIA-WebFace
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_casia_webface.sh
```

Place licensed archives under `projects/datasets/casia-webface/` (gitignored).

## Dataset structure

```text
CASIA-WebFace/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html
- Packaging: https://github.com/biometric-community/CASIA-WebFace/issues
