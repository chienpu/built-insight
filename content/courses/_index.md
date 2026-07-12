---
title: Courses
summary: My courses
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: courses
    content:
      title: Courses
      page_type: docs
      text: |-
        These two graduate courses trace a single thread: how engineering data
        becomes trustworthy evidence, and how that evidence flows to the right
        person, in the right format, at the right time.

        Drawing on 20 years of AEC practice and ongoing research in semantic
        digital twins, both courses combine case-based instruction with a
        term-long capstone project — students leave with a governance
        architecture or integration plan they can defend, not just a grade.
      filters:
        folders:
          - courses
        kinds:
          - section
    design:
      view: date-title-summary
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---