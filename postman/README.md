# Postman Import Files (SimBiz 6 API V3)

## Files
- `SimBiz6-API-V3.postman_collection.json`
- `SimBiz6-API-V3.postman_environment.json`

## Import Steps
1. Open Postman.
2. Click **Import**.
3. Import both JSON files above.
4. Select environment **SimBiz6 API V3 - Default**.
5. Set `secret` value.
6. Run **Auth and System > Get Token**.
7. Continue with module endpoints.

## Notes
- Collection auto-adds `x-uid` from `{{uid}}` in pre-request script.
- `Get Token` test script stores token to environment variable `token` automatically.
- All list/document requests include sample `updated_from` and `updated_to` filters.
- Collection only includes endpoints shown in current API Usage wiki scope (excluded/hidden wiki endpoints are not included).
