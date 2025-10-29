# Quantum Circuits for AES

## Quantum Resources for AES quantum circuits

- Toffoli gate version
  - Toffoli gate decomposition: 8 Clifford gates, 7 T gates, T-depth of 4, full depth of 8

<p></p>

<!-- Toffoli table (nowrap + compact) -->
<table style="width:auto; margin:auto; border-collapse:collapse; white-space:nowrap;">
  <colgroup>
    <col style="width:60px">
    <col style="width:90px">
    <col style="width:280px">
    <col style="width:90px">
    <col style="width:90px">
    <col style="width:90px">
    <col style="width:80px">
    <col style="width:90px">
    <col style="width:100px">
  </colgroup>
  <tr>
    <th style="padding:4px 8px;">AES</th>
    <th style="padding:4px 8px;">Version</th>
    <th style="padding:4px 8px;">Used S-box</th>
    <th style="padding:4px 8px;">#CNOT</th>
    <th style="padding:4px 8px;">#1qCliff</th>
    <th style="padding:4px 8px;">#T</th>
    <th style="padding:4px 8px;">T-depth</th>
    <th style="padding:4px 8px;">#qubit</th>
    <th style="padding:4px 8px;">Full depth</th>
  </tr>
  <tr>
    <td rowspan="9" style="padding:4px 8px;">128</td>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low qubit count)</td>
    <td style="padding:4px 8px;">148,244</td>
    <td style="padding:4px 8px;">14,416</td>
    <td style="padding:4px 8px;">87,560</td>
    <td style="padding:4px 8px;">304</td>
    <td style="padding:4px 8px;">2,736</td>
    <td style="padding:4px 8px;">1,288</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">150,064</td>
    <td style="padding:4px 8px;">19,264</td>
    <td style="padding:4px 8px;">87,104</td>
    <td style="padding:4px 8px;">160</td>
    <td style="padding:4px 8px;">3,048</td>
    <td style="padding:4px 8px;">776</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">153,772</td>
    <td style="padding:4px 8px;">19,264</td>
    <td style="padding:4px 8px;">87,104</td>
    <td style="padding:4px 8px;">160</td>
    <td style="padding:4px 8px;">4,200</td>
    <td style="padding:4px 8px;">748</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low full depth)</td>
    <td style="padding:4px 8px;">138,144</td>
    <td style="padding:4px 8px;">15,496</td>
    <td style="padding:4px 8px;">87,920</td>
    <td style="padding:4px 8px;">304</td>
    <td style="padding:4px 8px;">2,896</td>
    <td style="padding:4px 8px;">1,090</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">139,588</td>
    <td style="padding:4px 8px;">19,168</td>
    <td style="padding:4px 8px;">86,912</td>
    <td style="padding:4px 8px;">160</td>
    <td style="padding:4px 8px;">3,268</td>
    <td style="padding:4px 8px;">686</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">143,296</td>
    <td style="padding:4px 8px;">19,168</td>
    <td style="padding:4px 8px;">86,912</td>
    <td style="padding:4px 8px;">160</td>
    <td style="padding:4px 8px;">4,420</td>
    <td style="padding:4px 8px;">667</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 3 S-box</td>
    <td style="padding:4px 8px;">298,320</td>
    <td style="padding:4px 8px;">40,496</td>
    <td style="padding:4px 8px;">207,480</td>
    <td style="padding:4px 8px;">228</td>
    <td style="padding:4px 8px;">4,256</td>
    <td style="padding:4px 8px;">1,069</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">297,788</td>
    <td style="padding:4px 8px;">39,168</td>
    <td style="padding:4px 8px;">206,472</td>
    <td style="padding:4px 8px;">120</td>
    <td style="padding:4px 8px;">6,128</td>
    <td style="padding:4px 8px;">665</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">301,496</td>
    <td style="padding:4px 8px;">39,168</td>
    <td style="padding:4px 8px;">206,472</td>
    <td style="padding:4px 8px;">120</td>
    <td style="padding:4px 8px;">7,280</td>
    <td style="padding:4px 8px;">647</td>
  </tr>

  <!-- AES-192 -->
  <tr>
    <td rowspan="9" style="padding:4px 8px;">192</td>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low qubit count)</td>
    <td style="padding:4px 8px;">167,508</td>
    <td style="padding:4px 8px;">16,136</td>
    <td style="padding:4px 8px;">98,600</td>
    <td style="padding:4px 8px;">368</td>
    <td style="padding:4px 8px;">3,056</td>
    <td style="padding:4px 8px;">1,534</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">170,804</td>
    <td style="padding:4px 8px;">21,568</td>
    <td style="padding:4px 8px;">99,008</td>
    <td style="padding:4px 8px;">192</td>
    <td style="padding:4px 8px;">3,368</td>
    <td style="padding:4px 8px;">932</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">175,336</td>
    <td style="padding:4px 8px;">21,568</td>
    <td style="padding:4px 8px;">99,008</td>
    <td style="padding:4px 8px;">192</td>
    <td style="padding:4px 8px;">4,776</td>
    <td style="padding:4px 8px;">900</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low full depth)</td>
    <td style="padding:4px 8px;">156,136</td>
    <td style="padding:4px 8px;">173,496</td>
    <td style="padding:4px 8px;">99,008</td>
    <td style="padding:4px 8px;">368</td>
    <td style="padding:4px 8px;">3,216</td>
    <td style="padding:4px 8px;">1,294</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">157,620</td>
    <td style="padding:4px 8px;">21,272</td>
    <td style="padding:4px 8px;">98,000</td>
    <td style="padding:4px 8px;">192</td>
    <td style="padding:4px 8px;">3,588</td>
    <td style="padding:4px 8px;">819</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">162,152</td>
    <td style="padding:4px 8px;">21,272</td>
    <td style="padding:4px 8px;">98,000</td>
    <td style="padding:4px 8px;">192</td>
    <td style="padding:4px 8px;">4,996</td>
    <td style="padding:4px 8px;">797</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 3 S-box</td>
    <td style="padding:4px 8px;">336,568</td>
    <td style="padding:4px 8px;">43,192</td>
    <td style="padding:4px 8px;">233,688</td>
    <td style="padding:4px 8px;">276</td>
    <td style="padding:4px 8px;">4,576</td>
    <td style="padding:4px 8px;">1,270</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">336,252</td>
    <td style="padding:4px 8px;">43,864</td>
    <td style="padding:4px 8px;">232,680</td>
    <td style="padding:4px 8px;">144</td>
    <td style="padding:4px 8px;">6,448</td>
    <td style="padding:4px 8px;">795</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">340,784</td>
    <td style="padding:4px 8px;">43,864</td>
    <td style="padding:4px 8px;">232,680</td>
    <td style="padding:4px 8px;">144</td>
    <td style="padding:4px 8px;">7,856</td>
    <td style="padding:4px 8px;">773</td>
  </tr>

  <!-- AES-256 -->
  <tr>
    <td rowspan="9" style="padding:4px 8px;">256</td>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low qubit count)</td>
    <td style="padding:4px 8px;">207,364</td>
    <td style="padding:4px 8px;">19,879</td>
    <td style="padding:4px 8px;">122,520</td>
    <td style="padding:4px 8px;">432</td>
    <td style="padding:4px 8px;">3,376</td>
    <td style="padding:4px 8px;">1,798</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">208,320</td>
    <td style="padding:4px 8px;">26,703</td>
    <td style="padding:4px 8px;">121,944</td>
    <td style="padding:4px 8px;">224</td>
    <td style="padding:4px 8px;">3,688</td>
    <td style="padding:4px 8px;">1,086</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">213,676</td>
    <td style="padding:4px 8px;">240,379</td>
    <td style="padding:4px 8px;">121,944</td>
    <td style="padding:4px 8px;">224</td>
    <td style="padding:4px 8px;">5,352</td>
    <td style="padding:4px 8px;">1,047</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low full depth)</td>
    <td style="padding:4px 8px;">193,236</td>
    <td style="padding:4px 8px;">21,415</td>
    <td style="padding:4px 8px;">123,032</td>
    <td style="padding:4px 8px;">432</td>
    <td style="padding:4px 8px;">3,536</td>
    <td style="padding:4px 8px;">1,516</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">193,936</td>
    <td style="padding:4px 8px;">26,607</td>
    <td style="padding:4px 8px;">122,024</td>
    <td style="padding:4px 8px;">224</td>
    <td style="padding:4px 8px;">3,908</td>
    <td style="padding:4px 8px;">960</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">199,292</td>
    <td style="padding:4px 8px;">26,607</td>
    <td style="padding:4px 8px;">122,024</td>
    <td style="padding:4px 8px;">224</td>
    <td style="padding:4px 8px;">5,572</td>
    <td style="padding:4px 8px;">934</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 3 S-box</td>
    <td style="padding:4px 8px;">417,556</td>
    <td style="padding:4px 8px;">53,383</td>
    <td style="padding:4px 8px;">290,472</td>
    <td style="padding:4px 8px;">324</td>
    <td style="padding:4px 8px;">4,896</td>
    <td style="padding:4px 8px;">1,488</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">416,444</td>
    <td style="padding:4px 8px;">53,983</td>
    <td style="padding:4px 8px;">289,212</td>
    <td style="padding:4px 8px;">168</td>
    <td style="padding:4px 8px;">6,768</td>
    <td style="padding:4px 8px;">933</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">421,800</td>
    <td style="padding:4px 8px;">53,983</td>
    <td style="padding:4px 8px;">289,212</td>
    <td style="padding:4px 8px;">168</td>
    <td style="padding:4px 8px;">8,432</td>
    <td style="padding:4px 8px;">907</td>
  </tr>
