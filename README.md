# TestingExtensions0_2_11-Bug

## Symptoms
Open project, hit test (Command+U), `TestingExtensions` fails to compile with a list of errors appearing to be related to not finding system `XCTest` framework.

## Attempts
I tried to add `use_frameworks!` into podfile and it can circumvent this problem, but I would avoid that because that creates separate issues for my personal project.

