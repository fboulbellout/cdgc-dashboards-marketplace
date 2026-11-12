# Dashboard file format (`cdgc-dashboard-export/v1`)

Each file under `dashboards/` is a portable, org-independent dashboard definition with a `cdgc_release` stamp (the export/import format is release-specific) and a `marketplace` tag block (`use_case`, `industry`, `source_systems`, `requirements`, `locale`).

- **dashboard**: `core.name`, `core.description`, `autoShareIncludedSavedSearches`.
- **widgets[]**: `order`, `widgetType`/`fullType`, `attributes` (`com.infa.application.dashboard.*`). Types: NoticeBoard, Search, DataQuality, Tickets, ClaireActivity, Jobs.
- **layout[]**: `{order,h,w,x,y}` on a 12-col grid, keyed by widget `order` (not ids) so it rebuilds on import against freshly-minted ids.
- **saved_searches{}**: reusable searches referenced by a widget's `savedSearchId`; the importer recreates them (or inlines their query) in the target org.

Deploy with the `cdgc-dashboard-export-import` skill. Masked values appear as `[EMAIL]`, `[PHONE]`, `[IP]`, `[NAME]`, `[CDGC-LINK]`.
