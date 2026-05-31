<h1 align="center">Nova Med Solutions Performance Report</h1>

<table align="center">
  <tr>
    <td width="1440">
      <h2 align="center">Client Background</h2>
      <strong>Nova Med Solutions</strong> is a pharmaceutical distributor serving hospitals, smaller distributors, resellers, and direct users across Europe and other global markets. The business depends on reliable medicine supply, strong customer relationships, disciplined pricing, and clear visibility into product demand.
      <br><br>
      The company has collected sales and customer data covering revenue, profit, medication performance, quantity sold, customer segment, buyer type, demographics, and geography. This analysis turns that operational data into a stakeholder-ready view of where the company is growing, where margin pressure exists, and which customer and market segments deserve more commercial focus.
      <br><br>
      Reporting for commercial and operations stakeholders, this project focuses on improving revenue visibility, product profitability, reseller retention, customer engagement, and market expansion decisions.
      <h3>Northstar Metrics</h3>
      <ul>
        <li><strong>Revenue and profit trends</strong> - Tracking monthly performance, demand peaks, weak periods, and the relationship between revenue and profit.</li>
        <li><strong>Product performance</strong> - Identifying which medications drive revenue, which sell in volume but underperform financially, and where pricing review is needed.</li>
        <li><strong>Sales efficiency</strong> - Comparing product profit margin and cost-to-revenue conversion.</li>
        <li><strong>Customer demographics</strong> - Understanding revenue contribution by gender, age group, segment, and buyer type.</li>
        <li><strong>Geographic performance</strong> - Comparing country-level sales to identify strong markets and underdeveloped opportunities.</li>
      </ul>
    </td>
  </tr>
</table>

<h2 align="center">Business Problems and Objectives</h2>

<table align="center">
  <tr>
    <td width="720" valign="top">
      <h3>Business Problem</h3>
      Nova Med Solutions has a broad customer base and product portfolio, but its sales data is underused. This limits the company's ability to explain monthly revenue movement, separate high-demand products from high-profit products, and identify which customer channels deserve the most protection.
      <br><br>
      The core risk is that strong headline sales may hide margin leakage, reseller concentration risk, and missed opportunities in lower-performing countries or customer segments.
    </td>
    <td width="720" valign="top">
      <h3>Project Objectives</h3>
      <ul>
        <li>Identify customer segments and buyer types driving the largest revenue share.</li>
        <li>Compare revenue, quantity sold, and profit margin across medications.</li>
        <li>Detect seasonal sales patterns that can improve forecasting.</li>
        <li>Understand demographic and geographic performance differences.</li>
        <li>Build an interactive Power BI dashboard for stakeholder decision-making.</li>
      </ul>
    </td>
  </tr>
</table>

<h1 align="center">Executive Summary</h1>

<h3 align="center">Revenue and Profit Trend</h3>

<div align="center">
  <img width="900" alt="Revenue and profit trend" src="reports/figures/revenue-profit-trend.png">
</div>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Chart Shows</h3>
      <ul>
        <li>Revenue and profit move closely together, which suggests profit is strongly tied to sales volume.</li>
        <li>The year is not evenly paced. January, July, and September show stronger performance, while February drops sharply.</li>
        <li>The gap between revenue and profit appears consistent, meaning cost control is relatively stable at the total-business level.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Stakeholder Interpretation</h3>
      <ul>
        <li>Nova Med Solutions does not appear to have a major company-wide cost-control crisis, but it does have a demand consistency challenge.</li>
        <li>The February dip should be investigated because it may reflect weak post-peak demand, inventory availability, seasonality, or campaign timing.</li>
        <li>Planning should focus on smoothing low months while preparing inventory and commercial activity around proven peak periods.</li>
      </ul>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="960">
      <h3>Executive Takeaway</h3>
      The business is profitable when demand is strong, but revenue momentum is uneven. The immediate opportunity is to use historical sales peaks to improve forecasting, campaign timing, and stock planning, while investigating why February underperforms so sharply. This gives stakeholders a clearer path: preserve the current cost discipline, then improve the predictability of demand.
    </td>
  </tr>
</table>

<h2 align="center">Dataset Structure and Analysis Process</h2>

