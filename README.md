# Suspending this project for while. There is another project that seem to be going in the same direction using cuelang too will be using that instead. cuev

# cuerun
Alternative task runner for cuelang's `cue cmd`

# introduction
General purpose task runner for cue, and supporting tool for [podman-cue](https://github.com/ravinsharma7/podman-cue)

# Tentative features (Some might be merged or redacted based on what is needed)
- tui management
- task scripting using cuelang
- parallized tasks. multiple task running without block tui
- run task in containers or host. decoupling run "compute" from tasks using configuration, or tui.
- mix "compute". shell +/- podman
- devcontainer support
- environment loading
- tasks run versioning and structured logs(queriable and searchable logs)
- tasks specific logs. runner and task log seperation. task reporting.
- task piping (regardless of "compute" location)
- task events.
- task circuit breaker / trap / signals
- task hooks.
- task healthcheck
- long running tasks. auto-restart.
- timeout, retry, backpressuring.
- subtasks
- lazy tasks.
- schedules tasks.
- conditional tasks.
- tasks ordering
- task priority
- looping task.
- task waiting and grouping
- crash report and resumable tasks
- replay
- idempotent warning.
- remote tasks
  

# How to
TBD
