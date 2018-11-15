---
layout: page
title: Participants
description: This is a test page
---

<script>
var Airtable = require('airtable');
var base = new Airtable({apiKey: 'keyIasevmGIHUwFL8'}).base('appAnZVyYqusNPV5Q');

base('Invitee list').select({
    // Selecting the first 3 records in Complete list:
    maxRecords: 3,
    view: "Complete list"
}).eachPage(function page(records, fetchNextPage) {
    // This function (`page`) will get called for each page of records.

    records.forEach(function(record) {
        console.log('Retrieved', record.get('Email'));
    });

    // To fetch the next page of records, call `fetchNextPage`.
    // If there are more records, `page` will get called again.
    // If there are no more records, `done` will get called.
    fetchNextPage();

}, function done(err) {
    if (err) { console.error(err); return; }
});
</script>