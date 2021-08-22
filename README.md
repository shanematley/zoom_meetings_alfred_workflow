# Zoom Meetings workflow for Alfred

Workflow for joining Zoom Meetings.

Regular zoom meetings are stored in a Markdown document found at a location specified by the ZOOM_MEETING_PATH Workflow Environment Variable.

The first table in the Markdown document will be used to populate the list of Zoom meetings. The expected format is:

| Description | Meeting Id | Passcode | URL |
| ----------- | ---------- | -------- | --- |
| Meeting Name | 123 456 789 | 000 | zoommtg://xxx.local/join?confno=123456789&pwd=xxx |
