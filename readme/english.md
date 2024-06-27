# PLAIF

> If you want to proceed reading about `PLAIF Inc.` in Korean, please
> visit [the Korean version](/README.md).

This is a repository that stores materials about PLAIF. This repository
documents the following contents:

1. About `PLAIF`
2. Teams & Members

## Introduce yourself as a PLAIFer

If you are reading this section, you must be a new member of PLAIF. We are
honored to have you with us! We would like
you to introduce yourself to the other members so that we can get to know you
better. Here are some tips on how to do
that.

### 1. Write an introduction

Please write a self-introduction page using Markdown. Feel free to write about
your job, the tools you use, and your
interests. If you are stuck, you can refer to the
following [example](/profile/software/members/jusung.md) and make a
few changes. Here are the steps on how to write a self-introduction page.

1. `Clone` this repo (ex. `git clone https://github.com/plaif-dev/.github.git`)
2. Create a `branch` on which to work on the introduction (
   ex. `git switch -c jusung/introduction`)
3. Create a `Markdown` file with your name in the `members/` directory of the
   team you are in under the `/profile/`
   directory (e.g. `profile/software/members/jusung.md`).
    1. If you cannot find your team, create a directory with the name of your
       team and configure the directory with the
       following structure.

```plaintext
team name
├─ team name.md
└─ members/
    └─ your name.md
```

4. Write your introduction in the Markdown file
5. Link the newly created page to the team page (
   e.g. `profile/software/software.md`) using a relative path.

### 2. Get peer reviews

Done writing your introduction? You are almost there. To double-check your
work, the next step is to request peer
reviews.
There might be some typos! The following is the method that we use - check it
out! (We follow the standard GitHub flow,
as delineated below 😊.)

1. `Commit` Introduction (
   e.g. `git commit -m "📝docs(introduction): add intro for someone"`)
2. `Push` Introduction (e.g. `git push origin jusung/introduction`)
3. Send a `Pull Request` for peer reviews (
   e.g. [Web Pull Request](https://github.com/PLAIF-dev/.github/compare))

```markdown
<!--Template for reference-->

## Details

* add a readme page for `your-name`

## Checklist

Please double-check that your Pull Request complies with the following requirements:

- [ ] 😊 Declarative commit message.
- [ ] 💯 No typos.

```

4. Repeat steps 1 and 2 if any modifications are necessary
5. Get all required approvals from at least 2 team members

### 3. Share your introduction

Got all the approvals you need from your team members? If so, please merge it
so that everyone can see it. If you have all necessary approvals, the Merge
button will be enabled in green at the bottom of the Pull Request. Click the
button to merge it into the main branch. Don't forget to delete the branch you
were working on after merging!
