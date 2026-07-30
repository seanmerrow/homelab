# homelab

```mermaid
flowchart TD
    Start@{ shape: circle, label: "Start" } --> jira("Partner creates\nRed Hat Jira\n(bug or RFE)")
    jira --> case{"If urgent,\ncustomer creates\nsupport case\n for bug/RFE"}
    jira --> patch{"Upstream\npatch exists?"}
    case --> link{"Link patch\nand/or case to Jira"}
    patch -->|Yes|link
    patch -->|No|create-patch("Create\nupstream patch")
    create-patch -->link
    link --> downstream("Once (or if) merged,\nRed Hat\ndownstreams\nthe patch")
    downstream --> test("Partner tests\nwith RPM from\nRed Hat")
    test -->|Pass|release("Red Hat releases\nin future release")
    release -->Stop@{ shape: circle, label: "Stop" }
    test -->|Fail|create-patch
```