<table align="center">
  <tr>
    <td width="960">
      The available project information describes a Power BI-led analysis using sales and customer data. The dataset includes revenue, profit, medication performance, quantity sold, customer demographics, buyer type, customer segment, and country-level sales performance.
      <br><br>
      The workflow followed a standard analytics process: data collection, cleaning, ETL, Power BI modelling, DAX/KPI creation, dashboard design, and insight reporting.
    </td>
  </tr>
</table>

<div align="center">
  <img width="900" alt="Nova Med customer dashboard" src="reports/figures/novamed-customer-dashboard.png">
</div>

<table align="center">
  <tr>
    <td width="960">
      <h3>Dashboard Role</h3>
      The dashboard acts as the stakeholder control layer for the analysis. It connects commercial metrics to product, customer, and geography views so decision-makers can move from headline revenue to the underlying drivers of performance.
    </td>
  </tr>
</table>

<h1 align="center">Insights Deep-Dive</h1>

<h1 align="center">Product Performance</h1>

<table align="center">
  <tr align="center">
    <td width="480" valign="top">
      <h3>Top 5 Drugs by Revenue</h3>
      <img width="420" alt="Top 5 drugs by revenue" src="reports/figures/top-5-drugs.png">
    </td>
    <td width="480" valign="top">
      <h3>Top 5 Revenue Contribution</h3>
      <img width="420" alt="Top 5 revenue contribution" src="reports/figures/top-5-revenue-contribution.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Charts Show</h3>
      <ul>
        <li>Doxycycline, Ergocalciferol, and Lisinopril form the strongest revenue base.</li>
        <li>Clonazepam and Ezetimibe follow closely, creating a balanced top-five portfolio.</li>
        <li>No single product appears to dominate the entire top group, which reduces overdependence on one medication.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Business Insight</h3>
      <ul>
        <li>The top portfolio is commercially healthy because revenue is distributed across multiple strong products.</li>
        <li>This gives Nova Med Solutions flexibility: the business can defend several high-value products rather than relying on one flagship medication.</li>
        <li>The next step is to compare these revenue leaders against margin and volume to avoid over-prioritizing products that sell well but convert profit less efficiently.</li>
      </ul>
    </td>
  </tr>
</table>

<table align="center">
  <tr align="center">
    <td width="480" valign="top">
      <h3>Bottom 5 Drugs by Revenue</h3>
      <img width="420" alt="Bottom 5 drugs by revenue" src="reports/figures/bottom-5-drugs.png">
    </td>
    <td width="480" valign="top">
      <h3>Top and Bottom Drugs by Quantity Sold</h3>
      <img width="460" alt="Top and bottom drugs by quantity sold" src="reports/figures/top-and-bottom-drugs-quantity.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Charts Show</h3>
      <ul>
        <li>Hydrochlorothiazide, Fluticasone, Amoxicillin, Montelukast, and Warfarin sit at the lower end of revenue performance.</li>
        <li>However, Hydrochlorothiazide, Montelukast, and Amoxicillin show stronger unit demand than their revenue ranking suggests.</li>
        <li>Doxycycline leads revenue but does not lead quantity sold, which points to a pricing, margin, or product-mix difference.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Business Insight</h3>
      <ul>
        <li>Low revenue does not always mean weak demand. Some products may sell in high volume but fail to convert demand into enough revenue.</li>
        <li>Hydrochlorothiazide, Montelukast, and Amoxicillin should be reviewed for pricing, discounting, package size, procurement cost, or channel mix.</li>
        <li>The commercial team should separate "high-demand products" from "high-revenue products" so pricing decisions are based on margin opportunity, not only sales volume.</li>
      </ul>
    </td>
  </tr>
</table>

<h1 align="center">Profit Margin and Sales Efficiency</h1>

<div align="center">
  <img width="900" alt="Profit and margin analysis" src="reports/figures/profit-and-margin.png">
