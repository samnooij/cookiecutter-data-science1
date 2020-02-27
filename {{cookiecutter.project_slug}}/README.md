# {{cookiecutter.project_name}}

_Date: {% now 'utc', '%Y-%m-%d' %}_  
{% if cookiecutter.email != " " -%}
_Author: {{cookiecutter.name}} ({{cookiecutter.email}})_
{% else -%}
_Author: {{cookiecutter.name}}_
{% endif %}

{{cookiecutter.project_short_description}}

---

## Project organisation

```
.
├── .gitignore
├── CITATION.cff
├── LICENSE
├── README.md
├── bin                <- Code and programs used in this project/experiment
├── data               <- All project data, divided in subfolders
│   ├── processed      <- Final data, used for visualisation (e.g. tables)
│   ├── raw            <- Raw data, original, should not be modified (e.g. fastq files)
│   └── tmp            <- Intermediate data, derived from the raw data, but not yet ready for visualisation
├── doc                <- Documents such as manuscript
│   └── literature     <- Subfolder for literature related to the project/experiment
├── envs               <- Conda environments necessary to run the project/experiment
├── log                <- Log files from programs
└── results            <- Figures or reports generated from processed data
```

---

## Licence

This project is licensed under the terms of the [fill in your licence here](LICENCE).

---

## Citation

Please cite this project as described [here](CITATION.cff).
