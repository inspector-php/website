# Introduction

Inspector is a testing application for *data*.

While you use excellent tools such as phpspec, phpunit, behat, etc for your unit and functional tests,
you can use inspector to test your production data.

## Why use Inspector?

It is really hard to know if all data in your production databases is valid.

* You never know what users do, it's unrealistic to validate *everything*.
* It's not just your application's UI accepting data. You need to think about importers, legacy data, api's and other suspicious sources.
* You may validate all user input *now*, but what about the data that entered your databases *before* you added validation?
* It's not just database integrity checking that matters. Sometimes complex combinations of data result in new problems.

## Why we developed Inspector

At LinkORB we're hosting hundreds of customer databases, with hundreds of tables and thousands of rows.

We noticed that our our support engineers spent a lot of time inspecting customer databases to find and solve problems.
We find all sorts of issues: Unexpected input, data inconsistencies, importer problems, mis-configurations, etc etc.

This lead us to the idea of automating those data inspections. This way, we can inspect *all* systems, *daily* and *pre-emptively*.

For each issue that's detected, a 'solution' is presented to either the user, or our support engineers, depending
on if the user can solve the problem through the app's UI.

### Benefits for our users:

* We find and solve issues before they do.
* Less need to send support tickets.

### Benefits for us:

* We can fix detected issues early, preventing furher unexpected behaviour.
* Once we automate an inspection, we know it will be detected in the future.
* Once we automate an inspection, we know it will be detected in all databases.
* Detected issues all provide a human-readable solution, simplifying support.