</div>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Chart Shows</h3>
      <ul>
        <li>Aspirin and Omeprazole show the strongest margin efficiency, with profit margins close to 0.98.</li>
        <li>Escitalopram also performs strongly from a profitability standpoint.</li>
        <li>Doxycycline is commercially important, but its margin efficiency is weaker than the most efficient products.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Business Insight</h3>
      <ul>
        <li>Nova Med Solutions has two different product stories: products that drive revenue and products that convert sales into profit most efficiently.</li>
        <li>Aspirin should be treated as a margin-protection and growth candidate because each additional sale appears to convert strongly into profit.</li>
        <li>Doxycycline should remain a priority, but stakeholders should review supplier costs, discounts, and operating costs to improve its profit conversion.</li>
      </ul>
    </td>
  </tr>
</table>

<table align="center">
  <tr align="center">
    <td width="480" valign="top">
      <h3>Doxycycline Revenue and Profit</h3>
      <img width="460" alt="Doxycycline revenue and profit trend" src="reports/figures/doxycycline-revenue-profit.png">
    </td>
    <td width="480" valign="top">
      <h3>Aspirin Revenue and Profit</h3>
      <img width="460" alt="Aspirin revenue and profit trend" src="reports/figures/aspirin-revenue-profit.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>Doxycycline Story</h3>
      <ul>
        <li>Doxycycline has clear sales spikes in early-year, mid-year, and late-year periods.</li>
        <li>Revenue and profit move together, but the visible gap suggests costs are taking a meaningful share of revenue.</li>
        <li>The product is important for sales growth, but margin improvement would make its growth more valuable.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Aspirin Story</h3>
      <ul>
        <li>Aspirin shows tighter alignment between revenue and profit.</li>
        <li>This indicates stable cost structure, predictable demand, and stronger profit conversion.</li>
        <li>Stakeholders should consider whether Aspirin can be scaled through reseller incentives or targeted demand generation.</li>
      </ul>
    </td>
  </tr>
</table>

<h1 align="center">Customer Demographics and Segments</h1>

<table align="center">
  <tr align="center">
    <td width="480" valign="top">
      <h3>Revenue by Gender</h3>
      <img width="520" alt="Revenue by gender" src="reports/figures/revenue-by-gender.png">
    </td>
    <td width="480" valign="top">
      <h3>Revenue by Customer Segment</h3>
      <img width="420" alt="Revenue by segment" src="reports/figures/revenue-by-segment.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Charts Show</h3>
      <ul>
        <li>Male customers contribute the highest revenue, with a notable peak around $3.3M in May.</li>
        <li>Female customers and the Other category follow similar patterns but at lower levels.</li>
        <li>Preferred customers contribute 36% of revenue, new customers 34%, and frequent buyers 30%.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Business Insight</h3>
      <ul>
        <li>The customer base is not evenly monetized. Male customers are currently the strongest demographic revenue engine.</li>
        <li>New customers nearly match preferred customers, which suggests acquisition is working, but retention and repeat purchase may need more focus.</li>
        <li>The lower frequent-buyer share is a warning sign: Nova Med Solutions may be winning customers but not fully converting them into higher-value repeat customers.</li>
      </ul>
    </td>
  </tr>
</table>

<table align="center">
  <tr align="center">
    <td width="320" valign="top">
      <h3>Segment by Gender</h3>
      <img width="300" alt="Revenue segment by gender" src="reports/figures/revenue-segment-by-gender.png">
    </td>
    <td width="320" valign="top">
      <h3>Revenue by Buyer Type</h3>
      <img width="300" alt="Revenue by buyer type" src="reports/figures/revenue-by-buyer-type.png">
    </td>
    <td width="320" valign="top">
      <h3>Revenue by Age</h3>
      <img width="300" alt="Revenue by age" src="reports/figures/revenue-by-age.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="320" valign="top">
      <h3>Segment View</h3>
      <ul>
        <li>Male customers dominate across multiple customer segments.</li>
        <li>The Other gender category appears weaker among frequent buyers.</li>
        <li>This points to a targeted engagement opportunity.</li>
      </ul>
    </td>
    <td width="320" valign="top">
      <h3>Buyer-Type View</h3>
      <ul>
        <li>Resellers generate 88% of total revenue.</li>
        <li>Direct users contribute a much smaller share.</li>
        <li>This makes reseller retention one of the highest-priority commercial risks.</li>
      </ul>
    </td>
    <td width="320" valign="top">
      <h3>Age View</h3>
      <ul>
        <li>Revenue is relatively competitive across age groups.</li>
        <li>The business is not overly dependent on one age bracket.</li>
        <li>This supports broad market positioning rather than narrow age-based targeting.</li>
      </ul>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="960">
      <h3>Customer Story</h3>
      Nova Med Solutions is highly dependent on reseller channels and has strong revenue from male customers, but the customer segment mix shows room to improve repeat-purchase value. The company should protect reseller relationships first, then use targeted campaigns to increase frequent-buyer contribution and unlock growth from under-penetrated demographic groups.
    </td>
  </tr>
