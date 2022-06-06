<div style="display:flex;justify-content-center">
 
 Hey Iam soufyen, Fullstack developper.
  <img align="right" alt="Coding" width="400" src="./tenor.gif itemid=15828752.gif">

 1+ years experienced Jvavscript/php with hands-on experience in identifying web-based user interactions along with designing & implementing highly responsive user interface components by deploying React concepts. Proficient in translating designs & Website wireframes into high-quality code, and writing application interface code via JavaScript and ReactJS workflows. Adept at monitoring & maintaining front-end performance With Backend Api with laravel and troubleshooting & debugging the same to bolster overall performance
 
 
- 🔭 I’m currently working on React.js & Laravel
- 🌱 I’m currently learning ReactNative & Node.js



![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=soufyen004&show_icons=true)

![](https://komarev.com/ghpvc/?username=soufyen004)

 name: Latest blog post workflow
on:
  schedule: # Run workflow automatically
    - cron: '0 * * * *' # Runs every hour, on the hour
  workflow_dispatch: # Run workflow manually (without waiting for the cron to be called), through the Github Actions Workflow page directly

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v2
      - name: Pull in dev.to posts
        uses: soufyen004/blog-post-workflow@master
        with:
          feed_list: "https://dev.to/feed/soufyen004,https://www.gautamkrishnar.com/feed/"
 
 </div>
