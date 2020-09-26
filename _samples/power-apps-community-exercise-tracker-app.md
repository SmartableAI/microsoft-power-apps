---
title: "Exercise Tracker App"
excerpt: "This app tracks body weight exercises and shows you your progress. There are 2 versions of the app, an offline app which only tracks the previous"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Exercise-Tracker-App/td-p/649156
type: download
publishedDateTime: 2020-08-05T12:47:00Z
heat: 52

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/591/1/Exercise%20Tracker_offline.msapp"
    type: "download"
    title: "Download Source Code"
    attribution: "Power Apps Community"

provider:
  name: Power Apps Community
  domain: microsoft.com
  images:
    - url: /assets/images/organizations/microsoft.com-50x50.jpg
      width: 50
      height: 50
  authors:
    - name: RickIrvine

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com/t5/image/serverpage/image-id/167294i3371C55843CE705A/image-size/large?v=1.0&px=999
    width: 999
    height: 573
    isCached: true

secured: "OldPSGHWwgx9WH0+ovlEpgOvd9ZLasrvVaxXROWW4cDFCGwyzktHKw5CZZYwau0gjjvF5M+AiH60IdS4D+Rw4Ow12XQAttyEZnLUI22D/4OySlm3aUTwc+8EuxqETtYEaryPDgMKDl8ZOKsbcshymW9q3NBpPJXcDa8yPQshnTsCUmq9/cTQGJkCvqzxYLRp7W0D9rDixHTi1694sGHt6yTPvrSwEGhz/hZ59Xtjhjf4dBlG49H+2zAdgB2Do/LZClpedgwnsPo9QIfjARW0bPNQrP8gxfsaTvH+q8cop08n9/ZyPSaPtIaMR/x4+20Q3wNJXtkrx3RkCnMrEoMEDc9tVKrZRvEGkRiI/4dXRPteIbKQx4BIcvXUy1SAQTDy+EerAv4LCJOGPpLuywDwsg==;scYIO7/L2ix0TBL6OZcqKA=="
---
<p>This app tracks body weight exercises and shows you your progress.&nbsp; There are 2 versions of the app, an offline app which only tracks the previous month and an online app which tracks your all time progress and saves the records in a SharePoint list.&nbsp;&nbsp;3 columns make up the list:</p><p>&nbsp;</p><p>Exercise: Text</p><p>Reps: Number</p><p>ExerciseDate: Date</p><p>&nbsp;</p><p>There is an auto cleanup of the local collection for anything older than a month.&nbsp; To deal with the delegation issue with SharePoint, it checks for when there are more than 500 rows in the list, copies the totals into variables then writes back 4 records consolidating the records into one for each exercise.&nbsp;</p><p>&nbsp;</p><p>I've attached both versions of the app if anyone wanted to try it out.</p><p>&nbsp;</p><p>Thanks!</p><p><span class="videoUrl hidden">watch?v=jpvr5qslccg</span></p>