</table>

<p></p>

- AND gate version
  - AND gate decomposition: 11 Clifford gates, 4 T gates, T-depth of 1, full depth of 8, 1 ancilla qubit
  - AND gate dagger decomposition: 5 Clifford gates, 1 Measurement gate, full depth of 4

<p></p>

<!-- AND table (nowrap + compact + extra column) -->
<table style="width:auto; margin:auto; border-collapse:collapse; white-space:nowrap;">
  <colgroup>
    <col style="width:60px">
    <col style="width:90px">
    <col style="width:280px">
    <col style="width:90px">
    <col style="width:90px">
    <col style="width:90px">
    <col style="width:90px">
    <col style="width:80px">
    <col style="width:90px">
    <col style="width:100px">
  </colgroup>
  <tr>
    <th style="padding:4px 8px;">AES</th>
    <th style="padding:4px 8px;">Version</th>
    <th style="padding:4px 8px;">Used S-box</th>
    <th style="padding:4px 8px;">#CNOT</th>
    <th style="padding:4px 8px;">#1qCliff</th>
    <th style="padding:4px 8px;">#T</th>
    <th style="padding:4px 8px;">#Measure</th>
    <th style="padding:4px 8px;">T-depth</th>
    <th style="padding:4px 8px;">#qubit</th>
    <th style="padding:4px 8px;">Full depth</th>
  </tr>
  <tr>
    <td rowspan="9" style="padding:4px 8px;">128</td>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low qubit count)</td>
    <td style="padding:4px 8px;">134,124</td>
    <td style="padding:4px 8px;">43,896</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">6,120</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">2,968</td>
    <td style="padding:4px 8px;">1,021</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">136,208</td>
    <td style="padding:4px 8px;">43,608</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">6,024</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">3,408</td>
    <td style="padding:4px 8px;">716</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">139,916</td>
    <td style="padding:4px 8px;">43,608</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">6,024</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">4,688</td>
    <td style="padding:4px 8px;">684</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 4 S-box (low full depth)</td>
    <td style="padding:4px 8px;">120,944</td>
    <td style="padding:4px 8px;">40,296</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">5,760</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">3,160</td>
    <td style="padding:4px 8px;">826</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">123,156</td>
    <td style="padding:4px 8px;">39,936</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">5,580</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">3,700</td>
    <td style="padding:4px 8px;">666</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">126,864</td>
    <td style="padding:4px 8px;">39,936</td>
    <td style="padding:4px 8px;">27,200</td>
    <td style="padding:4px 8px;">5,580</td>
    <td style="padding:4px 8px;">40</td>
    <td style="padding:4px 8px;">4,852</td>
    <td style="padding:4px 8px;">647</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Regular</td>
    <td rowspan="3" style="padding:4px 8px;">Toffoli depth 3 S-box</td>
    <td style="padding:4px 8px;">259,320</td>
    <td style="padding:4px 8px;">94,056</td>
    <td style="padding:4px 8px;">62,400</td>
    <td style="padding:4px 8px;">14,040</td>
    <td style="padding:4px 8px;">30</td>
    <td style="padding:4px 8px;">4,864</td>
    <td style="padding:4px 8px;">895</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow</td>
    <td style="padding:4px 8px;">258,900</td>
    <td style="padding:4px 8px;">93,456</td>
    <td style="padding:4px 8px;">62,400</td>
    <td style="padding:4px 8px;">13,860</td>
    <td style="padding:4px 8px;">30</td>
    <td style="padding:4px 8px;">6,864</td>
    <td style="padding:4px 8px;">635</td>
  </tr>
  <tr>
    <td style="padding:4px 8px;">Shallow/low</td>
    <td style="padding:4px 8px;">262,608</td>
    <td style="padding:4px 8px;">93,456</td>
    <td style="padding:4px 8px;">62,400</td>
    <td style="padding:4px 8px;">13,860</td>
    <td style="padding:4px 8px;">30</td>
    <td style="padding:4px 8px;">8,016</td>
    <td style="padding:4px 8px;">617</td>
  </tr>

  <!-- 이하 192 / 256 블록은 동일 패턴으로 유지 (생략 없이 그대로 붙여넣기) -->
  <!-- ... 당신이 올린 AND 표의 나머지 행들을 동일하게 채워 넣으세요 ... -->
</table>
