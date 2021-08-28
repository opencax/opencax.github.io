# GSoC Acceptance Requirements

This lays out the basic "rules and requirements" that our organizations
require of all Summer of Code (whether GSoC or SOCIS) participants whose
project proposals are accepted. Unless otherwise arranged with the
organization administrator (contact 'brlcad' via IRC on irc.libera.chat),
it will be expected that all students will comply with the requirements
outlined below.

## Application Recommendations

### Make a patch

While this is *optional*, it greatly increase your chances of being
selected. Basically, a patch is some change to the software (submitted
wither as a patch file or a pull request). If working with us is your
top priority, a patch will help us see how well you are at dealing
with other people's code. Don't worry, though. It doesn't need to be
more than a few lines. It can be a bug fix or implement some minor
feature. It's more important that it applies without hassle and provides
some improvement. This is one of several opportunities to impress, so
be creative. Link to any patches in your application.

### Come talk to us

You really should be talking to developers long before you submit an
application. Discuss your ideas via IRC and e-mail (mailing list).
Communication is a huge part of our evaluation criteria.

### Maintain a dev log

It's strongly recommended that you maintain a public development log
that is updated every day you work. Most students don't have a habit
of discussing their work adequately and this intrinsically documents
progress. Communication ftw. Dev logs are also a great way to let
people in the community follow your project and provides a place to
showcase cool highlights!

## Participation Requirements

### License appropriately

Participation requires that any work performed will be provided in
good faith and consistent with contributor requirements. Unless approved
in advance in writing, all rights (copyright) will be assigned to the
organization. If your country does not allow assignment of copyright,
non-exclusive rights to use the code in perpetuity will be required.
You will be credited for your work regardless.

### Report activity daily

In addition to your ongoing discussions, it is required to regularly
submit a progress report of daily activity. These reports usually won't
need to be more than a sentence or two but they should provide clear
concise information on what you did, things you discovered, tasks
completed, difficulties encountered, milestones reached, days off, and
other similar details. If you did nothing, that's okay! We want to know
when you're concentrating on code, at the beach, and everything in
between.

### List your milestones

Everyone is required to submit a minimum of three and a maximum of ten
project milestones. These are not deliverables but, rather, are overall
tasks that should be completed throughout the duration of your work.
These should be necessary implementation steps and not include any
research or familiarity phases. In the end, there is code that must be
produced and your milestones should be a (very) rough breakdown for
estimating your progress. These milestones should be published in your
first progress report, that is, at the beginning of coding.

### Be communicative

All students will be expected to be reachable via IRC and e-mail while
they are working. Participants must be responsive, actively engaged in
discussions, and available for questions, comments, and suggestions from
other developers. See here if you are new to IRC and need help.

## Coding Requirements

### Compile and run

Being able to compile and run on your own hardware is a very basic
task that is considered essential. We're more than happy to help you
get started the first time if you run into a problem, but you are
expected to put forth duly diligent effort. Additionally, understanding
the existing user community is very important for most developers to
have at least a basic familiarity. In the end, your changes will
(hopefully) be pushed out to the community and you should be cognizant
of what that will mean.

### Be familiar with revision control

You will be expected to abide by the same coding requirements of other
developers. You must know the basics for how to work with the project's
revision control system including checking out/in changes, resolving
conflicts, and creating patches. Whether you work on a branch or on the
mainline trunk will depend on the project.

### Evaluate performance

Performance is something we always strive to keep in mind. Quantitatively
evaluate your performance and the impact your modifications will make.
Don't prematurely optimize and don't over-architect, but also don't make
guesses or assumptions either. Use a performance profiler, test your
code, add debug timers, and/or have a peer review your work.

### Write maintainable code

This requirement cannot be stressed enough. How maintainable is your
end result. This is not only maintainability from the stand-point of
source code longevity, but involves other higher-level aspects. Does
your implementation use interfaces, languages, tools, or techniques
that introduce some new development requirement? If so, that choice
needs to be discussed and justified or otherwise mitigated. Any new
external dependencies need to be approved by the core developers.
Is your code comprehensive and comprehensible? Well-documented?
Organized? You are required to follow existing dev guidelines, code
style, and established conventions.

### Write portable code

We appreciate code being as portable as possible with effort continually
taken to make sure code works on a variety of environments. While each
developer's perception of what is reasonable certainly fluctuates over
the years and from developer to developer, the general intention is that
code written should function the same on most moderately popular
operating system environments. It is each dev's responsibility to either
make sure their code isn't platform-specific or that equivalent
functionality is implemented for other maintained platforms. You are
expected to interact with other devs when portability issues are
raised and to promptly resolve any problems. Portability of any
dependencies being used must similarly be taken into account and
relates to the aforementioned maintainability requirement.

### Write complete code

Perhaps treat each week like it is your last. You should be able to hand
over functional code over just about any time during development (within
a day or so) to another developer. Focus on completing tasks, completing
code features, and working on keeping your code functional at all stages
of development. That way, no matter how far you get on your milestones
or deliverable(s), other developers will be able to review, test, and
readily integrate your code. Plan your development approach accordingly.
You should generally not "stub" code functionality (though comments
are good), but instead focus on coding "deep" instead of "wide". It's
generally preferred to have 2 features that work fully, than 5 features
that half-work or even 20 features that are all 90% complete.
