.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. http://www.sphinx-doc.org/en/master/rest.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See the [wiki:GSoCProjectIdeas ideas list] for some suggested project ideas.
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then opening a pull request to request us to review your draft proposal.
.. You can do this even before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. PDF proposal right up to the deadline by just uploading a new file, so don't
.. leave it until the last minute to upload a version.  The deadline is
.. strictly enforced by Google, with no exceptions no matter how creative your
.. excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
.. 
.. You're welcome to include diagrams or other images if you think they're
.. helpful - see http://www.sphinx-doc.org/en/master/rest.html#images for how
.. to do so.
.. 
.. Please take care to address all relevant questions - attention to detail
.. is important when working with computers!
.. 
.. If you have any questions, feel free to come and chat with us on IRC, or
.. send a mail to the mailing lists.  To answer a very common question, it's
.. the mentors who between them decide which proposals to accept - Google just
.. tell us HOW MANY we can accept (and they tell us that AFTER student
.. applications close).
.. 
.. Here are some useful resources if you want some tips on putting together a
.. good application:
.. 
.. "Writing a Proposal" from the GSoC Student Guide:
.. https://google.github.io/gsocguides/student/writing-a-proposal
.. 
.. "How to write a kick-ass proposal for Google Summer of Code":
.. http://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

======================================
Project: Text-Extraction Libraries
======================================

About You
=========

 * Name: Bruno Baruffaldi

 * E-mail address: baruffaldibruno@gmail.com

 * IRC nickname(s): barufa/barufab

 * Any personal websites, blogs, social media, etc: linkedin.com/in/brunobaruffaldi/

 * github URL: github.com/barufa

 * Biography:

.. Tell us a bit about yourself.

I’m a final year student of Computer Science at the National University of Rosario, Argentina. I like to consider myself as a problem solver. I have involved in competitive programing and have developed a few personal projects that can be found on my github account. I am always learning new things and I think that this project could be a great opportunity to apply this knowledge in the real world.

Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

**Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.**

This is my first time to apply to google summer of code and/or Google Code-in.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

In the past I have worked with Databases and Information Retrieval systems. Unfortunately, I do not have much experience working on projects that involves this kind of systems.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

While I have used a lot of open source libraries/programs either in personal projects or work for college, I do not have much experience working with source code of free software projects.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I am final year Computer Science student with GPA:4.46/5.

I have participated in the ACM-ICPC South America / South 2016 and 2017 competition and I have attended Winter Computer Science School (ECI - UBA) 2018.

During the last years I also have developed different projects such as a telegram bot, a distributed game server and Trivia solver among others.

**What development platforms, tools and methods do you prefer to use?**

I am very comfortable working with Atom and Git. Also, I am used to using gdb for debugging purposes.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

During the last semester I have been working on a personal project based on a question answering system focused on solving trivia questions of games such as InGame or HQTrivia. Broadly speaking, the program uses web scraping to get information from the internet and tries to weigh the different options to approximate a solution. This project has been really useful to take my first steps in NLP and IR and its accuracy for InGame is 86%.

**What timezone will you be in during the coding period?**

UTC–03:00

**Will your Summer of Code project be the main focus of your time during the
program?**

During coding period Gsoc will be my prior project and I will adapt my schedule to it if it is necessary. I will also be
attending a course at the university whose workload is 7 hours per week during the months of May and June and an
English course whose workload is 4 hours per week.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

30 hours per–week.

Monday–Saturday 8am–1pm UTC–03

**Are you applying for other projects in GSoC 2019?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

Actually I’m thinking about applying for ‘Text-Extraction Libraries’ but I am not sure if I am going to apply to another
project.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

I think Xapian is an interesting organization that can solve many problems of the developers, and this project seems to be the most suitable to get in touch with Xapian’s source code for first time. Moreover, this project will allow me to apply different concepts to improve my coding skills.

At college, I have worked with information retrieval systems and ontologies, and this branch of artificial intelligence seems to be very promising and it can be applied to a large number of real-world projects. Besides, although I do not have much experience working with systems for indexed text search, I am eager to learn more about it.

On the other hand, adding this kind of support to projects is not unusual and I believe that acquiring experience in these types of modifications will greatly improve my coding skills.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

I think that users would be the most benefited, since this project represents a great improvement because it would speed up indexing and Omega would become less dependent on external programs.

Also, at the risk of sounding selfish, I will be largely benefited because this opportunity will allow me to gain experience with a real world project and work with a mentor to help me clarify my doubts.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The project is based on adding support to extract text from various file formats during indexing through external libraries. For this, we can uses multithreading and resource constraints to isolate library bugs in a subprocess to avoid them from crashing omindex.
There is already code within the project that is responsible for this kind of error handling. Also, some formats are already supported through libraries.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Olly implemented a patch for libwv2 library that has a similar mechanism and seems to work properly. Although the code does not solve problems such as infinite loops, we can consider it as a first approach to a correct solution. In addition, the source code works with external filters and it handles their bugs isolating said external filters in subprocesses (this is implemented in modules runfilter and index_file).

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

I have considered that the focus should be placed on the design of the solution and that it should allow to incorporate or replace libraries in a simple way. However, this kind of modifications could take a lot of work and time and we will not take advantage of the existing code.

