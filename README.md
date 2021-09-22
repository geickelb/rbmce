<h1 align="center">

</h1>
<p>
<img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
<a href="https://github.com/pedroermarinho/markdown-readme-generator#readme" target="_blank"><img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" /></a>
<a href="https://github.com/pedroermarinho/markdown-readme-generator/graphs/commit-activity" target="_blank"><img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /></a>
<a href="https://github.com/pedroermarinho/markdown-readme-generator/blob/master/LICENSE" target="_blank"><img alt="License:MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a>

</p>

### RBMCE (Rule-Based Microbiology Concept Extractor):
>This code was developed to provide an open-source python package to extract clinical concepts from free-text semi-structured microbiology reports. The two primary outputs for this package are (1) an binary estimation of patient bacterial infection status and (2) a list of all clinically relevant microorganisms found in the report. These outputs were validated on two independent datasets and achieved f-1 scores over 0.95 on both outputs when compared to expert review. Full details on background, algorithm, and validation results can be seen at our paper here: (currently being written, will update once submitted to archive).

### 🏠 [Homepage](https://github.com/geickelb/rbmce)
### ✨ [package](https://pypi.org/project/rbmce/)

## Requirements
```sh
* python >=3.6.8
* pandas >=0.25.0

```

## Install
```sh
pip install rbmce
***add

```

## Usage
#### Inline:
```sh
import rbmce
import pandas as pd
d={'parsed_note': 'No Salmonella, Shigella, Campylobacter, Aeromonas or Plesiomonas isolated.', 'culture_id': 1, 'visit_id': 1}
df=pd.DataFrame(data=d, index=[1])
rbmce.run(df)
***add

```
#### Command Line:
```sh
mrgenerator-cli
***add

```


## Run tests
#### Inline 
```sh
from rbmce import debug
test_str='No Salmonella, Shigella, Campylobacter, Aeromonas or Plesiomonas isolated.'
debug.rbmce_str_in(test_str)

```
#### Command Line:
```sh
python -m rbmce.debug 'No Salmonella, Shigella, Campylobacter, Aeromonas or Plesiomonas isolated.'

```


## Author
👤 **Garrett Eickelberg**







## 🤝 Contributing
Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/pedroermarinho/markdown-readme-generator/issues). You can also take a look at the [contributing guide](https://github.com/pedroermarinho/markdown-readme-generator/blob/master/CONTRIBUTING.md)
## Show your support
Give a ⭐️ if this project helped you!
## Credits
**[Markdown Readme Generator](https://github.com/pedroermarinho/markdown-readme-generator)**
## 📝 License

This project is [MIT](https://github.com/pedroermarinho/markdown-readme-generator/blob/master/LICENSE) licensed.

---
_This README was created with the [markdown-readme-generator](https://github.com/pedroermarinho/markdown-readme-generator)_