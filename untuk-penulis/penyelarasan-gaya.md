# Gaya Penulisan

Dokumen ini ditulis untuk menyelaraskan gaya penulisan buku ini.

## Senarai Label Persamaan
Persamaan dirujuk menggunakan direktif ``{eq}`label` ``.
| Nama | label |
|:--- | :---|
| Hukum Stefan-Boltzmann | hukum_stefan_boltzmann |
| Hukum Sesaran Wien | hukum_sesaran_wien |

## Senarai pemalar
Pemalar disimpan sebagai pembolehubah kod yang ditulis sebagai {{label}} dan label diganti dengan apa yang sudah ditakrifkan dalam `_config.yml`.

| Nama | label |
|:---|:---:|
| Stefan-Boltzmann | pemalar_stefan_boltzmann |

## Hukum
````{admonition} Nama Hukum
Keterangan hukum...
```{math}
:label: hukum_newton
  F=ma,
```
```{admonition} dengan maksud bahawa...
:class: tip, dropdown

| simbol | maksud | nilai |
| :---: | :--- | :--- |
| $F$ | daya | pembolehubah bergerak balas |
| $m$ | jisim jasad | pembolehubah tidak bersandar |
| $a$ | pecutan | pembolehubah tidak bersandar |
```
````