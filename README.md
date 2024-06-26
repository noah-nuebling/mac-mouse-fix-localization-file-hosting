# mac-mouse-fix-localization-file-hosting

The plan is to automatically upload .xcloc files for Mac Mouse Fix translators to the Releases page of this repo. So we can then provide download links to translators.

We don't want anyone to actually look at this repo, it's just that GitHub Releases is the most straight-forward way I can think of right now to host automatically generated ( and .zip-ed up) .xcloc files. 

Alternatives:
- I guess we could use Amazon Web Services or something to host the files, but that's more complicated and I'm not as familiar. 
- We tried uploading to GitHub Gists but it doesn't seem to take zip files or folders (.xcloc files are actually folders)
- We tried uploading to github.com/noah-nuebling/mac-mouse-fix/assets (where files are stored when you attach them to a Comment/Issue/Discussion) but there doesn't seem to be an API for that as of June 2024
- We could host the .xcloc files one the Releases page for the mac-mouse-fix repo, but I don't want to clutter things up.

Other:
- If we could make this repo private we might want to do that.
