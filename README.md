# FamilySearch Web Search Endpoints - Postman collection

The JSON endpoints that the FamilySearch website itself calls: Full-Text search, historical record search and personas, Family Tree reads, Catalog search, and record images. Companion to [FamilySearch-API-Postman](https://github.com/mikeyeves/FamilySearch-API-Postman), which covers the documented developer API.

## Import
In Postman: **Import > Link** and paste
`https://raw.githubusercontent.com/mikeyeves/FamilySearch-Web-Search-Postman/main/FamilySearch_Web_Search_Endpoints.postman_collection.json`

## Requests
| Folder | Requests |
|---|---|
| Full-Text | search by text and place |
| Historical records | personas search; persona detail |
| Family Tree | tree search; person; families; sources |
| Catalog | search by place and keyword |
| Images | dist.jpg; image-data; image parents |

## Notes
- Sign in at familysearch.org, copy the `fssessionid` cookie value into the `fs_session` variable. Sessions expire (401 = sign in again).
- These are undocumented website endpoints and may change. Read only; keep request rates low. FamilySearch blocks bulk image-listing (`/children`).
- Collection ids and example values come from the Holder-Stewart research (Jackson Co., AL).

Built for family-history research (Genealogy-Vault), November 2026. Status lines say what was live-tested.

## Licence
Collection: CC0. The data and images belong to the source institutions; follow their terms of use.
