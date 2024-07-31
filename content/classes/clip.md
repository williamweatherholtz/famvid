---
fields:
  - name: Title
    type: Input
    options: {}
    path: ""
    id: 4TVmOF
  - name: Event
    type: Input
    options: {}
    path: ""
    id: xzltcp
  - name: Location
    type: Input
    options: {}
    path: ""
    id: YtKkQA
  - name: Source Footage
    type: File
    options:
      dvQueryString: dv.pages('"class_data/Source Footage"')
      customRendering: page.file.name
    path: ""
    id: UFjCvj
  - name: Date
    type: Date
    options:
      dateShiftInterval: 1 day
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: 7bAzPu
  - name: People
    type: MultiFile
    options:
      dvQueryString: dv.pages('"class_data/People"')
      customRendering: page.file.name
    path: ""
    id: pqeGym
  - name: Youtube Link
    type: Input
    options: {}
    path: ""
    id: DhMg4b
  - name: Source Footage Original Timestamp
    type: Time
    options:
      dateShiftInterval: 1 minute
      dateFormat: HH:mm:ss
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: 3pISpJ
  - name: Source Footage Youtube Timestamp
    type: Time
    options:
      dateShiftInterval: 1 minute
      dateFormat: HH:mm:ss
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: ng5MQd
  - name: filtering details
    type: Input
    options:
      template: audio corrected using Davinci Resolve
    path: ""
    id: zmK8pl
version: "2.92"
limit: 20
mapWithTag: true
icon: file-video
tagNames: 
filesPaths:
  - Videos
bookmarksGroups: 
excludes: 
extends: 
savedViews: []
favoriteView: 
fieldsOrder:
  - 4TVmOF
  - 7bAzPu
  - YtKkQA
  - xzltcp
  - pqeGym
  - UFjCvj
  - 3pISpJ
  - DhMg4b
  - ng5MQd
  - zmK8pl
---
A video extracted from raw footage