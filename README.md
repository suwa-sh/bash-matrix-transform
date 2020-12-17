# bash-matrix-transform

## script

```bash
cat data/key_value.csv | # key-value形式のcsvから
lib/parsrc.sh          | # line field indexed value に変換
lib/self 2 1 3/NF      | # 行番号と列番号のカラムを入れ替え
sort                   | # makrc用に行番号,列番号でsort
lib/makrc.sh             # csvに変換
```

## refs

- [ShellShoccar-jpn/Parsrs](https://github.com/ShellShoccar-jpn/Parsrs)
  - parsrc.sh
  - makrc.sh
- [Tukubai/self](https://uec.usp-lab.com/TUKUBAI_MAN/CGI/TUKUBAI_MAN.CGI?POMPA=MAN1_self)
