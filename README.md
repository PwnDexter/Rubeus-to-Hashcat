# Rubeus-to-Hashcat
Converts / formats Rubeus kerberoasting output into hashcat readable format

## Install

```
git clone https://github.com/PwnDexter/Rubeus-to-Hashcat.git
```

## Usage

Run the script and specify the file with the raw rubeus output -i <input file> and then specify the file to save the parsed output too -o <output file>
```
python Rubeus-to-Hashcat.py -i rubeus-raw-output.txt -o formatted-for-hashcat.txt
```
