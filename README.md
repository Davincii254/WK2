Updated React nucampsite repo with hooks, function components, and RTK

Instructors:

Use:

### `npm ci`

to clean install the node_modules folder in any branch. Clean install means it will use the existing package-lock.json file and won't alter it.

Use:

### `git branch`

to view the available branches. Each branch represents the nucampsite course project at the end of a particular exercise or workshop task.

Use:

### `git switch <branchname>`

To checkout and switch to a branch. You can use the files in that branch as an answer key, to compare against your students' for grading and to provide help. P

Please do not share this repository with any students. It is for instructors' use only.

If you find any issues with this repository, contact Nucamp's Director of Curriculum.

##### Version history

-   v2.0 - hooks + RTK + Formik + React Spring + other major updates added to React curriculum
-   v2.1 - moved week 4 exercise: add middleware to be the final exercise of the week, where it makes more sense after exercise: addComment
-   v2.2 - renamed branch wk5-01-fetchCampsites to wk5-01-async-campsites, bunch of misc small tweaks in week 5 including update to how ws task 3 is handled (updated to use postComment.rejected extraReducer and use Promise.reject, in stead of a try catch block and throw, to make it more like the code students have been writing during the week)
-   v2.2.1 - removed unnecessary Row from PartnersList component from wk2-ws-task4 branch on.
