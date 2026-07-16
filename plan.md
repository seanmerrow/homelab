# Cyber Plan

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Cyber Plan
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section School
        Fall Semester             :done,    des1, 2014-01-06,2014-01-08
        Winter Break               :active,  des2, 2014-01-09, 3d
        Spring Semester               :         des3, after des2, 5d

    section Certification
        CCST Cybersecurity :crit, done, 2014-01-06,24h
        CCNA          :crit, done, after des1, 2d
        CCNA Cybersecurity             :crit, active, 3d
        CCNP Cyber Core        :crit, 5d
        CCNP Cyber Elective           :2d
```
