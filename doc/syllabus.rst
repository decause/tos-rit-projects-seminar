Syllabus
========

Projects Seminar in FLOSS Game Development
------------------------------------------

 - Syllabus - http://ritfloss.rtfd.org/ -- (subject to change)
 - Course Number - 4080.590.01
 - Room - Orange Hall, Room 1380 (013-1380)
 - Tuesday, Thursday -- 10:00am-11:50am
 - Instructor - Ralph Bean <rjbpop@rit.edu>

   - Office:  Building 17, Room 3110 (17-3110)
   - Office Hours:  Friday, 1:00pm-3:00pm

 - IRC - irc.freenode.net, ``#floss-seminar``
 - Email list - `floss-seminar@lists.rit.edu
   <https://lists.rit.edu/mailman/listinfo.cgi/floss-seminar>`_
 - Blog Planet - http://threebean.org/floss-planet
 - The source for this syllabus can be found at
   http://github.com/ralphbean/tos-rit-projects-seminar

Text Books
----------

.. _casual:

You can :download:`download the textbooks here <textbooks.zip>`.

Casual Game Design
~~~~~~~~~~~~~~~~~~
`Casual Game Design:  Designing Play for the Gamer in ALL of Us
<http://www.amazon.com/Casual-Game-Design-Designing-Gamer/dp/0123749530>`_.

.. _isometric:

Making Isometric Social Real-Time Games with HTML5, CSS3, and Javascript
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Making Isometric Social Real-Time Games with HTML5, CSS3, and Javascript.
<http://www.amazon.com/Making-Isometric-Social-Real-Time-Javascript/dp/1449304753>`_

Goals of the course
---------------------


Having taken this course, students should be able to:

 - Demonstrate competence with modern FLOSS development tools and conventions
   (git, public forges, unit tests, bug trackers, wikis, etc..).
 - Demonstrate competence with modern web development technologies (HTML5,
   Javascript, CoffeeScript, CSS3, etc..).
 - Document their work progress, accomplishments, and pitfalls by way of weekly
   blog posts.
 - Work with and contribute to existing open source projects.
 - Build and manage a new project using open source tools.
 - Deploy a web application to the `cloud <http://rhcloud.com>`_.
 - Have a fun, open-source web-based game for their portfolio and/or to show
   off to their friends.

The spirit of the course
------------------------

While still a course where you will receive a letter grade, the spirit of the
course is intended to be both `open` and `fun`.  This is a seminar course,
so an experimental approach will be taken.

An `open` course -- students will have access to the 'document source' for the
syllabus and grading rubric.  While you are reading `the syllabus` right now,
as a student of the class you have a right to `fork the upstream repository
<http://github.com/ralphbean/tos-rit-projects-seminar>`_, make modifications,
and submit patches for review.  Barring a troll festival, this can create a fun,
dynamic environment in which the course curriculum can develop by the very same
mechanism being taught during the quarter (community-driven).

A `fun` course -- while the primary deliverable for the course is a working
web-based game, we are going to subject the course itself to `gamification`.
Instead of grading students' final projects individually, projects will be
pitted against one another through a scheme developed by the students
themselves, called the :doc:`final_project_rubric`.

For example, one way this could work is through simple accumulation of weighted
point values awarded for the presence of certain features: a game that works in
all modern browsers as well as on mobile devices gets +5 points, a game that
includes a velociraptor gets +3 points, etc...

Licensing
---------

All code developed by students in the course must be licensed (by the student)
under any one of the `licenses approved by the open source initiative
<http://www.opensource.org/licenses/category>`_.

Your code that you write is your code, with which you can do what you will;
true.  However, if you're unwilling to license code you write for an open source
course with an open source license, you're in the wrong course.

Schedule
--------

