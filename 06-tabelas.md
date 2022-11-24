# Tabelas


|Column 1|Column 2|Column 3|
|---|---|---|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|---|---|---|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Alinhar coluna no centro

|Column 1|Column 2|Column 3|
|:---:|:---:|:---:|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|:---:|:---:|:---:|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Alinhar coluna a esquerda

|Column 1|Column 2|Column 3|
|:---|:---|:---|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|:---|:---|:---|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Alinhar coluna a direita

|Column 1|Column 2|Column 3|
|---:|---:|---:|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|---:|---:|---:|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>


### Tabela - _rowspan_ (emenda de linhas)
<table>
  <tr>
    <th>coluna 1</th>
    <th>coluna 2</th>
    <th>coluna 3</th>
  </tr>
  <tr>
    <td>linha 1 - coluna 1</td>
    <td>linha 1 - coluna 2</td>
    <td rowspan="2" align="center">linha 1 & 2 - coluna 3</td>
  </tr>
  <tr>
    <td>linha 2 - coluna 1</td>
    <td>linha 2 - coluna 2</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>coluna 1</th>
    <th>coluna 2</th>
    <th>coluna 3</th>
  </tr>
  <tr>
    <td>linha 1 - coluna 1</td>
    <td>linha 1 - coluna 2</td>
    <td rowspan="2" align="center">linha 1 & 2 - coluna 3</td>
  </tr>
  <tr>
    <td>linha 2 - coluna 1</td>
    <td>linha 2 - coluna 2</td>
  </tr>
</table>
```

### Table - _colspan_ (emenda de colunas)
<table>
  <tr>
    <th>coluna 1</th>
    <th>coluna 2</th>
    <th>coluna 3</th>
  </tr>
  <tr>
    <td>linha 1 - coluna 1</td>
    <td colspan="2" align="center">linha 1 - coluna 2 & 3</td>
  </tr>
  <tr>
    <td>linha 2 - coluna 1</td>
    <td>linha 2 - coluna 2</td>
    <td>linha 2 - coluna 3</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>coluna 1</th>
    <th>coluna 2</th>
    <th>coluna 3</th>
  </tr>
  <tr>
    <td>linha 1 - coluna 1</td>
    <td colspan="2" align="center">linha 1 - coluna 2 & 3</td>
  </tr>
  <tr>
    <td>linha 2 - coluna 1</td>
    <td>linha 2 - coluna 2</td>
    <td>linha 2 - coluna 3</td>
  </tr>
</table>
```