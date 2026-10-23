# Superstore Europe — Sales & Profit Analysis with Tableau

A Tableau dashboard and visual story exploring sales, profit and product performance in the Superstore Europe dataset.

Developed as a project for **Tecniche di Data Visualization**, part of the **ProfessionAI Master in Data Analytics**.

**[Explore the interactive story on Tableau Public](https://public.tableau.com/app/profile/claudio.lombardi/viz/Progetto_17818648724080/Storia1)**

The workbook's dashboard and narrative are in Italian. This README provides an English overview.

## Project objective

The project uses visual analysis to identify differences in product performance and develop hypotheses for marketing budget allocation and catalogue review.

Key questions include:

- How do sales evolve over time?
- How do sales and profit vary across products, categories and countries?
- Which products combine relatively high sales with low profit?
- Which products warrant further investigation for growth, cost optimisation or catalogue review?

## Dashboard and visual story

The **Superstore Europa — Performance Overview** dashboard brings together:

- KPI cards for total sales, total profit, total quantity and distinct orders.
- Sales over time and sales by category.
- Profit by country, including a geographical view.
- Quantity by delivery mode.
- Filters for product, delivery mode, order date and country/region.

The workbook also contains product-level sales-versus-profit scatter plots. A seven-point Tableau story moves from a performance overview to growth opportunities, products requiring optimisation, catalogue review and concluding marketing recommendations.

## Analytical approach

Products are explored using their sales and profit totals, with reference lines and selected examples supporting the narrative. The story groups the discussion around strong performers, potential growth opportunities, products to optimise and products to review for possible removal.

These groups support exploratory decision-making. Recommendations are hypotheses to investigate, rather than measured outcomes of a marketing intervention.

## Interpretation and limitations

- **Sales** represents sales value, while **Quantity** measures units. They should not be treated as interchangeable measures of volume.
- **Profit** is an absolute amount. The sales-versus-profit analysis does not directly measure profit margin, which would require a ratio such as profit divided by sales.
- Historical sales and profit alone do not establish marketing return on investment or prove that additional advertising will increase profitability.
- Budget or catalogue decisions would require further information, including campaign costs, customer demand, product lifecycle and operational constraints.

## Repository contents

| File | Description |
|---|---|
| [Progetto.twb](Progetto.twb) | Tableau workbook containing the worksheets, dashboard and story. |
| [superstore.xlsx](superstore.xlsx) | Excel data source used by the workbook, through the `Orders` worksheet. |
| [README.md](README.md) | Project overview and instructions. |

The `.twb` stores the workbook definition; the Excel data is supplied separately. The workbook connection uses the relative filename `superstore.xlsx`.

## How to explore

### In a browser

Open the [Tableau Public story](https://public.tableau.com/app/profile/claudio.lombardi/viz/Progetto_17818648724080/Storia1) to explore the published interactive version.

### Locally

1. Download the repository using **Code → Download ZIP**, then extract it.
2. Keep `Progetto.twb` and `superstore.xlsx` in the same folder.
3. Open `Progetto.twb` in Tableau Desktop or Tableau Public desktop.
4. If Tableau requests the data source, select the included `superstore.xlsx` file and its `Orders` worksheet.

The workbook was saved with Tableau 2026.1.2. An older Tableau release may require a compatible export.

## Tools and skills

Tableau Public · Excel data connection · KPI reporting · Time-series visualisation · Geographical analysis · Scatter plots · Dashboard filters · Visual storytelling

## Author

[Claudio Lombardi](https://github.com/PsyClaudio) · [Tableau Public profile](https://public.tableau.com/app/profile/claudio.lombardi)
