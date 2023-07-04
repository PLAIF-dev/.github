# PLAIF

> If you want to proceed reading about `PLAIF Inc.` in korean, please visit [the korean version](/README.md).

This is a repository that stores materials about PLAIF. This repository documents the following contents.

 1. About `PLAIF`
 2. Teams & Members

## Introduce you as PLAIFer

If you are reading this section, you must be a new member of PLAIF. We are honored to have you with us! We would like you to introduce yourself to the other members so that we can get to know you better. Here are some tips on how to do that.

### 1. Write introduction

Please write a self-introduction page using markdown. Feel free to write about your job, the tools you use, and your interests. If you are stuck, you can refer to the following [example](/profile/software/members/jusung.md) and make a few changes. Here are the steps on how to write a self-introduction page.

1. `Clone` this repo (ex. `git clone https://github.com/plaif-dev/.github.git`)
2. Create a`branch` you are going to work on the introduction(ex. `git switch -c jusung/introduction`)
3. Create `a markdown` file with your name in the `members/` directory of the team you are in under the `/profile/` directory (e.g. `profile/software/members/jusung.md`).
   1. If you cannot find your team, create a directory with the name of your team and configure the directory with the following structure.

```plaintext
team name
├─ team name.md
└─ members/
    └─ your name.md
```

4. Write down your introduction the markdown file
5. Link the newly created page to the team page (e.g. `profile/software/software.md`) using a relative path.

### 2. Get peer reviews

Done writing your introduction? You are almost there. Please get peer reviews for `double-check`.There might be some typos! Let's check it out using the following method. (We are following github flow 😊.)

1. `Commit` Introduction(ex. `git commit -m "📝docs(introduction): add intro for someone"`)
2. `Push` Introduction(ex. `git push origin jusung/introduction`)
3. Send `Pull Request` for peer reviews(ex. [Pull Request in Web](https://github.com/PLAIF-dev/.github/compare))

```markdown
<!--Template for reference-->

## Details

* add readme page for `your-name`

## Checklist

Please double check your Pull Request is following below:

- [ ] 😊 Declarative commit message.
- [ ] 💯 No typo.

```

4. Repeat `1~2 process` if there needs any modification
5. Get all `approvals` from at least 2 team members

### 3. Share your introduction

Got all approvals from your team members? If so, please merge it so that everyone can see it. If you have all the approvals, the Merge button will be enabled in green at the bottom of the Pull Request. Click the button to merge it into the main branch. Don't forget to delete the branch you were working on after merging!
