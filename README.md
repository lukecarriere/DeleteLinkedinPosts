# DeleteLinkedinPosts
Delete your Linkedin Posts

Recently I decided to leave my industry, online video, that I've been working in for years. 
I want to rethink my personal brand and begin cultivating an audience around Digital Currency instead.
This led me to want to start from a blank slate regarding content on professional networking platforms, while retaining my follower base.
I've already deleted Facebook, Instagram, and WhatsApp due to privacy concerns, but I've stayed on Linkedin and Twitter.
For twitter, I was able to easily find some helpful scripts to 
1) unfavorite tweets 
2) unretweet tweets, 
3) delete my tweets, and 
4) unfollow accounts.

Here are some of those helpful Twitter resources: 
1. https://www.quora.com/How-can-I-bulk-delete-my-Tweets-E-g-I-want-to-delete-the-first-thousand-or-all-Tweets-before-a-certain-date
2. https://little418.com/2018/10/bulk-delete-tweets-javascript-console.html
3. https://gist.github.com/parkr/d600696478d03d6f9c32
4. https://jeffreifman.com/2018/04/12/how-to-delete-your-twitter-favorites-with-javascript/

But for linkedin, all I could find was a way to unfollow people and bulk delete messages, not posts. [perhaps because MSFT owns Linkedin and also GitHub?]
1. Unfollow people: https://mighil.com/mass-unfollow-people-on-linkedin/
2. https://gist.github.com/twhitacre/d4536183c22a2f5a8c7c427df04acc90 (This was the basis for my hack below)
3. https://www.linkedin.com/pulse/how-delete-multiple-linkedin-messages-hack-peter-abilla

HOW TO USE IT: 
Step 1. Use Brave browser or Chrome
Step 2. Login to your Linkedin account and go to your recent activity at this URL (replace the USERNAME with your own):
https://www.linkedin.com/in/USERNAME/detail/recent-activity/shares/
Step 3. Then right click on the page and click "Inspect"
Step 4. Select Console and copy/paste the below script into the bottom right input area and hit Enter.
Step 5. It will continue running and loading new posts as long as you stay on the browser window
