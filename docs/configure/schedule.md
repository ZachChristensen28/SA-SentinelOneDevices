# Update Schedule

!!! info "To update the schedule modify the `SentinelOne Devices Lookup - Gen` saved search. It is recommended to clone the default search before making changes (see [Clone Saved Search](../best-practice/clone-search))."

The default saved search runs on the 29th minute of every hour to update and continually build the SentinelOne assets. Most users will find that this schedule works for their environment.

To update the default schedule perform the following steps:

1. Navigate to Settings > Searches, reports, and alerts.
1. Set the "App" dropdown to `SA-SentinelOneDevices`.
1. Set the "Owner" dropdown to `All`.
1. Click "Edit" under actions for the search `SentinelOne Devices Lookup - Gen` or the name of the cloned search (see [Clone Saved Search](../best-practice/clone-search)).
1. Click "Edit Schedule" and update the schedule and necessary.
