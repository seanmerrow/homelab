# Cyber Plan

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Cyber Plan
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section School
        Fall Semester             :  des1, 2026-09-01,2026-12-15
        Winter Break              :  des2, after des1, 2026-12-16,2027-01-23
        Spring Semester           :  des3, after des2, 2027-01-24,2027-05-15

    section Certification
        CCST Cybersecurity        : done, 2014-01-06,24h
        CCNA                      : done, after des1, 2d
        CCNA Cybersecurity        : active, 3d
        CCNP Cyber Core           : 5d
        CCNP Cyber Elective       :2d
```


