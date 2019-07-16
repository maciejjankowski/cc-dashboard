# [team coding dashboard](https://github.com/maciejjankowski/team-coding-dashboard)
### Difficulty & Time involvement
4/5, 2 weeks. 2 APIs to use, RaspberryPI configuration. 
### Description
This a dashboard which we can display on the projector.

It should contain:
* github statistics for every registered team
* list of workshops happening within next 2 weeks
* list of taken and free PA and consultations slots based on calendar
* successes: Passed PA, GO, Jobs
* number of students who got a job this month, quarter and total

### User stories
* I want be able to see daily/weekly progress and volume of commits in all teams (overview)
* I want to be able to see which workshops are happening in current and following weeks 
* I want to see who booked PA, consultations and trial interviews
* I want to be able to see how many consultation and PA slots are left
* I want to be able to schedule a trial interview or a consultation with any mentor
* I want the dashboard to adaptively change information displayed
  * In the morning until 9:00-10:00 it should display the time remaining until 10:00
* It should display the upcoming workshop
* It should run on raspberry pi with chrome [kiosk mode](https://stackoverflow.com/questions/39068389/opening-chrome-browser-in-full-window-or-kiosk-mode-on-windows-7) and [on-screen keyboard](https://chrome.google.com/webstore/detail/google-input-tools/mclkkofklkfljcocdinagocijmpgbhab)
