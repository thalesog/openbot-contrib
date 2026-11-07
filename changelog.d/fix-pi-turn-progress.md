### Fixed

- A Pi turn no longer says the provider sent no update while a tool runs, a request retries, or the
  context compacts. The activity line now shows the tool's partial output, the retry, or the
  compaction, and repeats the current step every 20 seconds while Pi is silent. Before, the Pi
  client dropped those records, so the line stayed still and blamed the provider.
