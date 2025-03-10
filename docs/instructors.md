---
layout: module
title: Instructor Information
module: false

program:
  before:
    title: Before the Event
    trainings:
      - custom:
          title: Recording Videos (optional)
          description: |
            **Anybody is welcome to record one of the GTN tutorials**, and add it to the Video
            Library. Even if another recording already exists!  Both the tutorial and Galaxy
            change frequently, having regular and/or multiple recordings of tutorials is great!
            <br><br>
            Please have a look at our [video recording guide](./events/smorgasbord2/recording.html)
            for tips and tricks around recording a GTN tutorial.
            <br><br>
            **Procedure around video recordings**
            1. Update the GTN materials (if necessary)
            2. Record your video ([tips & tricks](./events/smorgasbord2/recording.html))
            3. Submit your video ([submission form](https://docs.google.com/forms/d/e/1FAIpQLSdYlHLqkt4PdY8uarkv1j01ZuWlEp5w3sGmZ1uy7N45j7ikwQ/viewform?usp=sf_link))
            4. We will upload your video to YouTube
            5. We will put the (autogenerated) captions in a Google Doc
            5. You will check/fix the autogenerated captions
            6. We will upload the captions and your video will go live!

            Feel free to let us know of your recording plans before you start, we are happy
            to walk you through all the steps involved, and answer any questions you may have.

      - custom:
          title: Check Event Page
          description: |
            Have a look at the [course page for your event](./events)
            here you will see all the content that will be covered.
            <br>
            If you you see any mistakes, please let us know!
            <br><br>
            Below each training video, there is a table with all relevant information regarding
            the tutorial, including **link to the corresponding GTN tutorial**, which you may wish
            to read ahead of time.
            <br><br>
            In table you will also find a link to a **Slack channel**.
            This is where participants will ask any questions about this tutorial.
            **Please join all the channels you want to help out with!**.
            <br><br>
            More info on Slack below.
      - custom:
          title: Slack for Support
          description: |
            1. Join the [GTN Training Slack](https://gtnsmrgsbord.slack.com/), using this [invite link](https://join.slack.com/t/gtnsmrgsbord/shared_invite/zt-x7vinbs1-BA~Kht6N86JBhDq0uTIVdQ")
            2. Ask to be added to the [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN) channel.
            3. Browse channels and join the ones you would like to help with!
               - Slack channels for each session can be found under the videos on the event page.
            4. Familiarize yourself with the platform ([short guide](./slack.html))
      - custom:
          title: Add Yourself to the Instructor List
          description: |
            We would like to add all instructors to the [Video Library Hall-of-Fame](./contributors)! (And to your event page).

            1. **Familiar with git?** Add yourself to the [instructors.yaml](https://github.com/gallantries/video-library/blob/main/docs/instructors.yaml)
               file and create a Pull Request
            2. **Not familiar with git?** No problem! Just provide us your
               - name
               - affiliation
               - (optional) a profile picture

               We will add you to the list!
               You can ask us in the [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN)
               channel of Slack (or via DM)
      - custom:
          title: Create a 30-second introduction video (optional)
          description: |
            For some events (such as the annual Smörgåsbord), we like to have a *Meet your
            instructors* video as part of the welcome session.
      - custom:
          title: Tutorial Testing
          description: |
            You can help greatly by helping us test materials ahead of time!

            1. Check the event web page, does it look correct? any broken links? etc
            2. Run a tutorial and let us know if it works or not
  during:
    title: During the Event
    trainings:
      - custom:
          title: Icebreakers
          description: |
            To encourage engagement on Slack, many events have **icebreaker questions**

            **Instructors are encouraged to answer these the daily icebreakers** in Slack as
            well, and respond to the answers from participants

            Our aim with these questions is to provide a fun and welcoming environment for all,
            which will make it easier for participants to ask their questions about the tutorials
            in Slack. The more activity there is on Slack, the lower the barrier for shy
            participants to join in!

      - custom:
          title: Answering Questions
          description: |
            1. Join the Slack channels for all trainings you want to help out with.
            2. Just keep an eye on Slack throughout the event, when you can.
            3. You are NOT expected to be around all the time; we all have jobs and other
               commitments, just help out when you have some time!
      - custom:
          title: When you don't know an answer
          description: |
            That is totally ok!

            You can either:
            1. Check the tutorial FAQ page (link in table below video, top of Slack channel)
            2. Wait for somebody else to answer it
            3. Ping an instructor who you think might know the answer
            4. **Has question gone unanswered for a long time?** post a link to it
               in the #instructors channel to see if anybody knows the answer (other instructors
               may not have seen the question)
            5. Remind the participant to **be patient**, some questions can only be answered by a
               small number of instructors, who may not be around right now, but they will
               provide an answer eventually.
      - custom:
          title: When there is a problem with the Galaxy server
          description: |
            Many questions may be about a tool not working as expected, or other problems with Galaxy
            If you suspect that the problem is with the server, rather than a mistake by the
            participant, please:

            1. Ask participant which server they are using
            2. **Share** the message to the [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN) channel (see [Slack info page](./slack) for instruction)
            3. Ping one of the admins/representatives for that server
               - Galaxy Main (US): **@Nate Coraor, @Jen Hillman-Jackson**
               - Galaxy EU: **@Gianmauro Cuccuro, @Björn Grüning**
               - Galaxy AU: **@Simon Gladman, @Anna Syme**

      - custom:
          title: Code of Conduct violations
          description: |
            GTN events have a [Code of Conduct](https://galaxyproject.org/community/coc/) that
            we expect all participants and instructors to honour.

            If you witness any violations, report it in the
            [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN) channel on
            Slack, and one of the members of the
            [CoC committee](https://galaxyproject.org/community/coc/#reporting-issues) will
            handle it further.

  after:
    title: After the Event
    trainings:
      - custom:
          title: Give us your feedback
          description: |
            link to survey to follow.
  faq:
    title: Frequently Asked Questions
    description: Some common Galaxy questions are listed in the [GTN FAQ page](https://training.galaxyproject.org/training-material/faqs/galaxy/). The icon behind each FAQ title will take you to the FAQ page, which you can easily share with participants.
    trainings:
      - custom:
          title: How do I share my history?
          description: |
            Often it helps to look at a participant's history to understand their problem better.
            - Ask the participant to [share their history via link](https://training.galaxyproject.org/training-material/faqs/galaxy/histories_sharing.html) and post it in Slack.
      - custom:
          title: I can't find tool X!
          description: |
            If a participant can't find a tool:
            1. Make sure they are working on one of the supporting servers
               - see *"Available on these Galaxies"* section in the overview box at top of tutorial.
            2. Tool search sometimes doesn't return the right results
               - Encourage them to use GTN-in-Galaxy, many tutorials will have direct links to
                 the correct tools this way
            4. Think something else is wrong? Report it in [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN) channel
               and ping the admins of that server (see *When there is a problem with the
               Galaxy server* above)

      - custom:
          title: Tool Y isn't working!
          description: |
            If a participant reports a tool is not working, please ascertain:
            1. Which Galaxy server are they using?
            2. Make sure they have used the correct settings and input files
            3. It can be useful to have them **share their history** with you
               ([instructions](https://training.galaxyproject.org/training-material/faqs/galaxy/histories_sharing.html))
            4. If you think there is a problem with the server, report it in [#instructors](https://gtnsmrgsbord.slack.com/archives/C01ES97MZBN) channel
               and ping the admins of that server.

      - custom:
          title: "[Smörgåsbord] I don't know what tutorials to do!"
          description: |
            For Smörgåsbord events, we don't offer a fixed program, but participants
            can pick and choose which tutorials they want to follow. This flexibility can be
            overwhelming for some.

            If people are new to the bioinformatics world and don't know where to start, you
            can recommend the [Bioinformatics Buffet](./modules/bioinformatics-buffet) module. This covers the introductory
            sessions for a range of popular topics.

---

Thanks for being an instructor at one or more GTN Events!

On this page we aim to provide all the information you need, but please don't hesitate to ask us any remaining questions you may have!


