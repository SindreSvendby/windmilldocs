# Settings

The flow settings are divided into four tabs:

- [Metadata](#metadata)
- [Schedule](#schedule)
- [Shared Directory](#shared-directory)
- [Graph](#graph)

## Metadata

The metadata tab allows you to configure the flow name, summary, and description.
Permissions can be configured in two ways:

- By user: Select a user
- By folder: Select a folder

![Flow Metadata](../assets/flows/flow_settings_metadata.png)

## Schedule

Flows can be triggered by any schedules, their webhooks or their UI but they only have only one primary schedules with which they share the same path. The primary schedule can be set here.

A CRON expression is used to define the schedule. Schedules can also be disabled.

![Flow Schedule](../assets/flows/flow_settings_schedule.png)

## Shared Directory

Steps will share a folder at `./shared` in which they can store heavier data and pass them to the next step.

Beware that the `./shared` folder is not preserved across suspends and sleeps.

![Flow Shared Directory](../assets/flows/flow_settings_shared_directory.png)

## Graph

Flows can be visualized in a graph view. The graph view is useful to quickly understand the flow structure, with loops and branches.

![Flow Graph](../assets/flows/flow_settings_graph.png)