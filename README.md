# Google Calendar API

The Google Calendar API provides RESTful access to Google Calendar data, enabling applications to create, view, and manage calendar events, access control lists, and user settings. It supports creating and managing multiple calendars, querying free/busy information, setting up push notifications for changes, and integrating calendar functionality into third-party applications.

## Base URL

```
https://www.googleapis.com/calendar/v3
```

## Resources

The Google Calendar API v3 provides the following resources:

- **Calendars** - Create, read, update, and delete calendars
- **Events** - Manage calendar events including recurring events, quick add, and import
- **Acl** - Manage access control lists for calendar sharing
- **CalendarList** - Manage the user's list of subscribed calendars
- **Settings** - Retrieve and monitor user calendar settings
- **Freebusy** - Query free/busy availability for calendars
- **Colors** - Retrieve calendar and event color definitions
- **Channels** - Manage push notification channels

## Artifacts

| Artifact | Path |
|----------|------|
| APIs.yml | [apis.yml](apis.yml) |
| OpenAPI 3.1.0 | [openapi/openapi.yml](openapi/openapi.yml) |
| JSON Schema (Draft 2020-12) | [json-schema/json-schema.yml](json-schema/json-schema.yml) |
| JSON-LD Context | [json-ld/json-ld.jsonld](json-ld/json-ld.jsonld) |

## Documentation

- [Calendar API Overview](https://developers.google.com/workspace/calendar/api/guides/overview)
- [REST API Reference](https://developers.google.com/workspace/calendar/api/v3/reference)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