</table>

<h1 align="center">Geographic Results</h1>

<table align="center">
  <tr align="center">
    <td width="480" valign="top">
      <h3>Revenue by Country</h3>
      <img width="450" alt="Revenue by country" src="reports/figures/revenue-by-country.png">
    </td>
    <td width="480" valign="top">
      <h3>Country Drilldown by Segment</h3>
      <img width="420" alt="Revenue drilldown by country and segment" src="reports/figures/revenue-country-segment-drilldown.png">
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>What the Charts Show</h3>
      <ul>
        <li>Canada is the strongest market, generating approximately $32M in revenue.</li>
        <li>Australia contributes approximately $15M, making it a strong secondary market.</li>
        <li>The United States generates approximately $6M, making it the lowest-performing market in the view.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Business Insight</h3>
      <ul>
        <li>The geographic revenue base is uneven. Canada is the clear anchor market, while the United States appears underdeveloped.</li>
        <li>The country drilldown suggests Preferred Customers are important to high-performing market revenue.</li>
        <li>Stakeholders should investigate whether lower-performing countries have weaker reseller coverage, pricing barriers, lower availability, or less effective customer acquisition.</li>
      </ul>
    </td>
  </tr>
</table>

<h1 align="center">Recommendations</h1>

<table align="center">
  <tr>
    <td width="960">
      <h3>Based on the uncovered insights, these are the main actions Nova Med Solutions can take from the analysis.</h3>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td width="480" valign="top">
      <h3>Sales and Forecasting</h3>
      <ul>
        <li>Investigate the February revenue dip and identify whether it is caused by demand seasonality, stock availability, campaign timing, or channel performance.</li>
        <li>Use January, July, and September as planning anchors for inventory, reseller engagement, and promotional campaigns.</li>
        <li>Track monthly revenue and profit variance so commercial teams can respond earlier to demand changes.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Product Strategy</h3>
      <ul>
        <li>Review pricing and procurement costs for Hydrochlorothiazide, Montelukast, and Amoxicillin because they show stronger unit demand than revenue contribution.</li>
        <li>Protect Lisinopril and Doxycycline as core revenue products, but review Doxycycline margin efficiency.</li>
        <li>Scale Aspirin through reseller incentives or targeted demand generation because it appears highly efficient from a margin perspective.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="480" valign="top">
      <h3>Customer and Channel Strategy</h3>
      <ul>
        <li>Prioritize reseller retention because resellers generate 88% of total revenue.</li>
        <li>Develop retention campaigns that move new customers into frequent-buyer behavior.</li>
        <li>Strengthen engagement with high-value male customers while testing growth opportunities in under-penetrated demographic groups.</li>
      </ul>
    </td>
    <td width="480" valign="top">
      <h3>Geographic Strategy</h3>
      <ul>
        <li>Protect Canada as the highest-value market and document which commercial practices are driving its performance.</li>
        <li>Investigate the United States underperformance by reviewing reseller coverage, pricing, availability, and acquisition channels.</li>
        <li>Build localized growth plans for lower-contributing countries instead of applying one global sales approach.</li>
      </ul>
    </td>
  </tr>
</table>

<h2 align="center">Project Links</h2>

<table align="center">
  <tr>
    <td width="960">
      <ul>
        <li>Portfolio case study: <a href="https://emmakola.github.io/project.html">Nova Med Solutions</a></li>
        <li>GitHub profile: <a href="https://github.com/EmmaKola">EmmaKola</a></li>
      </ul>
    </td>
  </tr>
</table>
