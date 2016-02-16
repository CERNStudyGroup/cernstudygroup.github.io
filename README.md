#Mozilla Study Groups

[![Join the chat at https://gitter.im/CERNStudyGroup/cernstudygroup.github.io](https://badges.gitter.im/CERNStudyGroup/cernstudygroup.github.io.svg)](https://gitter.im/CERNStudyGroup/cernstudygroup.github.io)

Welcome to the CERN [Mozilla Science Lab](https://www.mozillascience.org/)'s Study Group project!

### Wait: What's a 'Mozilla Study Group'?

Mozilla Study Groups are fun, informal meetups of your friends and colleagues from around your local institution or town to share skills, stories and ideas on using code for research. The goal is to create a friendly, no-pressure environment where people can share their work, ask for help on a coding problem, and learn and work together with their peers.

## For Participants

Welcome to our CERN Mozilla Study Group! A few things to do & know now that you're here:

 - **Watch this repo:** up in the top right, there's a button that says 'Watch'; click it, and set yourself to 'Watching'. This will send you email notifications of new discussions; if you don't want email, but would like an alert just on GitHub, change the setting in Settings -> Notification Center (Settings is the little cog in the top right).
 - **Check out the issue tracker:** click on 'issues' in the sidebar on the right; this is where all the conversations this study groups is having live. Use this space to ask questions, request events, make suggestions, or just say hi.
 - **Read the code of conduct:** this Study Group is for everyone - we abide by a [set of rules](https://www.mozillascience.org/code-of-conduct/) that require everyone be treated with respect. Help us make a space where everyone feels welcome, and we'll all have a better time!
 - **Add yourself to the website:** If you'd like to appear on the website under the 'Who we Are' section, have a look at the `_data/members.yml`; send us a pull request with an entry for yourself, or open an issue and we'll do it for you.

## How to Launch a New Event

When you're ready to list a new event for your Study Group, follow these steps, or [watch this video](https://youtu.be/abglQgEIccw) where we walk you through event listing.

 1. **Make a new Issue to describe your event.**
   - Click on 'Issues' over on the right sidebar of your repo,
   - click the green 'New Issue' button near the top right.
   - You'll then see a form where you can give your event a title and a description - fill these out with all the relevant information:
     - Where will your event be? Include a link to a map.
     - When will it be? Date and time.
     - Should people do anything to prepare beforehand (install any dependencies, set something up?)
 2. **Go to the `_posts` directory**. If you've forked this repo, it'll be at `https://github.com/yourUserName/cernstudygroup.github.io/tree/master/_posts` - or you can click on `_posts` in your repo.
 3. **Make a new file** by clicking on the `+` sign beside `_posts/` Name it like the following:

    ```
    YYYY-MM-DD-word.markdown
    ```

    where `YYYY-MM-DD` is the date of your event, and `word` is anything you want.
 4. **Cut and paste the following into your new file:**

    ```
    ---
    title: Study Group Meetup
    text: a one sentence description of your event
    location: Hacky Hour Stadium
    link: https://github.com/yourUserName/studyGroup/issues/1234
    date: 2016-01-04
    startTime: '15:00'
    endTime: '16:00'
    ---
    ```

    Change all the fields to describe your event; make sure the `link` is the address of the issue you created When you're done, click 'Commit Changes' at the bottom.
