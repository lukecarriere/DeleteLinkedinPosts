# DeleteLinkedinPosts
Delete your Linkedin Posts

Recently I decided to leave my industry, online video, that I've been working in for years. 
I want to rethink my personal brand and begin cultivating an audience around Digital Currency instead.
This led me to want to start from a blank slate regarding content on professional networking platforms, while retaining my follower base.
I've already deleted Facebook, Instagram, and WhatsApp due to privacy concerns, but I've stayed on Linkedin and Twitter.
For twitter, I was able to easily find some helpful scripts from these helpful Twitter resources:
1) unfavorite tweets: https://jeffreifman.com/2018/04/12/how-to-delete-your-twitter-favorites-with-javascript/
2) unretweet tweets: https://gist.github.com/parkr/d600696478d03d6f9c32
3) delete my tweets: https://little418.com/2018/10/bulk-delete-tweets-javascript-console.html and
4) delete some tweets: https://www.quora.com/How-can-I-bulk-delete-my-Tweets-E-g-I-want-to-delete-the-first-thousand-or-all-Tweets-before-a-certain-date 
5) unfollow accounts:https://lifehacker.com/use-a-script-to-clear-out-your-twitter-feed-and-start-f-827264023

But for linkedin, all I could find was a way to unfollow people and bulk delete messages, not posts. [perhaps because MSFT owns Linkedin and also GitHub?]
1. unfollow people: https://mighil.com/mass-unfollow-people-on-linkedin/
2. delete messages: https://www.linkedin.com/pulse/how-delete-multiple-linkedin-messages-hack-peter-abilla
3. delete messages: https://gist.github.com/twhitacre/d4536183c22a2f5a8c7c427df04acc90 (This was the basis for my hack below)

HOW TO USE THIS CODE TO REMOVE YOUR POSTS FROM LINKEDIN: <br>
Step 1. Use Brave browser or Chrome<br>
Step 2. Login to your Linkedin account and go to your recent activity at this URL (replace the USERNAME with your own):
https://www.linkedin.com/in/USERNAME/detail/recent-activity/shares/ <br>
Step 3. Then right click on the page and click "Inspect"<br>
Step 4. Select Console and copy/paste the below script into the bottom right input area and hit Enter.<br>
Step 5. It will continue running and loading new posts as long as you stay on the browser window<br>
