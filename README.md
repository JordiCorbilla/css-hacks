# css-hacks

A curated list of CSS hacks by Jordi Corbilla

## 1) Child Selectors

<table>
  <tbody>
    <tr>
      <th align="center">first-child<br>li:first-child</th>
      <th align="center">last-child<br>li:last-child</th>
      <th align="center">second-child<br>li:nth-child(2)</th>
      <th align="center">sixth-child<br>li:nth-child(6)</th>
    </tr>
    <tr>
      <td align="center"><b>*first</b></td>
      <td align="center">first</td>
      <td align="center">first</td>
      <td align="center">first</td>
    </tr>
    <tr>
      <td align="center">second</td>
      <td align="center">second</td>
      <td align="center"><b>*second</b></td>
      <td align="center">second</td>
    </tr>
    <tr>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center">third</td>
    </tr>
    <tr>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
    </tr>
    <tr>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
    </tr>
    <tr>
      <td align="center">sixth</td>
      <td align="center"><b>*sixth</b></td>
      <td align="center">sixth</td>
      <td align="center"><b>*sixth</b></td>
    </tr>    
  </tbody>
</table>
