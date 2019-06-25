# rime-logic-symbols

A Rime Input Method Designed for Logic. 爲邏輯系統設計的 Rime 輸入方案

## Demo

![Demo](https://raw.githubusercontent.com/dsh0416/rime-logic/master/.assets/output.gif)


## Features

- Enter Logic Symbols with ASCII Shape
- Providing Symbols with Same Usage as Candidates

## Usage

See [Dictionary File](https://github.com/dsh0416/rime-logic/blob/master/logic_symbols.dict.yaml) for Definitions

## Installation

### Download
```bash
git clone https://github.com/dsh0416/rime-logic.git
cd rime-logic
ln -s ./logic_symbols.* THE_DIRECTORY_OF_YOUR_RIME_LIBRARY
```

### Installation

- Edit `default.custom.yaml`
- Add `- schema: bopomofo_symbols` to `schema_list`
- Re-deploy

## History

- 2019.6.25 Initial Release
