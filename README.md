# jorgetheengineer-static

## Hosting:
S3

## Link:
http://jorgetheengineer.com

## Desctiption:
Here I am experimenting with static content hosting using AWS S3. I will continue to add more content and features as time goes on.

## Project Setup:
Static content in plain HTML, CSS and JS is commited to GitHub. AWS CodePipeline sources from this repo upon commiting to *main*. A CodeBuild stage clears the previous contents of the target S3 bucket to not accumulat unused files.
Finally, a deploy stage uploads the new content to the bucket and the website is updated.

