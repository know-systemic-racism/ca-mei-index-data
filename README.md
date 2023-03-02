# mei
This repository holds data in development related to military equipment owned by California law enforcement agencies. The data is made available in this repository in two tables as comma separated (csv) format.

## Data Codebook
|Column Heading | Description |
|---------------| ------------|
| *Listed name* | The product as listed in MEI (military equipment inventory). Capitalization as written in the inventory. |
| *Standardized name* | These names may be standardized based on website description. |
| *Description* | This is our own description or whatever else describes the item in the inventory - particularly where we don't know the category. |
| *Category* | As listed in the AB481 policy as required categories of equipment to inventory. |
| *Manufacturer* | The person or company that makes the product. |
| *Manufacturer* | URL	The main (start) page for the company website. |
| *Supplier Name* | Vendor - The person or company from whom the product is purchased. |
| *Item page URL* | Link to the page that lists the item and details. |
| *Link to image* | Direct link to an image of the item itself.|
| *Cost* | This is the item cost as calculated not from the vendor but based on the MEI. |
| *Life Span (years)*| This is taken from the MEI. (May include a range)|

You will also find a Palladio save file (json) which is to be used to visualize the data with the open source browser based platform, [Palladio](https://hdlab.stanford.edu/palladio/). Open the Palladio app, choose "Load an existing project" and then "Load a remote Palladio file." Copy the link below and paste it into the "Load a remote Palladio file" field.

[/Palladio_MEI_20230124.json](https://raw.githubusercontent.com/know-systemic-racism/mei/main/Palladio_MEI_20230124.json)