+----+---+----------------------------+----------+-------------------+-------------------+
|Week|Day|Topic                       |Reading   | Assigned          | Due               |
+----+---+----------------------------+----------+-------------------+-------------------+
|1   |1  | Introductions, Syllabus,   |:ref:`1-1`|:doc:`hw/fflight`  |                   |
|    |   | Mailman, IRC, git, github  |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Bugfix deep dive           |:ref:`1-2`|:doc:`hw/bugfix`   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|2   |1  | Casual Games: Matching,    |:ref:`2-1`|                   |:doc:`hw/fflight`  |
|    |   | Sorting, and Seeking       |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Introduction to HTML5      |:ref:`2-2`|:doc:`program/1`   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|3   |1  | Casual Games: Managing,    |:ref:`3-1`|                   |                   |
|    |   | Hitting, and Chaining      |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Audio, WebWorkers, and     |:ref:`3-2`|                   |                   |
|    |   | CoffeeScript               |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|    |   | **Holiday Break**          |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|4   |1  | Pitch Session : Talk about |          |                   | :doc:`program/1`  |
|    |   | your game.                 |          |                   | :doc:`hw/bugfix`  |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Paper Prototypes : Lecture |          |                   |                   |
|    |   | and Build                  |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|5   |1  | Paper Prototypes : (con't) |          |:doc:`hw/rubric`   |                   |
|    |   | Project Decisions          |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Server choices, Social     |:ref:`4-2`|:doc:`program/2`   |                   |
|    |   | APIs, and `le Cloud`.      |          |                   |                   |
|    |   | (#openshift)               |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|6   |1  | **No class**               |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Casual Games: Constructing,|:ref:`4-1`|                   |:doc:`hw/rubric`   |
|    |   | Socializing, and Physics   |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|7   |1  | Digital Prototype : Build  |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Digital Prototype : Play   |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|8   |1  | Digital Prototype : Report |          |                   |:doc:`program/2`   |
|    |   | and Revise                 |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Guest Lecture              |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|9   |1  | Digital Prototype : Build  |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Digital Prototype : Report |          |                   |                   |
|    |   | and Revise                 |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|10  |1  | Play Testing/Development   |          |                   |                   |
+    +---+----------------------------+----------+-------------------+-------------------+
|    |2  | Play Testing/Development   |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+
|11  |?  | Final Presentations        |          |                   |                   |
+----+---+----------------------------+----------+-------------------+-------------------+

Required Reading
----------------


.. _1-1:

The Syllabus
~~~~~~~~~~~~

 - You're reading the syllabus right now.  It is posted at
   http://ritfloss.rtfd.org/

.. _1-2:

The Open Source Way
~~~~~~~~~~~~~~~~~~~

 - `What they didn't teach me in college
   <http://ericholscher.com/blog/2009/nov/10/what-they-didnt-teach-me-college/>`_
 - `How to Start Contributing to Open Source Projects
   <http://maymay.net/blog/2009/02/11/how-to-start-contributing-to-open-source-projects/>`_
 - `Understanding Open Source Licensing
   <http://openacs.org/about/licensing/open-source-licensing>`_
 - `Revitalizing Computing Education Through Free and Open Source Software
   <http://www.cs.trincoll.edu/~ram/pubs/CACM09-Morelli.pdf>`_
 - `Why Open Source Misses the Point of Free Software
   <http://www.gnu.org/philosophy/open-source-misses-the-point.html>`_

.. _2-1:

Casual -  Week 2
~~~~~~~~~~~~~~~~

 - :ref:`casual`

   - chapters 1-6 (139 pages).  It's light reading, trust me.

.. _2-2:

Isometric - Week 2
~~~~~~~~~~~~~~~~~~

 - :ref:`isometric`

   - chapters 1-3 (65 pages).  This reading is not quite so
     light.

.. _3-1:

Casual -  Week 3
~~~~~~~~~~~~~~~~

 - :ref:`casual`

   - chapters 7-9 (36 pages)

.. _3-2:

Isometric - Week 3
~~~~~~~~~~~~~~~~~~

 - :ref:`isometric`

   - chapter 4 (18 pages)

.. _4-1:

Casual -  Week 4
~~~~~~~~~~~~~~~~

 - :ref:`casual`

   - chapters 10-12 (56 pages)

.. _4-2:

Isometric - Week 4
~~~~~~~~~~~~~~~~~~

 - :ref:`isometric`

   - chapter 5 (25 pages)


Grading
-------

Assignments are due at midnight of the day they are marked as due.

Late submissions will be deducted 10% per day they are late.

----

Your final grade for the quarter will be derived from the following weights.

+--------------------------------------------------------+--------------+
| Component                                              | Weight       |
+========================================================+==============+
|In-Class Participation                                  | 10%          |
+--------------------------------------------------------+--------------+
|FLOSS Dev Practices (Blogging, patching, writing, IRC)  | 15%          |
+--------------------------------------------------------+--------------+
|Homework Assignments                                    | 10%          |
+--------------------------------------------------------+--------------+
|Programming Assignments                                 | 15%          |
+--------------------------------------------------------+--------------+
|Paper Prototype                                         | 10%          |
+--------------------------------------------------------+--------------+
|Final Project                                           | 40%          |
+--------------------------------------------------------+--------------+

----

*Class partitipation* is speaking in class, answering questions, etc...

----

*Blog updates* -- students are required to keep a blog to which they post updates
about their investigations, progress, success, and pitfalls.  This blog can be
hosted anywhere, but must be added to the course `planet
<http://threebean.org/floss-planet/>`_ (there are instructions on how to do this
in :doc:`hw/fflight`).

 - You must make at least one blog post per week to receive full credit.
 - You must participate regularly in the course's IRC channel: asking and
   answering questions.
 - You must participate in the course's mailman list,
   `floss-seminar@lists.rit.edu
   <https://lists.rit.edu/mailman/listinfo.cgi/floss-seminar>`_.
 - Contributions to the course curriculum, syllabus, and rubric are factored in
   here as well.

Blogging is good for you and good for the `FLOSS community at large
<http://xkcd.com/979/>`_.

----

The *homework assignments* are listed in the syllabus.  You will be able to
complete some of these in class.

----

*Programming assignments* are more in depth, but will amount to two deliverables
derived from one of the course's two textbooks, `Making Isometric Social
Real-Time Games with HTML5, CSS3, and Javascript
<http://www.amazon.com/Making-Isometric-Real-Time-JavaScript-ebook/dp/B005KOJ4DK/ref=dp_kinw_strp_1?ie=UTF8&m=AG56TWVU5XWC2>`_.

There are two assignments:
 - :doc:`program/1`
 - :doc:`program/2`

----

Students' *paper prototypes* are presentations to the rest of the class on their
idea for their game, *before a single line of code is written*.

These are 'play sessions'.  You will need to bring some playable version of your
game so we can all try it out.  For instance, if you're thinking about a
first-person-shooter, come with a set of rules for playing 'pointing tag' and
we'll all really play it, in person.

The rest of the students will comment on your prototype.  Take notes and:
 - Use them to improve your design
 - Turn in a copy for your grade

----

Your *final project* will be the culmination of the quarter's work and will be
graded according to the :doc:`final_project_rubric`.

----

Additionally, graduate students are expected to complete some extra work as described in :doc:`hw/gradproj`.

Lightning Talks - Extra Credit
------------------------------

Every Tuesday for the first portion of class, any student has the opportunity
to give a `lightning talk <http://en.wikipedia.org/wiki/Lightning_Talk>`_ on a
topic of their chosing.  Your lightning talk must be less than 5 minutes in
length and must be at least remotely related to the course material.

You will receive +1 extra credit points towards your final grade for every
lightning talk you give.  Only the first three lightning talks offered will be
allowed during a given class.  Talks will be chosen from among those offered by
students on a FIFO basis.
