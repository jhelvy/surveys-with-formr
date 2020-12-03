
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Overview

These files were used in creating John Helveston’s rstudio::conf 2021
lightning talk “Using {formr} to create R-powered surveys with
individualized feedback.”

View the slides
[here](https://jhelvy.github.io/surveys-with-formr/slides/surveys-with-formr.html)

-----

# Surveys

In my presentation, I showed several examples of how to use the {formr}
package to create different types of surveys. The surveys are all
generated from Google sheets, which can be found here:

1.  [randomImagesDemo](https://docs.google.com/spreadsheets/d/1hs551J6PYJNxc4sftmJyUqj6XYGYFVnN_5faQBWY7cs/edit?usp=sharing)
    demonstrates how to randomly display different images.
2.  [timedQuizDemo](https://docs.google.com/spreadsheets/d/1PAHG15ijvVpCO3Ny9biAnzJTonLLfzPDDBKg1vA0ZEs/edit?usp=sharing)
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
