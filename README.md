# Json File Translator from soure to target language

## Set up

- Clone the repository

```bash
 git clone https://github.com/Ginohmk/json_file_lang_translator.git
```

- Cd into the folder

```bash
cd json_file_lang_translator

```

## Folder structure

.
├── data (holds json file)
│ ├── source.json
│
├── lib
│ ├── **pycache**.py
│ ├── translator.py
│
├── app.py
├── test.py
└── README.md

## How to use

- You need to place your source json file inside of data folder and name it source.json

- Run the program

```bash
python3 app.py

```

- Follow thw prompt

  - Enter the abbreviation of the source language (For English en )
  - Enter the abbreviation of the target language (For Spanish es)

- Allow it to run the program, your output target json translation will be in the data folder, with the <target abbrviation name>.json
