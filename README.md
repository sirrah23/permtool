# permtool

This tool allows you to view and edit file permissions.

## Prerequisites

Make sure you have pipenv installed.

## Installation

```bash
git clone https://github.com/sirrah23/permtool.git
cd permtool
pipenv install
```

## Usage

```bash
python3 permtool --help
python3 permtool read "/path/to/directory/" 
python3 permtool read "/path/to/file" 
python3 permtool write "/path/to/file" 755
python3 permtool write "/path/to/directory" 755
python3 permtool write --filter="655" "/path/to/directory" 755
```
