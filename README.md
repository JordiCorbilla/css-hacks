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
      <th align="center">last three<br>li:nth-child(n+2)</th>
      <th align="center">first three<br>li:nth-child(-n+3)</th>      
    </tr>
    <tr>
      <td align="center"><b>*first</b></td>
      <td align="center">first</td>
      <td align="center">first</td>
      <td align="center">first</td>
      <td align="center">first</td>
      <td align="center"><b>*first</b></td>
    </tr>
    <tr>
      <td align="center">second</td>
      <td align="center">second</td>
      <td align="center"><b>*second</b></td>
      <td align="center">second</td>
      <td align="center">second</td>
      <td align="center"><b>*second</b></td>
    </tr>
    <tr>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center">third</td>
      <td align="center"><b>*third</b></td>
    </tr>
    <tr>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
      <td align="center">fourth</td>
      <td align="center"><b>*fourth</b></td>
      <td align="center">fourth</td>
    </tr>
    <tr>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
      <td align="center">fifth</td>
      <td align="center"><b>*fifth</b></td>
      <td align="center">fifth</td>
    </tr>
    <tr>
      <td align="center">sixth</td>
      <td align="center"><b>*sixth</b></td>
      <td align="center">sixth</td>
      <td align="center"><b>*sixth</b></td>
      <td align="center"><b>*sixth</b></td>
      <td align="center">sixth</td>
    </tr>    
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <th align="center">odd selection<br>li:nth-child(odd)</th>
      <th align="center">even selection<br>li:nth-child(even)</th>
      <th align="center">second-child<br>li:nth-child(2)</th>
      <th align="center">sixth-child<br>li:nth-child(6)</th>
      <th align="center">last three<br>li:nth-child(n+2)</th>
      <th align="center">first three<br>li:nth-child(-n+3)</th>      
    </tr>
    <tr>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>item1</li>
          <li>item2</li>
          <li>item3</li>
          <li>item4</li>
          <li>item5</li>
          <li>item6</li>
        </ul>
      </td>      
    </tr>
  </tbody>
</table>
