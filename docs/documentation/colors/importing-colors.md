---
icon: lucide/cloud-download
description: Guide on how to import colors into your Color-Chan color list
---

!!! info "Note"

    Importing colors will not overwrite your existing color list. The imported colors will be added to the end of your current color list.


Color-Chan's import feature allows you to easily transfer color lists between different servers. This is particularly useful for server administrators who manage multiple servers and want to maintain a consistent color scheme across them, or for setting up a new server with the same colors as an existing server.


## Importing colors

!!! info "Please be patient"

    Depending on the size of the color list being imported, the import process may take some time to complete. Please wait for the confirmation message before continuing.

You can import colors into your server using the `/import color list id:<export_id>` command. Replace `<export_id>` with the ID of the color list you want to import from. See the exporting section below for more information on how to get an export ID.


## Exporting colors

You can get your server's export ID using the `/export color list` command. This command will generate a unique ID that can be used to import your color list into another server.
