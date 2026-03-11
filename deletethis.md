git filter-branch -f --env-filter "
    GIT_AUTHOR_NAME='Perry Lim'
    GIT_AUTHOR_EMAIL='123717942+limx0139@users.noreply.github.com'
    GIT_COMMITTER_NAME='Perry Lim'
    GIT_COMMITTER_EMAIL='123717942+limx0139@users.noreply.github.com'
  " HEAD