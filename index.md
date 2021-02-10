# Megaventory Connector for Google Data Studio

## [Home](https://szzsa.github.io/megaventory-connector)
## [Support](https://szzsa.github.io/megaventory-connector/support)
______________________________________
# Home
This is a Megaventory community connector for Google Data Studio.<br>
Access the following link to use the connector:<br>
[GDS Megaventory Connector](https://datastudio.google.com/datasources/create?connectorId=AKfycbzZsRGJjR_8HaHN8lrOevw4vc_iu6Xpd0cWkrx9LWA)
## API
### Documentation
For more details about Megaventory API please go to <br>
[api.megaventory.com](https://api.megaventory.com)
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
    <th>Name</th>
    <th>Description</th>
    <th>Type</th>
  </thead>
  <tr>
    <td>Number</td>
    <td>Document Number</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>PO Number</td>
    <td>PO Number (Document Reference Number)</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Date</td>
    <td>Document Date</td>
    <td>Date</td>
  </tr>
  <tr>
    <td>End User</td>
    <td>End User (Contact Person)</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Sales Rep</td>
    <td>Sales Rep (Tags)</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>SKU</td>
    <td>Product SKU</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Product</td>
    <td>Product Description</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Unit Price</td>
    <td>Product Price per Unit</td>
    <td>Currency (USD)</td>
  </tr>
  <tr>
    <td>Quantity</td>
    <td>Product Quantity per Document Row</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>Amount</td>
    <td>Total Amount per Document Row</td>
    <td>Currency (USD)</td>
  </tr>
  <tr>
    <td>Ship-By Date</td>
    <td>Ship-By Date</td>
    <td>Date</td>
  </tr>
  <tr>
    <td>On Hold</td>
    <td>Flag (boolean) indicating On Hold state</td>
    <td>Boolean</td>
  </tr>
  <tr>
    <td>Ordered</td>
    <td>Flag (boolean) indicating Ordered state</td>
    <td>Boolean</td>
  </tr>
  <tr>
    <td>Client ID</td>
    <td>Document Supplier Client ID</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Client Name</td>
    <td>Document Supplier Client Name</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Inventory Location ID</td>
    <td>Document Inventory Location ID</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Ordered From</td>
    <td>Document Inventory Location Name</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Status</td>
    <td>Document Status</td>
    <td>Text</td>
  </tr>
</table>
