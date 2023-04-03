## Alerts

<div class="alert-protip">
  <span class="alert">&times;</span>
  <strong>Pro Tip 1</strong><br>Method <strong>rename</strong> can take a function: <pre>df.rename(columns=lambda x: x.lstrip())</pre>
</div>


<div class="alert-warning">
  <strong>Note:</strong>
  <p>Note that method works on both axes - `axis=1` - means columns.</p>
</div> 
## Color palette

Several colors are defined in the theme as variables. They are divided in 2 groups: 
### Text colors
    --red-txt-color
    --green-txt-color
    --yellow-txt-color
### Background colors
    --red-bg-color
    --green-bg-color
    --yellow-bg-color
    --light-blue-bg-color

### Usage
Use as the names imply - first group for text and the second for backgrounds. They are designed be readable in different combinations and change according to the theme mode (light/dark).
Text:
```
style="color:var(--red-txt-color)"
```
Background:
```
style="background-color:var(--red-bg-color)"
```


See the striped table example below.
## Striped Table
For striped table use class="table-striped" in the table tag. As result the color of the rows of the table will alternate.
If you want custom colors for the text or the background in the table, it's advisable to use the color palette from above so it looks good in both light and dark theme.

<table border="1" class="dataframe table table-striped text-center">
  <thead>
    <tr style="text-align: center;">
      <th></th>
      <th>Color</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td style="background-color:var(--red-bg-color)"> red-bg-color</td>
    </tr>
    <tr>
      <th>1</th>
      <td style="background-color:var(--green-bg-color)"> green-bg-color</td>
    </tr>
    <tr>
      <th>2</th>
      <td style="background-color:var(--yellow-bg-color)"> yellow-bg-color</td>
    </tr>
    <tr>
      <th>0</th>
      <td style="color:var(--red-txt-color)"> red-txt-color</td>
    </tr>
    <tr>
      <th>1</th>
      <td style="color:var(--green-txt-color)"> green-txt-color</td>
    </tr>
    <tr>
      <th>2</th>
      <td style="color:var(--yellow-txt-color)"> yellow-txt-color</td>
    </tr>
  </tbody>
</table>

## Code


```python
import pandas as pd
from pandas.util.testing import makeTimeSeries

df = makeTimeSeries()
df.head()
```

## result:

    2000-01-03   -2.066624
    2000-01-04   -0.897585
    2000-01-05   -0.458669
    2000-01-06    1.038565
    2000-01-07   -0.058897
    Freq: B, dtype: float64


## Quote

> It's possible to create a Series or DataFrame with time series data for tests. Both have index datetime and numeric values.


## Link

[https://datascientyst.com/how-to-create-a-dataframe-of-random-integers-with-pandas/](https://datascientyst.com/how-to-create-a-dataframe-of-random-integers-with-pandas/)

## List
* item1
* item2

## Headings
## title 2
### title 3
#### title 4
##### title 5

## Image

![](https://datascientyst.com/content/images/2021/12/create-easily-dummy-dataframe-test-data.png)

## InfoBoxes 1

<div class="alert-protip">
  <span class="alert"></span>
  <strong>Rules of thumb</strong><br>
  <strong>1</strong>
  <pre>2</pre>    
   Always work with "timezone-aware" datetime objects.<br>
   Always store datetime in UTC and leave rendering of timezones to the front-end.
</div>

## InfoBoxes 2

<div class="alert-protip">
  <span class="alert"></span>
  <strong>Pro Tip 1</strong><br>Method <strong>rename</strong> can take a function: <pre>df.rename(columns=lambda x: x.lstrip())</pre>
</div>

## Colapsible

<button class="collapsible-header">Open Collapsible</button>
<div class="collapsible-body">
<p><div><strong>rows</strong> - observations, records, trials</div>
<div><strong>columns</strong> -  variable, feature</div></p>  
</div>


## Wrapped Image

<p><img class="about" src="https://datascientyst.com/content/images/2022/06/panda_about.png" alt="Pineapple" style="width:170px;height:170px;margin-left:15px;float: right;">
Wrap image around text. Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.Wrap image around text.</p>