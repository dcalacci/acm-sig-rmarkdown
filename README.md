# ACM SIG RMarkdown template

Want to only write RMarkdown and not deal with latex at all? Want to streamline submitting to CSCW and similar venues? This here is the repo for you!

This is a fork/adjustment of the ACM RMarkdown template to include current standards for SIG community review and camera-ready submissions. It includes YAML header data and template info that can help set rights info and other details needed for submissions.

### Do you have an example of what it looks like?

Sure do! See `./examples/manuscript-camera-ready.pdf` for an example of a camera ready version, and `./examples/manuscript-review.pdf` for an example of a blind review version. The only difference between these two documents are the following YAML headers in the Rmd:

#### Review

``` yaml
## Rendering parameters
# true if submitting for camera ready; Fill out rights info above.
camera-ready: false
# true if blind review
anonymous: true
# true if review copy
review: true
```

#### Camera Ready

``` yaml
## Rendering parameters
# true if submitting for camera ready; Fill out rights info above.
camera-ready: true
# true if blind review
anonymous: false
# true if review copy
review: false
```

### How do I use it?

1.  Clone the repository
2.  Open `manuscript.Rmd` in RStudio
3.  Write your paper, including code and figures
4.  Knit (`cmd+shift+k`)
5.  latex magic ???????????
6.  Publish

### Does it work?

I have used this template in two successful submissions to SIG conferences, so it sure seems like it!
