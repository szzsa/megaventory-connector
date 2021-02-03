# Megaventory Connector for Google Data Studio

## [Home](https://szzsa.github.io/megaventory-connector)
## [Support](https://szzsa.github.io/megaventory-connector/support)
______________________________________
# Home
This is a Megaventory community connector for Google Data Studio.
## API
### Documentation
For more details about Megaventory API please go to [api.megaventory.com](https://api.megaventory.com)
### Filters
Only the following document types are retrieved:
<table>
  <thead>
    <th>Id</th>
    <th>Abbreviation</th>
    <th>Description</th>
  </thead>
  <tr>
    <td>2</td>
    <td>GOSI</td>
    <td>Goods Out and Sales Invoice</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SO</td>
    <td>Sales Order</td>
  </tr>
</table>

## Data

### Dimensions
<table>
  <thead>
    <th>Id</th>
    <th>Name</th>
    <th>Type</th>
  </thead>
  <tr>
    <td>DocumentNo</td>
    <td>Number</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentReferenceNo</td>
    <td>Reference</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentDate</td>
    <td>Date</td>
    <td>Date</td>
  </tr>
  <tr>
    <td>DocumentContactPerson</td>
    <td>End User</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentTags</td>
    <td>Tags</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentRowProductSKU</td>
    <td>SKU</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentRowProductDescription</td>
    <td>Product</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>DocumentRowUnitPriceWithoutTaxOrDiscount</td>
    <td>Unit Price</td>
    <td>Currency (USD)</td>
  </tr>
  <tr>
    <td>DocumentRowQuantity</td>
    <td>Quantity</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>DocumentRowTotalAmount</td>
    <td>Amount</td>
    <td>Currency (USD)</td>
  </tr>
</table>
