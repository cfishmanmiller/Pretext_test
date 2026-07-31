# Math Trailhead

This is a working prototype of a precalculus review tool using WeBWorK. Almost all of the problems from the [moodle](https://moodle.reed.edu/course/view.php?id=6466) are in here, but some threw errors (the most common of which being a missing statement tag) and those were commented out. Some other problems had rendering issues that were fixed locally on WeBWorK but not here, such as using 'x' for LaTeX instead of ['x']. These were left in, and comments were left on all of the cases that I noticed (but likely not all of them). The front matter and syllabus pages are blank.

Each section has a blurb at the top summarizing the contents and providing resources. These are all in [main](source/main.ptx). The individual pages within each section are under [activities](source/activities).

## Instructions

You can build the course using

```bash
pretext build course
```

and view it with

```bash
pretext view course
```