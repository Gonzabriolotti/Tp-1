~/Desktop/Tp-1> git -c credential.helper=/usr/share/smartgit/lib/credentials.sh add --force -- CV.md
~/Desktop/Tp-1> git -c credential.helper=/usr/share/smartgit/lib/credentials.sh commit --file=/tmp/smartgit2616740048044994080/commit754869494404514268.tmp -o -- CV.md
[main c1e5dd6] commit
 1 file changed, 3 insertions(+), 2 deletions(-)
~/Desktop/Tp-1> git -c credential.helper=/usr/share/smartgit/lib/credentials.sh push --porcelain --progress --recurse-submodules=check origin refs/heads/main:refs/heads/main
failed to push some refs to 'https://github.com/Gonzabriolotti/Tp-1'
To https://github.com/Gonzabriolotti/Tp-1
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
! refs/heads/main:refs/heads/main [rejected] (fetch first)
hint: to the same ref. You may want to first integrate the remote changes
Done
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
'main' rejected (non-fast-forward)
