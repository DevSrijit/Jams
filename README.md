# Jams 🫐🍓🍇
Teaching coding is hard. Running engaging Hack Club meetings is even harder. By September we want to create a repository of the most incredible coding projects ever! This summer you can build the future of Hack Club workshops - we're calling them Jams!

Work with the team at HQ to contribute a jam and **we'll pay you $200** for it. it'll be used by thousands of Hack Clubbers around the world!

**What is a Jam?**

The goal is to build a highly curated list of quality projects for varying technical abilities. The content is high quality, slides, videos within a beautiful page that's easy to filter... They're real projects that can be completed in under 1 hour, are very visual, and have clear paths for continued hacking. Members should be inspired to keep hacking on the project after the session, not left feeling stuck without knowing what to do next. Everyone's result is different


** example?

### Here's how to get started:
* Make a pull request into (folder)
**Submission requirements:**

_Updated by <StaticMention username="matthew" avatar="https://cloud-dl8z4zly8.vercel.app/t0266frgm-u4qak9srw-cf4e2e522a71-512" link="https://matthewstanciu.me/" /> on 10/29/2020. Starting today, all newly-submitted workshops will have to follow these new requirements. [Click here](https://hack.af/workshop-bounty-original) to see the previous version of this announcement._

- You must be a club leader or an active community member in order to submit a workshop
- Your workshop must be original and not plagiarized.
- Your workshop must produce a compelling, specific, real project, using real code. **It should not be a tutorial** for a language or service. It should also not be a series of small projects with no clear ending or final product.
  - ✅ [Animated 3D Models](https://workshops.hackclub.com/3d_models_with_zdog/), which uses a simple JavaScript library to create awesome-looking 3D models
  - ❌ A tutorial for how to get started with AWS
  - ❌ A workshop on an introduction to Scratch
- Your workshop must be able to be completed in around 20 minutes, but it should be very easy for people to make big changes to it.
- At the end of your workshop, you must include links to at least 3 demos clearly showing the initial project being changed in big ways. These demos should serve as examples for how hackable your workshop is. Each demo should include a link to the project and a link to the source code.
  - ✅ [Tunes](https://workshops.hackclub.com/tunes/), which includes 3 projects at the end that stem from the project made in the workshop but are very noticeably different and clearly made independently
  - ❌ A todo list app whose examples for hacking are adding icons, changing the background color, or other small incremental changes that don't meaningfully build on the project the workshop has made
- Your workshop must involve code, and not require desktop software or hardware, since not all clubs will have those resources.
  - ✅ A Python workshop where the first step is to start a new Python project at [repl.it/languages/python](https://repl.it/languages/python)
  - ❌ A workshop on making an Android app that requires installing Android Studio
- At the beginning of your workshop, you must include the link to the final demo and the final code.
- Your workshop must be in English at native-level proficiency. Phrasing and grammar must be perfect.
- By default, all workshops should be written in Markdown or another format that can be easily be added to the [Workshops page](https://workshops.hackclub.com). Workshops submitted in a different format are also encouraged, but the format must be approved by <StaticMention username="matthew" avatar="https://cloud-dl8z4zly8.vercel.app/t0266frgm-u4qak9srw-cf4e2e522a71-512" link="https://matthewstanciu.me/" /> first
- Each step in your workshop should be very clearly explained and should continually give context for where the user is in the workshop.
  - ✅ [Konami Code](https://workshops.hackclub.com/konami_code/): each step contains a small block of code that is clearly explained right afterward. Phrases such as "just above the closing `</body>` tag", code blocks that include new lines of code being shown in their entirety, and a constant reminder of what the current code should look like, all make sure the person going through the workshop is never lost. Any code concepts or information about a library are made optional to learn more by clicking a link.
  - ❌ A workshop that includes many large blocks of code for the user to copy/paste, and does not explain what much of the code does
  - ❌ A workshop in which each step contains a block of code with no instructions for where to include it
- Your workshop must not be the same or too similar to [any existing workshop](https://workshops.hackclub.com). Make sure to check on this before you start writing your workshop—if your workshop is too similar to an existing one, it won't be able to be merged at all!
- Every piece of media (image, GIF, video, etc.) you include in your workshop should include alt text that clearly describes what's in the piece of media
  - ✅ `![A close-up of a gecko foot being pressed on glass](https://mbs.zone/geck)`
  - ❌ `![](https://mbs.zone/geck)`
  - ❌ `![animal](https://mbs.zone/geck)`

Hack Club workshops are entirely open source on GitHub. Workshops are submitted using [pull requests](https://guides.github.com/activities/hello-world/#pr).

In addition to submitting the workshop itself, we ask that you test your workshop in a club meeting and record a 1-2 minute clip during the meeting showing what people built. You could turn on Zoom recording for 2 minutes near the end of the meeting. Or walk around with your phone's camera showing what people built if you're in-person. This meeting can be a real club meeting or a mock meeting where you gather 3+ friends.

Every workshop we accept as part of the workshop bounty program should be something we're proud to stand by as official Hack Club curriculum. If any of the above requirements are not hit, we will ask you to resubmit once you've met all guidelines. If this is your first time submitting a workshop, your submission will likely be rejected multiple times before it's ready to merge. Writing a good workshop is very challenging, and although we are a very small team and we can't promise that we'll be able to provide detailed editing and feedback on submissions, we will work with you to get your workshop in a good spot.

**How to submit:**

- Create a pull request to [`hackclub/hackclub`](https://github.com/hackclub/hackclub) on GitHub with a new folder in the [`workshops/`](https://github.com/hackclub/hackclub/tree/main/workshops) directory called the name of your workshop. Make sure to follow the lowercase snake case format, like the other workshops. Put your workshop in a file named `README.md`.

  - If your workshop is a slideshow or another binary format, export it and upload to the `#cdn` channel on the Hack Club Slack. Then link it from `README.md`.
  - At the top of the file, include the following metadata (author being your GitHub @username):

    ```
    ---
    name: 'Sound Galaxy'
    description: 'Visualize sound by making particles move in a galaxy'
    author: '@MatthewStanciu',
    img: 'cdn-link-to-image-summarizing-your-workshop'
    ---
    ```

- Upload your meeting recording to the `#workshop-skunkworks` channel on Slack.
- Copy the link to the Slack message containing your recording and include it in the text of your pull request.
- Submit! If you have questions about submission, please ask in `#workshop-bounty` on Slack

**How to get your payment:**

Once your pull request is merged, you'll be sent a private form to share your payment details and tax forms with us.

- Total payment: $200 USD
- Available payment methods for US citizens:
  - Mailed check. You must be able to sign [Form W-9](https://www.irs.gov/pub/irs-pdf/fw9.pdf) (this is a standard tax document that the IRS forces Hack Club to collect - don't worry, we have a flow for collecting electronic signatures).
  - Receiving funds in a [Hack Club Bank](https://hackclub.com/bank) account (ex. if you want the funds to be structured as a grant to your Hack Club or your hackathon / nonprofit)
- Non-US citizens must have a PayPal account we can send funds to and be able to provide a signed [Form W-8BEN](https://www.irs.gov/pub/irs-pdf/fw8ben.pdf) certifying that they are not subject to US tax law (Don't worry! This form is quite simple and similarly required by the IRS)

You will receive a screenshot confirming payment once it's been made, usually within 7 days of form submission. Checks can take up to 2 weeks to arrive.

**Wrapping up:**

This is a very new experiment. We'll be iterating on the workshop guidelines throughout the semester and working to make sure that everyone is having the best experience possible.

If you have any questions, please message in `#workshop-bounty` on Slack. I'll be hanging out there to help out.

\- Zach

---

_Earlier I mentioned that running a club was hard. During the first 6 weeks of this school year, I am personally onboarding every new Hack Club myself._

_I'm also speaking with many folks about their own Hack Clubs, some who are close to HQ and some who are not so close, and sharing excerpts below (with permission, of course)._

### Conversation with Matthew on his club and workshops

_Bloomington, IN. 2:59 PM on Thursday, September 3rd, 2020._

**What makes a good Hack Club meeting?**

A lot of it is the leader. The leader has to provide the energy and make sure people are having fun. It is important that people learn stuff, but it may be even more important that people have fun than actually learn stuff. That doesn't mean people shouldn't learn stuff, just that it's really important they have a good time. One of the best ways to make sure people have a good time is to have them making some real while having fun.

**You ran your Hack Club for 4 years. You mentioned that when you were a freshman and starting out, it was bad. Only later in your junior and senior years you feel like you "cracked" the format and started consistently running good meetings that had regular high attendance. What was the difference between your club when it was bad vs. good?**

When it was bad, we mostly did nothing. During meetings, I would say: "OK, everyone can do whatever they want. Let me know if you need help thinking of a project." But really **people just got lost and nobody asked for help**. I was also working on my own projects during club meetings, which a lot of club leaders do. I thought that would inspire my members to build projects of their own, but in retrospect I think it just made me less approachable.

As soon as I stopped working on my own projects and got up and spent the whole meeting walking around the room, being energetic, checking in, and asking people if they needed help, I could feel a huge difference. Truly nobody in your club is going to ask for help, especially if they think you're busy. Admitting they need help makes them feel weird because they feel like they're bothering you. You have to check in with your members if you want them to ask you for help.

My Hack Club actually became good when I was running content every week. Because there wasn't good content available via the Hack Club workshops, I started writing my own workshops each week for club meetings.

**What was the difference between the bad and the good workshops you made?**

Usually the bad workshops, well—none were really bad—but the worst ones were the ones where the end result wasn't very satisfying or people had to spend too much time writing too much code that they didn't understand to get something tangible.

The best ones were where the end product was something really, really cool, visually appealing, and made in 10 or 20 minutes. Also, the best ones had 5 examples right out of the gate of how other people have hacked it. Then people would do the workshop and at the end everyone would end up with something different.

For members, good workshops take very little time and effort to produce something very visually appealing and very hackable. And there are inspiring examples of how the workshop could be further hacked.

A lot of the old Hack Club workshops felt more like tutorials than workshops. Because people spent 45 minutes going through the tutorial and then making something that they didn't feel very satisfied by. [Synth](https://workshops.hackclub.com/synth/) was the best workshop not made by me because it was very satisfying, but even it took an hour to do and that was too long for a good club meeting.

My favorite workshop I've made is [Sound Galaxy](https://workshops.hackclub.com/sound_galaxy/). Most people, especially beginners, don't know that it's actually possible to take input from your microphone and turn it into colorful blops that show up on the screen with input from your microphone. And it's even more impressive you can do that as a complete beginner and newbie in 40-50 lines of code. Every member I've seen do that workshop was very impressed that it was possible to make something so cool that they didn't even know was possible in such a short amount of time.

_Thanks to Christina Asquith, Claire Wang, Lachlan Campbell, Malte Lauterbach, Matt Gleich, Matthew Stanciu, Max Wofford, Sam Poder, and other Hack Clubbers in the community for their feedback on this post._

</Letterhead>
