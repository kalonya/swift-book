# Çeviri Projesine Katkıda Bulunma

Bu projeye katkıda bulunarak Swift'in resmi kitabının Türkçeye kazandırılmasına yardımcı olduğunuz için teşekkür ederiz!

## Nasıl Katkıda Bulunabilirim?

* **Hata Bildirimi:** Çeviride gördüğünüz bir yazım hatasını, teknik bir yanlışı veya anlamsız bir cümleyi bildirmek için lütfen bir "Issue" açın.
* **Çeviri Önerisi:** Mevcut bir çeviriyi iyileştirmek veya yeni bir bölümü çevirmek için bu repoyu forklayarak bir "Pull Request" gönderebilirsiniz.

## İş Akışı

1.  Bu repoyu kendi GitHub hesabınıza forklayın.
2.  `translation-tr` dalını temel alarak yeni bir dal oluşturun (Örn: `feature/ceviri-bolum-5`).
3.  Değişikliklerinizi yapın ve commit'leyin.
4.  Kendi fork'unuzdan bizim `translation-tr` dalımıza bir Pull Request açın.

If this is your first contribution,
start by making a fork of the Git repository.

In your fork,
make a new branch starting at `main`
with a brief, descriptive name.
Branch names are ephemeral:
When a pull request is merged,
the merge commit doesn’t include name of your feature branch.

If you need to incorporate changes from `main` or resolve a merge conflict,
merge `main` into your feature branch.
Before creating a pull request,
you can instead rebase your feature branch onto `main` if you prefer,
but don't rebase commits that are part of a pull request.

## Writing commit messages

Use the Git commit message to communicate with other contributors —
both the people working on the project now
who are reviewing your changes,
and people who join the project in the future
who will need to understand what you changed and why.

Every commit starts with a one-sentence summary.
The summary usually fits in 50 characters,
but it's OK to exceed that amount occasionally
if rewriting for brevity would make it too hard to read.
If it's hard to write a good summary,
try breaking your changes into multiple smaller commits.

If you can't explain the commit entirely in its summary,
skip one line and add additional information.
This additional information includes information like
the reasons for the change,
the approach you took when making it,
alternatives you considered,
and a summary of what you changed.
Hard wrap these lines at 72 characters
and leave a blank line between paragraphs.
The body of a commit is plain text,
not markdown like the content of the book.

Following these formatting conventions in your commit
makes it easier to read
in places like the output from `git` and notification emails.
Most text editors can help you write a commit message
by marking lines that are too long
and hard wrapping text automatically.

## Submitting a pull request

Use the following steps when creating a new pull request:

1. Test that your changes build locally by running `docc preview TSPL.docc`.
2. Create a pull request in this repository.
3. Write a brief message in the pull request to introduce your work in context.

Within a few days,
someone will assign reviewers and start a build in CI.

During the review of the pull request,
add new commits on your branch to incorporate feedback,
but don’t rebase or force push.
Rewriting the branch's history
makes it hard for reviewers to see
what changed since the last time they reviewed your changes.
If there are merge conflicts,
merge `main` into your branch or use the GitHub web UI
to resolve the conflicts when accepting the pull request.

After a pull request is merged, delete the feature branch.

Tüm katkılar, projenin [orijinal lisansı](LICENSE.txt) altında kabul edilecektir.