Therefore, I consider that the best way to carry out the project is to add the different libraries following the scheme present in the source code of xapian (svgparse, atomparse, etc) and perform an error handling through multithreading and resource constraints.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

During the Coding Period, I will have to carry out different researches such as what library I would use and how to do it. These investigations are contemplated within the timeline.

**How useful will your results be when not everything works out exactly as
planned?**

In case there is any delay in the project, I think that the progress made would be very useful, because the code would be tested and documented as the project progresses.

Project Timeline
----------------

.. We want you to think about the order you will work on your project, and
.. how long you think each part will take.  The parts should be AT MOST a
.. week long, or else you won't be able to realistically judge how long
.. they might take.  Even a week is too long really.  Try to break larger
.. tasks down into sub-tasks.
.. 
.. The timeline helps both you and us to know what you should do next, and how
.. on track you are.  Your plan certainly isn't set in stone - as you work on
.. your project, it may become clear that it is better to work on aspects in a
.. different order, or you may some things take longer than expected, and the
.. scope of the project may need to be adjusted.  If you think that's the
.. case during the project, it's better to talk to us about it sooner rather
.. than later.
.. 
.. You should strive to break your project down into a series of stages each of
.. which is in turn divided into the implementation, testing, and documenting of
.. a part of your project. What we're ideally looking for is for each stage to
.. be completed and merged in turn, so that it can be included in a future
.. release of Xapian. Even if you don't manage to achieve everything you
.. planned to, the stages you do complete are more likely to be useful if
.. you've structured your project that way. It also allows us to reliably
.. determine your progress, and should be more satisfying for you - you'll be
.. able to see that you've achieved something useful much sooner!
.. 
.. Look at the dates in the timeline:
.. https://summerofcode.withgoogle.com/how-it-works/
.. 
.. There are about 3 weeks of "community bonding" after accepted students are
.. announced.  During this time you should aim to complete any further research
.. or other issues which need to be done before you can start coding, and to
.. continue to get familiar with the code you'll be working on.  Your mentors
.. are there to help you with this.  We realise that many students have classes
.. and/or exams in this time, so we certainly aren't expecting full time work
.. on your project, but you should aim to complete preliminary work such that
.. you can actually start coding at the start of the coding period.
.. 
.. The coding period is broken into three blocks of about 4 weeks each, with
.. an evaluation after each block.  The evaluations are to help keep you on
.. track, and consist of brief evaluation forms sent to GSoC by both the
.. student and the mentor, and a chance to explicitly review how your project
.. is going with Xapian mentors.
.. 
.. If you will have other commitments during the project time (for example,
.. any university classes or exams, vacations, etc), make sure you include them
.. in your project timeline.

I opted for a relaxed timeline. While I believe that some weeks have a lower workload, in case of having more time I could move forward with the work of the following week or make some additional contribution (depending on what the mentor deems appropriate). As this is one of the first times I plan a project in this way, I prefer a more relaxed work plan and if you have time during the project try to extend it instead of an overloaded plan with which I can easily have difficulties to complete.

Community Bonding Period: May 6 – May 24:

- Get to know the community, interact with the people.
- Read and understand the Xapian code base, get to know all the relevant classes.
- Try to solve existing issues, go through code review process.
- Research about different libraries.
- Make sure that everything is ready for coding.

Coding Week 1: May 27–May 31:

- Design, implement and get familiar with classes to add the libraries and handle errors.
- Write proper documentation

Coding Week 2: June 3–June 7:

- Add zip files reading library.
- Test code.

Coding Week 3: June 10–June 14:

- Add pdf files reading library.
- Add PostScript support.

Coding Week 4: June 17–June 21:

- Test indexing of documents. Fix issues if any.
- Add documentation if it is required

Coding Week 5: June 24–June 28 (evaluations: June 24-28):

- Add support for MS Office 2007 documents
- Test code.

Coding Week 6: July 1–July 5:

- Add MS Excel documents reading library
- Add MS Outlook support

Coding Week 7: July 8–July 12:

- Add MS Powerpoint documents reading library
- Add MS Word documents reading library

Coding Week 8: July 15–July 19:

- Test indexing of documents. Fix issues if any. 
- Add documentation if it is required

Coding Week 9: July 22–July 26 (evaluations: July 22-26):

- Add DjVu files reading library
- Add support for Markdown files

Coding Week 10: July 29–August 2:

- Add support for OpenDocument format documents
- Add support for MS Publisher documents

Coding Week 11: August 5–August 9:

- Add support for OpenOffice/StarOffice documents

Coding Week 12: August 12–August 16:

- Test indexing of documents. Fix issues if any. 
- Add documentation if it is required.

Coding Week 13: August 19–August 23 (evaluations: August 19-26):

- Write proper documentation and samples of how to add support for a new file format.
- Test all code of the project.

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

I have exchanged a few emails on the list.

- lists.xapian.org/pipermail/xapian-devel/2019-March/003313.html
- lists.xapian.org/pipermail/xapian-devel/2019-March/003314.html
- lists.xapian.org/pipermail/xapian-devel/2019-March/003315.html
- lists.xapian.org/pipermail/xapian-devel/2019-March/003317.html

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

I totally agree to dual-license all my contributions to Xapian under the GNU GPL version 2 and all later versions, and the MIT/X licence.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1376

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

I would have to use libraries like Poppler, libe-book, Libmspub amoung others.
All these libraries belong to free software.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
