# surfs_up

## Overview of the analysis:
Provide statistical temperature data for the months of June and December in Oahu, based on the sqlight db "hawaii.sqlite"

## Resources
- Data Source: hawaii.sqlite
- Software: Python 3.7, Jupyter Notebook, 1.68.1

## Results
- There is only an 8&deg; difference (56&deg;-64&deg;F) between June and December for minimum temperature
- There is only a 4&deg; difference (71&deg;-75&deg;F) between June and December for average/mean temperature
- There is only a 2&deg; difference (83&deg;-85&deg;F) between June and December for maximum temperature


### Month of June Statistics

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>temp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>1700.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>74.944118</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3.257417</td>
    </tr>
    <tr>
      <th>min</th>
      <td>64.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>73.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>75.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>77.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>85.000000</td>
    </tr>
  </tbody>
</table>

### Month of December Statistics

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>temp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>1517.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>71.041529</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3.745920</td>
    </tr>
    <tr>
      <th>min</th>
      <td>56.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>69.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>71.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>74.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>83.000000</td>
    </tr>
  </tbody>
</table>

## Summary
Based upon the statistical data it shows that the temperature for Oahu stays comparatively consistent year around.

Providing two additional queries covering the precipitation of both June and December might yield statistical data supporting Oahu's temperate climate.
