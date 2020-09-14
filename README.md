# Daylight Saving Time Changes By Timezone

A parseable list of the exact times in UTC that each timezone each year switches to Daylight Savings time, and the offset for each.

Sample:
`````json
"America/Toronto": {
    "1970": {
        "daylight": [
            "1970-04-26 07:00:00",
            "1970-10-25 06:00:00"
        ]
    },
    "1971": {
        "daylight": [
            "1971-04-25 07:00:00",
            "1971-10-31 06:00:00"
        ]
    },
    ...
    "2036": {
        "daylight": [
            "2036-03-09 07:00:00",
            "2036-11-02 06:00:00"
        ]
    },
    "2037": {
        "daylight": [
            "2037-03-08 07:00:00",
            "2037-11-01 06:00:00"
        ]
    },
    "offset": {
        "default": {
            "utc_offset": -18000,
            "dst_offset": -16
        }
    }
}
