# Market Basket Analysis
Market basket analysis is a technique used in data mining and retail industry to identify the relationships between different products that are frequently purchased together by customers. It is highly used by retail,finance, ecommerce, in store for cross selling their product.

Because of sensitive information i have not printed datasets and result but have added visualizations part which was done using Power BI using Force Directed Graph.
For sample of data, i have added how data looked like by changing product name and company name,address.
<b>Sample Table structure</b>
<table>
  <tr>
    <th>Transacti</th>
    <th>Product</th>
    <th>Detail R</th>
    <th>Product Base Description</th>
    <th>Line Ext</th>
    <th>Line GST $</th>
    <th>Trading Name</th>
    <th>Contact Given Names</th>
    <th>Contact Surname</th>
    <th>Contact Email Address</th>
    <th>Delive</th>
  </tr>
  <tr>
    <td>2023-05-27</td>
    <td>1659</td>
    <td>1418161</td>
    <td>Product2</td>
    <td>46.45</td>
    <td>4.65</td>
    <td>Company1</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2023-05-27</td>
    <td>T25</td>
    <td>1418162</td>
    <td>Product3</td>
    <td>5.07</td>
    <td>0.51</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2023-05-27</td>
    <td>3825</td>
    <td>1418162</td>
    <td>Product4</td>
    <td>4.69</td>
    <td>0.47</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2023-05-27</td>
    <td>Y68</td>
    <td>1418163</td>
    <td>Product5</td>
    <td>304.36</td>
    <td>30.44</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2023-05-27</td>
    <td>289</td>
    <td>1418164</td>
    <td>Product6</td>
    <td>35.48</td>
    <td>3.55</td>
    <td>Company2</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>
<h2>Sample Output in table</h2>
<table>
 <tr>
   <th>Rule</th>
   <th>Antecedents</th>
   <th>Consequents</th>
   <th>Antecedent Support</th>
   <th>Consequent Support</th>
   <th>Support</th>
   <th>Confidence</th>
   <th>Lift</th>
   <th>Leverage</th>
   <th>Conviction</th>
   <th>Zhang's Metric</th>
 </tr>
 <tr>
   <td>18</td>
   <td>Product 1</td>
   <td>Product 6</td>
   <td>0.021104</td>
   <td>0.073574</td>
   <td>0.005048</td>
   <td>0.239216</td>
   <td>3.251342</td>
   <td>0.003496</td>
   <td>1.217724</td>
   <td>0.707363</td>
 </tr>
 <tr>
   <td>19</td>
   <td>Product 5</td>
   <td>Product 8</td>
   <td>0.073574</td>
   <td>0.021104</td>
   <td>0.005048</td>
   <td>0.068616</td>
   <td>3.251342</td>
   <td>0.003496</td>
   <td>1.051013</td>
   <td>0.747426</td>
 </tr>
</table>
<p><b>Interpretation</b>We can interpret that whenever people buy Product 1 there is 23% chances of buying product 5.Similarly there is 0.5% of chances of having this transactions overall.</p>
