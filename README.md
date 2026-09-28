# PWA-Tutorial

This is a tutorial of how to make PWA of a simple website.

## Windows MSIX package (PWABuilder)

In PWABuilder, open **Package for stores** and generate the **Windows** package. Enter these values from the Microsoft Partner Center Product Identity section:

| PWABuilder field | Value |
| --- | --- |
| Package ID (`Package/Identity/Name`) | `NiaziSoft.ZiarateJumalImamZamanaas` |
| Publisher ID (`Package/Identity/Publisher`) | `CN=55BE1A01-9FBC-4BA9-8CD6-50CB8B8627F` |
| Publisher display name | `NiaziSoft` |

Additional identity values shown in Partner Center:

| Field | Value |
| --- | --- |
| Package Family Name (PFN) | `NiaziSoft.ZiarateJumalImamZamanaas_1rdzjj19rcx26` |
| Package SID | `S-1-15-2-3119545799-2283126220-1154304453-3092810576-3936336974-2626159965-2481869875` |
| Store ID | `9N7NZRXWRCKH` |

PWABuilder's Windows package form requires the Package ID, Publisher ID, and Publisher display name. The PFN and SID are reference values; the Store ID identifies the Store listing.
