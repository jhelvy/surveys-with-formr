
<!-- README.md is generated from README.Rmd. Please edit that file -->

Last updated: December 08, 2020

# Overview

These files were used in creating John Helveston’s rstudio::conf 2021
lightning talk titled “Using {formr} to create R-powered surveys with
individualized feedback.”

[<svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 576 512"><path d="M576 24v127.984c0 21.461-25.96 31.98-40.971 16.971l-35.707-35.709-243.523 243.523c-9.373 9.373-24.568 9.373-33.941 0l-22.627-22.627c-9.373-9.373-9.373-24.569 0-33.941L442.756 76.676l-35.703-35.705C391.982 25.9 402.656 0 424.024 0H552c13.255 0 24 10.745 24 24zM407.029 270.794l-16 16A23.999 23.999 0 0 0 384 303.765V448H64V128h264a24.003 24.003 0 0 0 16.97-7.029l16-16C376.089 89.851 365.381 64 344 64H48C21.49 64 0 85.49 0 112v352c0 26.51 21.49 48 48 48h352c26.51 0 48-21.49 48-48V287.764c0-21.382-25.852-32.09-40.971-16.97z"/></svg>
View slides in a new
window](https://jhelvy.github.io/surveys-with-formr/slides/index.html)

[<svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 384 512"><path d="M369.9 97.9L286 14C277 5 264.8-.1 252.1-.1H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48V131.9c0-12.7-5.1-25-14.1-34zM332.1 128H256V51.9l76.1 76.1zM48 464V48h160v104c0 13.3 10.7 24 24 24h104v288H48zm250.2-143.7c-12.2-12-47-8.7-64.4-6.5-17.2-10.5-28.7-25-36.8-46.3 3.9-16.1 10.1-40.6 5.4-56-4.2-26.2-37.8-23.6-42.6-5.9-4.4 16.1-.4 38.5 7 67.1-10 23.9-24.9 56-35.4 74.4-20 10.3-47 26.2-51 46.2-3.3 15.8 26 55.2 76.1-31.2 22.4-7.4 46.8-16.5 68.4-20.1 18.9 10.2 41 17 55.8 17 25.5 0 28-28.2 17.5-38.7zm-198.1 77.8c5.1-13.7 24.5-29.5 30.4-35-19 30.3-30.4 35.7-30.4 35zm81.6-190.6c7.4 0 6.7 32.1 1.8 40.8-4.4-13.9-4.3-40.8-1.8-40.8zm-24.4 136.6c9.7-16.9 18-37 24.7-54.7 8.3 15.1 18.9 27.2 30.1 35.5-20.8 4.3-38.9 13.1-54.8 19.2zm131.6-5s-5 6-37.3-7.8c35.1-2.6 40.9 5.4 37.3 7.8z"/></svg>
Download slides as a
PDF](https://jhelvy.github.io/surveys-with-formr/slides/surveys-with-formr.pdf)

# Surveys

In my presentation, I showed several examples of how to use the {formr}
package to create different types of surveys. The surveys are all
generated from Google sheets, which can be found here:

1.  [Random
    images](https://docs.google.com/spreadsheets/d/1hs551J6PYJNxc4sftmJyUqj6XYGYFVnN_5faQBWY7cs/edit?usp=sharing)
    demonstrates how to randomly display different images.
2.  [Conjoint
    surveys](https://docs.google.com/spreadsheets/d/1Ih3Pt6uz-gp5vc0SBxBzl4K0aZoRLwI6dtdtZiXSLz0/)
    demonstrates how to create a conjoint survey with formr (go to the
    [formr4conjoint](https://github.com/jhelvy/formr4conjoint) repo for
    a more detailed description)
3.  [Timed
    quizzes](https://docs.google.com/spreadsheets/d/1PAHG15ijvVpCO3Ny9biAnzJTonLLfzPDDBKg1vA0ZEs/edit?usp=sharing)
    demonstrates how to create a timed quiz with randomly generated
    questions.

To use any of these surveys yourself, go to
[formr.org](https://formr.org/), create an account. Once you log in, go
to the [admin](https://formr.org/admin) page and create a new survey.
You can then paste in the link to the Google sheet there. If you want to
edit it, just create copy of the Google sheet into your own Google Drive
account and use the shared link to that Google sheet.

Once you have a survey uploaded, you can make it live by creating a
“Run” and inserting the survey you created by clicking on the
<img src="images/pen-square-solid.svg" width=20> icon as well as a
“Stop” point to end the survey by clicking on the
<img src="images/stop-solid.svg" width=20> icon. The link to the survey
will be `https://your_run_name.formr.org`.

You can control the “publicness” of the survey by modifying the “volume”
icons:

  - <img src="images/eject-solid.svg" width=20> means only you can
    access the survey

  - <img src="images/volume-off-solid.svg" width=15> means you and
    people who have an access code can access (no new users can enroll).

  - <img src="images/volume-down-solid.svg" width=20> means people who
    have the link can access.

  - <img src="images/volume-up-solid.svg" width=25> means the link is
    public, everyone can access.

-----

### License

![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License](https://creativecommons.org/licenses/by-sa/4.0/).
